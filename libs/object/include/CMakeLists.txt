# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

liblet_includes(
  INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/object/fixedSwarm.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/lazyInit.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/make.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/objectRefCount.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/objectWithWeakRef.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/queryCast.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/refCounted.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/refCountedObject.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/swarm.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/unknownObject.h
        ${CMAKE_CURRENT_SOURCE_DIR}/object/weakPtr.h
  )