if (LCM_FOUND)
  add_executable(acrobotURDFDynamicsTest urdfDynamicsTest.cpp)
  target_link_libraries(acrobotURDFDynamicsTest drakeRBSystem)
  add_test(NAME acrobotURDFDynamicsTest COMMAND acrobotURDFDynamicsTest)
endif(LCM_FOUND)
