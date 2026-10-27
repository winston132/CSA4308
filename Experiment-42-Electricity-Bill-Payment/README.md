# Experiment 42: Electricity Bill Payment & Slab Tariff System

## 1. Overview
PowerPay implements an official bi-monthly electricity billing system with precise mathematical slab calculation algorithms for Domestic and Commercial connections, late payment penalties, and payment gateway settlement.

## 2. Tariff Formulas & Mathematical Rules
- **Domestic Connection Slabs**:
  - First 100 units: ₹1.00 / unit
  - 101 to 200 units: ₹2.50 / unit
  - 201 to 500 units: ₹4.00 / unit
  - 501+ units: ₹6.00 / unit
- **Commercial Connection Slabs**:
  - First 100 units: ₹2.00 / unit
  - 101 to 200 units: ₹4.50 / unit
  - 201 to 500 units: ₹6.00 / unit
  - 501+ units: ₹7.00 / unit
- **Late Payment Penalty**: ₹10 added per day past the due date.
- **Bi-Monthly Cycle Management**: Displays duration start and end date with instant itemized cost breakdowns.

## 3. Technology Stack
- Semantic HTML5, CSS3 Grid Layout
- Monospace Financial Typography (`JetBrains Mono`)
- Real-time JavaScript Calculation Engine & Receipt Generator

## 4. Output Demonstration
![Electricity Bill Payment](screenshot.png)


## 5. Source Code Execution Screenshot
A capture of the source code implementation (`index.html`) executed for this experiment:
![Source Code Screenshot](code_screenshot.png)

## 6. Execution Output Verification
The execution output and verification details are recorded directly inside the source code comments of `index.html` and visually confirmed in `screenshot.png`.
