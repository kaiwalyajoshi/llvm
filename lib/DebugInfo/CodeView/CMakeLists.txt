add_llvm_library(LLVMDebugInfoCodeView
  FieldListRecordBuilder.cpp
  Line.cpp
  ListRecordBuilder.cpp
  MemoryTypeTableBuilder.cpp
  MethodListRecordBuilder.cpp
  RecordSerialization.cpp
  SymbolDumper.cpp
  TypeDumper.cpp
  TypeRecord.cpp
  TypeRecordBuilder.cpp
  TypeStreamMerger.cpp
  TypeTableBuilder.cpp

  ADDITIONAL_HEADER_DIRS
  ${LLVM_MAIN_INCLUDE_DIR}/llvm/DebugInfo/CodeView
  )
