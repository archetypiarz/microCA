add_executable(microCA_tests
  main_test.cpp
)

find_package(GTest REQUIRED)
target_link_libraries(microCA_tests PRIVATE GTest::GTest GTest::Main)
