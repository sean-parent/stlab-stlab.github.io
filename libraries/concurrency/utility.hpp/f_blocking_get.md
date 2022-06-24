---
layout: function
title: blocking_get
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/utility.hpp
overloads:
  "template <class T>\nauto blocking_get(future<T>, const std::chrono::nanoseconds &) -> decltype(x.get_try())":
    annotation:
      - deprecated (Use blocking_get_for instead.)
    arguments:
      - description: __OPTIONAL__
        name: x
        type: future<T>
      - description: __OPTIONAL__
        name: timeout
        type: const std::chrono::nanoseconds &
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <class T>\nauto blocking_get(future<T> x, const std::chrono::nanoseconds & timeout) -> decltype(x.get_try())"
  "template <typename T>\nT blocking_get(future<T>)":
    arguments:
      - description: __OPTIONAL__
        name: x
        type: future<T>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename T>\nT blocking_get(future<T> x)"
namespace:
  - stlab
  - v1
---
