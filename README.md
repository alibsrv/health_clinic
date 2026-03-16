# Community Health Clinic API

A RESTful API built to transition a local community health clinic from a paper-based system to a digital one. This system manages patient registrations, generates unique patient IDs, and handles appointment bookings while ensuring data integrity by preventing double-booked time slots.

## Features
* **Patient Registration:** Register new patients with their name, address, and medical history.
* **Unique ID Generation:** Automatically generates a unique Patient ID upon successful registration.
* **Appointment Booking:** Allows registered patients to book available time slots using their Patient ID.
* **Slot Validation:** Checks for scheduling conflicts to ensure an appointment slot is open before confirming a booking.

## Technologies Used
* Python
* Django
* Django REST Framework (DRF)
* SQLite (Default) 

## Prerequisites
Ensure you have the following installed on your local machine:
* Python 3.8+
* pip (Python package installer)

## Installation & Setup

**1. Clone the repository**
```bash
git clone (https://github.com/alibsrv/health_clinic)
cd clinic-api
