---
title: "A Framework for Efficient Analysis of String Constraints"
collection: talks
type: "Talk"
permalink: /talks/halfphd
venue: "Half PhD"
date: 2017-11-16
location: "Uppsala, Sweden"
---

Checking the satisfiability of string constraints is a crucial problem. It has been motivated by numerous application areas such as security, web programming and model checking. For example, cross-site scripting, one of the most common web vulnerabilities, is typically caused by improper handling of strings by web applications. However, existing string solvers are able to handle only fragments of string constraints because they come in very different forms.

We present a uniform and efficient framework for checking the satisfiability of a large class of string constraints. The framework is based on the observation that both satisfiability and unsatisfiability of common constraints can be demonstrated through witnesses with simple patterns. These patterns are captured using flat automata each of which consists of a sequence of simple loops.

We present a Counter-Example Guided Abstraction Refinement (CEGAR) framework which contains both an under- and an over-approximation module. The flow of information between the modules allows to increase the precision in an automatic manner. We have implemented the framework as a tool and performed extensive experimentation that demonstrates both the generality and efficiency of our method.
