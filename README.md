# TripTales Backend

Backend API for **TripTales**, a platform designed to help users organize and manage group trips in a simple and collaborative way.

This backend is built with **Django** and uses **SQLite** as the database for development and testing purposes.

---

## 🚀 Features

- RESTful API architecture
- User and group trip management
- CRUD operations for trips, activities, and participants
- Modular Django structure (models, views, serializers)
- Lightweight SQLite database for development

## API Endpoints

- /api/users/ - User and profile management
- /api/trip-groups/ - Trip group CRUD operations
- /api/diary-posts/ - Posts and feed management
- /api/post-media/ - Media upload and management
- /api/group-invites/ - Invitation system
- /ws/chat/{group_id}/ - WebSocket chat endpoint
