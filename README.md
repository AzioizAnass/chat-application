# WebSocket Chat Application with Spring Boot and STOMP

This project demonstrates a simple real-time chat application using **Spring Boot**, **WebSocket**, and **STOMP** for bidirectional communication. The application allows users to send and receive messages in real-time using WebSocket connections.

## Technologies Used

- **Spring Boot** - Framework for building Java-based web applications.
- **WebSocket** - Protocol for two-way communication between the client and the server.
- **STOMP** (Simple Text Oriented Messaging Protocol) - Message protocol used for WebSocket communication.
- **SockJS** - Provides fallback support when WebSocket is not available.
- **Java 17** - Java runtime used for the backend.
- **HTML/CSS/JavaScript** - Frontend technologies for building the chat interface.

## Features

- Real-time messaging between clients.
- User joins and leaves notifications.
- Simple chat interface.
- Unique avatars generated based on the first letter of the user's name.

## Installation

### Prerequisites

1. **Java 17** or higher: Ensure you have Java 17 or a later version installed.
2. **Maven**: This project uses Maven to manage dependencies and build the project.
   
### Backend Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/websocket-chat-app.git
   cd websocket-chat-app

2. Install the required dependencies using Maven:
    mvn clean install

3. Run the Spring Boot application:
    mvn spring-boot:run
   
5. The backend will run on http://localhost:8080. This will serve both the chat functionality and the WebSocket endpoint.
