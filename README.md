# WOD — Wish • Organize • Delight

## Project Overview
**WOD** is a digital gifting platform that simplifies the process of sharing, organizing, and contributing to personalized gifts.  
It allows users to create wishlists, explore gift ideas, reserve gifts to avoid duplication, and contribute as groups for shared presents.  

This system was developed as part of our **Web Applications Engineering course (IT312)** at **King Saud University**, College of Computer and Information Sciences (CCIS).

---

## System Features
- **User Accounts** — Secure login and signup with hashed passwords.  
- **Wishlists** — Personalized wishlists with item management.  
- **Posts (Gift Ideas)** — Explore and share creative gift options.  
- **Reservations** — Prevent duplicate gifts through booking.  
- **Group Contributions** — Shared payment for group gifts.  
- **Notifications** — Event and reservation reminders.  
- **Calendar & Events** — Manage birthdays and special occasions.  

---

## System Design
The system follows a **three-tier architecture**:
1. **Presentation Layer (Frontend)** — HTML, CSS, and JavaScript.
2. **Application Layer (Logic)** — PHP for authentication and backend logic.
3. **Data Layer (Database)** — MySQL to store user, post, wishlist, and event data.

---

## Main Pages
| Page | Description |
|------|--------------|
| `index.html` | Homepage and main navigation |
| `login.html` | User login page |
| `signup.html` | User registration |
| `posts.html` | Gift ideas gallery |
| `wishlist.html` | User's wishlist |
| `friend-wishlist.html` | View friends’ wishlists |
| `group_contribution.html` | Group gift details |
| `calendar.html` | Event and reminder page |
| `profile.html` | User profile |

---

## Database
Implemented using **MySQL** with 8 tables:
- `users`
- `posts`
- `wishlists`
- `wishlist_items`
- `group_contributions`
- `reservations`
- `notifications`
- `events`

Each table is designed for scalability and future integration with e-commerce APIs.

---

## Team Members

- Renad Alowais
- Ghada Alqahtani
- Shooq Alawdah
- Noura Alamro
- Reema Alraqibah

---

## Tools & Technologies
- HTML5, CSS3, JavaScript  
- PHP & MySQL (MAMP)  
- GitHub for version control  
- Visual Studio Code  
- phpMyAdmin  
- Canva & Figma for UI design  

---

## Deployment
The project is hosted on **GitHub Pages**:  
[https://renadl.github.io/WOD/](https://renadl.github.io/WOD/)

---

## Preview
![WOD Interface](images/Box%20Logo%20(2)%202.png)

---

## License
This project was developed for academic purposes only.  
© 2025 — King Saud University | College of Computer & Information Sciences.
