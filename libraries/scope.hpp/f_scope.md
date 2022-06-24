---
layout: function
title: scope
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: scope.hpp
overloads:
  "template <typename T, typename F>\nauto scope(std::mutex &, F &&)":
    arguments:
      - description: __OPTIONAL__
        name: m
        type: std::mutex &
      - description: __OPTIONAL__
        name: f
        type: F &&
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename T, typename F>\nauto scope(std::mutex & m, F && f)"
  "template <typename T, typename... Args>\nauto scope(Args &&...)":
    arguments:
      - description: __OPTIONAL__
        name: args
        type: Args &&...
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename T, typename... Args>\nauto scope(Args &&... args)"
namespace:
  - stlab
  - v1
---
