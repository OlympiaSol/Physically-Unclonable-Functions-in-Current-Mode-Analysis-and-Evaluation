# **Development and Analysis of a Physically Unclonable Function Circuit**  

### **Diploma Thesis – University of Ioannina**  
**Author:** Christina Olympia Soldatou  
**Supervisor:** Professor Yiorgos Tsiatouhas  
**Department:** Computer Science and Engineering, School of Engineering  
**Date:** February 2025  

## **Overview**  
This repository contains the design, implementation, and evaluation of a **Current-Mode Physically Unclonable Function (PUF)**, developed as part of my diploma thesis at the **University of Ioannina**.  

Physically Unclonable Functions (PUFs) are a fundamental hardware security technology that leverages manufacturing variations in integrated circuits to generate unique cryptographic keys. Unlike traditional security methods, PUFs do not require key storage in memory, making them resilient to cloning and data extraction attacks.  

This thesis presents a novel **current-mode PUF architecture** designed to improve **reliability against environmental fluctuations**, such as temperature and supply voltage variations. The circuit was implemented using **UMC's 90nm CMOS technology** and evaluated through **Monte Carlo simulations** in **Cadence Virtuoso & Spectre**.  

## **Key Features**  
The proposed PUF operates based on **current differentials** rather than voltage, enhancing stability and reliability. The design consists of a **256×3 PUF array**, with **128 active rows** generating unique cryptographic keys. **Current sensing comparators** are used to determine the strongest response for authentication.  

To validate performance, **5,000 Monte Carlo simulations** were conducted under different environmental conditions. The results demonstrate **96.81% reliability** under **supply voltage variations**, **98.04% reliability** under **temperature fluctuations**, **49.96% uniqueness**, and **48.57% uniformity**.  
