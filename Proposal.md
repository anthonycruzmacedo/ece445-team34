# 1. Introduction

## Problem

Around 3 million people per year develop pressure sores, with over 500,000 cases requiring extended hospitalization. Wheelchair users face a higher risk of developing pressure sores and their best solution today is to manually adjust every 15-30 minutes.

However, not all wheelchair users are able to readjust their seat position when needed (e.g., those with limited mobility). Those with limited sensation are at an even higher risk of developing pressure sores since they are unable to feel when a readjustment is needed.

While cushions provide some relief to wheelchair users, the solution they offer is static, limited, and does not eliminate the risk of pressure sores. Currently, research into dynamic solutions is limited and no commercially available solution exists.

## Solution

With a combination of resistive sensors, a programmable pneumatic pump, and thermoplastic polyurethane bladders, we will be able to create a dynamic seat cushion to relieve pressure for wheelchair users. The sensors will detect areas and time durations of high pressure(s), and then translate these signals into inflation controls for cushions in the surrounding areas.

We will be collaborating with Dr.Golecki’s group where we will handle the electronics portion (sensors, PCB + micorcontroller for air pump) and they will handle the mechanical portion (design of cushions). We are in charge of developing the high-resolution sensor array that determines where the user wants pressure to be relieved, optimizing for efficiency and compactness.

## Visual Aid

## High-Level Requirements

- The dynamic seat cushion fits within the dimensions 22in Wide x 15in Deep x 4in High so as to contrain the product to an appropriate size for standard wheelchairs.
- The sensor array detects when the time threshold is met for each area that meets or exceed the pressure threshold. The time threshold is set by the user in multiples of 5 minutes. The pressure threshold is to be defined (options include user-set PSI, percentage of high-low differential, etc.).
- When an area meets the time and pressure thresholds, the cushion bladder inflates in surrounding areas to a new pressure that drops the original area's pressure below the pressure threshold.

# 2. Design

## Block Diagram

## Subsystem Overview

## Subsystem Requirements

## Tolerance Analysis

# 3. Ethics and Safety
