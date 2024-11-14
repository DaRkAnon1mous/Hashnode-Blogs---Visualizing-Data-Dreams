---
title: "Handling Errors Gracefully in Python with try, except, and finally"
datePublished: Tue Aug 06 2024 00:32:33 GMT+0000 (Coordinated Universal Time)
cuid: clzhornap000409mdcug18z9z
slug: handling-errors-gracefully-in-python-with-try-except-and-finally
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1722789599390/4c2f1da2-4225-4496-8c9f-2d6340c40314.png
tags: python, python3, python-beginner, exceptionhandling

---

#### Introduction

![Road to become a Python Ninja — Handling Exceptions | by VJ | Medium](https://miro.medium.com/v2/resize:fit:1400/1*H1w53c6-i93iXR6fipIr4A.png align="left")

Error handling is a critical aspect of robust software development. Python provides a straightforward and flexible approach to handle errors using `try`, `except`, and `finally` blocks. This blog post will guide you through these constructs, helping you write more resilient code.

#### The `try` Block

The `try` block allows you to test a block of code for errors. If an error occurs, it is intercepted, and the flow of control is transferred to the corresponding `except` block.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789007735/ae98b66f-6fda-48f4-98ef-b4f9db54b9c3.png align="left")

Output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789027653/1844090a-2962-4bc8-b3e1-f7e47b729d27.png align="left")

#### Multiple `except` Blocks

You can handle different exceptions separately using multiple `except` blocks:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789070172/5b4203be-1ab0-42be-95ef-90c7b4433bde.png align="left")

Output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789110841/8b60dcad-2d11-4ebd-b673-f5ae61382be5.png align="left")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789130383/7d3d3d6c-1feb-40d0-83a7-bf10ac217a8b.png align="left")

#### The `finally` Block

The `finally` block is optional and will always execute, regardless of whether an error occurred or not. It is commonly used for cleanup actions, such as closing files or releasing resources.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789217583/55c66ea0-6ffa-4921-8a42-de337f0d8c87.png align="left")

Output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789228938/1819cb9c-13b8-4223-8452-833d6141fc5f.png align="left")

#### The `else` Block

An `else` block can be added after the `except` block(s). It runs if no exceptions are raised in the `try` block:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789285655/dc123f8a-008a-421a-ada6-09cdcd491583.png align="left")

Output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789300462/1a6e2b1e-c5af-42c8-a6aa-7fc732a6eb8a.png align="left")

#### Raising Exceptions

You can raise exceptions manually using the `raise` keyword:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789419236/94f91764-fb7b-4e34-906e-d1d271006d38.png align="left")

Output:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1722789431033/96aeb8db-75e8-47e8-b466-50898b9569eb.png align="left")