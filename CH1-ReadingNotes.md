# Chapter 1 - Introduction

<!-- TOC -->

- [Chapter 1 - Introduction](#chapter-1---introduction)
  - [What Operating Systems Do](#what-operating-systems-do)
    - [User View](#user-view)
    - [System View](#system-view)
    - [Defining Operating Systems](#defining-operating-systems)
  - [Computer-System Organization](#computer-system-organization)
    - [Interrupts](#interrupts)
      - [Overview](#overview)
      - [Implementation](#implementation)
    - [Storage Structure](#storage-structure)
    - [I/O Structure](#io-structure)
  - [Computer-System Architecture](#computer-system-architecture)
    - [Single-Processor Systems](#single-processor-systems)
    - [Multiprocessor Systems](#multiprocessor-systems)
    - [Clustered systems](#clustered-systems)
  - [Operating-Systems Operations](#operating-systems-operations)
    - [Multiprogramming and Multitasking](#multiprogramming-and-multitasking)
    - [Dual-Mode and Multimode Operation](#dual-mode-and-multimode-operation)
    - [Timer](#timer)
  - [Resource Management](#resource-management)
    - [Process Management](#process-management)
    - [Memory Management](#memory-management)
    - [File-System Management](#file-system-management)
    - [Mass-Storage Management](#mass-storage-management)
    - [Cache Management](#cache-management)
    - [I/O System Management](#io-system-management)
  - [Security and Protection](#security-and-protection)
  - [Virtualization](#virtualization)
  - [Distributed Systems](#distributed-systems)
  - [Kernel Data Structures](#kernel-data-structures)
    - [Lists, Stacks, and Queues](#lists-stacks-and-queues)
    - [Trees](#trees)
    - [Hash Functions and Maps](#hash-functions-and-maps)
    - [Bitmaps](#bitmaps)
  - [Computing Environments](#computing-environments)
    - [Traditional Computing](#traditional-computing)
    - [Mobile Computing](#mobile-computing)
    - [Client-Server Computing](#client-server-computing)
    - [Peer-to-Peer Computing](#peer-to-peer-computing)
    - [Cloud Computing](#cloud-computing)
    - [Real-Time Embedded Systems](#real-time-embedded-systems)
  - [Free and Open-Source Operating Systems](#free-and-open-source-operating-systems)
    - [History](#history)
    - [Free Operating Systems](#free-operating-systems)
    - [GNU/Linux](#gnulinux)
    - [BSD Linux](#bsd-linux)
    - [Solaris](#solaris)
    - [Open-Source Systems as Learning Tools](#open-source-systems-as-learning-tools)
  - [Summary](#summary)

<!-- /TOC -->

---

## What Operating Systems Do

- A Computer system can be divided into roughly four components
  - the ***Hardware***
  - the ***Operating System***
  - the ***Application Programs***
  - the ***User***

- **The Hardware**
  - the Central Processing Unit (CPU)
  - the Memory (RAM, Cache, Registers)
  - the input/output (I/O) devices
- **The Application Program**
  - define ways in which the resources are used to solve users' computing problems'
  - Ex: Word processors, spreadsheets. compliers, web browsers
- **The Operating System**
  - Controls hardware
  - Manages Resources

> An operating System is similar to a government. Like a government, it performs no useful function by itself.

### User View

***The User view varies according t the interface being used***

- Laptops and Desktops are optimized for single use(one user at a time). So their OS's are:
  - designed for *ease of use*
  - designed with performance and security focuses
  - no focus on **resource utilization**

Some devices offer little to no user view, i.e ***embedded computers***

### System View

The Operating System is most intimately involved with the hardware as a ***resource allocator***.

Many resources are involved in problem solving:

- CPU Time
- Memory Space
- Storage space
- I/O Devices
- etc.

The OS arbitrates over all the requests and organizes them to operate the system efficiently and fairly.

A Operating system is a **Control Program**. A Control Program manages the execution of ser programs to prevent errors and improper use of the computer.

### Defining Operating Systems

Operating Systems are varied and many because of the multitude of designs and uses of computers.

## Computer-System Organization

### Interrupts

#### Overview

#### Implementation

### Storage Structure

### I/O Structure

## Computer-System Architecture

### Single-Processor Systems

### Multiprocessor Systems

### Clustered systems

## Operating-Systems Operations

### Multiprogramming and Multitasking

### Dual-Mode and Multimode Operation

### Timer

## Resource Management

### Process Management

### Memory Management

### File-System Management

### Mass-Storage Management

### Cache Management

### I/O System Management

## Security and Protection

## Virtualization

## Distributed Systems

## Kernel Data Structures

### Lists, Stacks, and Queues

### Trees

### Hash Functions and Maps

### Bitmaps

## Computing Environments

### Traditional Computing

### Mobile Computing

### Client-Server Computing

### Peer-to-Peer Computing

### Cloud Computing

### Real-Time Embedded Systems

## Free and Open-Source Operating Systems

### History

### Free Operating Systems

### GNU/Linux

### BSD Linux

### Solaris

### Open-Source Systems as Learning Tools

## Summary