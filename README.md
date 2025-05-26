# Online Movie Streaming Website

A web application for display movies online built with vanilla PHP and modern CSS.

## Features

### User Features
- User registration and authentication
- Browse movies by genre
- View movie details (title, description, length, release year, etc.)
- Create and manage personal playlists
- Search functionality for movies
- Responsive design for all devices

### Admin Features
- User management (add/edit/delete users)
- Genre management (add/edit/delete genres) 
- Movie management
- Role-based access control (admin/user)

## Technology Stack

### Backend
- Vanilla PHP
- MySQL Database
- PDO for database operations
- Session-based authentication

### Frontend
- HTML5
- CSS3
- Boxicons for icons
- Owl Carousel for sliders
- Responsive design using CSS Grid and Flexbox

### Database Structure
- Users table (id, name, email, password, role)
- Movies table (id, title, description, length, release_year, etc)
- Genres table (id, genre_name)
- Playlists table
- Subscription Plans table(not completed)
- Movie-Genre relationships

## File Structure
```
├── app.css              # Main CSS styles
├── app.js              # Frontend JavaScript
├── grid.css            # Grid system styles
├── home.php            # Home page
├── homeadmin.php       # Admin dashboard
├── movies.php          # Movies listing
├── movie_detail.php    # Individual movie page
├── movie_genre.php     # Genre-specific movies
├── playlist.php        # User playlists
├── genre.php          # Genre management
├── genreadd.php       # Add new genre
├── genreedit.php      # Edit genre
├── user.php           # User profile
├── useradmin.php      # User management
├── useradd.php        # Add new user
├── useredit.php       # Edit user
├── login.php          # Login page
├── register.php       # Registration page
├── Pager.php          # Pagination component
├── images/            # Image assets
    ├── movies/        # Movie posters
    ├── series/        # TV series posters
    └── cartoons/      # Animation posters
```

## Installation

1. Clone the repository
2. Set up a PHP development environment (e.g., XAMPP, WAMP)
3. Create MySQL database and import the schema
4. Configure database connection in PHP files
5. Place the project in your web server's root directory
6. Access through localhost in your browser

## Credits

Developed by:
- Đinh Hoàng Phúc - 2001216045
- Nguyễn Hoài Tiến - 2033216575
- Phạm Huỳnh Hữu Thành - 2001210048
