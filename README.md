
---
<h1 align="center">⚡ Dev Flux ⚡</h1>

### A Software-Defined Virtual Sensor Framework for Edge-Centric Attack Simulation and Dataset Generation

<p align="center">
  <img src="https://i.pinimg.com/originals/82/9e/ad/829ead615e5e61cd01a1cc2d2a4dd1cc.png" alt="Dev Flux" width="1200">
</p>


---

## ℹ What is Dev Flux?

**Dev Flux** is a centralized, software-defined platform designed to **simulate, monitor, and record realistic edge device behavior** under both **normal** and **anomalous** conditions.

Instead of relying on expensive physical hardware such as routers, IoT devices, or authentication servers, Dev Flux creates **virtual sensors** that behave like real systems using:

- Mathematical models  
- Time-series equations  
- Controlled randomness  
- Scenario-driven state transitions  

The platform enables **reproducible experimentation**, **machine-learning-ready dataset generation**, and **multi-device anomaly research**, all through an intuitive web-based interface.


## 🛠️ Why Dev Flux Exists

Modern cybersecurity and edge computing research depends heavily on almost realistic testbeds. However, most researchers and students face serious limitations:

- Physical devices are expensive
- Testbed setup is complex and time-consuming
- Existing simulators generate unrealistic random data
- Multi-device and coordinated attack scenarios are hard to model
- Reproducible datasets are difficult to produce

**Dev Flux solves this problem** by providing a fully software-based alternative that produces **almost realistic, time-correlated, and labeled data**, suitable for research, teaching, and experimentation.


## 🌟 What This Project Enables

Dev Flux allows users to:

- Simulate realistic **device-level** behavior
- Inject controlled anomalies
- Monitor behavior live through a centralized dashboard
- Replay historical runs for inspection and analysis
- Automatically generate **ML-ready datasets** with proper labeling
- Study **multi-device and distributed attack patterns**
- Experiment **without any physical hardware**


## 🔑 Key Benefits

- **Hardware-Free Testbed**  
  No routers, IoT boards, or servers required.

- **Equation-Driven Sensor Models**  
  Data evolves over time instead of appearing as random noise.

- **Scenario-Based Experimentation**  
  Attacks can be injected gradually, suddenly, or in coordinated waves.

- **Reproducibility**  
  Same scenario → same behavior → consistent datasets.

- **ML Readiness**  
  Clean labels, timestamps, and structured outputs for anomaly detection research.

- **Educational Value**  
  Ideal for demonstrations, labs, and learning environments.

---

## 🗂 Project Evolution and Versioning

> Dev Flux is a **single evolving project**, developed iteratively to improve realism, usability, and research capability. Each version represents a **clear milestone**, not a separate idea.
> The repository reflects this journey transparently and intentionally. Below is a structured overview of each version.

<details>
  <summary><h2>🔹 Version 0 – Core System Foundation</h2></summary>
  <br>
    <p align="center">
      <img src="https://i.pinimg.com/originals/22/f0/f7/22f0f71abfd1218d3b56ba0b878ddb37.png" alt="Dev Flux Version" width="1200">
    </p>
  
  ### ⏩ Overview
  Dev Flux V0 establishes the **functional foundation** of the project. All core ideas, sensor models, dataset generation logic, and system behavior are present in this version.
  
  Access Site: <a href="https://dev-flux-v0.onrender.com" target="blank">Dev Flux (Version 0)</a>.

  ### ⏩ What Was Implemented
  - Virtual sensors for:
    - Network (normal + anomalous)
    - Authentication (normal + anomalous)
  - Equation-driven, time-correlated data generation
  - Threaded sensor execution
  - Live monitoring through a web interface
  - Historical run replay
  - Dataset generation and download
  - Clean labeling for ML use

 ### ⏩ User Manual
 1. Launch the application web. 
 2. Open the **Sensors** tab.
 3. Toggle individual sensors:
    - Network
    - Network Anomaly
    - Authentication
    - Authentication Anomaly
 4. Observe real-time data in live tables.
 5. Ensure all sensors are **OFF**. 
 6. Go to **Dataset Generator**, enter name and turn dataset mode **ON**. 
 7. The system automatically: 
    - Starts all sensors
    - Synchronizes logs
    - Applies ground-truth labels
 8. Stop dataset mode to: 
    - Package logs
    - Generate metadata
    - Create a ZIP dataset. [Download datasets directly from the UI]

**Best for:** ML pipelines, academic experiments, reproducible research. 

  ### ⏩ Technical Characteristics
  - Flask backend
  - JSONL-based logging
  - Mathematical and probabilistic sensor models
  - Bootstrap-based frontend
  - Premium UI with animated interactions

  ### ⏩ Purpose of V0
  - Prove feasibility of software-defined edge sensors
  - Demonstrate realistic data generation
  - Establish the complete end-to-end pipeline

</details>


<details>
  <summary><h2>🔹 Version 1 – UI Refinement & Code Stabilization</h2></summary>
  <br>
    <p align="center">
      <img src="https://i.pinimg.com/originals/2d/8b/b5/2d8bb56eb3e0d842b4135306d72e8862.png" alt="Dev Flux Version" width="1200">
    </p>
  
  ### ⏩ Overview
  Dev Flux V1 is **functionally equivalent to V0**. The system behavior, data models, and outputs remain the same.
  
  Access Site: <a href="https://dev-flux-v1.onrender.com" target="blank">Dev Flux (Version 1)</a>.

  ### ⏩ What Changed
  - Minor UI interaction refinements:
    - Smoother animations
    - Enhanced visual feedback
  - Internal code cleanup and structure improvements
  - Improved readability and maintainability
  - More consistent naming and organization

 ### ⏩ User Manual
 1. Launch the application web. 
 2. Open the **Sensors** tab.
 3. Toggle individual sensors:
    - Network
    - Network Anomaly
    - Authentication
    - Authentication Anomaly
 4. Observe real-time data in live tables.
 5. Ensure all sensors are **OFF**. 
 6. Go to **Dataset Generator**, enter name and turn dataset mode **ON**. 
 7. The system automatically: 
    - Starts all sensors
    - Synchronizes logs
    - Applies ground-truth labels
 8. Stop dataset mode to: 
    - Package logs
    - Generate metadata
    - Create a ZIP dataset. [Download datasets directly from the UI]

