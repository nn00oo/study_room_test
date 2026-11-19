# StudySpace

StudySpace is a front-end prototype for finding and booking quiet study rooms on campus. It provides a complete client-side booking flow using sample room data, with no server or account setup required.

## Features

- Search for rooms by date, start time, end time, and group size
- Filter available rooms by building and facilities
- View room details, capacity, description, and facilities
- Confirm a booking with a name and university email
- Receive a generated booking reference
- View and cancel bookings
- Reset the prototype to its initial state
- Responsive Bulma-based interface with keyboard and screen-reader support

## Room data

The prototype includes rooms across:

- Hartley Library
- Marlow Building
- Riverside Hub

Facilities include whiteboards, screens, power sockets, and step-free access. Some rooms are seeded as already booked for tomorrow to demonstrate availability filtering.

## Run locally

No build step or dependencies are required. Open `index.html` directly in a browser, or serve the project with a simple local HTTP server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

- `index.html` - the complete prototype, including markup, styling, sample data, and booking logic
- `README.md` - project documentation

## Prototype limitations

This is a demonstration rather than a production booking system:

- Room and booking data are stored only in browser memory
- Bookings are lost when the page is refreshed
- There is no backend, authentication, database, or payment integration
- Help and Account navigation items are placeholders
- External room photos are not included; the room page uses photo placeholders

The interface is built with HTML, CSS, JavaScript, and [Bulma 1.0.2](https://bulma.io/), loaded from jsDelivr.