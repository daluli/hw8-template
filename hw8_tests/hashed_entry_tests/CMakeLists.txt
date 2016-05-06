include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runHW8HashedEntryTests_1 ../hashed_entry_tests/hashed_entry_check.cpp)
target_link_libraries(runHW8HashedEntryTests_1 hw8_library gtest gtest_main)
