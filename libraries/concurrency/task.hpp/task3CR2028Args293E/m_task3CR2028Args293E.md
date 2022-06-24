---
layout: method
title: task<R (Args...)>
owner: __MISSING__
brief: __MISSING__
tags:
  - method
defined_in_file: concurrency/task.hpp
is_ctor: true
overloads:
  task<R (Args...)>():
    annotation:
      - default
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: task<R (Args...)>()
  task<R (Args...)>(const task<R (Args...)> &):
    annotation:
      - delete
    arguments:
      - description: __OPTIONAL__
        name: unnamed-0
        type: const task<R (Args...)> &
        unnamed: true
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: task<R (Args...)>(const task<R (Args...)> &)
  task<R (Args...)>(std::nullptr_t):
    arguments:
      - description: __OPTIONAL__
        name: unnamed-0
        type: std::nullptr_t
        unnamed: true
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: task<R (Args...)>(std::nullptr_t)
  task<R (Args...)>(task<R (Args...)> &&):
    arguments:
      - description: __OPTIONAL__
        name: x
        type: task<R (Args...)> &&
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: task<R (Args...)>(task<R (Args...)> && x)
  "template <class F, std::enable_if_t<!std::is_same<std::decay_t<F>, task<R (Args...)>>::value, bool> >\ntask<R (Args...)>(F &&)":
    arguments:
      - description: __OPTIONAL__
        name: f
        type: F &&
    description: __MISSING__
    return: __OPTIONAL__
    signature_with_names: "template <class F, std::enable_if_t<!std::is_same<std::decay_t<F>, task<R (Args...)>>::value, bool> >\ntask<R (Args...)>(F && f)"
---
