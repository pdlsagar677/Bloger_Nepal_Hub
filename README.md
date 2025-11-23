Next.js Blog App

A modern and feature-rich Next.js Blog Application that allows users to create, edit, and delete posts with a smooth UI and fast performance. The app includes AI-powered blog generation, user interactions (likes & comments), admin moderation, and full post/user management. Built using MongoDB, Cloudinary, Zustand, and Next.js App Router, this platform is clean, scalable, and production-ready.

🚀 Features
👤 User Features

Create blog posts with images

Edit and delete posts

Like & unlike posts

Comment on posts

Automatic deletion of all posts when user account is removed

View posts from others

Mobile-friendly and clean UI

🤖 AI-Generated Blog System

The app includes a built-in AI blog generator where users can:

Enter a topic or keywords

Automatically generate a full blog post using AI

Edit and customize the generated content

Save it as a regular post

Includes auto-title creation and paragraph structuring

This helps users create content faster and improves the overall writing experience.

🛠 Admin Features

Manage all user accounts

Delete, block, or review users

Full post moderation tools

Remove inappropriate content

Manage comments and engagement

Auto-delete all posts when a user is deleted

🧰 Tech Stack
Frontend

Next.js 14 (App Router)

React

Zustand (global state management)

Tailwind CSS

Backend

MongoDB (Mongoose)

Next.js API Routes

JWT authentication

Media

Cloudinary for fast and secure image storage

AI

Uses an AI API (OpenAI )

Generates content, titles, content

📦 Core Functionalities
✨ Post Management

Create, edit, delete posts

Upload images directly to Cloudinary

Admin can manage all posts

Automatic cascade deletion when a user is removed

❤️ Likes & 💬 Comments

Like system with toggle

Add and remove comments

Admin moderation included

🤖 AI Blog Tools

AI generated blog writer

Smart title generator

Auto-format long paragraphs

Optional tone/style adjustments

🔧 State Management — Zustand

Used for:

Auth handling

Post data

Admin dashboard

UI state (editor, modals, etc.)

Lightweight, reactive, and efficient for large Next.js apps.

☁️ Cloudinary Image Upload

Secure uploads

Automatic optimization

Fast CDN delivery

Supports multiple formats