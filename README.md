# Booking-app
This is a simple booking application built using Go. It allows users to book tickets for the Go Conference and displays real-time ticket availability.
# Features 
Ticket booking system for a conference
Real-time updates on ticket availability
User-friendly prompts for booking
Confirmation message upon successful booking

# Project Structure

Booking-app/
│
├── Booking-app/
│   ├── go.mod         # Go module file
│   ├── main.go        # Main application file
│   └── helper/
│       └── helper.go  # Helper functions
├── .git/              # Git repository configuration
└── README.md          # Project documentation

# Installation

1. Clone the repository:

git clone https://github.com/your-username/Booking-app.git
cd Booking-app

2. Initialize Go modules (if not already done):

go mod init booking-app
go mod tidy

# Running the Application

To run the booking application, use the following command:
go run ./Booking-app/main.go ./Booking-app/helper/helper.go

# Example Usage
Welcome to Go Conference booking application
We have total of 50 tickets and 50 are still available.
Get your tickets here to attend
Enter your first name: sonali
Enter your last name: singh
Enter your email address: ssona@gmail.com
Enter number of tickets: 3
List of bookings is [{sonali singh ssona@gmail.com 3}]
Thank you sonali singh for booking 3 tickets. You will receive a confirmation email at ssona@gmail.com
47 tickets remaining for Go Conference

# Contributing

Feel free to submit issues or pull requests. Contributions are welcome!




