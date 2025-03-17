# Social Connect

Social Connect is a social media platform built using Django, designed to function similarly to Instagram. Users can create posts, interact with others through likes and follows, and receive a personalized feed based on their following list.

## Features
- **User Authentication** – Secure user registration and login.
- **Post Management** – Users can upload, edit, and delete posts.
- **Like Feature** – Users can like posts.
- **Follow/Unfollow** – Users can follow or unfollow other users.
- **Personalized Feed** – Displays posts from followed users.
- **CRUD Operations** – Full functionality for user-generated content.

## Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite / PostgreSQL
- **Authentication**: Django Authentication System

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/social-connect.git
   cd social-connect
   ```

2. Apply migrations:
   ```sh
   python manage.py migrate
   ```

3. Create a superuser:
   ```sh
   python manage.py createsuperuser
   ```

4. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage
- Sign up and log in to the platform.
- Upload posts with images and captions.
- Like posts from other users.
- Follow/unfollow users to customize your feed.
- View a personalized feed based on followed users.


