include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runBasicHW8Tests ../basic_tests/basic_check.cpp)

target_link_libraries(runBasicHW8Tests gtest gtest_main)
target_link_libraries(runBasicHW8Tests hw8_library)