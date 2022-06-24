---
layout: function
title: for_each_argument
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: utility.hpp
overloads:
  "template <class F, class... Args>\nvoid for_each_argument(F &&, Args &&...)":
    arguments:
      - description: __OPTIONAL__
        name: f
        type: F &&
      - description: __OPTIONAL__
        name: args
        type: Args &&...
    description: __OPTIONAL__
    return: __OPTIONAL__
    signature_with_names: "template <class F, class... Args>\nvoid for_each_argument(F && f, Args &&... args)"
namespace:
  - stlab
  - v1
---
