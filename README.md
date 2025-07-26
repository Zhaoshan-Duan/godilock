# Godilock

A real-time chat and collaboration platform built with **Go** and **HTMX** for the Boot.dev 2025 Hackathon. A testament that modern web app don't need heavy JavaScript frameworks to deliver smooth, responsive experiences.

## Feature Roadmap

### MUST-HAVES

- [] Real-time messaging via Server-Sent Events + HTMX
- [] Mutliple chat rooms with automatic room creation
- [] Message history (last 100 messages per room)
- [] User identification
- [] Responsive UI that works on desktop/mobile
- [] Room discovery: homepage shows active rooms

### Should-haves

- [] File Upload and sharing
  - Drag & drop file uploads
  - Image preview in chat
  - File download links
- [] User Presence System
  - "Who's online" indicator per room
  - Join/leave notifications
  - Active user count
- [] Typing indicators
  - Show when someone is typing
  - Real-time update via SSE
  - Auto-clear after inactivity
- [] Room Management
  - Create custom rooms with descriptions
  - Room settings (public/private)
  - Delete empty rooms automatically

## Technical Stacks

Frontend: HTMX
Go Server: Server-Sent Events
In-memory Storage: Concurrent Safe Maps


## Quick Start
```bash
# Clone and run
git clone https://github.com/yourusername/godilock
cd godilock
go run main.go

# Open browser
open http://localhost:8080
```
