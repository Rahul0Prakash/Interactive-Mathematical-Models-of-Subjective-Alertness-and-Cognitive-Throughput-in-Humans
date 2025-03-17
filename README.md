
# Interactive Mathematical Models of Subjective Alertness and Cognitive Throughput in Humans

## 📖 Overview

This repository contains an implementation of **mathematical models for subjective alertness and cognitive throughput** based on **circadian rhythms, homeostatic sleep regulation, and external factors like light exposure**. The model predicts **fluctuations in cognitive performance and alertness** based on sleep-wake schedules.

This implementation is derived from the research paper:  
📄 **[Jewett & Kronauer (1999)](Jewett & Kronauer (1999).pdf): "Interactive Mathematical Models of Subjective Alertness and Cognitive Throughput in Humans"**  
and has been adapted for my **M.Sc. Usability Engineering thesis**:

📝 **"Beyond the Clock: Energy-Based, Mindful Time Management"**  
🎓 **Master of Science in Usability Engineering, Hochschule Rhein-Waal**  

This research explores **how circadian rhythms and homeostatic sleep drive** can be leveraged to improve productivity and well-being by strategically aligning work schedules with **cognitive performance peaks and dips**.

🔗 **GitHub Repository:** [Interactive Mathematical Models](https://github.com/Rahul0Prakash/Interactive-Mathematical-Models-of-Subjective-Alertness-and-Cognitive-Throughput-in-Humans)


## 🔬 Features & Model Overview

✔ **Circadian Rhythm Simulation** – Based on the **Jewett-Kronauer model**, this implementation tracks alertness fluctuations over the day.  
✔ **Sleep Debt & Homeostasis Integration** – Models the effects of prior wakefulness on cognitive performance.  
✔ **Light Exposure Effects** – Evaluates how different light intensities impact alertness.  
✔ **Configurable Sleep Schedule** – Users can set sleep and wake times to test different schedules.  
✔ **Graphical Visualizations** – Displays **circadian oscillations, alertness levels, and cognitive throughput predictions**.  

---

## 🔧 Installation & Dependencies

### **1️⃣ Install Required Libraries**
Before running the notebook, install the necessary Python dependencies:

```bash
pip install numpy matplotlib scipy
```
or, inside the Jupyter Notebook:
```python
!pip install numpy matplotlib scipy
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/Rahul0Prakash/Interactive-Mathematical-Models-of-Subjective-Alertness-and-Cognitive-Throughput-in-Humans.git
cd Interactive-Mathematical-Models-of-Subjective-Alertness-and-Cognitive-Throughput-in-Humans
```

### **3️⃣ Open the Jupyter Notebook**
```bash
jupyter notebook
```
Then, navigate to **`subjectiveAlertness_CognitiveThroughput.ipynb`** and run the simulation.

---

## 🚀 Running the Simulation

1️⃣ **Modify Parameters** – Open the Jupyter Notebook and update the following variables as needed:

#### **⏳ Sleep Timing (Modify Here)**
```python
sleep_start = 0  # Sleep start time 
wake_start = 8   # Wake time 
```

#### **📅 Simulation Time Settings**
```python
Simulation_Time = 24  # Total hours to simulate (full day)
dt = 20/60  # Time step in hours (20 minutes)
```

#### **☀️ Light Exposure Settings** (Simulations were run of the baseline constant routine experimental protocol (baseCR))
```python
I_wake = 150  # Light intensity during wakefulness (lux)
I_sleep = 0   # Light intensity during sleep (lux)
```

2️⃣ **Run All Notebook Cells** – Execute all cells to generate:
- **Circadian oscillation graphs**
- **Alertness level predictions**
- **Cognitive throughput analysis**
- **Comparison of different sleep schedules**

---

## 📊 Sample Output
The notebook generates visualizations showing **alertness levels over a 24-hour period**. These include:
✔ **Circadian oscillations**  
✔ **Homeostatic sleep drive variations**  
✔ **Cognitive throughput fluctuations**  
✔ **Impact of sleep deprivation & recovery**  

Example Graph:  
![Example Graph](Output-subjectiveAlertness_CognitiveThroughput.pdf) *(Replace with actual plot if available)*  

---

## ⚙️ Advanced Customization

- Modify **circadian rhythm parameters** for different chronotypes.
- Adjust **sleep homeostasis equations** to model long-term sleep deprivation.
- Integrate **real-world data** (e.g., Fitbit, sleep trackers) for more personalized simulations.

---

## 📜 References & Citations
- **Jewett, M. E., & Kronauer, R. E. (1999).** Interactive mathematical models of subjective alertness and cognitive throughput in humans.
- This implementation was developed for the **M.Sc. Usability Engineering thesis** at Hochschule Rhein-Waal.

---

## 🤝 Acknowledgments
- **Jewett & Kronauer (1999)** for their foundational work on **circadian rhythm modeling**.
- This project is part of **"Beyond the Clock"**, a study on **energy-based, mindful time management**.

---

## 📩 Contact
For inquiries, collaborations, or suggestions, feel free to reach out! 🚀
```

---

### ✅ **Next Steps**
📌 **To update your GitHub README:**
1. Go to: **[Edit README](https://github.com/Rahul0Prakash/Interactive-Mathematical-Models-of-Subjective-Alertness-and-Cognitive-Throughput-in-Humans/edit/main/README.md)**
2. Paste the updated README.md content above.
3. Click **Commit changes**.

🚀 Your repository is now **fully documented and ready for publishing!** 🎯 Let me know if you need **any refinements or additions**.
