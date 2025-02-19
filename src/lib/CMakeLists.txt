# Create a library called "medical_imaging_secure"
add_library(medical_imaging_secure_lib medical_imaging_secure.cpp)

# Specify include directories for the library
target_include_directories(medical_imaging_secure_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
