# HealthCare Clinic — Static Clinic Page

A minimal, responsive, and accessible static clinic web page built with plain HTML and CSS (no build tools).

This repository contains a single page, `clinic.html`, which showcases a fictional healthcare clinic's services, doctors, booking form, contact information and a simple interactive booking confirmation.

## Features

- Modern dark UI with responsive layout
- Hero section with stats and quick actions
- Services grid and doctors directory
- Booking form with basic client-side validation and confirmation
- Contact section with clinic info and illustrative map
- No external build tools — single self-contained HTML file

## Files

- `clinic.html` — main single-file site. Open directly in a browser to preview.

## Quick start — preview locally

1. Open the file in your browser:

   - Double-click `clinic.html` in your file explorer, or
   - In VS Code, right-click the file and choose "Open with Live Server" (if you have the Live Server extension), or
   - From a terminal (PowerShell on Windows):

     php -S localhost:8000 -t .; then open http://localhost:8000/clinic.html in your browser

   Note: The file can be opened directly (file:///) but some browser features (date picker, fetch from local files) behave better when served over HTTP.

## Deployment — GitHub Pages

To host this page on GitHub Pages from this repository:

1. Initialize a git repository (if not already):

   git init; git add .; git commit -m "Initial commit"

2. Create a new repository on GitHub and push your code. Example (replace the URL with your repo):

   git remote add origin https://github.com/<your-username>/<your-repo>.git; git branch -M main; git push -u origin main

3. In your GitHub repository settings, enable GitHub Pages and set the source to the `main` branch and the `/ (root)` folder. Save.

4. Your site will be available at `https://<maiyashchauhan>.github.io/<your-repo>/clinic.html` shortly.
# clinic
