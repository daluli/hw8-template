include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runHW8AddTests_3 hashed_dictionary_addTest.cpp)
target_link_libraries(runHW8AddTests_3 hw8_library gtest gtest_main)
