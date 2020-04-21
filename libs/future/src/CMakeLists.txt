# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_sources(
  SOURCES
        ${CMAKE_CURRENT_SOURCE_DIR}/cancellationTokenImpl.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/executor.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/futureImpl.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/futureImpl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/futureTask.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/promise.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/promiseGroup.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/whenAll.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/whenAny.cpp
)
