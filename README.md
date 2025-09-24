# Smart India Hackathon Workshop
# Date: 24.09.25
## Register Number: 25011836
## Name: ISHWARYA M
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
A distinct technical strategy to enable small and marginal farmers in India might be implementing, “Agri-Drones with Edge AI,” i.e., a fleet of autonomous drones operated via edge computing. The drones will periodically fly the farmland to collect high-resolution imagery and sensor information regarding soil moisture, nutrient levels, and pest information, then process the information using light-weight AI models directly on the drone to provide immediate location specific recommendations.The implementation of an integrated, rugged, solar-charged ground station will offer farmers voice-based updates in their native language through a simple handheld device and will not require an internet connection. The drones will also assess irrigation needs and optimize water use, while the ground station will synchronize data collected from the drones with the cloud-based platform for experts to track long-term trends in farming practices. Owing to agri-tech collaborations, this solution reduces dependency on guesswork, optimizes resource use, and is scalable across a range of fields.

The "Agri-Drones with Edge AI" solution is possible with existing technologies to offer this. Affordable drones, edge processing units for AI, and solar-powered systems are all available today and in use for agriculture and other uses. The initial capital investment for drone hardware, training the AI on local datasets, and establishing the ground station may be financed through partners in agri-tech and government grant proposals, making it feasible for pilot studies projects in some of the prominent agricultural development communities. The costs for maintenance and operational use can be handled through community cooperatives, in which farmers may contribute small fees or labor shares to manage the cooperative facilities. 

## Technical Approach
FlowChart:
![InShot_20250924_104304314](https://github.com/user-attachments/assets/5ac31e9c-d742-43be-8cd1-9c96a302bb23)



Programming languages: Python,c++

Python (primary): Ideal for high-level scripting, sensor integration, and automation. Use libraries like DroneKit or MAVSDK for controlling drone flights and missions. Python's simplicity suits rapid prototyping and is widely used in agri-drones (e.g., via ROS - Robot Operating System).

C++ (for performance-critical parts): If low-latency flight control is needed, embed C++ in firmware like PX4 for real-time processing. Python can interface with it via wrappers.

## Feasibility and Viability
The fact the service is solar powered will also ensure its viability in remote locations.Viability is further substantiated through the possibility of enhancing crop yields by 20-30% while reducing input costs based on evidence from ICT-based advisory studies indicating a reasonable return on investments. Scalability in different environments is possible with modular drone designs, although initial attention should be directed to challenges associated with training local operators and incorporating data privacy.

## Impact and Benefits
<h3>IMPACT</h3>
The "Agri-Drones with Edge AI" solution would unlock a considerable impact by providing small and marginal farmers with accurate, real-time agricultural insights to improving crop yields by potentially 20-30% and lowering input costs via optimized water and fertilizer usage. This would encourage food security and enhanced livelihoods, providing a pathway for farmers out of poverty while promoting sustainable practices than reduce harm to the environment.

<h3>BENEFITS</h3>
Benefits involve enhancement of soil health via strategic interventions, diminishing dependence on chemical overuse, and reduced crop losses due to early pest detection - customized to local conditions. The voice-based system is aligned with offline accessibility, eliminating literacy and language barriers for more than 86% of India's small farmers, while the community-managed model encourages collaboration. Over the longer term, the system could attract additional investment from agri-tech and government organizations, expanding benefits into varying areas.
## Research and References
Marut Drones - India's First Multi Utility Agri Dronemarutdrones.com/ 
