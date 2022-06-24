---
layout: function
title: merge
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/channel.hpp
overloads:
  "template <typename S, typename F, typename... R>\nauto merge(S, F, R...)":
    annotation:
      - deprecated (Use merge_channel<unordered_t>)
    arguments:
      - description: __OPTIONAL__
        name: s
        type: S
      - description: __OPTIONAL__
        name: f
        type: F
      - description: __OPTIONAL__
        name: upstream_receiver
        type: R...
    description: __OPTIONAL__
    return: __OPTIONAL__
    signature_with_names: "template <typename S, typename F, typename... R>\nauto merge(S s, F f, R... upstream_receiver)"
namespace:
  - stlab
  - v1
---
