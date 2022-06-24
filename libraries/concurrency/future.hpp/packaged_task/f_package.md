---
layout: function
title: package
owner: __MISSING__
brief: __MISSING__
tags:
  - function
defined_in_file: concurrency/future.hpp
overloads:
  auto package(std::function<void (stlab::task<void ()>)>, __lambda) -> std::pair<detail::packaged_task_from_signature_t<void ()>, future<detail::result_of_t_<void ()>>>:
    arguments:
      - description: __OPTIONAL__
        name: executor
        type: std::function<void (stlab::task<void ()>)>
      - description: __OPTIONAL__
        name: f
        type: __lambda
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: auto package(std::function<void (stlab::task<void ()>)> executor, __lambda f) -> std::pair<detail::packaged_task_from_signature_t<void ()>, future<detail::result_of_t_<void ()>>>
  "template <typename Sig, typename E, typename F>\nauto package(E, F &&) -> std::pair<detail::packaged_task_from_signature_t<Sig>, future<detail::result_of_t_<Sig>>>":
    arguments:
      - description: __OPTIONAL__
        name: executor
        type: E
        unnamed: true
      - description: __OPTIONAL__
        name: f
        type: F &&
        unnamed: true
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename Sig, typename E, typename F>\nauto package(E executor, F && f) -> std::pair<detail::packaged_task_from_signature_t<Sig>, future<detail::result_of_t_<Sig>>>"
  "template <typename Signature, typename E, typename F>\nauto package(E, F &&) -> std::pair<detail::packaged_task_from_signature_t<Signature>, future<detail::result_of_t_<Signature>>>":
    arguments:
      - description: __OPTIONAL__
        name: unnamed-0
        type: E
        unnamed: true
      - description: __OPTIONAL__
        name: unnamed-1
        type: F &&
        unnamed: true
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <typename Signature, typename E, typename F>\nauto package(E, F &&) -> std::pair<detail::packaged_task_from_signature_t<Signature>, future<detail::result_of_t_<Signature>>>"
namespace:
  - stlab
  - v1
---
