Pet-Care Appointment Web App — PRD (MVP Version)
1. Purpose

The Pet-Care Appointment Web App enables pet owners to book essential services such as veterinary checkups, grooming, and vaccinations at nearby clinics within a single city.
This MVP focuses on simplicity and includes only the basic flows required to validate the booking experience.

2. Target Users
Primary Users

Pet owners living in a single city who need to book pet-care services.

Secondary Users

Pet clinics offering basic services and wanting to accept online appointments.

3. Scope (MVP Only)
In-Scope Features

User registration and login

Pet registration (add/edit/remove)

View list of clinics

Simple map view showing clinic locations (within one city)

View services offered by each clinic (checkup, grooming, vaccination)

View available time slots

Book an appointment

View upcoming appointments

Out-of-Scope (Not included in MVP)

Payments

Notifications

Multi-city selection

Directions or advanced navigation

Chat with clinics

Reviews or ratings

Medical history for pets

Admin dashboard for clinics

4. Core User Flows
4.1 User Registration Flow

User opens app → taps Sign Up

Enters name, email, password

Logs in and sees dashboard

4.2 Pet Registration Flow

User goes to “My Pets”

Clicks “Add Pet”

Enters: name, type, breed, age

Pet appears in list

4.3 Clinic Browsing Flow

User opens “Clinics”

Sees list of clinics in the city

Switches to simple map to view clinic pins

Selects a clinic to view details

4.4 Booking Flow

User chooses a clinic

Picks a service type

Sees available time slots

Selects a pet

Confirms appointment

Appointment is saved and visible under “My Appointments”

4.5 Appointment View Flow

User opens “My Appointments”

Sees upcoming bookings with clinic, date, time, pet, and service

5. Functional Requirements
5.1 User Accounts

Users can sign up, log in, and log out

Users can update basic profile details

5.2 Pets

Add/edit/remove pet profiles

Each pet belongs to exactly one user

5.3 Clinics

Display clinic name, address, location pin on map, and contact

Show list of services per clinic

5.4 Services & Slots

Each clinic has fixed services

Each clinic has predefined time slots per day

Only available slots can be booked

5.5 Appointments

Appointment must store:

user

pet

clinic

service

time slot

Appointment appears under “My Appointments”

6. Non-Functional Requirements (MVP Level)

Fast & simple UI

Booking flow must finish within 2 minutes

Prevent double-booking the same slot

Map view must load quickly with clinic pins

App should work smoothly on mobile-size screens

7. Success Metrics (MVP Validation)

Number of registered users

Number of registered pets

Number of clinic views

Number of appointments booked

User feedback on ease of booking

8. Constraints

Only one city supported

Only essential services covered (checkup, grooming, vaccination)

Minimalist design due to MVP scope
