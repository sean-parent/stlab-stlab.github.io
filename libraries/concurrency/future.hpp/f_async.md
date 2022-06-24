---
layout: function
title: async
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/future.hpp
overloads:
  "template <typename E, typename F, typename... Args>\nauto async(E, F &&, Args &&...) -> future<detail::result_t<std::decay_t<F>, std::decay_t<Args>...>>":
    arguments:
      - description: __OPTIONAL__
        name: executor
        type: E
      - description: __OPTIONAL__
        name: f
        type: F &&
      - description: __OPTIONAL__
        name: args
        type: Args &&...
    description: __OPTIONAL__
    return: __OPTIONAL__
    signature_with_names: "template <typename E, typename F, typename... Args>\nauto async(E executor, F && f, Args &&... args) -> future<detail::result_t<std::decay_t<F>, std::decay_t<Args>...>>"
namespace:
  - stlab
  - v1
---
