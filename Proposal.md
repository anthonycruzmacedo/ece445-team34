# 1. Introduction

## Problem

Approximately 3 million people develop pressure sores every year, and over 500,000 cases require extended hospitalization. Wheelchair users face a higher risk of developing pressure sores and their best solution today is to manually adjust every 15-30 minutes. However, those with limited mobility and/or sensation are at a higher risk of developing pressure sores. This group of wheelchair users may struggle with manual readjustments and/or with feeling when a readjustment is needed (Robinson et al., 2023).

While conventional cushions provide some relief, the solution they offer is static, limited, and does not eliminate the risk of pressure sores due to its inability to adapt to the user. Moreover, research into dynamic solutions is limited and no commercially available dynamic solution exists.

## Solution

With a combination of resistive sensors, a programmable pneumatic pump, and thermoplastic polyurethane bladders, we will be able to create a dynamic seat cushion to relieve pressure for wheelchair users. The sensors will detect areas and time durations of high pressure(s), and then translate these signals into inflation controls for cushions in the surrounding areas.

We will be collaborating with Dr.Golecki’s group where we will handle the electronics portion (sensors, PCB + micorcontroller for air pump) and they will handle the mechanical portion (design of cushions). We are in charge of developing the high-resolution sensor array that determines where the user wants pressure to be relieved, optimizing for efficiency and compactness.

## Visual Aid

![](/images/Visual%20Diagram.png)

## High-Level Requirements

- The dynamic seat cushion fits within the dimensions 22in. Wide x 15in. Deep x 4in. High, which is suitable for standard wheelchairs.

- The sensor array signals the microcontroller when a target area exceeds the pressure threshold. While this signal is high, the microcontroller counts down to determine if the target meets the time threshold.

- When both thresholds are met, the microcontroller inflates areas surrounding a target such that the target drops below the pressure threshold.

![](/images/Visual%20Aid%20-%20Thresholds.png)

# 2. Design

## Block Diagram

## Subsystem Overview

## Subsystem Requirements

## Tolerance Analysis

# 3. Ethics and Safety
