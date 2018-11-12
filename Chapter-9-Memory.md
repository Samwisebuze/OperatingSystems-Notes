# Chapter 9 - Memory

<!-- TOC -->

- [Chapter 9 - Memory](#chapter-9---memory)
	- [9.1 Background](#91-background)
		- [9.1.1 Basic Hardware](#911-basic-hardware)
		- [9.1.2 Address Binding](#912-address-binding)
		- [9.1.2 Logical Versus Physical Address Space](#912-logical-versus-physical-address-space)
		- [9.1.4 Dynamic Loading](#914-dynamic-loading)
		- [9.1.4 Dynamic Linking and Shared Libraries](#914-dynamic-linking-and-shared-libraries)
	- [9.2 Contiguous Memory](#92-contiguous-memory)
		- [9.2.1 Memory Protection](#921-memory-protection)
		- [9.2.2 Memory Allocation](#922-memory-allocation)
		- [9.2.3 Fragmentation](#923-fragmentation)
	- [9.3 Paging](#93-paging)
		- [9.3.1 Basic Method](#931-basic-method)
		- [9.3.2 Hardware Support](#932-hardware-support)
		- [9.3.3 Protection](#933-protection)
		- [9.3.4 Shared Pages](#934-shared-pages)
	- [9.4 Structure of the Page Table](#94-structure-of-the-page-table)
		- [9.4.1 Hierarchical Paging](#941-hierarchical-paging)
		- [9.4.2 Hashed Page Tables](#942-hashed-page-tables)
		- [9.4.3 Inverted Page Tables](#943-inverted-page-tables)
		- [9.4.4 Oracle SPARC Solaris](#944-oracle-sparc-solaris)
	- [9.5 Swapping](#95-swapping)
		- [9.5.1 Standard Swapping](#951-standard-swapping)
		- [9.5.2 Swapping with Paging](#952-swapping-with-paging)
		- [9.5.3 Swapping on Mobile Systems](#953-swapping-on-mobile-systems)
	- [9.6 Example: Intel 32- and 64-bit Architecture](#96-example-intel-32--and-64-bit-architecture)
		- [9.6.1 IA-32 Architecture](#961-ia-32-architecture)
		- [9.6.2 x86-64](#962-x86-64)
	- [9.7 Example: ARMv8 Architecture](#97-example-armv8-architecture)
	- [9.8 Summary](#98-summary)

<!-- /TOC -->

## 9.1 Background

**Memory consists of a large array of bytes, each with its own address.**

A typical instruction-execution cycle:

- Fetch an instruction from memory
  - CPU check the address in the PC (Program Counter)
- Decode the instruction
  - This may cause operands to be fetched from memory
- Store results back in memory

We can ignore _how_ a program generates memory addresses.

### 9.1.1 Basic Hardware



### 9.1.2 Address Binding

### 9.1.2 Logical Versus Physical Address Space

### 9.1.4 Dynamic Loading

### 9.1.4 Dynamic Linking and Shared Libraries

## 9.2 Contiguous Memory

### 9.2.1 Memory Protection

### 9.2.2 Memory Allocation

### 9.2.3 Fragmentation

## 9.3 Paging

### 9.3.1 Basic Method

### 9.3.2 Hardware Support

### 9.3.3 Protection

### 9.3.4 Shared Pages

## 9.4 Structure of the Page Table

### 9.4.1 Hierarchical Paging

### 9.4.2 Hashed Page Tables

### 9.4.3 Inverted Page Tables

### 9.4.4 Oracle SPARC Solaris

## 9.5 Swapping

### 9.5.1 Standard Swapping

### 9.5.2 Swapping with Paging

### 9.5.3 Swapping on Mobile Systems

## 9.6 Example: Intel 32- and 64-bit Architecture

### 9.6.1 IA-32 Architecture

### 9.6.2 x86-64

## 9.7 Example: ARMv8 Architecture

## 9.8 Summary