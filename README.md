﻿# Apogee_triggered_parachute_ball
A fun parachute toy that detects as it reaches apogee when thrown.
It works by measuring Z-axis acceleration in the NED frame. this is done by doing a frame transformation on the accelerations measured by the imu(from body frame - NED frame).

Electronics Hardware:
IMU ICM20948
Microcontroller ESP32 WROOM-32
3V3 Buck-Boost Converter
1s Li-ion battery
micro servo motor
