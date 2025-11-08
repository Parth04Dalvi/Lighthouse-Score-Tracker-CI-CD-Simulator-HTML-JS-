# Lighthouse-Score-Tracker-CI-CD-Simulator-HTML-JS-
⚡ Lighthouse Score Tracker & CI/CD Simulator

Web Performance Monitoring Dashboard

This project is a single-page web application designed to simulate a real-world continuous integration (CI) dashboard for tracking website performance using Google Lighthouse metrics. It allows developers to input a URL and instantly retrieve a simulated, structured performance audit, demonstrating a strong understanding of Web Performance Optimization (WPO) principles.

✨ Key Features & Technical Highlights

Core Vitals Display: Clear visualization of crucial performance metrics like Lighthouse Score, First Contentful Paint (FCP), and Largest Contentful Paint (LCP).

Performance Gauge: Uses SVG/Canvas to render a dynamic radial gauge representing the overall Lighthouse Score (simulated).

Historical Trend Simulation: Includes a component to show a simulated historical trend line, proving architectural thinking for time-series monitoring.

CI/CD Workflow Simulation: The application's process simulates the typical steps in a CI pipeline: Input → Queue → Processing → Structured Report Output.

Responsive Metrics: A clean, actionable UI built with Tailwind CSS that uses color coding (Green/Yellow/Red) to indicate metric health.

🛠️ Technology Stack

Frontend: HTML5, Vanilla JavaScript (for simulation and DOM manipulation)

Styling: Tailwind CSS (for professional, responsive UI)

Visualization: Chart.js (for rendering the historical trend line)

Simulation Core: Pure JavaScript logic modeling the structure of a Lighthouse API response.

🚀 How to Run the Tracker

Open the file: Load lighthouse_tracker/index.html in your browser.

Input URL: Enter any website URL 

Run Audit: Click the "Run Lighthouse Audit" button.

View Results: After a simulated processing delay, the dashboard will populate with the categorized performance metrics, including the final score and historical trends.
