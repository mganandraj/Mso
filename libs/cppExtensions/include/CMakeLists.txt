# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/cppExtensions/array.h
        ${CMAKE_CURRENT_SOURCE_DIR}/cppExtensions/autoRestore.h
        ${CMAKE_CURRENT_SOURCE_DIR}/cppExtensions/stringLiteral.h
  INCLUDES_WIN
        ${CMAKE_CURRENT_SOURCE_DIR}/cppExtensions/threadLocal_fls.h
  INCLUDES_POSIX
        ${CMAKE_CURRENT_SOURCE_DIR}/cppExtensions/threadLocal_pthread.h
)
