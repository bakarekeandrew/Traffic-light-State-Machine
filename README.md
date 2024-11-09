# Traffic-light-State-Machine
Bakareke Andrew 25497

State Machine of Traffic Light of Gishushu 
==========================================
<img width="261" alt="Software modeliing and design" src="https://github.com/user-attachments/assets/76af17ca-7530-424c-900d-0a8badc48585">
# Gishushu Traffic Light Control System

## Overview
 This is a State machine for controlling traffic lights at the Gishushu intersection. The system manages traffic flow through three distinct states (Green, Yellow, and Red) with specific 
 transition rules and timing conditions.

## State Machine Description

### States
1. **Green Light**
   - Initial state for allowing traffic flow
   - Transitions to Yellow when preparing to stop
   - Duration: [Configurable] seconds

2. **Yellow Light**
   - Intermediate warning state
   - Indicates preparation for stop
   - Duration: [Configurable] seconds (typically 3-5 seconds)

3. **Red Light**
   - Stop state
   - All vehicles must come to a complete stop
   - Duration: [Configurable] seconds

### State Transitions
- Green → Yellow: "Preparing to stop" transition
- Yellow → Red: "Cars must stop" transition
- Red → Green: "Cycle repeating" transition

