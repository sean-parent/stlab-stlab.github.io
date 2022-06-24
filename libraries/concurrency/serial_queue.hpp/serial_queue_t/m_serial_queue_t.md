---
layout: method
title: serial_queue_t
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined_in_file: concurrency/serial_queue.hpp
is_ctor: true
overloads:
  serial_queue_t(const stlab::serial_queue_t &):
    arguments:
      - description: __OPTIONAL__
        name: unnamed-0
        type: const stlab::serial_queue_t &
        unnamed: true
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: serial_queue_t(const stlab::serial_queue_t &)
  serial_queue_t(stlab::serial_queue_t &&):
    arguments:
      - description: __OPTIONAL__
        name: unnamed-0
        type: stlab::serial_queue_t &&
        unnamed: true
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: serial_queue_t(stlab::serial_queue_t &&)
  "template <typename Executor>\nexplicit serial_queue_t(Executor, stlab::schedule_mode)":
    arguments:
      - description: __OPTIONAL__
        name: e
        type: Executor
      - description: __OPTIONAL__
        name: mode
        type: stlab::schedule_mode
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename Executor>\nexplicit serial_queue_t(Executor e, stlab::schedule_mode mode)"
---
