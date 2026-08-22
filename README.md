# 8051-Based Digital Temperature Monitoring System

## Overview

This project implements a digital temperature monitoring system using the **AT89C51 (8051) microcontroller**. An **LM35 temperature sensor** is used to sense temperature, while an **ADC0804** converts the analog sensor output into digital data for processing by the microcontroller.

The measured temperature is displayed on a **16×2 LCD**.

The complete circuit was designed and tested using **Proteus simulation** while learning 8051 Assembly programming and peripheral interfacing.

## Objective

The objective of this project is to understand temperature sensing, analog-to-digital conversion, microcontroller interfacing, and LCD-based data visualization using the 8051 microcontroller.

## System Architecture

```text
       LM35
        │
        │ Analog Temperature Signal
        ▼
     ADC0804
        │
        │ Digital Data
        ▼
     AT89C51
      (8051)
        │
        │ LCD Data/Control
        ▼
     16×2 LCD
        │
        ▼
 Temperature Display
