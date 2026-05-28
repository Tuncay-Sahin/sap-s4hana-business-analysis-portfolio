# Use Case: SAP Inventory Management

**Use Case Name:** Automate Purchase Order Generation

## Step 1: Questions for your client

1. *Could you walk me through your current process for managing reagent inventory?*  
2. *What specific data points are you recording in your Microsoft Access database versus what you write down on paper?*  
3. *Can you describe a recent "failed experiment" caused by inventory issues—was it due to an expired reagent or a stockout?*  
4. *How do you currently identify which reagents are nearing their expiration date?*  
5. *When a reagent is delivered, how do you decide where to store it and how is that location recorded?*  
6. *What is the biggest challenge you face when trying to reorder materials?*  
7. *How do you determine the "minimum stock level" for a specific reagent before you know it’s time to reorder?*  
8. *Could you explain the approval process required before a purchase order can be sent to a vendor?*  
9. *When you are on leave, what are the most common mistakes your colleagues make when trying to use your current system?*  
10. *Are there specific safety regulations or "hazardous material" classifications we need to track for certain chemicals?*  
11. *What kind of weekly or monthly reports would help you justify laboratory spending to your supervisors?*  
12. *How would you like the system to alert you—via email, a dashboard notification, or a mobile alert?*  
13. *Are there specific vendors you must use, or do you have the flexibility to shop around for better prices?*  
14. *Does your lab have existing barcodes on reagents, or would you like the new SAP system to generate them for you?*  
15. *If you could change one thing about the way you currently find a "missing" vial, what would it be?*

## Step 3: Have ChatGPT to transcribe and analyze the interview 

	*This summary is generated based on the persona of Garima, the lab technician.*

**Summary Report: Reagent Management System Requirements**

The interview with Garima revealed a high-stress environment stemming from a fragmented inventory process. Currently, the lab relies on a mix of paper logs and an outdated Access database, leading to significant data silos. The primary **pain points** are "invisible" expiration dates and the lack of a standardized location naming convention, which causes experiment failures and safety risks.

**Prioritized Requirements:**

* **Centralized Real-Time Tracking:** A single SAP-based "Source of Truth" to replace paper and Access.  
* **Automated Alerts:** Low-stock notifications and "Days until Expiration" triggers.  
* **Simplified UI:** A user-friendly interface that allows non-expert colleagues to log usage and reorder without intensive training.  
* **Reporting:** Automated generation of stock levels and consumption patterns.

**Open Questions:** We still need to clarify the specific SAP module integration (e.g., SAP MM or a simplified S/4HANA Fiori app) and whether existing lab hardware (barcode scanners) is compatible with the proposed digital solution.

Step 4: Summarize the key findings and insights from the interview

| Key Findings & Insights | Manual Inefficiency: Heavy reliance on manual entry in Microsoft Access leads to frequent human error and outdated stock levels. Knowledge Silos: The current system is so complex that work stops when Garima is on vacation, creating a single point of failure. |
| :---- | :---- |
| Desired Features & Functionality | **Visual Expiration Tracking:** A dashboard that highlights reagents nearing their end-of-life. **Automated Reordering:** The system should trigger a Purchase Order request when stock hits a pre-defined threshold.  **Location Mapping:** A digital "map" or locator to find specific vials across various shelves and tubes. |
| Constraints & Requirements |  **User Experience:** The tool must be simple enough for all lab staff to use with minimal training to ensure data integrity during Garima's absence.  **SAP Compatibility:** The solution must fit within a "simple version" of SAP, focusing on core Inventory Management (IM) functions. |
| Next Steps | **System Demo:** Schedule a walkthrough of a simplified SAP Fiori interface for Garima to test usability. **Data Migration:** Begin auditing the current Access database to prepare for cleaning and uploading data into SAP. |

