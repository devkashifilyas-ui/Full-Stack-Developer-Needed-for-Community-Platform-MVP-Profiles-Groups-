# Alliance by NEST --- Community Platform MVP Demo

This repository contains a demo prototype for Alliance, the community
coordination layer of the NEST (National Esports Tournament) ecosystem.

Alliance v1 is intentionally simple. The goal of this MVP is to provide
a clean foundation where esports players and organizers can find each
other and form groups without unnecessary complexity.

------------------------------------------------------------------------

## Product Philosophy

Alliance launches intentionally simple.

Features are added only when: users clearly request them usage proves
the need or friction is clearly observed

The goal is clarity and speed rather than feature density.

------------------------------------------------------------------------

## What Alliance IS (v1)

Alliance provides:

Player profiles\
Group discovery\
Join request workflows\
Organizer approvals

The platform acts as the community layer of the NEST ecosystem.

------------------------------------------------------------------------

## What Alliance is NOT (v1)

The MVP intentionally excludes:

Messaging\
Scheduling\
Tournament brackets\
Stats tracking\
Payments\
Voice chat\
Discord-style communication systems\
Advanced automation

These systems are intentionally deferred until real usage proves they
are needed.

------------------------------------------------------------------------

## Core User Types

### Players

Players want to:

Create a profile\
Find groups\
Join communities\
See who else plays

They do not want complex dashboards or heavy setup.

### Organizers

Organizers want to:

Create groups\
Attract players\
Approve join requests\
Build visible communities

They do not want complicated admin tooling.

------------------------------------------------------------------------

## Core Platform Actions

### Player Actions

Create profile\
Browse groups\
Request to join groups\
View group members\
Leave groups

### Organizer Actions

Create groups\
Define group description and tags\
Review join requests\
Approve or reject players

------------------------------------------------------------------------

## Demo Screens

The prototype includes six primary screens.

Home\
Create Profile\
Browse Groups\
Group Detail\
Organizer Dashboard\
Architecture Overview

Each screen demonstrates a specific user flow of the MVP.

------------------------------------------------------------------------

## Database Structure

Core tables used in the demo:

Users\
PlayerProfiles\
Groups\
GroupMemberships\
JoinRequests\
GroupTags

These tables support profiles, group discovery, and membership
workflows.

------------------------------------------------------------------------

## Anti-Spam Strategy

Community platforms require basic protections.

Suggested mechanisms:

Email verification\
Join request rate limiting\
Organizer approval workflow\
Moderation capability

These prevent spam accounts from abusing the platform.

------------------------------------------------------------------------

## Recommended Technology Stack

Frontend\
Next.js or React

Backend API\
Node.js

Database\
PostgreSQL

Storage\
Cloud object storage for avatars and media

This stack keeps the MVP simple while supporting future scaling.

------------------------------------------------------------------------

## Scaling Path

The architecture supports future features such as:

Unified NEST account system\
Tournament integrations\
Moderation tools\
Events and scheduling\
Community messaging\
Analytics

The relational data model ensures these systems can be added without
rebuilding the core platform.

------------------------------------------------------------------------

## Deployment

The demo can be hosted using:

GitHub Pages\
Netlify\
Vercel

Simply upload the demo files and enable static hosting.

------------------------------------------------------------------------

## Author

Kashif Ilyas\
Full Stack Engineer
