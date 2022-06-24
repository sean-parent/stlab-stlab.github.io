---
layout: function
title: make_ready_future
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/utility.hpp
overloads:
  "template <typename E>\nfuture<void> make_ready_future(E)":
    arguments:
      - description: __OPTIONAL__
        name: executor
        type: E
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename E>\nfuture<void> make_ready_future(E executor)"
  "template <typename T, typename E>\nfuture<std::decay_t<T>> make_ready_future(T &&, E)":
    arguments:
      - description: __OPTIONAL__
        name: x
        type: T &&
      - description: __OPTIONAL__
        name: executor
        type: E
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename T, typename E>\nfuture<std::decay_t<T>> make_ready_future(T && x, E executor)"
namespace:
  - stlab
  - v1
---
