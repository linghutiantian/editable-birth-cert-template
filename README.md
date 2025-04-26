# Editable Birth Certificate HTML Template

**Note:** This template is pre-filled with Chinese labels and placeholders, intended for use in translating an English birth certificate into Chinese.

## Overview

This project provides an HTML template designed to resemble a US birth certificate document. It features extensive use of the `contenteditable` attribute, allowing most text fields to be modified directly within a web browser. The template includes basic styling (CSS) and JavaScript for dynamic barcode generation.

**Note:** The original template was styled based on a specific location (California, USA), but the personal and specific location data within the HTML has been obfuscated and replaced with generic placeholders (e.g., `[First Name]`, `[State Name]`, `[YYYY年MM月DD日]`).

## Features

*   **HTML Structure:** Mimics the layout and fields commonly found on a birth certificate.
*   **Direct Editing:** Uses `contenteditable="true"` extensively, allowing users to click and edit fields like names, dates, locations, and numbers directly in the browser.
*   **CSS Styling:** Basic styling is included to define layout, borders, and text appearance.
*   **Dynamic Barcode:** Includes JavaScript using the `JsBarcode` library (via CDN) to generate a CODE39 barcode based on the content of an editable field. The barcode updates automatically as the associated text is modified.

## Structure

*   **`index.html` (or your chosen filename):** The single HTML file containing:
    *   HTML structure (`<table>`, `<div>`, etc.) defining the certificate layout.
    *   Inline CSS (`<style>` block) for presentation.
    *   Inline JavaScript (`<script>` block) for editability enhancements and barcode functionality.
*   **External Dependency:**
    *   `JsBarcode` library: Loaded via CDN (cdnjs.cloudflare.com) for barcode generation.

## How to Use

1.  Open this HTML file in a modern web browser (e.g., Chrome, Firefox, Edge, Safari).
2.  Click on the text fields (often indicated by dotted underlines or their context within the form) to edit their content.
3.  Modify the text in the field designated for the barcode value (`[Barcode Value]`) and observe the barcode image update dynamically.

## Technology Used

*   HTML5
*   CSS3
*   JavaScript (Vanilla)
*   [JsBarcode Library](https://github.com/lindell/JsBarcode)

## ⚠️ Important Disclaimer & Warning ⚠️

*   **This is a TEMPLATE and NOT an official document.** It holds no legal validity.
*   **DO NOT use this template for any fraudulent, illegal, or deceptive purposes.** Attempting to create, use, or pass off a modified version of this template as a genuine birth certificate is illegal and carries severe legal consequences.
*   This template is provided solely for educational purposes, technical demonstration (e.g., showcasing `contenteditable`, HTML layout, basic JS integration), or as a starting point for *legitimate* template design exercises.
*   The developer assumes no responsibility for any misuse of this template. Use responsibly and ethically.