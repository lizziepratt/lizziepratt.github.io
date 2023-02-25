---
layout: single
title:  "Vector bundles are determined by their transition functions"
date:   2022-03-04
categories: math
usemathjax: true
published: false
---
A basic question when you encounter any new category is to ask, when are two objects in it isomorphic? A couple weeks ago, I learned what a holomorphic vector bundle was. At the time my professor made the remark: "holomorphic vector bundles of rank r are determined up to isomorphism by their transition functions."

I asked him to define a morphism of vector bundles. Instead, he proved the remark (seemingly on the fly, it was very impressive). What follows is that proof.

Claim:
$$\{ \text{holomorphic vector bundles over } X \text{ of rank }r\} \\
= \varinjlim_{U = \{U_i\} \text{ open covering }} \{g_{ij}: U_{ij} \to \text{Gl}_r(\mathbb{C}) \text{ holomorphic } / g_{ij} \sim h_ig_{ij}h_j \}$$

Here $h_i: U_i \to \text{Gl}_r(\mathbb{C}).$

Remark: The entire right hand side is the first Cech cohomology group.

Proof:
