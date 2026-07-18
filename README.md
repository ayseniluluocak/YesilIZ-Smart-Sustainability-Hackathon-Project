# YeşilİZ: AI-Powered Smart Sustainability Ecosystem

This repository contains the conceptual design, business model, system architecture, and AI-generated prototype of YeşilİZ, developed during the GDG Bursa Tent Camp Hackathon 2026[cite: 1].

---

## Project Update: Prototype Deployed
The proof-of-concept demo code has been successfully integrated into this repository. Due to the strict time constraints of the hackathon, the functional demo was co-created using AI-driven rapid prototyping tools through the joint efforts of the project team to demonstrate the core logic of the ecosystem.

---

## Team and Collaboration Acknowledgement
This project was a collaborative team effort during the GDG Bursa 2026 Hackathon[cite: 1]. While I am hosting the repository and managed the live presentation phase, the entire conceptualization, system logic, and business model were designed equally with my hackathon team members. Furthermore, the accompanying prototype demo was collectively prompted and generated using AI tools through our team's joint effort.

### Team Members
* Mehlikanur Kartav
* Ayşe Göktürk
* Ayşenil Uluocak
* Muhammet Erdem Aycin
* Efe Aslan

---

## Problem Definition
* **Late Detection of Environmental Issues:** Local environmental and sustainability violations cannot be reported instantly, which delays solutions and causes the problems to grow.
* **Dispersed Reporting Mechanisms:** Existing complaint channels are disorganized, which complicates citizen participation and weakens collective action.
* **Technical Deficiencies:** The current framework lacks structured environmental data, relies on complex manual verification of visual reports, and operates without real-time data analysis capabilities.

---

## Solution and Value Proposition
YeşilİZ is an end-to-end citizen-participatory smart city platform where residents generate real-time environmental data, artificial intelligence classifies and prioritizes reports, and local municipalities take direct action.

### Value Proposition Canvas
* **Real-Time City Data:** Provides a filtered, live stream of urban data to track the ecological health of the city.
* **Verified Environmental Reports:** Delivers clean field data validated by artificial intelligence to filter out ungrounded submissions.
* **SDG Alignment:** Built to directly align urban data collection infrastructure with the United Nations Sustainable Development Goals.

---

## System Architecture
1. **Upload:** The user uploads the location details and the image of the environmental issue through the mobile application.
2. **AI Analysis:** The artificial intelligence engine processes the visual data to verify its authenticity, determine the violation type, and assign a priority score.
3. **Action:** Filtered and structured data is routed directly to the relevant municipal field teams.
4. **Feedback:** Once resolved, the status update is communicated back to the user to ensure transparency.

---

## Technical Architecture and Security
* **GDPR Compliance and Data Security:** Secure identity verification is handled via e-Government (e-Devlet) API integration. To ensure strict personal data privacy regulations, national ID numbers are not stored, and users are assigned an Anonymous User ID in the database. The platform also features automated face and license plate blurring.
* **Abuse and Fraud Prevention:** To prevent system exploitation and spam, a daily limit of 15 reports per user is enforced alongside trust scores and strict GPS-based location validation.

---

## Environmental Incentive System
The platform uses a gamified, non-cash reward system based on Green Points (Yeşil Puan). If a user reports an issue, a flat 1 Green Point base reward is given. If the user resolves the environmental issue independently, the AI model assigns a variable reward scaling from 1 to 50 Green Points depending on the impact magnitude.

### Green Point Advantages
* Free public transportation passes
* Discounts at municipal social facilities
* Priority access to municipal cultural events

---

## Target Audience
* **Citizens:** Environmentally conscious individuals who use smart devices and want to contribute to sustainable urban life.
* **Local Governments:** Municipalities looking to manage field resources efficiently and generate structural sustainability reports.
* **Schools and Youth:** Dynamic young demographics joining the system through voluntary community and school eco-projects.

---

## Strategic Partnerships
* **Ministry of Environment, Urbanization and Climate Change (ÇŞİB):** Responsible for legislation, national environmental dataset regulation, and e-Government API support to provide legal infrastructure and reliability.
* **Municipalities:** Act as the pilot field region providers, supplying field intervention teams and budget support for rewards to drive local deployment.
* **Telecommunications and NGOs:** Build the communication infrastructure and raise public awareness to scale the user base.

---

## Deployment Strategy: Bursa Pilot Model
The platform is designed to launch simultaneously in the two most active districts of Bursa to optimize system performance before a wider release:
* **Nilüfer:** Chosen for initial testing due to high digital literacy and environmental awareness among the population.
* **Osmangazi:** Utilized for field validation testing within densely populated residential areas and urban transformation zones.
* **Scalable Architecture:** Built on a modular design ready to expand across the national smart city network after the pilot phase.

---

## Repository Contents
* `2026 Bursa GDG Hackathon proje-YeşilİZ.pptx`: The official pitch deck presentation used during the hackathon[cite: 1].
* `1000057813.jpg`: Hackathon participation certificate document.
* Prototype Source Files: The functional prototype code developed collectively by the team using AI-driven rapid prototyping tools.

---

## Project Contact
* **Project Network:** Turkey Smart and Sustainable Cities Network
* **Email:** yesiliz.info@gmail.com

---

## Hackathon Certificate
![GDG Bursa 2026 Participation Certificate](1000057813.jpg)