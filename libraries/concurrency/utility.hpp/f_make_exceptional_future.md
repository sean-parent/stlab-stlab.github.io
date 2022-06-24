---
layout: function
title: make_exceptional_future
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/utility.hpp
overloads:
  "template <typename T, typename E>\nfuture<T> make_exceptional_future(std::exception_ptr, E)":
    arguments:
      - description: __OPTIONAL__
        name: error
        type: std::exception_ptr
      - description: __OPTIONAL__
        name: executor
        type: E
    description: __OPTIONAL__
    return: __OPTIONAL__
    signature_with_names: "template <typename T, typename E>\nfuture<T> make_exceptional_future(std::exception_ptr error, E executor)"
namespace:
  - stlab
  - v1
---
