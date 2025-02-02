# TerrorNets
Terrorist Network Datasets

## Overview
This repository contains five **GML-formatted terrorist network datasets** and algorithms used for analyzing leadership structures within clandestine organizations. The datasets represent different terrorist networks, and the algorithms aim to identify **primary conspirators** and **leaders** based on network topology and information flow.

## Files Included

### **Datasets (GML Format)**
- `TerrorNet1.gml`
- `TerrorNet2.gml`
- `TerrorNet3.gml`
- `TerrorNet4.gml`
- `TerrorNet5.gml` 

Each **GML file** contains:
- **Nodes** representing individuals or entities involved in the network.
- **Edges** representing relationships (e.g., communication, transactions, influence links) between these individuals.
- **Metadata** providing additional contextual information on nodes and edges.

These datasets are structured to maintain **graph consistency** while allowing for **comparative analysis** across different terrorist organizations.

### **Primary Conspirators in Each Network**
The following individuals were identified as the **primary conspirators** in each terrorist network:

- **TerrorNet1:** Salar, Ekbal, Dr. Abdul Hameed, Asadulla, Gilani
- **TerrorNet2:** Sivarasan, Subha, Santhan, Murugan, Arivu
- **TerrorNet3:** Asif Khan, Faisal Shaikh, Sohail, Tanveer Ansari, Ehtesham
- **TerrorNet4:** Tiger Memon, Phanasmiyan, Nasir Dakhla, Yakub Abdul Razak Memon, Asgar Yusuf Mukadam
- **TerrorNet5:** Abu Kafa, Zaki-ur-Rehman Lakhvi, Hafiz Sayeed, Ismail Khan, Abu Hamza

### **Detailed Network Descriptions**
#### **TerrorNet1**
The primary conspirators in **TerrorNet1**—Salar, Ekbal, Dr. Abdul Hameed, and Asadulla—were actively involved in organizing the attack. Salar and Asadulla were responsible for procuring materials and managing logistics such as manpower and funding. Ekbal and Dr. Abdul Hameed assisted in acquiring explosives and securing transportation, in addition to attending all planning meetings. The attack was orchestrated under the directives of Tiger Memon and Bilal Ahmad, who played key leadership roles.

#### **TerrorNet2**
In **TerrorNet2**, Sivarasan, Subha, and Santhan were the main operatives behind the assassination plot. Sivarasan handled planning and execution, while Subha and Santhan provided logistical and operational support. They remained close to him throughout the mission. The overarching strategy was devised by Prabhakaran and Pottu Amman, who guided the attack and directed key conspirators.

#### **TerrorNet3**
The two primary conspirators in **TerrorNet3**, Faisal Shaikh and Asif Khan, were instrumental in recruiting individuals for training in Pakistan under the supervision of Azam Chima. They also managed financial resources for the attack’s planning and execution. Unlike traditional hidden leadership models, this network exhibited an active leadership approach, with Azam Chima personally financing, planning, and maintaining communication with key operatives.

#### **TerrorNet4**
In **TerrorNet4**, Tiger Memon, Phanasmiyan, and Yakub Memon played central roles. Tiger Memon and Phanasmiyan were involved from the early stages, securing arms and personnel from coastal Mumbai. Yakub Memon provided funding through Hawala networks and managed storage and transportation of explosives. The attack was executed under the guidance of Dawood Ibrahim, who provided strategic directives to the conspirators.

#### **TerrorNet5 (Dausa Blast)**
The primary conspirators in **TerrorNet5** network, included Abu Kafa, Zaki-ur-Rehman Lakhvi, Hafiz Sayeed, Ismail Khan, and Abu Hamza. These individuals coordinated the attack through well-planned logistics, financial backing, and strategic execution. The attack was conducted under the influence of external extremist networks, leveraging cross-border support. Leadership figures provided directives while maintaining a decentralized operational structure to reduce traceability.


## How to Use the Data
- The **GML datasets** can be loaded using graph analysis libraries such as **NetworkX (Python)**.
- The algorithms can be applied to the loaded graphs to identify key actors.
- The results can be visualized using **graph plotting tools** like **Matplotlib, Gephi, or Cytoscape**.

## Example Code
```python
import networkx as nx

# Load a GML file
G = nx.read_gml("TerrorNet1.gml")

# Print basic network statistics
print(f"Number of nodes: {G.number_of_nodes()}")
print(f"Number of edges: {G.number_of_edges()}")
```

## Applications
- **Clandestine Network Analysis**: Identifying key figures in covert networks.
- **Security & Intelligence**: Understanding leadership hierarchies in terrorist cells.
- **Graph Theory Research**: Exploring structural properties of illicit networks.


---
For any queries or contributions, feel free to reach out.
