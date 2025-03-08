# SAP ABAP Shipment ALV Report 📦

## Overview
A comprehensive SAP ABAP shipment tracking report that integrates delivery, material, and shipping information across multiple SAP modules. The report combines data from shipment management (VTTP/VTTK), delivery processing (LIPS/LIKP), and billing (VBRK) to provide a complete view of shipment operations.

### Data Integration
- **Shipment Data (VTTP/VTTK)**
- **Delivery Details (LIPS/LIKP)**
- **Billing Information (VBRK)**

### Key Features
- Multi-table data integration with optimized joins
- Comprehensive filtering options:
  - Delivery Numbers
  - Plants
  - Creation Dates
- Detailed material and shipping information
- Complete tracking of document flow
- User and time stamp tracking
- Carrier and route monitoring

### Business Benefits
- End-to-end shipment visibility
- Integrated delivery tracking
- Material movement monitoring
- Financial value tracking
- Complete audit trail
- Operational efficiency insights

### Presentation Layer
- ALV Grid display
- Interactive user interface
- Custom field catalog
- Layout variants

# Screen Documentation

## 1. Selection Screen
<p align="center">
  <em>Main selection screen featuring delivery filtering, plant selection, creation date range, and field catalog configuration options</em>
  <br>
  <img src="Shipment/screens/1.png" alt="Selection Screen">
</p>

## 2. Validation Rules

### Status Selection Validation
<p align="center">
  <em>Validation preventing simultaneous selection of 'All' with specific status options (Old/Temporary/New)</em>
  <br>
  <img src="Shipment/screens/2.png" alt="Status Validation">
</p>

### Date Range Validation
<p align="center">
  <em>Creation date (ERDAT) validation preventing future date selection</em>
  <br>
  <img src="Shipment/screens/3.png" alt="Date Validation">
</p>

### Delivery Number Validation
<p align="center">
  <em>Delivery number (VBELN) range validation ensuring lower limit doesn't exceed upper limit</em>
  <br>
  <img src="Shipment/screens/4.png" alt="Delivery Validation">
</p>

## 3. ALV Output Display

<p align="center">
  <em>ALV Grid display showing shipment details with color-coding based on status</em>
  <br>
  <img src="Shipment/screens/5.png" alt="ALV Default View">
</p>

<p align="center">
  <em>Different color schemes and groupings based on shipment criteria</em>
  <br>
  <img src="Shipment/screens/8.png" alt="ALV Alternative View 1">
  <br>
  <img src="Shipment/screens/9.png" alt="ALV Alternative View 2">
</p>

## 4. Additional Features

### Print Functionality
<p align="center">
  <em>Print preview and options accessed via toolbar print icon</em>
  <br>
  <img src="Shipment/screens/6.png" alt="Print Options">
</p>

### Layout Management
<p align="center">
  <em>Layout selection between user-specific and default system layouts</em>
  <br>
  <img src="Shipment/screens/7.png" alt="Layout Selection">
</p>

### Navigation Feature
<p align="center">
  <em>Direct navigation to ZSHIPMENT_DEMO transaction via shipment number (TKNUM) hotspot</em>
  <br>
  <img src="Shipment/screens/10.png" alt="Transaction Navigation">
</p>

### Status Filtering
<p align="center">
  <em>Filtered view when 'New' status is selected, showing only relevant records</em>
  <br>
  <img src="Shipment/screens/11.png" alt="Status Filter">
</p>

## Technical Features
- Interactive ALV Grid
- Color-coding based on status
- Hotspot navigation
- Multiple layout options
- Print functionality
- Status-based filtering
- Comprehensive validation rules
- Direct transaction navigation

## New Feature: Adobe Form Integration

### Printing Functionality
The system now supports printing shipment reports using Adobe Forms with the following features:

#### How to Print
1. **Access Print Function**
   - Click the print button in the toolbar
   - Alternatively, use the keyboard shortcut `SHIFT + F1`

# Screen Documentation for PDF Abdobe Form  

### Print Action
<p align="center">
  <em>Click to print button into the toolbar or press SHIFT+F1</em>
  <br>
  <img src="Shipment/screens/print.png" alt="print">
</p>

### Output Device and Print Preview
<p align="center">
  <em>Choose LP01 as output device and click on print preview</em>
  <br>
  <img src="Shipment/screens/action.png" alt="action">
</p>

### Popup to open or save PDF on the desktop
<p align="center">
  <em>Choose open PDF or save it on the desktop.</em>
  <br>
  <img src="Shipment/screens/openpdf.png" alt="openpdf">
</p>

## Shipment Report PDF Preview
![Page 1](Shipment/screens/page1.png)

## PDF
[![PDF](https://img.shields.io/badge/📥_Download_PDF-2ea44f.svg)](Shipment/adf.pdf) [![Size](https://img.shields.io/badge/3.6_KB-orange.svg)](Shipment/adf.pdf)
