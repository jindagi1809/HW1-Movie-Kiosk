# Movie Theater Ticket Kiosk

This self-service kiosk lets customers view available movies and showtimes, choose an available seat, and purchase a ticket. After a successful purchase, the system provides a confirmation and prevents the same seat from being sold twice for the same showtime.

## Expanded Use Case: Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The kiosk is available, and a showtime has seats available for purchase.

### Main Steps
1. The customer views available movies and showtimes.
2. The customer selects a showtime.
3. The system displays available seats.
4. The customer selects a seat and requests a purchase.
5. The system checks availability and temporarily holds the seat to prevent another purchase.
6. The customer provides payment, and the system processes it successfully.
7. The system marks the seat as sold, creates the ticket, and displays a confirmation.

**Postcondition:** The purchase is recorded, a ticket and confirmation are provided, and the seat cannot be sold again for the same showtime.
