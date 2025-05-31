
# 🔧 Ticket Complaint Clustering & Technician Allocation Optimization

This project uses real-world complaint ticket data to perform **geospatial clustering** and create an efficient **technician deployment plan** across urban service hubs. The goal is to improve field service management by visualizing hotspots of complaints, calculating technician workloads, and recommending optimal manpower deployment based on ticket density.

## 📌 Problem Statement

In high-density cities with growing electric vehicle usage, handling customer complaints efficiently requires a data-driven approach. This project addresses the challenge by:
- Clustering complaint locations using **Folium + MarkerCluster**
- Visualizing ticket volumes by **geo-coordinates and sub-areas**
- Analyzing ticket density and aligning technicians based on workload
- Planning the number of technicians required per region for SLA compliance

---

## 🗺️ Technologies Used

- **Python**
  - `folium` for interactive maps
  - `folium.plugins.MarkerCluster` for geo-point clustering
- **Pandas & Google Sheets** for ticket data preparation
- **Excel** for operational planning
- **Leaflet.js** (via Folium) for rendering HTML maps
- **VSCode** (used for prototyping)

---

## 🧠 Key Features

- 📍 **Map-Based Clustering**  
  Visualizes all ticket locations and clusters them to identify complaint hotspots.

- 📊 **Hub/Sub-Area Planning**  
  Each complaint is grouped under a defined **hub and sub-area** based on service zones.

- 👨‍🔧 **Technician Load Estimation**  
  Uses ticket volume and average resolution capacity (8 tickets/day/tech) to recommend number of technicians needed.

- 📈 **Data-Driven Service Optimization**  
  Helps reduce complaint resolution time by improving resource allocation and zone coverage.

---
## 🗺 Cluster Maps

- Chatterpur clustering map : [Click here to open map](https://drive.google.com/file/d/1dGjObhCPh1gj7sbZJ9DvD24m2Xq30ipT/view?usp=drive_link)
- Greater Noida clustering map : [Click here to open map](https://drive.google.com/file/d/1zZjCUEk6OU3SxrZUqv83Xw7Gln6YTQJL/view?usp=drive_link)
- Mundka clustering map : [Click here to open map](https://drive.google.com/file/d/1vH188uo4iChZztMqMxGfRuKc5ipmyGUv/view?usp=drive_link)
- Sahibabad clustering map : [Click here to open map](https://drive.google.com/file/d/1C2S2_esGB7xORkBDQH2wQ25hQBZNlDq0/view?usp=drive_link)
- Sec-17 Gurugram clustering map : [Click here to open map](https://drive.google.com/file/d/1vn_ZBIz7bzUYZSYhSUz9ZXfBAG5myXYM/view?usp=drive_link)
- Sec-69 Gurugram clustering map : [Click here to open map](https://drive.google.com/file/d/1Lklc4-5VdiQR9gM_qlaz5frEiFH3NQO5/view?usp=drive_link)

---

## 📌 Future Enhancements

- 🔥 Add **heatmaps** to visualize intensity of complaints.
- 📆 Automate monthly summary reports from raw ticket dumps.
- 🚀 Build a **dashboard** using Looker Studio or Plotly Dash.
- 📱 Integrate mobile app location tracking for real-time technician assignment.

---

## 📁 Data Sensitivity

> 🚨 All data shown here is anonymized and for demo/portfolio purposes. No sensitive user or location data is publicly exposed.

---

## ⭐️ If you like this project, give it a star — and feel free to fork or contribute!
