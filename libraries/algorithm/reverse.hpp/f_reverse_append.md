---
layout: function
title: reverse_append
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: algorithm/reverse.hpp
overloads:
  "template <typename I>\nI reverse_append(I, I, I)":
    arguments:
      - description: __OPTIONAL__
        name: first
        type: I
      - description: __OPTIONAL__
        name: last
        type: I
      - description: __OPTIONAL__
        name: result
        type: I
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename I>\nI reverse_append(I first, I last, I result)"
  "template <typename R, typename I>\nI reverse_append(R &, I)":
    arguments:
      - description: __OPTIONAL__
        name: range
        type: R &
      - description: __OPTIONAL__
        name: result
        type: I
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename R, typename I>\nI reverse_append(R & range, I result)"
namespace:
  - stlab
  - unsafe
---
