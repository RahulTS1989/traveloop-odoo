# Traveloop – AI Powered Travel Planning Module

Traveloop is an Odoo-based travel management module designed to simplify trip planning and budgeting.  
The project was developed as a hackathon MVP to demonstrate how Odoo can be used to build smart and scalable travel solutions.

The module allows users to create trips, manage travel expenses, organize activities, and publish trip details through a public webpage interface.

---

# Features

## Trip Management
- Create and manage travel plans
- Add trip start and end dates
- Store destination and travel details

## Budget Tracking
- Separate budget categories:
  - Transport
  - Hotel
  - Food
  - Activities
- Automatic total budget calculation

## Activity Planning
- Add trip activities and notes
- Organize schedules for better planning

## Public Trip Page
- Share trip details through a public webpage
- Dynamic rendering using Odoo QWeb templates

## Odoo Integration
- Built using Odoo module architecture
- Uses models, controllers, and XML views
- Easy to extend and customize

---

# Tech Stack

- Python
- Odoo Framework
- XML / QWeb Templates
- PostgreSQL
- HTML/CSS
- Git & GitHub

---

# Project Structure

```bash
traveloop_module/
│
├── controllers/
│   └── main.py
│
├── models/
│   ├── activity.py
│   ├── budget.py
│   ├── city.py
│   └── notes.py
│
├── views/
│   ├── public_templates.xml
│   └── other_views.xml
│
├── security/
│
├── static/
│
├── __init__.py
├── __manifest__.py
└── README.md
