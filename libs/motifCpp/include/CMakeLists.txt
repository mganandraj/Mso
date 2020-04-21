# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/assert_IgnorePlat_emptyImpl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/assert_motifApi.h
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/libletAwareMemLeakDetection.h
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/motifCppTest.h
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/motifCppTestBase.h
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/testCheck.h
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/testInfo.h
  INCLUDES_APPLE
        ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/assert_IgnorePlat_apple.h
)

if(${MSO_LIBLET_TEST} STREQUAL GTEST)
  liblet_includes(
    INCLUDES
          ${CMAKE_CURRENT_SOURCE_DIR}/motifCpp/gTestAdapter.h
  )
elseif(${MSO_LIBLET_TEST} STREQUAL XCTEST)
#  liblet_includes(
#    INCLUDES
#      motifcpp/xcTestAdapter.h
#  )
else()
  message(FATAL_ERROR "Unsupported MSO_LIBLET_TEST: ${MSO_LIBLET_TEST}")
endif()