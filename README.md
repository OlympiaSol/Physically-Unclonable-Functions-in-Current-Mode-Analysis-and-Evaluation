**Diploma Thesis – University of Ioannina**  
**Title:** *Physically Unclonable Functions in Current Mode: Analysis and Evaluation*  
**Author:** *Christina Olympia Soldatou*  
**Supervisor:** *Professor Yiorgos Tsiatouhas*  
**Department:** Computer Science and Engineering, School of Engineering  
**Date:** February 2025  

### **Description**  
This repository contains the **design, implementation, and evaluation** of a **Current-Mode Physically Unclonable Function (PUF)**, developed as part of my diploma thesis at the **University of Ioannina**.  

PUFs are an essential hardware security primitive that leverage manufacturing variations to generate unique cryptographic keys without requiring memory storage, making them resistant to cloning and attacks. Traditional **voltage-based PUFs** often suffer from reliability issues due to **temperature and supply voltage fluctuations**.  

This thesis presents a **novel current-mode PUF architecture**, designed to enhance reliability against environmental variations. The circuit was implemented using **UMC's 90nm CMOS technology** and simulated in **Cadence Virtuoso & Spectre**. The design consists of an **array of 256 rows × 3 columns of PUF cells**, with **128 active rows**. Current-mode comparators are used to evaluate and compare the generated currents, identifying the "winning" column based on the strongest response.  

To assess the circuit's performance, **5,000 Monte-Carlo simulations** were conducted for each environmental condition. The results demonstrate:  
- **Reliability**: 96.81% under supply voltage variations  
- **Reliability**: 98.04% under temperature fluctuations  
- **Uniqueness**: 49.96%  
- **Uniformity**: 48.57%  
