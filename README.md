# Ultra Low-Voltage Low-Power CMOS 5-2 Compressor

This project implements an **ultra low-voltage, low-power CMOS 5:2 compressor** based on **Figure 13** from the IEEE paper  
*“Ultra Low-Voltage Low-Power CMOS 4-2 and 5-2 Compressors for Fast Arithmetic Circuits.”*  

Designed and simulated in **Cadence Virtuoso** using the **gpdk045 (45 nm CMOS)** technology.  
The focus is on optimizing **power**, **delay**, and **area** for efficient high-speed arithmetic circuits used in **VLSI** and **DSP** systems.

---

## 🔧 Features
- Implemented XOR, XNOR, and MUX submodules from scratch  
- Verified transient performance for all 128 input combinations  
- Achieved full-swing outputs and low Power–Delay Product (PDP)  
- Designed following IEEE Figure 13 reference schematic  

---

## 🧠 Tools & Technology
| Parameter | Description |
|------------|-------------|
| **Tool Used** | Cadence Virtuoso |
| **Technology Node** | 45 nm CMOS (gpdk045) |
| **Simulation Type** | Transient (Cadence ADE) |
| **Supply Voltage (VDD)** | 0.8 V – 1.2 V |
| **Analysis Focus** | Power, Delay, PDP, Full-Swing Verification |

---

## 🚀 How to Open the Project in Cadence
1. **Download** the project folder from this repository.  
2. **Open a terminal** inside the downloaded directory.  
3. **Follow the setup commands** mentioned in the included `README_NOTES.txt` (or the provided Notepad file).  
4. Launch **Cadence Virtuoso**.  
5. Use the **Library Manager** to open:
   - `Schematic` view for circuit design  
   - `Layout` view for DRC/LVS verification  
   - Run **Transient Simulation** in ADE to view output waveforms  

---

## 📄 Reference
**IEEE Paper:**  
T. K. B. Rao, D. Radhakrishnan, and P. V. Rao,  
“Ultra Low-Voltage Low-Power CMOS 4-2 and 5-2 Compressors for Fast Arithmetic Circuits,”  
*IEEE Transactions on Circuits and Systems II: Express Briefs*,  
Vol. 54, No. 5, pp. 412–416, May 2007.

---

## 👥 Contributors
- **Chandan Sai Pavan Padala**
- **D Rushikesh**
