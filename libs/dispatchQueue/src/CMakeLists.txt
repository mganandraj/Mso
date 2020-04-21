# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_sources(
  SOURCES
        ${CMAKE_CURRENT_SOURCE_DIR}/looperScheduler.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/queueService.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/queueService.h
        ${CMAKE_CURRENT_SOURCE_DIR}/taskBatch.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/taskBatch.h
        ${CMAKE_CURRENT_SOURCE_DIR}/taskContext.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/taskContext.h
        ${CMAKE_CURRENT_SOURCE_DIR}/taskQueue.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/taskQueue.h
        ${CMAKE_CURRENT_SOURCE_DIR}/threadMutex.h
        ${CMAKE_CURRENT_SOURCE_DIR}/uiSchedulerStub.h
  SOURCES_APPLE
        ${CMAKE_CURRENT_SOURCE_DIR}/threadPoolScheduler_linux.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/uiScheduler_linux.cpp
  SOURCES_LINUX
        ${CMAKE_CURRENT_SOURCE_DIR}/threadPoolScheduler_linux.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/uiScheduler_linux.cpp
  SOURCES_WIN
        ${CMAKE_CURRENT_SOURCE_DIR}/threadPoolScheduler_win.cpp
  SOURCES_WIN32
        ${CMAKE_CURRENT_SOURCE_DIR}/uiScheduler_linux.cpp
  SOURCES_WINRT
        ${CMAKE_CURRENT_SOURCE_DIR}/uiScheduler_winrt.cpp
)
