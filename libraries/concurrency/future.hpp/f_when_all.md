---
layout: function
title: when_all
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/future.hpp
overloads:
  "template <typename E, typename F, typename I>\nauto when_all(E, F, std::pair<I, I>)":
    arguments:
      - description: __OPTIONAL__
        name: executor
        type: E
      - description: __OPTIONAL__
        name: f
        type: F
      - description: __OPTIONAL__
        name: range
        type: std::pair<I, I>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename E, typename F, typename I>\nauto when_all(E executor, F f, std::pair<I, I> range)"
  "template <typename E, typename F, typename... Ts>\nauto when_all(E, F, future<Ts>...)":
    arguments:
      - description: __OPTIONAL__
        name: executor
        type: E
      - description: __OPTIONAL__
        name: f
        type: F
      - description: __OPTIONAL__
        name: args
        type: future<Ts>...
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename E, typename F, typename... Ts>\nauto when_all(E executor, F f, future<Ts>... args)"
namespace:
  - stlab
  - v1
---
