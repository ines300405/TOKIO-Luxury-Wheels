# Luxury Wheels – Fleet Management

A **fleet management system** for the company **Luxury Wheels**, developed in Python with a **Tkinter GUI**.
This application allows managing clients, vehicles, reservations, payments, and provides a dashboard with statistics.

---

## Features

- **Client Management**: Add, update, delete, list, and export clients to CSV.
  
- **Vehicle Management**: Add, edit, remove, mark vehicles for maintenance, and export vehicle data.

- **Reservation Management**: Create, update, delete reservations, and export to CSV.

- **Payment Management**: Register payments, associate with reservations and payment methods.

- **Dashboard**: Visualize fleet, reservations, and payment statistics.

- **Automatic Alerts**: Receive notifications for upcoming vehicle maintenance or inspections..

---

## Project Structure

luxury_wheels/
│
├─ controllers/        # Business logic for each module (clients, vehicles, reservations, payments)
├─ models/             # Data models representing entities
├─ ui/                 # Tkinter UI components for each module
├─ utils/              # Helper functions (tooltips, export, alerts)
├─ db/                 # SQLite database connection and scripts
├─ main.py             # Entry point of the application
└─ photo_cars/         # Vehicle images used in the application

---

## Technology Stack

- **Python 3.11**+
- **Tkinter** (GUI framework)
- **SQLite** (local database)
- **Pillow (PIL)** for image handling
- CSV for data export
- Logging for debugging and alerts

## Installation

1. Clone the repository:
  git clone <REPOSITORY_URL>
  cd luxury_wheels

2. Create a virtual environment:
  python -m venv venv

3. Activate the environment:
    - **Windows**:
  venv\Scripts\activate

    - **macOS/Linux**:
  source venv/bin/activate

4. Install dependencies:
  pip install -r requirements.txt

5. Run the application:
  python main.py

## How It Works

**Main Menu**: Navigate between Clients, Vehicles, Reservations, Payments, and Dashboard.

**Client Module**: Manage client data and export CSV.

**Vehicle Module**: Manage vehicles, mark maintenance, preview images.

**Reservation Module**: CRUD operations for reservations with date validation.

**Payment Module**: Register and track payments.

**Dashboard**: Summarizes fleet status, reservations, and payments.

**Alerts**: Pop-up notifications for upcoming vehicle maintenance or inspections.



