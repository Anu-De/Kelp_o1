Kelp: An AI Agent for Chronic Disease Monitoring

This repository documents the capstone project for Kelp, an AI-powered chronic disease monitoring assistant. Kelp is designed to revolutionize chronic care by enabling proactive management and bridging communication gaps between patients and healthcare providers.

📝 Table of Contents

    Project Overview

    Problem Statement

    Solution Overview

    Key Functionality & Value Proposition

    ⚙️ Technology Stack

    Agent Instructions & Grounding

    Kelp vs. A General-Purpose Chatbot

    Conclusion

    🚀 Future Scope

    References

Project Overview

Project Name: Kelp
Core Purpose: An intelligent AI agent for chronic disease monitoring.
Target Audience: Patients living with chronic diseases and their healthcare providers.
Target Diseases: Focused initially on Type 2 Diabetes, Hypertension, and Coronary Artery Disease.
Goal: To enable proactive care, improve patient adherence to treatment plans, reduce preventable hospital visits, and bridge the communication gap between patients and providers.
Problem Statement

The management of chronic diseases presents significant challenges:

    Burden of Chronic Disease: Conditions like Type 2 Diabetes, Hypertension, and Coronary Artery Disease demand continuous, long-term management, often overwhelming patients.

    Adherence Issues: Patients frequently struggle with adhering to complex medication schedules, dietary restrictions, and exercise regimens, leading to suboptimal health outcomes.

    Communication Gaps: There's a notable lack of continuous communication and support between patients and their healthcare providers in between scheduled appointments.

    Reactive Care Models: Healthcare is often reactive, addressing crises rather than preventing them, resulting in preventable hospitalizations, increased costs, and a diminished quality of life for patients.

Solution Overview

Kelp is an intelligent AI agent specifically engineered to address these challenges by providing continuous, proactive support for chronic disease management. It acts as a dedicated 24/7 assistant, offering real-time analysis, personalized insights, and timely interventions.
Key Functionality & Value Proposition

Kelp provides a comprehensive suite of features designed to empower patients and support healthcare providers:

    Continuous Data Analysis: Kelp continuously analyzes health data streams from various sources, including wearables (e.g., smartwatches), electronic medical records (EMRs), and direct patient inputs (e.g., self-reported symptoms, glucose readings).

    Personalized Insights & Predictive Analytics: Leveraging AI and predictive analytics, Kelp transforms raw data into actionable, personalized insights and recommendations for diet, exercise, and medication adjustments, tailored to the individual patient.

    Proactive, Severity-Based Alerts: The agent is designed to detect early warning signs of health deterioration. It sends timely, severity-categorized alerts to both the patient and their designated care provider, enabling rapid intervention (e.g., a low-priority trend vs. a high-priority critical reading).

    Medication & Task Reminders: To ensure adherence to treatment plans, Kelp sends automated reminders for medication dosages, upcoming appointments, and scheduled diagnostic tests.

    Empathetic & Clear Communication: All interactions with Kelp are designed to be clear, non-judgmental, and easy for patients to understand, avoiding technical medical jargon.

    Safety & Privacy: Patient data security and privacy are paramount. Kelp adheres strictly to all relevant patient data privacy regulations, such as HIPAA.

⚙️ Technology Stack

Kelp is built on a robust and scalable cloud-based infrastructure:

    Cloud Platform: IBM Cloud

    AI/ML Service: IBM watsonx.ai Studio

    Knowledge Base Development:

        The agent's specialized medical knowledge is compiled from curated, pre-existing datasets.

        Research and data validation are augmented by leveraging powerful search tools like Google Search and DuckDuckGo Search to ensure accuracy and up-to-date information.


Agent Instructions & Grounding

Kelp operates under a strict set of instructions to ensure its effectiveness, safety, and domain specificity:

    Specific Instructions for Kelp:

        Analyze and alert on key health metrics relevant to chronic diseases (e.g., blood pressure, glucose levels, heart rate variability).

        Provide personalized recommendations for diet, exercise, and medication based on a patient’s unique health data and treatment plan.

        Send timely reminders for medications, appointments, and scheduled tests.

        Communicate with empathy and clarity, ensuring all information is easy to understand and free of medical jargon.

        Uphold patient privacy and security at all times, adhering to regulations like HIPAA.

    Domain Constraint:

        Kelp is designed strictly as a chronic disease monitoring assistant. It is programmed to politely decline and redirect any questions or requests that fall outside this specific medical domain, ensuring focused and safe operation.

    General Instructions (Standard AI Behavior):

        Be helpful and factual within the designated chronic disease domain.

        Maintain a professional and respectful tone in all interactions.

        Prioritize patient safety; if a dangerous or crisis situation is detected, provide appropriate crisis resources.

        Recognize its limitations as an AI and communicate these implicitly or explicitly when necessary.
Result:

<img width="1862" height="964" alt="Screenshot_20250804_035340" src="https://github.com/user-attachments/assets/bb18f130-831c-4ac6-9309-6326e9088a72" />

<img width="1862" height="964" alt="Screenshot_20250804_035406" src="https://github.com/user-attachments/assets/a9aa70f1-09dc-4359-baca-1066d5746c64" />
<img width="1862" height="964" alt="Screenshot_20250804_035453" src="https://github.com/user-attachments/assets/7ac2e6d3-3c97-486c-bbda-bd7699120d70" />
<img width="1862" height="964" alt="Screenshot_20250804_035459" src="https://github.com/user-attachments/assets/54208469-17b3-444b-b23c-7a03f8cb59bb" />

Conclusion

Kelp represents a significant advancement in chronic disease management, moving healthcare from reactive interventions to proactive, preventative care. By empowering patients with continuous insights and facilitating seamless communication with providers, Kelp aims to improve treatment adherence, reduce hospitalizations, and ultimately enhance the quality of life for individuals living with chronic conditions. Built on a foundation of curated, factual knowledge and leveraging IBM's robust AI and cloud platforms, Kelp is a trustworthy, empathetic, and secure partner for both patients and healthcare teams.
