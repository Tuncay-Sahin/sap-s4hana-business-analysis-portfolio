**Prepared by:**Tuncay Şahin  
**Role:** SAP Business Analyst Candidate

---

# **ProTech Industries – SAP S/4HANA Procurement**

## **Traceability Matrix & Impact Analysis**

---

## **1\. Requirements Analysis**

### **1.1 Business Requirements**

**BR-01: Automate Purchase Order Approvals**  
The system shall automate the routing of purchase orders based on predefined workflows to reduce delays and improve efficiency.

**BR-02: Improve Supplier Management**  
The system shall provide tools to track supplier performance and reduce disputes.

**BR-03: Reduce Manual Approvals**  
The system shall minimize manual intervention in the purchase order approval process.

**BR-04: Enhance Reporting and Visibility**  
The system shall provide comprehensive reporting capabilities for better monitoring and decision-making.

---

### **1.2 Functional Requirements**

**FR-01: Purchase Order Workflow Configuration**  
The system shall allow configuration of approval workflows based on criteria such as purchase order amount, supplier, material type, and cost center.

**FR-02: Automated Approval Notifications**  
The system shall notify approvers automatically via SAP Fiori and/or email when approval is required.

**FR-03: Supplier Performance Tracking**  
The system shall track supplier KPIs such as delivery time, quality, and invoice accuracy.

**FR-04: Supplier Dispute Management**  
The system shall provide functionality to record and manage supplier disputes.

---

### **1.3 Requirement Relationships**

| Requirement | Design Approach | Test Strategy | System Support | Status |
| ----- | ----- | ----- | ----- | ----- |
| BR-01 | Workflow Design | Approval SLA Testing | SAP Flexible Workflow | In Progress |
| BR-02 | KPI Dashboard Design | KPI Accuracy Testing | SAP Fiori Analytics | Planned |
| BR-03 | Process Optimization | Manual vs Automated Testing | SAP MM | Planned |
| BR-04 | Reporting Design | Report Validation Testing | SAP Analytics | Planned |
| FR-01 | Workflow Configuration | Workflow Scenario Testing | S/4HANA MM | In Progress |
| FR-02 | Notification Setup | Notification Testing | SAP Fiori | Planned |
| FR-03 | KPI Data Model | Data Accuracy Testing | CDS Views | Planned |
| FR-04 | Dispute Process Design | Dispute Resolution Testing | Supplier Management | Planned |

---

## **2\. Traceability Matrix**

| Req ID | Description | Design Document | Test Case | System Component | Status |
| ----- | ----- | ----- | ----- | ----- | ----- |
| BR-01 | PO Automation | Workflow Design Document | TC-01 Approval SLA | SAP Flexible Workflow | In Progress |
| BR-02 | Supplier Management | KPI Dashboard Document | TC-02 KPI Accuracy | SAP Fiori | Planned |
| BR-03 | Reduce Manual Approvals | Process Optimization Document | TC-03 Efficiency Test | SAP MM | Planned |
| BR-04 | Reporting & Visibility | Reporting Design Document | TC-04 Report Validation | SAP Analytics | Planned |
| FR-01 | Workflow Configuration | Configuration Specification | TC-05 Workflow Test | S/4HANA MM | In Progress |
| FR-02 | Notifications | Notification Design Document | TC-06 Notification Test | SAP Fiori | Planned |
| FR-03 | Supplier KPI Tracking | CDS Design Document | TC-07 KPI Test | CDS Views | Planned |
| FR-04 | Dispute Management | Dispute Design Document | TC-08 Dispute Flow | Supplier Management | Planned |

---

## **3\. SAP Solution Manager Traceability**

### **3.1 Navigation Steps**

* Log in to SAP Solution Manager  
* Navigate to:  
  **Focused Build → Business Analyst → Requirements Management**

---

### **3.2 Linking Requirements**

* Select a requirement  
* Assign a Work Package  
* Link the requirement to:  
  * Design documents  
  * Development objects  
  * Test cases

Work Packages are used to break requirements into:

* Configuration tasks  
* Development activities  
* Testing assignments  
* Change requests

---

### **3.3 Traceability Capabilities**

* Requirement to Work Package linking  
* Requirement to Test Case mapping  
* Attachment of related documents  
* Export traceability reports to spreadsheet

---

### **3.4 Summary**

SAP Solution Manager enables:

* End-to-end traceability  
* Requirement lifecycle tracking  
* Efficient impact analysis

---

## **4\. Change Request & Impact Analysis**

### **4.1 Selected Requirement**

**FR-01: Purchase Order Workflow Configuration**

---

### **4.2 Proposed Change**

Introduce a new rule:

“Purchase orders above $50,000 require CFO approval.”

---

### **4.3 Impact Analysis**

| Impact Area | Description |
| ----- | ----- |
| Design Documents | Workflow logic must be updated |
| System Configuration | New approval step must be configured |
| Test Cases | New test scenarios must be created |
| User Roles | CFO must be added as approver |
| Process Flow | Approval time may increase |

---

### **4.4 Traceability Impact**

FR-01 → Workflow Configuration  
→ Test Case TC-05  
→ SAP MM Workflow

---

### **4.5 Conclusion**

Traceability ensures:

* Controlled change management  
* Clear visibility of dependencies  
* Reduced implementation risk

---

