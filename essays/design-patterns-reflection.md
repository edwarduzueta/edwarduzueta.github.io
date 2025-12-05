---
layout: essay
type: essay
title: "Design Patterns: The Invisible Training That Makes Us Better Developers"
date: 2025-11-15
published: true
labels:
  - Design Patterns
  - Software Engineering
  - ICS 314
---

Design patterns are one of those things you don’t really notice until you start seeing them everywhere. They’re not lines of code you copy and paste. They’re not strict rules drilled into you like syntax. They’re the invisible habits and structures that make code cleaner, systems easier to maintain, and teams work together without stepping on each other’s toes.

## First Impressions

When design patterns were first introduced in class, I honestly thought they were just another “theory” topic. Something you memorize for an exam and forget the moment the semester ends. But the more we built, the more I realized they weren’t abstract at all. They were already around me. In the same way that good military training hides inside your muscle memory, good software architecture hides inside patterns you don’t even notice yourself using.

I didn’t fully understand patterns the first time I heard about them. But I knew the feeling of messy code, of components doing too much, of logic leaking where it shouldn’t. Patterns weren’t just solutions— they were ways to avoid that chaos in the first place.

## Patterns in the Project

In our final project, design patterns showed up naturally, long before we said the words “factory,” “singleton,” or “MVC.” Instead, we found ourselves organizing code in ways that felt right, and only later did I realize they matched the classic patterns.

### Model-View-Controller

The first major pattern we used was **Model-View-Controller**. Even without formally naming it, we separated the app into three parts. The UI handled display, the data layer handled storage, and a middle layer coordinated everything. It made the project feel more structured. Instead of each part stepping on the others, the responsibilities were clear. It had the same feeling as working with a trained squad—everyone has their role, and things run smoother when no one tries to do everything at once.

### Singleton

We also ended up using a **Singleton** pattern without even calling it that. We realized early on we needed a single, consistent source of truth for user session data. We didn’t want ten components guessing what the “real” state was. The Singleton kept everything aligned. It was simple, but it kept the project stable in the same way having one chain of command prevents confusion.

### Factory

A **Factory** pattern appeared anytime we needed to create objects cleanly without repeating the same construction code everywhere. Instead of scattering setup steps across the app, we centralized them. It made the code easier to update, and we could change how things were created without breaking everything else.

### Observer  

Finally, the **Observer** pattern appeared when we needed different parts of the UI to react automatically whenever certain data changed. Instead of manually updating every component, things updated on their own. It reminded me of good communication: one message goes out, and everyone who needs to act, acts.

## Final Thoughts

By the end of the project, I realized design patterns aren’t just academic terms. They are tools that help systems stay flexible, stable, and understandable. They saved us time, prevented bugs, and made our group work less chaotic. I’ve learned that patterns matter not because they sound smart, but because they make you a better developer. Just like training in the Army, the point isn’t to memorize the terminology. The point is to absorb the habits so deeply that they become instinct.

---

Note: I used ChatGPT to help refine grammar and structure for this essay, but the ideas and final content reflect my own experiences and perspective.
