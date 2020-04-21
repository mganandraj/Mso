# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/platformAdapters/IUnknownShim.h
        ${CMAKE_CURRENT_SOURCE_DIR}/platformAdapters/types.h
  INCLUDES_WIN
        ${CMAKE_CURRENT_SOURCE_DIR}/platformAdapters/windowsFirst.h
)
