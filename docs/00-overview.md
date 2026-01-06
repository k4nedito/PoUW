# Project Overview

## Motivation

Some time ago I was actually thinking about this idea of replacing PoW with some arbitrary useful work like training ML models. And eventually I got some free time and motivation to do my first ever research. 

There are probably tons of ongoing research papers on academia level exploring this idea, even the very idea I'm trying to conceptualize in this repo - the _Proof of Useful Work_. In fact [this paper](https://www.mdpi.com/2073-8994/14/9/1831) with same name goes really deep in this concept.

Obviously I'm not trying to be that extensive with this research and I want to emphasize a lot on this - **I'm not trying to build a
blockchain, or a cryptocurrency, or a production level protocol**. This is simply to entertain the idea of possibility of replacing existing consensus mechanisms with something useful in some arbitrary system.

## Scope

This project focuses on:
- optimization-based work functions
- deterministic verification
- competitive solution discovery

This project explicitly does **NOT attempt to**:
- build a production blockchain
- design token economics
- solve full decentralization


## High-Level Idea
A shared optimization problem is defined at genesis. Validators compete to submit strictly improving solutions. The global state advances monotonically as better solutions are found.