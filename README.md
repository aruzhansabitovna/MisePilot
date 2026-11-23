# MisePilot — Smart Kitchen Management System

Group: Aruzhan Tazhmaganbet & Hüseyin Yiğit.

## Run
Upload ALL seven HTML files to the root of a public GitHub repository. Enable Settings → Pages → Deploy from branch → main → / (root). Open index.html. No build required.

## Pages
Dashboard, Inventory, Recipes, Preparation, Storage Zones, Kitchen Layout, Activity Log.

## Features
Three languages (English, Turkish, Russian), recipe images (internet required), step-by-step multilingual recipe guides, photo upload per step, printable guide, stock quantities, minimum stock alerts, storage locations, recipe-based stock deduction, cooking timer, kitchen layout, activity log, JSON export.

## Important limitations
This is a FRONT-END DEMO: data is saved separately in each browser's localStorage, not synchronized across staff devices. Recipe images are illustrative online photos. Step-by-step real preparation photos must be uploaded by the team; the placeholders are illustrations, not actual evidence of preparation. Timer pauses when navigating away or refreshing; remaining time is preserved. Kitchen layout is illustrative. Do not treat sample recipes or storage advice as validated food-safety procedures.

## Test checklist
1. Open each of the seven pages and navigate back.
2. Switch languages and verify the navigation, recipe title and instructions.
3. Add stock, adjust quantities, check low-stock warning and storage zones.
4. Open a recipe, upload a real step photo and print the guide.
5. Start cooking and confirm that recipe ingredients are deducted.
6. Open Preparation and run/pause the timer.
7. Review Activity Log and export JSON.
8. Repeat on mobile and desktop.

## User testing
Requirement: 10 kitchen employees and 1 storage employee, with participant feedback; report/video and class/fair presentation remain to be completed by the group.


Fix: HTML inline action escaping, storage filters, recipe detail modal, clickable dashboard statistics.
