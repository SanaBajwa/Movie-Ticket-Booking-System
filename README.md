

# 🎬 Online Movie Ticket Booking Website

An amazing **Online Movie Ticket Booking** system built using **PHP, MySQL, HTML, CSS, and JavaScript**, hosted locally on **Apache XAMPP Server**. This mini-project was developed as part of the **Database Management Systems (DBMS)** subject during the third year of engineering.

The website allows users to seamlessly browse, explore, and book tickets for movies across various theaters. It mimics real-world online booking systems and demonstrates full-stack web development and database integration.



## 🌟 Features

* 🔐 **User Authentication**

  * User registration and login dashboard
  * Session handling for secure access

* 🔍 **Movie Search**

  * Search bar for upcoming and latest movies

* 🎞️ **Movie Carousel**

  * Slider bar displaying upcoming movie posters

* 🎥 **Movie Details**

  * View trailers, synopsis, cast, and reviews

* 🎟️ **Book Tickets**

  * Choose movie, location, timing, and seats
  * Real-time seat selection and availability

* 📩 **Booking Confirmation**

  * Confirmation message sent to the registered mobile/email upon successful booking
  * Seats are blocked after booking



## 🧰 Technologies Used

* **Frontend**: HTML, CSS, JavaScript
* **Backend**: PHP
* **Database**: MySQL
* **Local Server**: Apache (XAMPP)


## 🛠️ Setup Instructions

### 1. Install XAMPP

Download and install [XAMPP](https://www.apachefriends.org/index.html) for your operating system.

### 2. Project Setup

* Clone or download the project files into the `htdocs` directory of your XAMPP installation.

  ```bash
  C:\xampp\htdocs\movie-booking
  ```

### 3. Import the Database

* Open **phpMyAdmin** from `http://localhost/phpmyadmin`
* Create a new database (e.g., `movie_booking`)
* Import the provided `.sql` file into this database

### 4. Configure Database Connection

* Open `config.php` or any connection file (based on your project structure)
* Update the database credentials:

  ```php
  $conn = mysqli_connect("localhost", "root", "", "movie_booking");
  ```

### 5. Run the Project

* Open your browser and navigate to:

  ```
  http://localhost/movie-booking/
  ```


## ⚙️ Dependencies

* XAMPP Server
* PhpMyAdmin
* MySQL Database



## 📌 Notes

* Ensure Apache and MySQL services are running in XAMPP before accessing the site.
* Use a test email/SMS service for confirmation notifications if implemented.



## 🙌 Contributing

Feel free to fork this repo and improve the project! Contributions like bug fixes, UI enhancements, and feature additions are welcome.
