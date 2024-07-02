# SKKU Textbook Trading Platform Using WebSockets

## Overview
This project aims to develop a second-hand textbook trading platform for Sungkyunkwan University students. Utilizing WebSocket technology, the platform facilitates real-time communication, allowing students to efficiently buy and sell textbooks and communicate instantly.

## Table of Contents
- Overview
- Goals
- Requirements
- Architecture & Design
- Timeline & Milestones
- Installation
- Usage
- Contributing
- License

## Goals
The primary goal is to create an efficient, user-friendly platform where students can:
- Buy and sell textbooks
- Communicate in real-time via chat
- Manage their textbook listings
- Receive real-time notifications

## Requirements
### User Management
- Users can sign up and log in.
- Only logged-in users can list books and use the chat feature.

### Book Listing and Management
- Sellers can input book details (title, author, publisher, condition) to list a book.
- Sellers can manage the status of their listings (e.g., available, sold).

### Chat Functionality
- Users can send and receive messages in real-time using WebSocket.
- Users can initiate and participate in private chats related to book transactions.

### Notification System
- Users receive notifications about chat messages and transaction statuses.

## Architecture & Design
### Web Client
- Develop the user interface and handle user requests.
- Use HTML, CSS, and JavaScript for frontend development.
- Update chat status in real-time via WebSocket.

### Backend Server
- Handle business logic including user authentication, book management, and chat processing.
- Use Spring Framework for backend development.
- Store data such as user information, book details, and chat histories.

### Database
- Manage and store user information, book listings, and chat data.
- Implement a NoSQL database.

### WebSocket Server
- Enable real-time chat functionality.
- Develop using Node.js and Socket.io.
- Support bidirectional communication between client and server.

### Security and Infrastructure
- Use HTTPS for secure data transmission.
- Enhance system security with user authentication and authorization.
- Utilize AWS for a reliable server infrastructure.

## Timeline & Milestones
1. **Requirements Analysis & Design (1 week)**
   - Analyze project requirements and design system architecture.
   - Draft function specifications and UI/UX design.

2. **Setup Environment & Project Initialization (1 week)**
   - Set up the development environment and install necessary tools and libraries.
   - Create a Git repository and establish a collaborative codebase.

3. **Frontend Development (3 weeks)**
   - Implement the web client and develop the user interface.
   - Design and implement frontend using HTML, CSS, and JavaScript.

4. **Backend Development (4-8 weeks)**
   - Implement backend server functionalities including user authentication, book management, and chat processing.
   - Develop the server using Spring Framework or Django.

5. **Database Setup & Integration (2 weeks)**
   - Design and set up the database.
   - Integrate the backend server with the database to perform CRUD operations.

6. **WebSocket Server Implementation (3 weeks)**
   - Develop the WebSocket server to enable real-time chat functionality.
   - Use Node.js and Socket.io to build the WebSocket server.

7. **Testing & Debugging (1-3 weeks)**
   - Test the developed system and fix bugs.
   - Collect user feedback to resolve issues and improve functionalities.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/EuijinJeong/TeamSphere.git
    ```
2. Navigate to the project directory:
    ```bash
    cd teamsphere
    ```
3. Install backend dependencies:
    ```bash
    cd backend
    ./mvnw install
    ```
4. Install frontend dependencies:
    ```bash
    cd frontend
    npm install
    ```
5. Start the development server:
    ```bash
    npm start
    ```

## Usage
1. Register as a new user or log in with existing credentials.
2. List a textbook for sale by providing necessary details.
3. Initiate or participate in a chat related to a book listing.
4. Complete transactions with the buyer or seller.

## Contributing
1. Fork the repository.
2. Create a new feature branch:
    ```bash
    git checkout -b feature/your-feature
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature
    ```
5. Open a pull request.


