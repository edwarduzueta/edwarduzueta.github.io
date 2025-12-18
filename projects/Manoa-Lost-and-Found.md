---
layout: project
type: project
image: img/Hawaii_Warriors_logo.svg.png
title: "Manoa Lost & Found"
date: 2025
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

**Manoa Lost & Found** is a web application designed to streamline the process of reporting and recovering lost items within the **University of Hawaiʻi at Mānoa** community. Each semester, students and staff lose personal items such as IDs, water bottles, textbooks, and electronics, often with no clear or centralized way to recover them.

This project addresses that gap by providing a single digital hub where authenticated UH users can post lost or found items, receive match notifications, and recover items through official campus offices.

## problem

The existing lost-and-found process at UH Mānoa is fragmented and inefficient. Students often must:

- email multiple departments  
- call campus offices individually  
- physically visit locations without knowing if their item was recovered  

There is no unified system to track updates, leading to frustration and lost property.

## solution

Manoa Lost & Found centralizes the entire workflow into one secure platform. The application allows users to:

- report lost or found items with photos and descriptions  
- filter listings by category, date, and location  
- receive notifications for potential matches  
- recover items through verified UH offices only  

All exchanges are handled through official campus locations, eliminating unsafe private meetups.

## features

### core functionality

- UH-authenticated access (@hawaii.edu only)  
- lost and found item feeds with advanced filtering  
- create, edit, and delete item posts  
- item detail pages with images and descriptions  

### user roles

**students & staff**
- manage personal lost and found posts  
- view matches and alerts in a personal dashboard  

**finders**
- submit found item reports  
- follow guided instructions for turning items in  

**admins**
- verify items at drop-off locations  
- update item status and moderate posts  
- manage users and site settings  

## development & deployment

The application is built using modern web technologies and deployed for public access.

- **framework:** Next.js (App Router)  
- **database:** PostgreSQL (Vercel / Neon)  
- **authentication:** NextAuth  
- **deployment:** Vercel  

- **live site:** https://manoa-lost-and-found.vercel.app  
- **repository:** https://github.com/manoa-lost-found/manoa-lost-and-found  

## team & collaboration

This project was developed as a **team effort**, with clearly defined roles across frontend, backend, UI/UX, and data modeling. Collaboration followed a GitHub-based workflow using issues, branches, pull requests, and code reviews.

## takeaways

- designed a real solution for a real campus problem  
- applied full-stack development practices  
- gained experience with authentication, databases, and deployment  
- improved teamwork and project coordination skills  

Manoa Lost & Found demonstrates how thoughtful design and modern web technologies can be used to improve everyday experiences within a university community.
