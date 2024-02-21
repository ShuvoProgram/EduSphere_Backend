<div align="center">
<img src='/github/logo-modified.png'/>
</div>

<h1 align="center">EduSphere: 📚 Empowering Education</h1>

<p>EduSphere 🎓 is a transformative project dedicated to revolutionizing education through innovative courses and cutting-edge learning experiences. With a commitment to fostering knowledge, EduSphere offers a diverse range of courses designed to empower learners in various domains. From interactive virtual classrooms to hands-on practical sessions, the project prioritizes engaging and personalized education. EduSphere's mission is to create a dynamic learning sphere where students thrive, gaining not just knowledge but also essential skills for the future. Join EduSphere and embark on a journey of educational excellence, where every course opens doors to endless possibilities. 🌐📚</p>

# EduSphere API Endpoints

## User Operations

`/users`

- POST /registration: Register a new user.
- POST /social-auth: Authenticate user via social media.
- POST /activate-user: Activate user account.
- POST /login: Log in user.
- GET /logout: Log out user.
- GET /refresh: Refresh access token.
- GET /me: Get user information.
- PATCH /update-userinfo: Update user information.
- PATCH /update-user-password: Update user password.
- PUT /update-avatar: Update user avatar.
- GET /get-all-users: Get all users (admin only).
- PATCH /update-user-role/:email: Update user role (admin only).
- DELETE /delete-user/:userId: Delete user (admin only).