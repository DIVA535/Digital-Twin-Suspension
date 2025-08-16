# Digital-Twin-Suspension
“Simulation of a Digital Twin for Vehicle Suspension Health Monitoring using Python (Quarter Car Model)”
# Digital Twin for Suspension Health Monitoring 🚗

## 📌 Project Description
This mini project simulates a **Quarter Car Suspension Model** in Python to demonstrate a **Digital Twin** for monitoring suspension health.  
By comparing **healthy vs. faulty suspension parameters (spring stiffness & damping)**, the system detects degradation in suspension performance.

---

## ⚙️ How It Works
1. Road input is simulated as a sine bump.  
2. The **quarter car model** equations are solved using `scipy.integrate.odeint`.  
3. Healthy suspension (original spring & damper) is compared with faulty suspension (degraded values).  
4. A **Health Index (RMS displacement)** is calculated to detect faults.  

---

## 🖥️ Requirements
Install Python libraries before running:
```bash
pip install numpy scipy matplotlib
