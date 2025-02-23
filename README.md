
---

## 📡 90-Degree Branch Line Coupler - Design & Simulation

> **Ansys HFSS Simulation of a 90-degree Branch Line Coupler Operating at 2.4 GHz**  
> *Designed with 4 wave ports and optimized for S-parameter performance analysis.*

---

### 🔹 Introduction
A **90-degree branch line coupler** is a **four-port** passive device used in RF and microwave circuits to split or combine signals with a phase difference of 90°. It is commonly applied in **power dividers, balanced mixers, and antenna feeding networks.**

In this post, we document the **design, setup, and simulation** of a **branch line coupler** using **Ansys HFSS 2024 R2 Student Edition**.

---

## 🔍 Design Specifications
| **Parameter**     | **Value** |
|------------------|----------|
| **Operating Frequency** | 2.4 GHz |
| **Number of Ports** | 4 (Wave Ports) |
| **Substrate Material** | FR4 Epoxy |
| **Substrate Thickness** | 1.6 mm |
| **Patch Thickness** | 0.035 mm |
| **Dielectric Constant (εr)** | 4.4 |
| **Loss Tangent (tan δ)** | 0.02 |
| **Ground Plane Thickness** | 1.6 mm |

---

## 📐 Design & Setup

### **1️⃣ Substrate (FR4 Epoxy)**
- **Position:** `(-25, -25, -0.25) mm`
- **Size:** `(50 × 50 × 1.6) mm`

### **2️⃣ Ground Plane**
- **Position:** `(-25, -25, -0.25) mm`
- **Size:** `(50 × 50 × 1.6) mm`

### **3️⃣ Patch (Coupler Layout)**
- **Position:** `(0, 0, 1.6) mm`
- **Size:** `(24.7 × 19.7 × 0.035) mm`

### **4️⃣ Wave Ports**
| **Port** | **Position (X, Y, Z)** | **Size (mm)** |
|---------|--------------------|--------------|
| **Port 1** | `(10.05, -20, 1.6)` | `3 × -1.6` |
| **Port 2** | `(10.05, 20, 1.6)` | `3 × -1.6` |
| **Port 3** | `(-10.05, 20, 1.6)` | `3 × -1.6` |
| **Port 4** | `(-10.05, -20, 1.6)` | `3 × -1.6` |

---

## 🎯 Simulation Setup

### **📊 HFSS Solution Setup**
- **Solution Frequency:** `2.4 GHz`
- **Maximum Passes:** `6`
- **Delta S:** `0.02`

### **📊 Frequency Sweep Setup**
| **Type** | **Start (GHz)** | **Stop (GHz)** | **Step (GHz)** |
|---------|---------------|-------------|------------|
| Linear Step | `1 GHz` | `5 GHz` | `0.01 GHz` |

---

## 📈 Results & Analysis

### **1️⃣ S-Parameter Performance**
Below is the simulated **S-parameter plot** displaying reflection and transmission characteristics:

![Result - S parameter](https://github.com/user-attachments/assets/5676e29b-7c2d-4cb4-846d-6fb20280ae0e)


- **S11 (Return Loss):** Indicates how much signal is reflected at input.
- **S21, S31 (Transmission Coefficients):** Measure the power split between ports.
- **S41 (Isolation):** Represents the isolation between non-adjacent ports.

### **2️⃣ Final Design**
The **optimized branch line coupler** is displayed below:


![Screenshot (493)](https://github.com/user-attachments/assets/bfd007df-2702-4507-918c-ce69a9a4167f)

---

## 🚀 Conclusion
The **90-degree branch line coupler** designed for **2.4 GHz** successfully splits signals into **two equal parts** with a **90-degree phase shift**. The **S-parameter analysis** validates the performance with acceptable return loss and transmission characteristics.

✅ **Key Takeaways:**
- Designed in **Ansys HFSS** with **4 wave ports**.
- **S-parameters** confirm efficient power division.
- Useful in **antenna networks & RF front-end circuits**.

---

## 📌 Next Steps
🔹 **Further optimization** for better impedance matching.  
🔹 **Fabrication & Testing** for real-world performance validation.  
🔹 **Integration with RF front-end systems**.

💬 *Have any questions or suggestions? Feel free to comment below!*  

📌 **Follow for more RF & Microwave Design posts!** 🚀

---

