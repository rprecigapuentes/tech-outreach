# Embedded Intelligence: From Neural Hardware to TinyML

### Authors
**Rosemberth Steeven Preciga Puentes**  
**Luis Guillermo Vaca Rincón**

---

## 📘 Overview

This one-hour educational presentation explores how modern hardware executes artificial intelligence locally — without relying on the cloud.  
The talk guides the audience through the evolution of *on-device AI*, from the mathematical principles of neural networks to specialized computing architectures like NPUs, and finally to TinyML systems capable of performing inference on microcontrollers.

Delivered as part of the course **Verificación de Sistemas Digitales (2025-I)** at **Universidad Nacional de Colombia**.

---

## 🧩 Structure

1. **Introduction**  
   Why AI is increasingly executed locally: privacy, latency, and energy efficiency as key motivators.

2. **Core Concepts**  
   - Neural networks, nodes, tensors, activation functions, weights, and loss functions.  
   - Floating-point operations and precision standards (IEEE 754).  
   - TOPS (Tera Operations per Second) as a performance metric.

3. **Hardware Foundations**  
   - Multiply–Accumulate (MAC) units as the computational heart of AI hardware.  
   - Functional overview of memory management (MMU, DMA, scratchpad SRAM).  
   - Energy–area tradeoffs in embedded designs.

4. **Precision and Quantization**  
   - Benefits of reduced precision (FP16, INT8, INT4).  
   - Quantization as a key enabler for mobile and embedded AI.  
   - Real industrial references (IBM, Siemens EDA, ResearchGate metrics).

5. **Commercial Implementations**  
   Case studies of leading hardware solutions:
   - **Apple Neural Engine (A11–A17 series)** — secure, energy-efficient AI in consumer devices.  
   - **Google Tensor & Pixel Visual/Neural Core** — on-device NLP and vision.  
   - **Samsung Exynos NPU** — architecture evolution and low-power optimization.  
   - **Qualcomm Snapdragon X Elite** — high-performance heterogeneous design for AI PCs.

6. **TinyML**  
   - Microcontrollers as the new AI frontier.  
   - Execution of neural models under 1 mW.  
   - Frameworks such as TensorFlow Lite Micro and ARM Ethos-U85 accelerators.  
   - Real-world applications: gesture recognition, wake-word detection, and environmental monitoring.

7. **Conclusions**  
   Embedded intelligence represents the convergence of hardware design, software optimization, and ethical computing.  
   On-device AI allows systems to be faster, safer, and more sustainable by reducing cloud dependency.

---

## 🧠 Key Takeaways

- Local AI execution improves privacy, latency, and energy efficiency.  
- Quantization and hardware specialization drive the next wave of embedded intelligence.  
- TinyML expands AI to micro-scale devices, transforming IoT into *intelligent edge systems*.  
- Future computing will rely on distributed intelligence — models that run where data is born.

---

## 📎 Resources

- Presentation slides: [View PDF](./slides.pdf)  
- References include IBM, ARM, Qualcomm, Samsung Semiconductor, IEEE 754, TinyML Foundation, and various academic and industrial whitepapers.

---

**Course:** *Verificación de Sistemas Digitales — Universidad Nacional de Colombia, 2025-I*  
**Language:** Spanish  
**Duration:** 1 hour
