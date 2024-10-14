Django Chat Platform



The Django Chat Platform is a web application designed for seamless communication, allowing users to engage in real-time chat with friends, manage their profiles, send and accept friend requests, and search for other members. This project features an intuitive interface and uses API calls combined with polling to enable live chat updates.


Main Features
User Authentication: Access to the platform requires users to log in. New users can create an account to get started.

Profile Management: Each user has a dedicated profile page with personal information. Users can update their profile details.

Simple Navigation: The interface includes easy-to-use buttons for "Edit Profile," "Logout," and "Search" to find other users on the platform.

Friendship Management: Users can manage two lists: "Friends" and "Requests." Clicking a friend's name allows access to their profile or starts a chat.

Chat Functionality: Initiate chats by selecting a friend’s name. Real-time chat updates are achieved using API calls and polling.

Friend Requests: Send friend requests by visiting a user's profile. Incoming requests can be accepted or declined, with accepted requests adding users to each other's friend lists.

Friend Options: Options available for friends include "Remove Friend" and "Chat."




User Workflow
The user logs in or registers for a new account.
On the main dashboard, the user can:
Edit their profile details.
Log out.
Search for other users.
View the list of friends and pending friend requests.
Within the friends and request lists:
Clicking a friend's name opens a chat window.
Clicking a pending request takes the user to the requester's profile.
Pending requests can be approved or rejected.
On a friend's profile:
Users have options to remove the friend or start chatting.
Tech Stack
Django (Python web framework)
Frontend: HTML, CSS, JavaScript
Backend: API integration and polling for real-time chat
Database: For storing user data and chat records (e.g., PostgreSQL)
Project Objectives
Deliver a responsive chat experience.
Ensure secure user authentication.
Design a user-friendly interface.
Achieve real-time chat functionality with API-based updates.
Implement a solid friend management system with requests.
Potential Future Improvements
Add notifications for new messages and friend requests.
Enable file and media sharing (e.g., images, documents).
Enhance profile customization with profile pictures and more details.
Support group chats and chat rooms.




Setup Guide
Follow these steps to get the Django Chat Platform running locally:

1.) Clone the project repository:

```git clone https://github.com/arpit910```

2.) Set up a virtual environment and install dependencies:

```
cd django-chat-app
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3.) Initialize the database:
```python manage.py migrate
```

4.)Launch the development server:
```python manage.py runserver```




Github: https://github.com/arpit910