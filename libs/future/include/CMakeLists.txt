# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/future/cancellationToken.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/arrayView.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/cancellationErrorProvider.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/cancellationException.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/executor.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/futureFuncInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/futureInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/futureTask.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/futureWeakPtrInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/ifuture.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/maybeInvoker.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/promiseGroupInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/promiseInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/resultTraits.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/sharedFutureInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/timeoutException.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/whenAllInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/details/whenAnyInl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/future.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/futureForwardDecl.h
        ${CMAKE_CURRENT_SOURCE_DIR}/future/futureWait.h
)
