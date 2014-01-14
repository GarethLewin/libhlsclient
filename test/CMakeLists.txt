CMAKE_MINIMUM_REQUIRED (VERSION 2.8)

SET(libhls_test_files test.cpp)

ADD_EXECUTABLE(test ${libhls_test_files})
TARGET_LINK_LIBRARIES(test libhls)
