# Airbnb Clone

A clone of the Airbnb website created as a personal project.

![Project Preview](screenshots/app-screenshot.png)

## Table of Contents

- [Airbnb Clone](#airbnb-clone)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
    - [Authentication](#authentication)
    - [Create Your Own Hotel](#create-your-own-hotel)
    - [Hotel Reservation](#hotel-reservation)
    - [Image Upload](#image-upload)
    - [Trips](#trips)
    - [Cancel Reservations](#cancel-reservations)
    - [Favorites](#favorites)
    - [Logout](#logout)
    - [Filtering](#filtering)
  - [Getting Started](#getting-started)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)

## Introduction

Welcome to my Airbnb clone project! This project aims to replicate the core features of the Airbnb website, allowing users to browse and book accommodations. Users can also create and list their own hotels, manage reservations, and more.

## Features

### Authentication

The project includes the following authentication options:

- Google Sign-In: Users can log in using their Google accounts.
- GitHub Sign-In: Users can log in using their GitHub accounts.
- Email Sign-Up and Sign-In: Users can sign up and log in using their email addresses.

### Create Your Own Hotel

Logged-in users have the ability to create and list their own hotels:

1. Log in to your account.
2. Click the "Airbnb Your Home" button.
3. Follow the steps to provide details about your hotel, such as location, description, photos, and pricing.
4. Your hotel will be listed and available for other users to book.

### Hotel Reservation

Logged-in users can reserve hotels by choosing dates from a calendar. Multiple reservations on the same dates are prevented.

### Image Upload

Users can upload images for their hotels to showcase them to potential guests.

### Trips

Users can view all their upcoming reservations on the /trips page.

### Cancel Reservations

Hotel creators can cancel guest reservations for their own hotels on the /reservations page.

### Favorites

Users can like specific hotels and view their liked hotels on the /favorites page.

### Logout

Users can log out of their accounts.

### Filtering

Users can filter hotels by country, date, price, and available rooms for rent.

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone the repository: `git clone https://github.com/your-username/airbnb-clone.git`
2. Navigate to the project directory: `cd airbnb-clone`
3. Install dependencies: `npm install` or `yarn install`
4. Set up environment variables for authentication (see [Configuration](#configuration))
5. Run the application: `npm start` or `yarn start`
6. Open your web browser and navigate to `http://localhost:3000`

## Usage

Once the application is running, you can:

- Browse available accommodations
- View accommodation details, photos, and reviews
- Log in using your Google, GitHub, or email account
- Create and list your own hotels
- Reserve hotels by choosing dates
- Upload images for your hotels
- View upcoming reservations
- Cancel guest reservations for your own hotels
- Like and view your liked hotels
- Log out of your account
- Filter hotels by various criteria
- ...

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Create a pull request

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or feedback, contact me at your@email.com.
