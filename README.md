# SAI U Events - Campus Event Management Platform

A modern, fully-functional web application for discovering, browsing, and registering for campus events at SAI University.

## 📋 Overview

SAI U Events is a comprehensive event management platform designed for university students. The app allows users to:
- **Create an account** with their university details
- **Browse upcoming campus events** by category and search terms
- **View detailed event information** including venue, time, capacity, and description
- **Register for events** and manage their event calendar
- **Track attendance** with a personal dashboard showing registered, upcoming, and completed events

## 🎯 Key Features

### Authentication
- **User Registration**: Create accounts with email, department, academic year, and registration number
- **User Login**: Secure login with email and password verification
- **Password Protection**: Show/hide password toggles for better UX

### Event Discovery
- **Browse Events**: View all 12 upcoming campus events
- **Category Filtering**: Filter by Tech, Cultural, Sports, Academic, or Social events
- **Search Functionality**: Real-time search across event titles, descriptions, venues, and tags
- **Event Cards**: View key information at a glance with visual progress bars showing event capacity

### Event Details
- **Comprehensive Information**: Full event descriptions, organizer, duration, and difficulty level
- **Attendance Tracking**: See how many spots are available and attendance percentage
- **Event Progress**: Visual capacity indicator showing how full the event is
- **Quick Registration**: One-click registration directly from the event detail page

### Personal Dashboard
- **Statistics Overview**: Track registered, upcoming, completed, and cancelled events
- **My Events List**: View all registered events with quick unregister option
- **Event Management**: Click on registered events to view details or unregister

### Design & UX
- **White & Blue Color Scheme**: Clean, professional aesthetic with gradient accents
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Elegant page transitions and hover effects
- **Intuitive Navigation**: Clear navigation between Browse, Dashboard, and Event Details

## 🎨 Color Palette

- **Primary**: `#3b82f6` - Blue (buttons, links, highlights)
- **Background**: `#ffffff` - White (main background)
- **Surface**: `#f8fafc` - Light blue-gray (input fields, cards)
- **Text**: `#1e293b` - Dark blue-gray (headings, body text)
- **Muted**: `#64748b` - Medium gray (secondary text, descriptions)
- **Accents**: Category-specific colors (Tech: Blue, Cultural: Orange, Sports: Green, etc.)

## 📱 Responsive Design

The app is fully responsive and works on:
- **Desktop** (1920px+)
- **Tablet** (768px - 1024px)
- **Mobile** (320px - 767px)

All layouts automatically adjust for optimal viewing on any device.

## 🗂️ Sample Events

The app includes 12 pre-loaded sample events across 5 categories:

### Tech (3 events)
- AI & Machine Learning Workshop
- Hackathon 2026
- Robotics Demo Day

### Cultural (3 events)
- Spring Cultural Festival
- Poetry Open Mic Night
- International Food Festival

### Sports (2 events)
- Intramural Basketball Finals
- Yoga in the Park

### Academic (2 events)
- Guest Lecture: Climate Science
- Career Fair: Tech Edition

### Social (2 events)
- Welcome Week Mixer
- Movie Night: Outdoor Cinema

## 🔐 Data Storage

The app uses **browser localStorage** to persist:
- Registered user accounts (email, name, department, year, registration number, password)
- User registration history (survives page refresh)

**Note**: This is a frontend-only application. User data is stored locally in the browser and is not sent to any server.

## 🚀 Getting Started

### Registration
1. Click "Create Account" on the welcome page
2. Fill in your details (name, email, department, academic year, registration number)
3. Create a password (minimum 6 characters)
4. Accept the Terms of Service
5. Click "Create Account"

### Login
1. Click "Sign In" on the welcome page
2. Enter your registered email and password
3. Click "Sign In"

### Browse Events
1. Click "Browse Events" from your dashboard
2. Use category filters to narrow down events
3. Use the search bar to find specific events
4. Click "View Details" on any event card

### Register for Events
1. From the event detail page, click "Register for Event"
2. The event will be added to your dashboard
3. View your registered events on the Dashboard tab

### Manage Registrations
1. Go to your Dashboard to see all registered events
2. Click on any event to view full details
3. Click the "Unregister" button to remove yourself from an event

## 🎨 Customization

The app includes an editable edit panel allowing you to customize:
- Login page title and subtitle
- Hero section title and subtitle
- Footer text

These customizations are configured through the Canva Code editor.

## 📊 Event Capacity System

Each event shows:
- **Current Attendees**: Number of people registered
- **Max Capacity**: Total spots available
- **Availability**: Number of spots remaining
- **Fill Percentage**: Visual progress bar showing how full the event is
- **Status Indicator**: "🔥 Spots filling up!" alert when 20 or fewer spots remain

## 🎯 User Flow

Welcome Screen
↓
Choose: Sign In or Create Account
↓
[Login/Register]
↓
Dashboard (Your Events Overview)
↓
Browse Events ←→ Event Details ←→ Register/Unregister
↓
Back to Dashboard


## ⚡ Technical Details

- **Framework**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Tailwind CSS with custom gradients and animations
- **Fonts**: Space Grotesk (headings), Inter (body text)
- **Storage**: Browser localStorage
- **No External Dependencies**: All functionality is self-contained

## 🔒 Privacy & Security

- Passwords are stored in browser localStorage only
- No data is sent to external servers
- User data is private to your browser
- Clear your browser data to reset the app

## 📝 Notes

- Sample events are pre-loaded and cannot be edited
- User data persists as long as the browser cache is not cleared
- Multiple user accounts can be created and accessed by logging in/out
- All event registrations are tied to the logged-in user account

## 🤝 Support

For issues or feature requests, please contact the SAI U Events development team.

---

**Version**: 1.0.0  
**Last Updated**: Spring 2026  
© 2026 SAI U. Built for students, by students.

This README provides a comprehensive guide to the app with sections for overview, features, colors, getting started, and technical details! 📚
