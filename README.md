# SURE_TRUST_MAJOR_PROJECT
SAP ABAP Solutions for Sales and Distribution Sector project for reporting using Smart Forms (Invoice), ALV interactive reports with Excel export, and SUBMIT-based integration with standard ME2M report. Focuses on efficient data retrieval, automation, and professional document generation.
SAP ABAP Solutions for Sales & Distribution Sector
Smart Forms | ALV Report | Excel Download | SUBMIT (ME2M)

Project Overview:
This repository contains my SAP ABAP Internship Project completed at SURE Trust (Nov 2025 – April 2026) under the guidance of Mr. Santhosh Pal (SAP ABAP Consultant, Infosys).

The project focuses on developing a Sales & Distribution Reporting System using core SAP ABAP concepts like:

1. Smart Forms
2. ALV Interactive Reports
3. SUBMIT Integration

It provides an end-to-end solution for data retrieval, analysis, reporting, and document generation.

Objectives:
Design Smart Forms (Invoice) for structured business documents
Develop interactive ALV reports for data analysis
Enable Excel export for external usage
Integrate standard SAP reports (ME2M) using SUBMIT
Improve reporting efficiency and reduce manual work

Project

1. Smart Forms – Invoice Generation
Developed Business Invoice Smart Form
Used standard tables:
BUT000 (Business Partner)
KNA1 (Customer Master)
Features:
Company logo
Header, Footer, Page numbering
Tabular structured data
Signature section
Integrated Smart Form with ABAP program using function module

Output: Professionally formatted invoice document

2. ALV Report with Excel Download
Developed interactive ALV report using:
REUSE_ALV_GRID_DISPLAY
Data source:
MSEG (Material Document table)
Features:
Sorting & filtering
User-friendly display
Custom Excel download button
File save dialog using CL_GUI_FRONTEND_SERVICES
Data export using GUI_DOWNLOAD

Output:
ALV report displayed in SAP
Downloadable Excel file for external analysis

3. SUBMIT Report (ME2M Integration)
Implemented SUBMIT to execute standard SAP report:
ME2M (Purchase Order Report)
Used:
SUBMIT RM06EM00
Input parameters:
Material
Plant

Working Flow:
User enters input values
Custom ALV report is generated
SUBMIT triggers standard ME2M report
Double-click navigation opens detailed transaction

Tables used:
EKKO – PO Header
EKPO – PO Item
EKET – Schedule Line
LFA1 – Vendor Data

Output:
Integrated custom + standard SAP reporting system

Technologies Used:
SAP ABAP
Smart Forms
ALV (ABAP List Viewer)
SUBMIT Statement
SAP GUI
SE38, SE11, SE80

Repository Structure:

SURE_TRUST_MAJOR_PROJECT/
│
├── SAP_ABAP_Project_Presentation.pptx
├── SAP_ABAP_Project_Documentation.pdf
└── README.md