**Best for:** ML pipelines, academic experiments, reproducible research. 

  ### ⏩ What Remained the Same
  - Same sensor logic
  - Same equation-based models
  - Same dataset generation pipeline
  - Same capabilities and outputs

  ### ⏩ Purpose of V1
  - Polish the system without altering behavior
  - Improve maintainability and clarity
  - Prepare the project for further architectural expansion

</details>

<details>
  <summary><h2>🔹 Version 2 – Scenario-Driven Testbed Introduction</h2></summary>
  <br>
    <p align="center">
      <img src="https://i.pinimg.com/originals/79/e7/da/79e7daf995f77989a470823960c1b050.png" alt="Dev Flux Version" width="1200">
    </p>
  
  ### ⏩ Overview
  Dev Flux V2 marks the **first real architectural shift**. The project transitions from manual sensor control to a **scenario-driven testbed model**.

  
  Access Site: <a href="https://dev-flux-v2.onrender.com" target="blank">Dev Flux (Version 2)</a>.

  ### ⏩ What Was Implemented
  - Scenario engine with time-based phases
  - Automated switching between normal and attack states
  - Coordinated behavior across multiple sensors
  - Central testbed controller
  - Testbed execution UI

  ### ⏩ User Manual
  1. Select & Upload a scenario JSON file. 
  2. Start the testbed.
  3. The system automatically:
    - Switches between normal and attack phases
    - Coordinates multiple sensors
  4. Monitor:
    - Live sensor data
    - Detected anomalies
  5. Stop the testbed to save the session.
  6. Load past sessions for analysis.

  **Best for:** IDS testing, attack pattern evaluation, security research.

  ### ⏩ UI Scope
  - Testbed fully implemented and operational
  - Other system sections shown as informational placeholders

  ### ⏩ Technical Focus
  - Scenario JSON definitions
  - Timeline-driven state management
  - Centralized logging
  - Testbed-oriented UI layout

  ### ⏩ Purpose of V2
  - Introduce automation and repeatability
  - Enable structured experiments
  - Shift from manual control to orchestration

</details>


<details>
  <summary><h2>🔹 Version 3 – Testbed-Centric Research Platform</h2></summary>
  <br>
    <p align="center">
      <img src="https://i.pinimg.com/originals/74/8c/e5/748ce5b32c3e6c45966d8ac02e8528ca.png" alt="Dev Flux Version" width="1200">
    </p>
  
  ### ⏩ Overview
  Dev Flux V3 refines V2 by **narrowing focus entirely to the testbed**. All non-essential UI sections are removed to create a **clean, research-oriented interface**.

  
  Access Site: <a href="https://dev-flux-v3.onrender.com" target="blank">Dev Flux (Version 3)</a>.

  ### ⏩ What Changed
  - Testbed becomes the sole active UI module
  - Simplified interface for live monitoring and replay
  - Clear separation between:
    - Monitoring
    - Anomaly detection
    - Historical analysis

  ### ⏩ User Manual
  1. Select & Upload a scenario JSON file. 
  2. Start the testbed.
  3. The system automatically:
    - Switches between normal and attack phases
    - Coordinates multiple sensors
  4. Monitor:
    - Live sensor data
    - Detected anomalies
  5. Stop the testbed to save the session.

  **Best for:** IDS testing, attack pattern evaluation, security research.

  ### ⏩ What Remained the Same
  - Same scenario engine
  - Same testbed controller
  - Same sensor logic and data generation

  ### ⏩ Purpose of V3
  - Reduce UI noise
  - Emphasize experimentation and observation
  - Support academic and research demonstrations

</details>

<details>
  <summary><h2>🔹 Version S – Streamlit Demo & Concept Showcase</h2></summary>
  <br>
    <p align="center">
      <img src="https://i.pinimg.com/originals/f8/15/22/f81522aef275c0c7ca2330142dd55733.png" alt="Dev Flux Version" width="1200">
    </p>
  
  ### ⏩ Overview
  Dev Flux VS is **not a separate implementation**, but a **demonstration layer** built on the same conceptual model.
  
  Access Site: <a href="https://dev-flux-demo.streamlit.app" target="blank">Dev Flux (Streamlit Version)</a>.

  ### ⏩ What It Provides
  - Embedded, predefined scenarios
  - Timeline-driven attack visualization
  - Simplified controls for non-technical audiences
  - No setup or backend requiredI

### ⏩ User Manual
1. Open the Streamlit app.
2. Select scenario duration (1, 2, or 3 minutes).
3. Click **Run**.
4. Watch:
    - Timeline progression
    - Active attack indicators
    - Attack summary table
5. Pause, resume, or reset the simulation.

**Best for:** Quick demos, non-technical audiences.

 ### ⏩ Technical Characteristics
  - Streamlit-based interface
  - Auto-refreshing simulation timeline
  - Visual attack indicators
  - Stateless demo execution

  ### ⏩ Purpose of VS
  - Public demonstration
  - Quick understanding of the system concept
  - Basic Presentation and showcase use

</details>

---
