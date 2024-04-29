# Task-28
Django Rest Framework უფრო ვრცლად


POST /api/register
{
  "username": "elene123",
  "password": "password123"
}

POST /api/login
{
  "username": "elene123",
  "password": "password123"
}

POST /api/posts
{
  "title": "My First Post",
  "content": "This is the content of my first post.",
  "author": "elene123",
  "date": "2024-04-29"
}


DELETE /api/posts/{post_id}

GET /api/posts/{post_id}

PUT /api/posts/{post_id}
{
  "title": "Updated Title",
  "content": "Updated content goes here."
}





