# RentACar Application

> This is the Lightning Web Component version of the RentACar application. If you are looking for the old Aura version,
> Car Rental CRM Project
> 🚗 Car Rental CRM – Salesforce Project (Short Summary)

A complete Car Rental Management CRM built on Salesforce to manage cars, bookings, customers, approvals, maintenance, and revenue insights. This project showcases Admin + Developer + LWC + Automation + Apex + Integration skills.

⭐ Project Overview

This CRM helps a car-rental business manage:

Car inventory & availability

Customer bookings

Preventing overlapping rentals

Manager approval for high-value bookings

Automated emails & notifications

Revenue dashboards & reports

🛠 Key Features
1. Data Model

Custom Objects: Car, Rental Booking

Relationships: Car ↔ Booking (Lookup), Customer ↔ Booking

Car fields: Model, Registration No, Daily Rate, Status

Booking fields: Start Date, End Date, Total Amount

2. Automation (Flows & Approvals)

Validation: End Date > Start Date

Auto-calculate Total Amount

Booking approval if amount > ₹50,000

Email alerts & in-app notifications to customer/agent

Task creation for car preparation

3. Apex Logic

Trigger to prevent overlapping bookings

Apex class for booking services

Scheduled job for upcoming rentals

Future & queueable jobs (e.g., insurance API)

Full test classes for deployment

4. Lightning Web Components (LWC)

Car Availability Search (by date)

Datatable showing available cars

Book Now button → creates booking via Apex

Navigation to booking record

5. Security & Access

OWD:

Car → Public Read Only

Rental Booking → Private

Profiles, Roles, Permission Sets

Login hours restriction for Agents

Field-level security for sensitive fields

6. Reports & Dashboards

Car Utilization Report

Revenue by Car Model

Manager Dashboard with KPIs

Dynamic dashboards for agents

7. Deployment & Data

Sample car dataset using Data Import Wizard

Change Sets / SFDX for deployment

Weekly backup enabled
