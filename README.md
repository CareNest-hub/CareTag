# CareTag Self-Contained Website

This package contains only two required HTML files:

- index.html — full CareTag form, design, and QR generator
- emergency.html — medical profile page opened after scanning

The CSS and JavaScript are embedded inside each HTML file, so the design will not
disappear even when style.css or script.js are not uploaded.

## GitHub Pages

Upload both files to the same repository folder:

1. index.html
2. emergency.html

Open the published index.html page and generate a new QR code.

Do not generate the QR by opening index.html directly from the computer because a
phone cannot open a file:/// address from another device.
