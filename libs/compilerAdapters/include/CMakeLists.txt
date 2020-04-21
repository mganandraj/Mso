# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/compilerFeatures.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/compilerWarnings.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/compilerWarnings_impl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/cppMacros.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/cppMacrosDebug.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/declspecDefinitions.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/functionDecorations.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/intrinsics.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/linker.h
        ${CMAKE_CURRENT_SOURCE_DIR}/compilerAdapters/managedCpp.h
  )