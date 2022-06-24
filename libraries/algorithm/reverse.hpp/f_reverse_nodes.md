---
layout: function
title: reverse_nodes
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: algorithm/reverse.hpp
overloads:
  "template <typename I>\nI reverse_nodes(I, I)":
    arguments:
      - description: __OPTIONAL__
        name: first
        type: I
      - description: __OPTIONAL__
        name: last
        type: I
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename I>\nI reverse_nodes(I first, I last)"
  "template <typename R>\ntypename R::iterator reverse_nodes(R &)":
    arguments:
      - description: __OPTIONAL__
        name: range
        type: R &
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename R>\ntypename R::iterator reverse_nodes(R & range)"
namespace:
  - stlab
  - unsafe
---
