add_llvm_library(LLVMPatmosSinglePath
  PatmosSinglePathInfo.cpp
  PatmosSPClone.cpp
  PatmosSPMark.cpp
  PatmosSPPrepare.cpp
  PatmosSPBundling.cpp
  PatmosSPReduce.cpp
  RAInfo.cpp
  SPScope.cpp
  SPScheduler.cpp
  PredicateDefinition.cpp
  )

add_dependencies(LLVMPatmosSinglePath PatmosCommonTableGen)