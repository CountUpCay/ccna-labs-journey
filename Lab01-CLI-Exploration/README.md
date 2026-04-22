# CCNA Lab 01 – CLI Exploration

## Overview

This lab focuses on understanding how the Cisco IOS CLI works by testing commands across different modes.

## Lab Environment

* Device: Cisco Switch (SW1)
* Tool: Cisco Packet Tracer
* Topology: Single switch with 4 connected PCs

## Objectives

* Understand CLI modes
* Identify which commands work in each mode
* Learn how to navigate the CLI

## CLI Mode Testing

### User EXEC Mode (SW1>)

* show interfaces status → works
* show running-config → fails
* hostname CaysonSW1 → fails

### Privileged EXEC Mode (SW1#)

* Entered using enable
* show running-config → works

### Global Configuration Mode (SW1(config)#)

* Entered using configure terminal
* hostname CaysonSW1 → works
* show running-config → fails

## What I Learned

* CLI has different modes with different permissions
* Prompt symbols show your current level
* Commands only work in the correct mode

## Challenges

* Tried commands in the wrong mode
* Needed to pay attention to the prompt

## Screenshots

To be added
