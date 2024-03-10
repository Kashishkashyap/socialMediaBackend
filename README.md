# Social Media Site

## Description
I've made the backend for this website.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Middleware](#middleware)
- [Models](#models)

## Installation
1. Clone the repository: `https://github.com/Kashishkashyap/socialMediaBackend.git`
2. Install dependencies: npm install

## Usage
1. Start the server: npm start
2. .env: PORT and MONGO_URI

## Routes
List of routes and their descriptions go here.
- `POST v1/api/users/auth/signup` Description: Register a new user
- `POST v1/api/users/auth/signin` Description: Login user
- `GET /v1/api/users/:id` Description: Get user profile by ID
- `PUT /v1/api/users/:id` Description: Update user profile by ID
- `DELETE /v1/api/users/:id` Description: Delete user profile by ID
- `POST /v1/api/posts/` Description: Create a new post
- `GET /v1/api/posts/:id` Description: Get post by ID
- `PUT /v1/api/posts/:id` Description: Update post by ID
- `DELETE /v1/api/posts/:id` Description: Delete post by ID
- - `POST /v1/api/follow/:id` Description: Follow a user by ID
- `DELETE /v1/api/follow/:id` Description: Unfollow a user by ID
- `GET /v1/api/follow/following` Description: Get list of users following the authenticated user
- `GET /v1/api/follow/followers` Description: Get list of users the authenticated user is following
- `GET /v1/api/feed` Description: Get posts from users that the authenticated user follows


## Middleware
List of middleware and their descriptions go here.
- `auth.js`: Description: To check if the user is authorized to do the action or not.

## Models
List of models and their descriptions go here.
- `User schema`
- `Post schema`
- `Follow schema`
