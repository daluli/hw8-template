include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runHW8RemoveTests_4 hashed_dictionary_removeTest.cpp)
target_link_libraries(runHW8RemoveTests_4 hw8_library gtest gtest_main)
