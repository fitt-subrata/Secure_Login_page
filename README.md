# Secure_Login_page

This is a secure user registration and login system developed using Python’s Flask framework. It allows users to register using email and password, with form validation and secure password hashing. All data is stored in a MySQL database. The application has a modern UI and includes client-side and server-side validation.

# Flask User Authentication System

A secure and modern user registration and login web application built with Python, Flask, and MySQL. This project demonstrates session management, password hashing, form validation, and a clean frontend design using HTML, CSS, and SweetAlert2.

# Project Overview

#Features

## User Authentication
Secure user registration with form validation
Secure login using hashed passwords (bcrypt)
Prevents duplicate registrations by checking for existing emails

## Form Validation
Backend form validation using Flask-WTF
Custom password strength hints and client-side checks using JavaScript + SweetAlert2

## Security
Passwords stored in the database using strong hashing via bcrypt
Secrets and database credentials managed using .env with python-dotenv
CSRF protection enabled by default through Flask-WTF

## Database Integration
MySQL used for storing user data (id, name, email, password)
Clean schema with unique email enforcement

## Frontend
Modern UI with custom HTML and CSS
Responsive form layout
Flash messages for registration, login success, and errors

## Code Structure
Organized with separate templates (login.html, register.html, dashboard.html)
Uses templates/ and static/ folders for scalable design
Code is clean and modular in a single app.py file

## Extras
Password field includes client-side rules (uppercase, number, symbol, etc.)
Dashboard access protected for authenticated users only
Logout feature clears the session



