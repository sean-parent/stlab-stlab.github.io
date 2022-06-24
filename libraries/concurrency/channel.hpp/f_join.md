---
layout: function
title: join
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/channel.hpp
overloads:
  "template <typename S, typename F, typename... R>\nauto join(S, F, R...)":
    annotation:
      - deprecated (Use zip_with)
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
    signature_with_names: "template <typename S, typename F, typename... R>\nauto join(S s, F f, R... upstream_receiver)"
namespace:
  - stlab
  - v1
---
