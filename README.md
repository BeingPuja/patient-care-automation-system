# patient-care-automation-system

## Overview
This project is an AI-powered operations automation system designed for an assisted living facility.

It integrates ClickUp for task management and n8n for workflow automation to streamline caregiving, sales, and visitor coordination.

---

## Features

- Caregiver task management system
- Medication tracking with status logging
- Sales CRM pipeline with lead tracking
- Visitor management with scheduled visits
- Automated weather-based email notifications

---

## Automation Workflow

The system uses n8n to:

1. Monitor visitor schedules
2. Filter visits based on visit date
3. Fetch weather data using OpenWeatherMap API
4. Send automated email notifications
5. Update task status to prevent duplicate alerts

---

## Tech Stack

- ClickUp (Task & CRM Management)
- n8n (Workflow Automation)
- OpenWeatherMap API
- SMTP Email Integration

---

## Key Design Decisions

- Implemented a state-based control mechanism using "Email Sent" flag
- Used scheduled triggers with filtering to ensure precise execution
- Designed system to handle multiple visitors simultaneously

---

## Future Improvements

- Replace current weather API with forecast-based API
- Add SMS notifications
- Improve scheduling with timezone handling
