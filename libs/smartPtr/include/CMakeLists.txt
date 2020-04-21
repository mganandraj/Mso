# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/smartPtr/cntPtr.h
        ${CMAKE_CURRENT_SOURCE_DIR}/smartPtr/smartPointerBase.h
        ${CMAKE_CURRENT_SOURCE_DIR}/smartPtr/smartPointers.h
  INCLUDES_WIN
        ${CMAKE_CURRENT_SOURCE_DIR}/smartPtr/smartHandles.h
)