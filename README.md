# Group Chat Application Using Java

![Project Front Page](path_to_your_front_page_image.jpg)

**Course**: CSE-312 (Computer Networking Lab)  
**Institution**: Green University of Bangladesh  
**Semester**: Spring 2024  
**Author**: MD Dulal Hossain (ID: 213902116)  
**Submission Date**: 08-06-2024  
**Instructor**: Rusmita Halim Chaity  

---

## Project Overview

[![Project Video Overview](path_to_thumbnail_image.jpg)](https://www.youtube.com/watch?v=your_video_link "Watch the video overview")

The **Group Chat Application** is a Java-based client-server chat system where multiple users can communicate in real-time. Built using **JavaFX** for the GUI and **socket programming** for network communication, this project supports features like text messaging, image sharing, emoji integration, and multi-client connections. This application demonstrates fundamental networking principles and offers an intuitive, user-friendly platform for group communication.

---

## Table of Contents
1. [Motivation](#motivation)
2. [Problem Definition](#problem-definition)
3. [Design Goals and Objectives](#design-goals-and-objectives)
4. [Applications](#applications)
5. [Project Details](#project-details)
6. [Implementation Workflow](#implementation-workflow)
7. [Tools and Libraries](#tools-and-libraries)
8. [Performance Evaluation](#performance-evaluation)
9. [Conclusion](#conclusion)
10. [Future Work](#future-work)

---

## Motivation

The primary motivation for this project is to gain hands-on experience with **network programming** and **GUI development** in Java. This project provides an opportunity to understand how client-server communication works, and how to handle multiple connections simultaneously. It also incorporates user interface design using JavaFX to ensure real-time, interactive communication.

---

## Problem Definition

The problem addressed by this project is the need for a simple, real-time communication tool that allows users to exchange text messages, images, and emojis over a network. The project aims to implement an intuitive and secure **group chat** system that handles multiple users simultaneously through a client-server architecture.

---

## Design Goals and Objectives

The primary objectives of the project are:
- **Real-time Communication**: Allow users to send text messages, images, and emojis in real-time.
- **Client-Server Architecture**: Implement a server that manages multiple client connections efficiently.
- **User-friendly GUI**: Use JavaFX to create an intuitive interface with features like emoji support and message history.
- **Scalability**: Ensure that the system can handle multiple users connecting at once.

---

## Applications

The **Group Chat Application** can be used in various scenarios:
- **Personal Messaging**: A simple chat system for personal use.
- **Team Collaboration**: Can be used in small teams for project discussions and image sharing.
- **Educational Use**: A basic client-server communication model for learning purposes in computer networking classes.

---

## Project Details

The application comprises both **client** and **server** components:
- **Client**: Users log in with a username and can send text, images, and emojis.
- **Server**: Manages client connections and relays messages between them. The server handles multiple clients concurrently through **multithreading**.

The project showcases fundamental **socket programming**, and the GUI is designed using JavaFX. It allows for message exchange in real-time and features emoji integration and image sharing.

---

## Implementation Workflow

1. **Server Setup**: The server starts and listens for incoming client connections.
2. **Client Login**: Users log in with a username.
3. **Message Exchange**: Clients can send messages, images, and emojis. The server relays messages to all clients except the sender.
4. **Server Management**: The server manages all client connections and handles disconnections.
5. **Real-Time Updates**: Both server and client interfaces display chat history and user messages in real-time.

---

## Tools and Libraries

The project uses several tools and libraries:
- **JavaFX**: For building the GUI.
- **Socket Programming**: For establishing client-server communication.
- **FXML**: To define the layout of the GUI.
- **JFoenix**: A material design library for JavaFX.
- **EmojiPicker Library**: For selecting and sending emojis.
- **Java Standard Library**: For core functionalities like file handling, threading, and network communication.

---

## Performance Evaluation

The application was tested on the following environment:
- **PC Configuration**:
  - RAM: 16GB
  - Storage: 512 GB SSD + 1TB HDD
  - Processor: Intel Core i5 10th Gen

### Results:
1. **Client-Server Communication**: The server handles multiple clients smoothly, facilitating real-time communication.
2. **GUI Performance**: The JavaFX GUI is responsive and user-friendly, supporting text messaging, image sharing, and emojis.
3. **Scalability**: The server can handle multiple concurrent users without performance degradation.

---

## Conclusion

The **Group Chat Application** successfully demonstrates client-server communication using Java sockets and provides a clean, responsive GUI. The project handles real-time messaging, image sharing, and emojis effectively. Future improvements could focus on enhancing security, adding message persistence, and refining the user interface.

---

## Future Work

Potential improvements include:
1. **User Authentication**: Implement password-based login for added security.
2. **Message History**: Store chat history on the server for users to access past conversations.
3. **Encryption**: Implement message encryption to secure communication.
4. **File Sharing**: Add support for file transfer between users.
5. **Cross-Platform Compatibility**: Develop mobile and web versions for wider accessibility.
6. **Scalability**: Enhance the server's ability to handle even larger numbers of clients concurrently.

---

## References

1. [JavaFX Documentation](https://openjfx.io/)
2. [Socket Programming in Java](https://docs.oracle.com/javase/tutorial/networking/sockets/)
3. [Learn Java](https://www.learnjavaonline.org/)
4. [GeeksforGeeks Java Tutorial](https://www.geeksforgeeks.org/java/)
5. [Codecademy Java Course](https://www.codecademy.com/learn/learn-java)
