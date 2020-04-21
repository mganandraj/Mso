# Copyright (c) Microsoft Corporation.
# Licensed under the MIT license.

set(THREADS_PREFER_PTHREAD_FLAG ON)
find_package(Threads QUIET)

liblet(eventWaitHandle
  DEPENDS
    Mso::object
  DEPENDS_LINUX
    Threads::Threads
)