# Pseudocode – Dual-Axis Solar Tracker

## Goal
Use 4 LDRs to track sun direction and move a solar panel via 2 servo motors.

## Flow
- [ ] Read light values from 4 LDRs (top, bottom, left, right)
- [ ] Compare top vs. bottom → vertical error
- [ ] Compare left vs. right → horizontal error
- [ ] Move vertical and horizontal servos to balance light
- [ ] Add hysteresis to avoid motor chatter
- [ ] Recenter at night using RTC timestamp
