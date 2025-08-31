# Fatigue Driving Early-Warning Technology Based on Physiological Signals

# (I) Project Introduction
This project focuses on developing a warning system for drowsy driving based on physiological signals. Drivers wear compact smart sensors, which, together with vehicle-mounted peripherals, capture physiological parameters through a human parameter sensing module and a head acceleration detection module. The system provides real-time alerts (audio and visual) for fatigue or other non-alert driving behaviors while recording data in the cloud. 

The research aims to establish mathematical models correlating body temperature, heart rate, blood oxygen, respiratory rate, and blood pressure during fatigue, combining these patterns with external survey data to generalize common trends in drowsy driving. An independent cloud database and a mobile app are developed for real-time feedback. The system is highly accurate and sensitive, offering a cost-effective solution for designing and developing fatigue detection software, making it feasible and scalable.  

---

# (II) Research Objectives
With the rapid development of the automotive industry, safe driving has become an increasingly important concern. Statistics show that more than 500,000 people die annually worldwide due to traffic accidents, with approximately 90,000 in China alone. Studies indicate that fatigue driving is the third major “risk factor influencing accident occurrence,” accounting for about 20–30% of total accidents. Therefore, studying and preventing drowsy driving has significant practical importance.  

The main objectives of this research are as follows:

1. Detect drivers’ physiological signals related to fatigue (e.g., heart rate, respiration, blood pressure, body temperature, etc.).  
2. Explore and establish mathematical models correlating body temperature, heart rate, blood oxygen, respiratory rate, and blood pressure during fatigue. Define normal physiological ranges for each attribute; exceeding these ranges triggers a warning.  
3. Analyze changes in fatigue patterns by combining external survey data and general trends in drowsy driving. Based on the driver’s alert state, monitor cognitive decline during fatigue and use a mobile app to display the fatigue status and determine whether to issue an alarm. Individual characteristics such as gender and age are considered to refine fatigue assessment metrics.  
4. Address cost-effectiveness. Current fatigue warning systems either have suboptimal detection performance or high costs, limiting widespread adoption. This research integrates traditional detection methods with mobile apps to provide a practical and affordable solution.  
5. Facilitate software development. Validating traditional detection methods requires substantial financial resources. This study allows easy experimental deployment through a mobile app, saving significant costs while ensuring reliability.  

---

# (III) Research Content
Research and design of a drowsy driving warning system have substantial practical significance. A complete system should consider:

1. **Safety and reliability:** The system must operate safely without introducing unexpected hazards or affecting normal driving behavior. Non-contact detection methods are generally preferred.  
2. **Accuracy and sensitivity:** Only systems with sufficient accuracy and sensitivity are suitable for deployment.  
3. **Real-time performance:** Real-time monitoring is essential for practical utility.  
4. **Usability and universality:** Vehicle interior space is limited and structurally complex. The system should be compatible with vehicle-mounted deployment and adaptable to different car models and work environments.  
5. **Cost-effectiveness:** Even high-performance systems cannot be widely adopted if costs are prohibitive.  

Considering these requirements and the current research landscape, this project focuses on developing a physiological-signal-based drowsy driving warning system. Physiological monitoring uses compact, wearable smart sensors to transmit driver state to the network, allowing real-time display via mobile or in-vehicle interfaces without negatively affecting driving. Physiological-based detection is highly sensitive and accurate, capable of quantifying fatigue metrics and providing early warnings for non-fatigue-induced risky behaviors. The approach is real-time, suitable for different vehicle types, and cost-effective, with easy implementation compared to alternative methods.  

---

## Key Research Tasks

### 1. Driver Physiological State Detection
- Utilizing Hadoop-based technology for analyzing physiological data.  
- **Sensor layer:**  
  - Wireless network platform selection  
  - MQTT protocol-based real-time communication  
- **Hardware design:**  
  1. Wearable biomedical sensors and devices  
  2. Establish mathematical models correlating body temperature, heart rate, blood oxygen, respiratory rate, and blood pressure during fatigue, with normal ranges triggering warnings if exceeded  
  3. Weak signal extraction algorithms, e.g., wavelet-based ECG signal processing  
  4. Main control MCU circuit design  

### 2. Fatigue Driving Recognition, Assessment, and Warning Design
- Based on physiological signal monitoring, head acceleration measurement identifies drowsy driving, offering a novel approach.  
- The system is simple, low-cost, and reliable, though misjudgments may occur in certain situations (e.g., due to road conditions). Algorithm improvements and wireless data reception are explored.  
- High-integration, low-cost, high-reliability MEMS accelerometer (ADXL330) and SPCE061A chip are used for development.  

### 3. Mobile Display of Driver Fatigue State
- **Application Layer:**  
  1. Android platform: Bluetooth communication, login/register, ECG display, body temperature/voltage display, data storage, software filtering  
  2. Web server design  
  3. JSON-based data transmission  
  4. Apache-Apollo communication server  
- **Data Analysis Layer:**  
  1. Heart rate acquisition module (filtering power, EMG, thermal noise, and electrode polarization interferences)  
  2. Body temperature acquisition module  
  3. Blood pressure module  
  4. Bluetooth peripheral circuit design  
  5. Vehicle speed measurement module  

### Video Introduction
Shared via cloud storage: original video.mp4
Link: https://pan.baidu.com/s/1yc14vixXztrY5Cd79Mqkxw?pwd=evue
Extraction code: evue

### Mobile App
Shared via cloud storage: Safety on the Move.apk
Link: https://pan.baidu.com/s/1jv8B9DfxLN4uk4M7B9QLvA?pwd=e6vn
Extraction code: e6vn
