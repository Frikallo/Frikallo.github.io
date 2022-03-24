---
title: "Mesh Transformer JAX"
cover:
    image: mesh-transformer-jax.png
    relative: True
layout: page
hideMeta: True
status: "Completed"
domain: ["Language Modeling"]
deliverables: ["Code","Model"]
description: An implementation of model & data-parallel autoregressive language models with JAX and Haiku for distributed TPUs.
---

[Mesh Transformer JAX](https://github.com/kingoflolz/mesh-transformer-jax) is an implementation of model & data-parallel autoregressive language models, utilizing [Haiku](https://github.com/deepmind/dm-haiku) and the `xmap`/`pjit` operators in [JAX](https://github.com/google/jax) to distribute computation on TPUs.

As the designated successor to GPT-Neo, Mesh Transformer JAX was used to train GPT-J-6B, a six billion parameter language model. For more information on Mesh Transformer JAX and GPT-J-6B, see the [blog post by Aran Komatsuzaki](https://arankomatsuzaki.wordpress.com/2021/06/04/gpt-j/).