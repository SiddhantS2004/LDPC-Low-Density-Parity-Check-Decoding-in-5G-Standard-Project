# 📡 LDPC Encoding and Decoding in 5G Standard

This repository contains the implementation of **Low-Density Parity-Check (LDPC) codes** used in the **5G New Radio (NR)** standard, developed as a course project for *CT216 - Introduction to Communication Systems* at DAIICT.

The project covers LDPC **encoding**, **modulation**, and **decoding** using both **hard-decision** and **soft-decision** (min-sum and sum-product) algorithms. All methods are implemented in line with the **3GPP TS 38.212** specifications.

---

## 🎯 Objectives

- Understand the structure and working of LDPC codes and their role in 5G communication.
- Implement encoding using base matrices and expansion factors as per 5G NR Base Graphs (BG1 and BG2).
- Simulate BPSK modulation and transmission over AWGN channels.
- Decode using:
  - Hard-decision decoding
  - Soft-decision decoding using Min-Sum
  - Enhanced decoding using Sum-Product algorithm

---

## 📚 Topics Covered

- LDPC Base Matrix and Expansion
- Encoding Examples and Rate Matching
- BPSK Modulation with AWGN Channel Simulation
- Hard Decoding Algorithm (Majority Voting)
- Soft Decoding Algorithms:
  - Min-Sum
  - Sum-Product (belief propagation)
- Performance Analysis:
  - Bit Error Rate (BER) vs. Eb/N0
  - Success Probability vs. Iterations
  - Comparison with Normal Approximation and Shannon Limits

---

## 🛠️ Technologies Used

- **Programming Language:** MATLAB
- **Simulation:** BPSK over AWGN
- **Graphs & Plotting:** Matplotlib / MATLAB plotting tools 
- **Reference Standard:** 3GPP TS 38.212

---

## 📈 Results Snapshot

- Implemented both BG1 and BG2 matrix structures
- Demonstrated hard-decision decoding with iterative parity checks
- Implemented Min-Sum soft decoding and compared performance
- Improved decoding using Sum-Product algorithm
- BER vs. Eb/N0 plotted for various code rates (1/4, 1/3, 1/2, 3/5, etc.)

---

## 👨‍🎓 Group Members (Group 24)

- Rishik Yalamanchili (202301258)  
- Chirag Katkoriya (202301259)  
- Mahek Jikkar (202301260)  
- Patel Nakul Jaymitkumar (202301261)  
- Priyanka Garg (202301262)  
- Yug Savalia (202301263)  
- Krish Patel (202301264)  
- Jalu Rishabh (202301265)  
- Vansh Vora (202301266)  
- Arav Vaitha (202301267)  
- Siddhant Shekhar (202301268)

---

## 🧑‍🏫 Faculty & Mentor

- **Professor:** Yash Vasavada  
- **Mentor:** Darpan Lungariya

---

## 📄 References

1. Gallager, R. G., *Low-Density Parity-Check Codes*, MIT Press  
2. 3GPP TS 38.212, *Multiplexing and channel coding*  
3. Andrew Thangaraj, NPTEL Lectures on LDPC Codes  
4. Communications Engineering Lab, KIT – LDPC Tutorials

---

> 📌 *This project was developed for academic learning purposes and demonstrates practical implementation of theoretical concepts in LDPC coding.*


