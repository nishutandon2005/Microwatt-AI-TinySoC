# Tiny AI Accelerator on OpenFrame

## Overview
Custom SoC on **OpenFrame** with a **4×4 systolic MAC-array** for real-time edge AI. Performs **keyword spotting ("Start"/"Stop")** and optional gesture classification using quantized tinyML models. **No cloud needed, <1mW power.**  

## Problem
Edge AI devices face latency, power, privacy, and resource constraints. **No open-source, tinyML ASIC exists** for ultra-low-power real-time inference.  

## Solution
- **Hardware MAC-array:** Fast matrix multiplication  
- **TinyML Model:** 1.8KB quantized weights  
- **GPIO/ADC Interface:** Live voice → LED  
- **Performance:** <10μs inference, <1mW power  

## Demo
1. Say **"Start"** → LED ON  
2. Say **"Stop"** → LED OFF  
3. Optional gesture control → LED PWM  

## Innovation & Impact
- **First tinyML ASIC on OpenFrame** platform  
- Ultra-low-latency hardware acceleration for edge AI  
- Fully **open-source, reproducible, hackathon-ready**  
- **Interactive demo** highlights real-world usability  
- **Educational value:** demonstrates AI + custom silicon co-design  

**License:** CC0 1.0 – Public Domain
