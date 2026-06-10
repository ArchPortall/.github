# ArchPortal

ArchPortal is a Steam-inspired web gaming platform developed as part of our third and final year integration project at KdG University.

Built over the course of 8 weeks by a team of four students, the platform was designed to provide a complete multiplayer gaming ecosystem with social features, game integrations, authentication, analytics, and a modern web experience.

## Team
- Pieter Neyt
- Axel Peeters
- Cian Van Acker
- Hugo Dor

---

# Architecture

ArchPortal was built using a modular monolith architecture with Spring Modulith, allowing us to separate the application into multiple bounded contexts while maintaining a single deployable system.

### Backend
- Java
- Spring Boot
- Spring Modulith

### Frontend
- React
- TypeScript

### Infrastructure
- Docker
- CI/CD Pipelines
- Keycloak Authentication
- SQL Databases

---

# Features

## Gaming Platform
- Fully functional Steam-inspired platform
- Integrated game management
- Game studio management
- Public user profiles
- Integrated payment and shop system

---

## Multiplayer Games

Two fully custom-built multiplayer games:
- Tic Tac Toe
- Checkers

Features included:
- Real-time multiplayer gameplay
- Lobbies
- Party system
- In-game chat support

---

## External Game Integration
- Anti-corruption layer for integrating external games
- Decoupled communication between platform and games
- Expandable integration architecture

---

# User & Social Features

## Friends System
- Send friend requests
- Accept friend requests
- Remove friends

## Chat System
- Private messaging
- Group chats
- Real-time messaging

## Parties
- Invite friends to parties
- Accept party invitations
- Party leaders can remove members
- Launch games directly from parties

## Notifications
- In-platform notifications
- Extensible notification architecture
- Planned email notifications

---

# Achievement System
- Games can define achievements
- Games can notify the platform when a player unlocks achievements
- Users can view unlocked achievements on their profiles

---

# Game Updates
- Game studios can publish updates
- Users can view game update posts

---

# Point Shop System
- Earn points through purchases
- Spend points on platform-related rewards
- Unlock platform perks and benefits

---

# Analytics
- Track game winners
- Track total playtime
- Track playtime per game
- Track last played games
- Track unlocked achievements

---

# Security
- Authentication and authorization handled using Keycloak
- Secure platform-wide identity management
- Protected APIs and secured communication

---

# Infrastructure & Deployment

Every component of the platform was containerized using Docker and automatically built through CI/CD pipelines.

The complete platform was deployed and hosted during development and testing on Cian's laptop 😄

---

# UI & Experience
- Modern dark-themed interface
- Animated starry background
- Responsive web experience

---

# 🚀 Project Goal

The goal of ArchPortal was to simulate the development of a production-scale software platform while applying software architecture principles, domain-driven design concepts, full-stack development practices, DevOps workflows, and collaborative agile development.

## 🎥 Demo Video

[Watch the demo on YouTube](https://youtu.be/vIcJKvguFF8)
