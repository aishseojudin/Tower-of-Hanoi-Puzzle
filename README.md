# Tower of Hanoi Project 🎮

## Team Members: 🙌
**•	Sneha Das - 23SCSE1280020                              
•	Ritik Kumar  - 23SCSE1280018                               
• Kushagr Singh - 23SCSE1280072                          
•	Sahil Raj    - 23SCSE1280059**

## Objective 🎯
The object of the Tower of Hanoi puzzle is to move all the disks from the source peg to the target peg, following these rules:
1. Only one disk can be moved at a time.
2. Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack. In other words, a disk can only be moved if it the uppermost disk on a stack.
3. No larger disk may be placed on top of a smaller disk.
   The puzzle's challenge lies in finding the optimal sequence of moves to complete the task efficiently.

## Problem Statement 🤔
Given a set of n disks of different sizes stacked on a source peg, the problem is finding the minimum number of moves required to transfer all the disks to the target peg, following the Tower of Hanoi puzzle rules.

## Project Website 
### Home Page
[hanoihome.webm](https://github.com/user-attachments/assets/59e707b4-0c47-4067-95d7-e44871207946)

### Sign up Page
![Screenshot 2024-12-07 122505](https://github.com/user-attachments/assets/4f185397-45a0-4192-94eb-10c4ad8e9608)

### Login Page
![Screenshot 2024-12-07 122401](https://github.com/user-attachments/assets/f4d7fef3-b14f-4140-815f-76fda85225a4)

### Game Page
![Screenshot 2024-12-07 133455](https://github.com/user-attachments/assets/6bf58f39-5cb3-4876-8101-5b7eddf2070b)

### Game History Page
![Screenshot 2024-12-07 122205](https://github.com/user-attachments/assets/32869f7f-b4ce-4731-9f93-a602c47701e6)

## Project Setup Guide 🛠️
### 1. Development Environment Setup
- Install Java JDK (version 8 or higher)
- Install MySQL Server
- Set up your preferred IDE (Eclipse, IntelliJ, etc.)

### 2. Database Setup
- Create MySQL database schema
- Configure database connection properties
- Execute initial database scripts
- Set up user authentication tables
- Configure connection pooling
  
### 3. The application features:
- Secure user registration and login system
- Interactive Tower of Hanoi game
- Score tracking and history
- Responsive design using Bootstrap
- Form validation
- Database persistence of user data and scores

### 4. Project Structure 📁
```
Tower-of-hanoi-puzzle/
├── README.md
└── HanoiPuzzle/
    ├── lib/
    │   ├── DatabaseConnection.java
    │   └── database_schema.sql
    ├── src/
    │   └── main/
    │       └── com/hanoiheights/
    │           ├── ScoreDAO.java
    │           └── UserDAO.java
    ├── webapp/
    │   ├── css/
    │   │   └── styles.css
    │   ├── js/
    │   │   ├── game.js
    │   │   └── scoreboard.js
    │   ├── game.html
    │   ├── login.html
    │   ├── register.html
    │   └── scoreboard.html
    └── pom.xml

```

## Technical Stack Overview ⚙
### 1. Programming Languages
   - Java (Backend logic)
   - HTML5/CSS3 (Frontend structure and styling)
   - JavaScript (Frontend logic and interactivity)
   - SQL (Database operations)

### 2. Core Components
   - Java Classes:
     * TowerOfHanoi: Main program entry
     * TowerSolver: Algorithm implementation
     * Towers: Data structure management
     * DAO Classes: Database operations
     * Service Classes: Business logic
   
   - Web Components:
     * HTML: Structure and content
     * CSS/Bootstrap: Styling and responsiveness
     * JavaScript: Game logic and validation
     * JDBC: Database connectivity

### 3. Data Management
   - MySQL Database
   - JDBC for database operations
   - Local Storage for user data
   - Array-based data structures
   - JSON for data serialization

### 4. Features
   - User authentication with database integration
   - Interactive gameplay
   - Score tracking with persistence
   - Auto-solver
   - Move validation
   - Progress tracking
   - Form validation
   - User profile management

### 5. Development Environment
   - Java Development Kit (JDK)
   - MySQL Database
   - Web development tools
   - Version control system
   - Maven for dependency management

## Database Schema 💾
### Tables:
1. Users
   - user_id (PK)
   - username
   - password
   - email
   - created_at

2. GameProgress
   - progress_id (PK)
   - user_id (FK)
   - level
   - moves
   - completion_time
   - date_played

3. UserStats
   - stats_id (PK)
   - user_id (FK)
   - total_games
   - best_score
   - average_moves

## Tower of Hanoi - Future Development Plans 🎮
### Planned Enhancements:
- 3D visualization using Three.js/WebGL
- Multiplayer mode with real-time competition
- AI-powered move suggestions
- Social media integration for score-sharing
- Mobile app development (iOS/Android)
- Advanced difficulty levels with time constraints
- Custom themes and animations
- Global leaderboard system
- Achievement/badge system
- Tutorial mode with interactive learning
- Voice commands for disk movement
- Profile customization
- Replay system for reviewing moves
- Performance analytics dashboard
- Multi-language support
- Accessibility features for differently-abled users

## Getting Started 🚀
1. Clone the repository
2. Set up the development environment
3. Configure database connection
4. Run database scripts
5. Build and run the project
6. Access the application at localhost:3306

🌟 This project aims to transform a classic puzzle into an engaging, modern gaming experience while maintaining its educational value. Join us in making learning fun! 🎯
