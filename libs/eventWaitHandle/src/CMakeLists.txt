# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_sources(
  SOURCES
        ${CMAKE_CURRENT_SOURCE_DIR}/eventWaitHandleImpl.h
  SOURCES_WIN
        ${CMAKE_CURRENT_SOURCE_DIR}/eventWaitHandleImpl_win.cpp
  SOURCES_POSIX
        ${CMAKE_CURRENT_SOURCE_DIR}/eventWaitHandleImpl_posix.cpp
)