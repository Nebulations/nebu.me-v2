---
enabled: true
title: "Parmesan (OS)"
desc: "A basic 32-bit operating system built entirely in C."
preview: "example.gif"
links: {
    "github": "https://github.com/Nebulations/parmesan"
}
---

# Overview
**Goal**: The primary goal of this project was to learn how to code in C, how pointers worked and how memory works.<br>
**AI usage**: The entirety of the Makefile to build the operating system, as well as everything assembly related was AI generated and was not built by me; the rest of the project was designed and built by me, with AI being used to explain things to me.

# How it works
This is a relatively small operating system with nothing major. You can create your own shell commands in the `kernel/shell/cmds` directory, and register it in the `kernel/shell/cmds.c` file. There is no file system, no internet; everything runs in memory. There are a few standard utilities provided inside of the `lib` directory, so you can theoretically build relatively small apps and run them within this operating system.

# What I learnt
- How to write a program in C
- How a memory allocator works and how to implement one in C
- How an operating system works under the hood
- How a shell works
- How to handle user input from a command line interface
- What is a driver