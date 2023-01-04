---
title: Section 5 Notes
date: Monday, 28 November, 2022
---

# DFD

> Data flow diagram is _graphical_ representation that describes _processes_ and _data movement_ through the organization.

## Components

- Entity
- Process
    - Child processes
- Data flow (represented by _arrows_)
- Data Store

### Process

> Process is an _function_ performed for a specific business reason.

Every Process has
- number
- name (_verb_ phrases)
- at lease one output 
- at least one input
- can be broken down into child processes
- has the visual shape of a rounded rectangle

A process that has no output is _black-hole process_
A process that has no input is _Miracle process_

### Data flow
> description oof movement of data from one point to another.

- Data is _single_ piece or  _logical collection_ of *several* pieces of information.

### Data store
> is collection of data that is stored in some way( determined _later_ during the physical model)

Every data store has
- a number (unique identifier)
- a name
- at least one input data flows (unless it's crated by another dfd)
    - The data store exists already $\therefore$ it doesn't need an input data flow
- at least one output data flows
- shall be connected to process

### Entity

> Person,org,system that is external to the system but interacts (*provides* data or *receives* data) with it

- External Entity _examples_:
    - *person*
    - *orgs*
    - *department*
    - *another system*

- Every entity has 
    - name
    - can't be connected to another entity i.e. it's independent in existence
    - has a shape of two rectangles inside of each other.

## Development of dfd

- built in levels *ie.e series of DFDs)

*Reason* Most process are complex to be created in a single DFD

### Context diagram 
> is a single process has the name of the system with external entities - has no data store

### Diagram 0
- major process
- 7 to 9 process
- numbered
