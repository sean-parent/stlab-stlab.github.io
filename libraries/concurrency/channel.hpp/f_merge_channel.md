---
layout: function
title: merge_channel
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/channel.hpp
overloads:
  "template <typename M, typename S, typename F, typename... R>\nauto merge_channel(S, F, R...)":
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
    signature_with_names: "template <typename M, typename S, typename F, typename... R>\nauto merge_channel(S s, F f, R... upstream_receiver)"
namespace:
  - stlab
  - v1
---
