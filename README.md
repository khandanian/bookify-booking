# Bookify — Booking Management Demo

A responsive Persian RTL appointment scheduling and management web app, built with vanilla HTML, CSS and JavaScript.

## Demo
https://khandanian.github.io/bookify-booking/

## Features
- Choose service, specialist, date and available start time
- Conflict detection based on each service's duration and specialist schedule
- Past dates and elapsed times cannot be booked
- Register bookings and receive a tracking ID
- Dashboard with today's appointments, upcoming bookings, completed bookings and completed-service revenue
- Manage appointment status: pending, confirmed, completed, cancelled
- Search, filter, delete, and export appointments to UTF-8 CSV
- localStorage persistence and responsive design

## Limitations
**Portfolio demo only.** No backend, authentication, payment, SMS, or synchronization across users/devices. Two separate browsers can reserve the same slot. Booking data is stored unencrypted in the local browser; do not enter sensitive real customer data. All services, specialists and prices are illustrative. Dates use Gregorian input; amounts are Iranian toman.

## Local development
Open `index.html` or serve with `python -m http.server 8080`.

## GitHub Pages
Enable **Settings → Pages → Build and deployment → Source: GitHub Actions** once. The workflow in `.github/workflows/deploy.yml` deploys on pushes to `main` and does not attempt Pages enablement via the restricted workflow token.
