# SafeHaven AI – Backend & AI Pipeline

## Overview
This document describes the backend and AI workflow for SafeHaven AI.

## AI Risk Analysis
- User inputs (images, location, sensor data) are processed.
- Google Gemini analyzes the data for potential safety risks.
- Risks are classified as Low, Medium, or High.

## Decision Engine
- Low risk → Safety suggestion shown to user
- Medium risk → Alert + precaution advice
- High risk → SOS triggered automatically

## Emergency Response
- Firebase sends real-time notifications to emergency contacts.
- Google Maps API provides live location sharing.
- Google Cloud supports scalable backend operations.

## Status
This MVP demonstrates feasibility and system design.
Full backend implementation is planned for future development.
