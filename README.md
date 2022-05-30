# yb-example

## Overview

This repository contains the example code taken from https://github.com/yugabyte/cassandra-cpp-driver/blob/2.9.0-yb/examples/perf/perf.c and modified according to Veritas's use-case.

## Compilation

g++ demo_perf.c -L/usr/local/lib64/ -lcassandra -Wl,-rpath=/usr/local/lib64 -luv

