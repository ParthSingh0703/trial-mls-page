# Trial MLS Residential Listing Form

## Overview
This project is a web-based simulation of an MLS (Multiple Listing Service) Residential Listing Form, designed for browser automation testing and demonstration purposes. It mimics the behavior and fields of a standard real estate listing input form, specifically tailored for the Austin/Texas market context.

## Features
- **Comprehensive Listing Form**: Includes detailed sections for Listing Meta, Address, Schools, Property Details, Utilities, Financials, and Showing instructions.
- **Glassmorphism Design**: A modern, dark-themed UI with glassmorphism effects and responsive layout.
- **Image Upload**: A dedicated page for uploading listing images with client-side previews, room type tagging, and description fields.
- **American Date Format**: Enforced "MM/DD/YYYY" format for date inputs.
- **Responsive**: Adapts to mobile and desktop viewports.

## Project Structure
- `index.html`: The main listing form application.
- `upload_images.html`: The image upload and management interface.

## How to Run
This is a static HTML/JS project. You can run it on any static file server.

### using Python (Pre-installed on macOS/Linux)
1. Open your terminal.
2. Navigate to the project directory.
3. Run the following command:
   ```bash
   python3 -m http.server 8080
   ```
4. Open your browser and visit: `http://localhost:8080/index.html`

## Technologies
- HTML5
- CSS3 (Custom Variables, Flexbox, Grid)
- Vanilla JavaScript
