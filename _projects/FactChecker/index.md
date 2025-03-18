---
layout: post
title: Bitcoin Mining Rig (Converting to AI Cluster)
order: 2
description: Engineered and maintained a large-scale crypto mining operation utilizing 32 NVIDIA RTX 3090 GPUs, gaining expertise in troubleshooting hardware issues, optimizing mining efficiency, and managing electrical load balancing for high-performance systems.
skills: 
- Time Management
- Project Management
- Initiative
- Software Testing
- Troubleshooting
- Python
main-image: /Resized_20211016_224731001.jpg
---
# Project Overview  
Designed and managed a high-performance **Bitcoin mining rig** consisting of **32 NVIDIA RTX 3090 GPUs**, optimizing for **maximum efficiency and profitability**. Developed expertise in **troubleshooting hardware failures, optimizing power consumption, and managing large-scale computational loads**.  

---

## Mining Rig Performance & Cooling Management  

### Mining Rig Status Overview  
{% include image-gallery.html images="8397988945045230406.jpg" height="400" %}  
- Monitored mining efficiency, temperature, and power consumption.  
- Identified VRAM temperatures peaking at **106°C**, leading to cooling system upgrades.  

### MSI Afterburner Overclocking Settings  
{% include image-gallery.html images="66978357890__E9C40A47-F7DE-44B9-BEF9-126CA0665950.jpg" height="400" %}  
- Adjusted voltage, core clocks, and fan speed to maximize mining efficiency while preventing VRAM overheating.  
- Implemented **undervolting (-300 MHz core clock, +950 MHz memory)** to reduce power draw and enhance stability.  

---

## Power & Cable Management  

### Power Distribution Unit (PDU) Setup  
{% include image-gallery.html images="1076598101922487436.jpg" height="400" %}  
- Implemented a **30A 240V PDU** to distribute power efficiently across multiple GPUs.  
- Ensured **stable voltage regulation** for continuous mining operations.  

### PCIe & Molex Power Configurations  
{% include image-gallery.html images="5839762036866183865.jpg, 2787536473794635888.jpg" height="400" %}  
- Managed PCIe and Molex connections to prevent overloading and power fluctuations.  
- Verified **power draw limits** to avoid exceeding PSU wattage capacities.  

### GPU Risers & Power Efficiency  
{% include image-gallery.html images="6364713284815438229.jpg" height="400" %}  
- Installed **USB-powered GPU risers** to enhance airflow and prevent direct motherboard overheating.  
- Ensured **each PCIe riser was adequately powered** for stable GPU operation.  

---

## Rig Assembly & Finished Build  

### Motherboard & GPU Installation  
{% include image-gallery.html images="5583488348889799236.jpg" height="400" %}  
- Selected a **mining motherboard** with **8+ PCIe slots** to accommodate multiple GPUs.  
- Configured **BIOS settings** for optimal GPU detection and stability.  

### Cooling System Setup  
{% include image-gallery.html images="4448498089542149461.jpg, 6467208871885152609.jpg" height="400" %}  
- Mounted **high-speed cooling fans** to reduce ambient and VRAM temperatures.  
- Fine-tuned fan speeds to **100% under heavy load** to maintain GPU temperatures below **80°C**.  

### Final GPU Installation & Rig Structure  
{% include image-gallery.html images="1956131881887025482.jpg, 7427944542927605676.jpg" height="400" %}  
- Optimized cable management and power distribution for a **clean, efficient build**.  
- **Hung GPUs in a vertical arrangement** to maximize airflow and reduce heat buildup.  

### Final Bitcoin Mining Rig Setup  
{% include image-gallery.html images="Resized_20220919_153244.jpeg, Resized_20211016_224731001.jpg" height="400" %}  
- Fully optimized and operational **32x RTX 3090 mining rig**.  
- Achieved **high hash rate while maintaining power efficiency** for long-term mining sustainability.  

---

## Key Achievements  
- **Achieved 99.97% uptime** with proper electrical load balancing.  
- **Reduced VRAM temperatures from 106°C to 80°C** through cooling modifications.  
- **Maximized mining efficiency** with optimized power draw and undervolting.  
- **Successfully converted the system for AI applications**, repurposing GPUs for machine learning workloads.  

---
## Future Plans & Endeavors  

With the decline in Bitcoin mining profitability and the increasing demand for AI compute power, the **mining rig is being repurposed into a high-performance AI cluster**. The following upgrades and modifications are planned:  

- **Transitioning from crypto mining to AI model training** using **PyTorch and TensorFlow**, leveraging the **32x RTX 3090 GPUs** for deep learning workloads.  
- **Building a distributed computing framework** to allow multiple users to run AI inference and model training jobs in parallel.  
- **Optimizing power efficiency further** by implementing **server-grade PSUs** and **dynamic workload balancing** to reduce unnecessary GPU usage.  
- **Exploring federated learning applications**, allowing secure AI model training across decentralized networks while preserving data privacy.  

The goal is to **transform this high-performance rig into an AI powerhouse**, capable of supporting **ML research, model fine-tuning, and real-time inference workloads**.  
