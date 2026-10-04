# Engineering Portfolio

I am a biomedical engineer and biomedical data science graduate student interested in developing technologies at the intersection of **medical devices, computational biology, machine learning, medical imaging, and engineering design**.

This repository contains selected research and engineering projects from my academic and research experience. Each project report provides additional detail on the problem, methodology, design process, results, and technical contributions.

---

## Projects

### 🩸 Soft Optical Sensor for Bleeding Detection During Colonoscopy
**Medical Devices · Soft Robotics · Sensors · PCB Design · Signal Processing**

Developed a soft optical sensing platform designed to detect bleeding outside the distal camera's field of view during colonoscopy. My work spanned multiple generations of the device, including fabrication of wired sensors, ex vivo testing using a bovine colon at Brigham and Women's Hospital, fluidic-system development, real-time bleeding visualization, flexible PCB design for the wireless platform, and exploratory IMU/Kalman-filter-based localization.

**Technologies:** MATLAB, soft lithography, PDMS, optical sensing, fluidics, KiCad, PCB design, IMU sensor fusion, Kalman filtering

[View Project Report](./Soft_Optical_Blood_Sensor_Portfolio_Report.pdf)

**Publications:**  
- *Ex vivo evaluation of a soft optical blood sensor for colonoscopy*, Device, 2024  
- *A Wireless Soft Optical Blood Sensor for Colonoscopy*, Advanced Sensor Research, 2025

---

### 🧪 Continuous-Flow Hormone Bioreactor
**Biomedical Engineering · Fluidics · Simulation · Control Systems**

Designed and tested a continuous-flow bioreactor intended to reproduce dynamic physiological hormone fluctuations for in vitro tendon research. The system combined MATLAB-controlled peristaltic pumping, passive mixing geometries, CAD-designed culture wells, COMSOL fluid simulations, and fluorescence-based experimental validation.

Sixteen design iterations were evaluated computationally and experimentally to investigate mixing performance and fluid distribution.

**Technologies:** COMSOL Multiphysics, MATLAB, Onshape, CAD, fluid mechanics, fluorescence assays

[View Project Report](./Continuous_Flow_Hormone_Bioreactor_Report.pdf)

---

### 🧬 Morphological Profiling for CAR-T Gene Discovery
**Computational Biology · Machine Learning · Cell Painting**

Developed a computational approach for identifying candidate CRISPR gene knockouts using morphological profiles from the JUMP Cell Painting dataset.

My primary contribution was developing the **fuzzy k-means clustering approach and code** used to generate probabilistic gene-level morphological states. These representations were combined with pathway-based ridge regression models to identify genes with morphological effects similar to ACAT1, a gene associated with enhanced T-cell function.

**Technologies:** Python, fuzzy k-means, PCA, ridge regression, Cell Painting, Gene Ontology, dimensionality reduction

[View Project Report](./Morphological_Profiling_CAR_T_Gene_Discovery_Report.pdf)

---

### 🚪 Room Occupancy Monitoring System
**Embedded Systems · Sensors · Arduino · CAD**

Designed and built an embedded room-occupancy monitoring system using paired infrared break-beam sensors to determine whether individuals were entering or leaving a room.

The system displayed the current occupancy on an LCD and activated visual and audible alerts when a configurable occupancy limit was exceeded. Testing demonstrated **100% counting accuracy at 2–3 mph, 98% at 4–5 mph, and 96% at 6–7 mph**.

**Technologies:** Arduino, infrared sensors, embedded programming, CAD, 3D printing, electronics

[View Project Report](./Room_Occupancy_Monitor_Final_Report.pdf)

---

### 🌍 European Road Network Graph Analysis
**Algorithms · Graph Theory · Rust**

Built a graph-analysis program representing **1,174 European cities** as nodes and highway connections as edges.

Implemented breadth-first search from scratch to calculate shortest-path distances and analyze how the connectivity of the road network changes as the allowed number of "degrees of separation" increases.

**Technologies:** Rust, breadth-first search, graph theory, adjacency lists, data analysis

[View Project Report](./European_Road_Network_Graph_Analysis_Report.pdf)

---

### 🌉 Truss Optimization and Structural Analysis
**Engineering Design · Structural Mechanics · MATLAB**

Designed and optimized a truss structure with the objective of maximizing its **load-to-cost ratio**. Structural analysis was used to calculate internal member forces, identify zero-force members, predict the limiting structural element, and reduce unnecessary material while maintaining load capacity.

**Technologies:** MATLAB, structural analysis, statics, optimization, engineering design

[View Project Report](./Truss_Optimization_Final_Design_Report.pdf)

---

## Research Interests

- Biomedical device development
- Biomedical data science
- Medical imaging and computer vision
- Machine learning for healthcare
- Computational biology
- Biosensors and signal processing
- Engineering simulation and modeling

---

## Technical Skills

**Programming:** Python, MATLAB, Java, R, Rust  
**Machine Learning:** deep learning, CNNs, clustering, regression, image segmentation  
**Engineering:** COMSOL, SolidWorks, Onshape, KiCad, Arduino  
**Data & Tools:** Git, GitHub, Docker, SQL, Jupyter

---

## About Me

I am currently pursuing an **M.S.E. in Biomedical Engineering with a concentration in Biomedical Data Science at Johns Hopkins University**. I previously earned a **B.S. in Biomedical Engineering with a minor in Data Science from Boston University**, graduating summa cum laude.

My work combines traditional biomedical engineering with computational methods, with particular interests in medical devices, biomedical imaging, machine learning, and data-driven healthcare technologies.
