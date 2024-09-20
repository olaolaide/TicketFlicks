# TicketFlicks

This project is a **Cinema Ticket Booking System API** built using **.NET 8** and **Entity Framework Core**. The API is designed to provide an intuitive and user-friendly interface for managing movie showtimes, theater arrangements, seat reservations, and bookings.

## Features

### Movie Management
- Retrieve a list of available movies with details such as title, description, duration, and genre.
- Add, update, and delete movies from the system.

### Theater & Showtime Management
- Create and manage multiple theaters with unique seating arrangements.
- Define and manage showtimes for movies, specifying date, time, and available seats.

### Seat Reservation
- Allow users to reserve seats for a specific showtime.
- Ensure only available seats can be reserved.
- Implement a reservation timeout to automatically release unconfirmed seats after a set duration.

### Booking Confirmation
- Enable users to confirm seat reservations and complete bookings.
- Provide details such as movie name, showtime, seats reserved, and total price.

## Technology Stack
- **.NET 8**
- **Entity Framework Core**
- **Clean Architecture & Domain-Driven Design (DDD)**
- **Validation and Error Handling** for a robust user experience
- **Swagger** for API documentation
- **MediatR** for handling CQRS and application logic

## Guidelines Followed
- Adherence to best practices in **API design** for clarity, consistency, and usability.
- Implementation of **error handling and validation mechanisms**.
- Use of **unit tests** to ensure reliability.

## How to Use
1. Clone the repository.
2. Build and run the project.
3. Access API documentation via **Swagger** for available endpoints, functionalities, and sample request/response payloads.
