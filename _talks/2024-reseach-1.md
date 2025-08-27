---
title: "Fatigue Performance of Zhuzhou Qingshuitang Bridge"
collection: talks
type: "Paper"
permalink: /talks/2024-research-1
venue: "Chongqing University"
date: 2023-04-10
location: "Shanghai, China"
---

Fatigue Performance; Truss arch bridge; Rain Flow

The project was completed in cooperation with the Bridge Branch of Shanghai Municipal Design Institute, under the guidance of Prof. Benjin Wang from Tongji University. The main work of the project was completed by me only.  
In this project, the vertical, single-point load force in the same direction as gravity is applied first. The force size is 100kN, and the stress value is calculated to determine the location of dangerous nodes. The method of determining dangerous node is mainly carried out from two aspects: static load and dynamic response stress amplitude.  
<img width="443" height="334" alt="image" src="https://github.com/user-attachments/assets/84820c9f-7b01-482e-9be2-4d006e550e31" />  
Fig.1 Finite element model.  
In Hypermesh software, the entire process will first establish the CAD wire-frame model of fatigue risk nodes according to the design drawings, then establish the fully coupled CAD surface model according to the wire-frame boundary conditions, and import the surface model into Hypermesh software for surface domain cutting to obtain the solid fine model based on Solid185 unit as the standard. It is set as ANSYS command flow, and finally imported into ANSYS for boundary condition coupling with the full-bridge model to obtain the full-bridge multi-scale model.  
<img width="1848" height="754" alt="27fda3af-bb3e-45be-be62-ca6352aa49d8" src="https://github.com/user-attachments/assets/ad738612-b469-4cf5-9792-a68d798ed711" />  
Fig.2 Establishment of the full-bridge multi-scale model.  
The rain-flow rectangular histogram is obtained by the rain-flow counting method, which includes the loading curve, stress cycle number and other parameters. The left figure is the result under the Chinese norm, and the right figure is the result under the European norm. The relationship between the number of periods and the period range can be seen in the stress concentration area, which basically corresponds to the number of vehicle fleets and axle load set before this report. The maximum value of the period range in the stress concentration area is about 30MPa, while the maximum value at the weld position is close to 20MPa.  
<img width="1684" height="1202" alt="0554e4a0-6625-4e70-9bb8-11979525f51f" src="https://github.com/user-attachments/assets/618f9837-f74d-4c45-81df-32a3ba9d132e" />  
Fig.3 Rectangular histogram of rain flow in a sample joint (Left: China code; Right: European code)  
The calculated stress amplitude of weld position was compared with the corresponding S-N curve of weld detail fatigue grade. The stress amplitude and S-N curve in the figure do not intersect. According to the definition of fatigue grade, it can be concluded that the fatigue grade at the weld position has exceeded the maximum value of the specified range, indicating that the fatigue life at the current weld position exceeds 100 years of the bridge design basis, which meets the requirements.  
<img width="413" height="340" alt="image" src="https://github.com/user-attachments/assets/3c94f700-4c13-41bb-88ca-0b26410954dd" />  
Fig.4 Compare the calculated stress amplitude of weld position with the corresponding S-N curve.


