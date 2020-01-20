# BlogGenerator

Blog for bakers

Funcitonalities:
 - create/delete posts
   - different media types
 - comment posts & respond to comments
 - post rating
 - timeline of user
 - user profile
 - create/delete user
 
 DB structure:
  - Post
    - 1 creator
    - 0..n comments
  - Comments
    - 1 creator
    - 0..n comments
  - User
    - 1 creator
    - 0..n Posts
    - 0..n Comments
    - 1 Profile
  - Rating
