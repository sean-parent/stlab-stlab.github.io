---
layout: method
title: operator|
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined_in_file: concurrency/channel.hpp
overloads:
  auto operator|(sender<T>):
    arguments:
      - description: __OPTIONAL__
        name: send
        type: sender<T>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: auto operator|(sender<T> send)
  "template <typename F>\nauto operator|(F &&) const":
    arguments:
      - description: __OPTIONAL__
        name: f
        type: F &&
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename F>\nauto operator|(F && f) const"
  "template <typename F>\nauto operator|(detail::annotated_process<F>)":
    arguments:
      - description: __OPTIONAL__
        name: ap
        type: detail::annotated_process<F>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename F>\nauto operator|(detail::annotated_process<F> ap)"
  "template <typename F>\nauto operator|(executor_task_pair<F>)":
    arguments:
      - description: __OPTIONAL__
        name: etp
        type: executor_task_pair<F>
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename F>\nauto operator|(executor_task_pair<F> etp)"
---
