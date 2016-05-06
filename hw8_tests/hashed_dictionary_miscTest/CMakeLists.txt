include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runHW8MiscTests_5 hashed_dictionary_miscTest.cpp)
target_link_libraries(runHW8MiscTests_5 hw8_library gtest gtest_main)
