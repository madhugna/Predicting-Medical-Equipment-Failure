# Predicting-Medical-Equipment-Failure

⭐**Project Overview**

This project proposes a Healthcare CRM integrated with predictive analytics to monitor medical equipment performance, forecast potential failures, and trigger preventive maintenance.

System Role: The CRM acts as a central platform for collecting equipment data (usage hours, performance metrics, error logs, maintenance history) and applying predictive models.


Value:

-> Enhances patient safety by avoiding sudden device breakdowns.

-> Reduces downtime of critical machines like ventilators, MRI scanners, and dialysis machines.

-> Saves costs by shifting from reactive to preventive maintenance.

-> Provides decision-makers with actionable insights via dashboards and reports.

Problem statement: https://github.com/madhugna/Predicting-Medical-Equipment-Failure/blob/9f9bbba866861e01f753d46219d33fefa7788465/Healthcare%20CRM%20Problem%20statement.pdf

Documenttation: https://docs.google.com/document/d/1LSXfgzqOPdHyMrVziW0Cy7ThPaWJKUHj_Mh6Zknd3eE/edit?usp=sharing

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 1: Problem Understanding & Industry Analysis

*Objective:*
To develop a predictive maintenance solution for critical hospital medical devices that minimizes equipment downtime, enhances patient safety, and optimizes operational costs by leveraging data-driven failure prediction, automated maintenance scheduling, and centralized monitoring dashboards.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 2: Org Setup & Configuration

*Objective:*
To establish a fully configured Salesforce development environment by setting up a Salesforce Developer Org, integrating it with VS Code and Salesforce CLI, and connecting it to a version-controlled GitHub repository, ensuring a structured and collaborative foundation for building the healthcare equipment failure prediction solution.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 3: Data Modeling & Relationships

*Objective:*
To design a robust Salesforce data model by creating custom objects, fields, and relationships that accurately represent medical devices, their usage logs, predictive failure insights, and maintenance tasks—enabling seamless tracking, prediction, and management of equipment health within the healthcare CRM system.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 4: Prediction Model Integration

*Objective:*

To build and train the Einstein Prediction Model using Medical_Device__c data.

To select influential fields like Usage Hours, Battery Level, Error Codes.

To deploy the model and configure predictions to write into Failure_Risk__c.

To expose prediction results for retrieval via Apex.

To ensure predictions are accurate, consistent, and updated for each device.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 5: Apex Programming (Developer)

*Objective:*

To create Apex classes that call the Einstein Prediction Service programmatically.

To fetch prediction scores for given medical device records.

To implement logic for computing thresholds (e.g., high/medium/low risk categories).

To prepare server-side controllers that LWC components can call.

To keep the Apex layer modular, reusable, and error-handled.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 6: User Interface Development (LWC Dashboard)

*Objective:*

To design a custom Lightning Web Component (LWC) that displays prediction scores.

To build a Prediction Dashboard showing device status and risk level.

To create interactive charts and cards for easy understanding by technicians/managers.

To embed the LWC inside the Medical Equipment Failure Predictor Lightning app.

To ensure the UI is responsive, user-friendly, and aligned with healthcare workflows.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 7: Integration & External Access

*Objective:*

To prepare for integration with IoT or telemetry data sources (e.g., device usage logs).

To simulate or import external usage data for predictions.

To expose APIs or endpoints for third-party healthcare systems to access predictions.

To ensure secure authentication and authorization in all external integrations.

To design the app for scalability with real-world medical device data streams.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 8: Data Management & Deployment

*Objective:*

To migrate sample datasets of medical devices into Salesforce.

To clean and validate data (ensuring consistent values for error codes, firmware versions, etc.).

To deploy LWC components, Apex classes, and metadata from sandbox to Developer Org.

To use GitHub for source control and maintain version history.

To ensure the app is production-ready and stable after deployment.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 9: Reporting, Dashboards & Security Review

*Objective:*

To create Salesforce native Reports and Dashboards summarizing device risks.

To provide managers with KPIs like % of devices in high-risk category.

To conduct a security review: check object/field access, sharing rules, and compliance.

To ensure only authorized roles can see prediction results and sensitive device data.

To align the system with healthcare standards (HIPAA, GDPR for device/patient data).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

✔️ Phase 10: Final Presentation & Demo Day

*Objective:*

To demonstrate the full workflow: device → usage data → Einstein prediction → LWC dashboard.

To showcase the app (Medical Equipment Failure Predictor) with its prediction UI.

To highlight how managers and technicians can act based on predictions.

To present outcomes like reduced downtime, cost savings, and improved safety.

To propose future scope (e.g., real-time IoT integration, advanced ML models in Python).


