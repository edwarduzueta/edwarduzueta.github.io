---
layout: project
type: project
image: img/Hawaii_Warriors_logo.svg.png
title: "Manoa Lost & Found"
date: 2025-12-17
published: true
labels:
  - Web Application
  - UH Manoa
  - Full Stack
  - Team Project
summary: "A centralized web application for the UH Mānoa community to report, track, and recover lost items using authenticated campus access and verified recovery workflows."
---

<div class="text-center p-4">
  <img width="200px" src="../img/Hawaii_Warriors_logo.svg.png" class="img-thumbnail" alt="Hawaii Warriors Logo">
</div>

## overview

**Manoa Lost & Found** is a web application designed to streamline the process of reporting and recovering lost items within the **University of Hawaiʻi at Mānoa** community. The platform provides a single, centralized hub where authenticated UH users can post lost or found items, receive match notifications, and recover items through official campus offices.

<div class="text-center p-4">
  <img src="../img/landing.png" class="img-thumbnail" alt="Manoa Lost & Found Landing Page">
</div>

## authentication

Access to the platform is restricted to UH Mānoa students and staff using an email ending in **@hawaii.edu**. This ensures that all users are verified members of the campus community and helps maintain security and trust within the system.

<div class="text-center p-4">
  <img src="../img/user-signin.png" class="img-thumbnail" alt="UH Sign-In Page">
</div>

## item feed & browsing

Users can browse all reported lost and found items through a unified feed. The feed supports filtering by category, date, location, and keywords, allowing users to quickly narrow results and locate relevant posts.

<div class="text-center p-4">
  <img src="../img/item-feed.png" class="img-thumbnail" alt="Lost and Found Item Feed">
</div>

Each listing displays a photo, brief description, status, and location. Users can click into individual posts to view full details.

## reporting items

### report lost item

Users can submit a **Lost Item** report by providing a description, category, last-seen location and time, and an optional photo. Once submitted, the item appears in the Lost Items feed and the user’s dashboard.

<div class="text-center p-4">
  <img src="../img/report-lost.png" class="img-thumbnail" alt="Report Lost Item Form">
</div>

### report found item

When a user finds an item, they can submit a **Found Item** report including where and when the item was found and where it was turned in. This ensures items are routed through official UH offices rather than private handoffs.

<div class="text-center p-4">
  <img src="../img/report-found.png" class="img-thumbnail" alt="Report Found Item Form">
</div>

## recovery workflow

Once a found item is turned in, administrators verify the item at designated drop-off locations such as the Campus Center or Library. Item status is updated in the system, and the owner is notified when it is ready for pickup.

All recoveries are handled through official UH offices to maintain safety and accountability.

## development & deployment

The application was built using modern web technologies and deployed for public access.

- **framework:** Next.js (App Router)  
- **database:** PostgreSQL (Vercel / Neon)  
- **authentication:** NextAuth  
- **deployment:** Vercel  

- **live site:** [https://manoa-lost-and-found.vercel.app](https://manoa-lost-and-found.vercel.app)  
- **repository:** [https://github.com/manoa-lost-found/manoa-lost-and-found](https://github.com/manoa-lost-found/manoa-lost-and-found)

## team & collaboration

This project was developed collaboratively by UH Mānoa students using a GitHub-based workflow. Team members contributed across frontend development, backend logic, UI/UX design, data modeling, and testing.

## takeaways

- designed a real solution for a real campus problem  
- applied full-stack development practices  
- implemented authentication, databases, and deployment pipelines  
- strengthened teamwork and collaborative development skills  

Manoa Lost & Found demonstrates how student-led development can create practical, scalable solutions for campus communities.
