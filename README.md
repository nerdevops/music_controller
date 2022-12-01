#### folowing this course:
    https://www.youtube.com/watch?v=JD-age0BPVo&list=PLzMcBGfZo4-kCLWnGmK0jUBmGLaJxvi4j&index=1


### Todo List of the course:

- [x] Django & React Tutorial #1 - Full Stack Web App With Python & JavaScript
- [X] Django & React Tutorial #2 - Django REST Framework
- [ ] Django & React Tutorial #3 - React Integration Using Webpack & Babel
- [ ] Django & React Tutorial #4 - React Router and Building Components
- [ ] Django & React Tutorial #5 - Handling POST Requests (Django REST)
- [ ] Django & React Tutorial #6 - Material UI Components
- [ ] Django & React Tutorial #7 - Calling API Endpoints From React
- [ ] Django & React Tutorial #8 - Creating The Room Join Page
- [ ] Django & React Tutorial #9 - ComponentDidMount and Django Sessions
- [ ] Django & React Tutorial #10 - Django Sessions and Leaving Rooms
- [ ] Django & React Tutorial #11 - Updating Django Models
- [ ] Django & React Tutorial #12 - React Default Props and Callbacks
- [ ] Django & React Tutorial #13 - Spotify API Tutorial (Authentication & Tokens)
- [ ] Django & React Tutorial #14 - Using the Spotify API
- [ ] Django & React Tutorial #15 - Pausing & Playing Music With Spotify API
- [ ] Django & React Tutorial #16 - Skipping Songs and Handling Votes
- [ ] Django & React Tutorial #17 - Functional Components (useState, useEffect)


### Django & React Tutorial #1 - Full Stack Web App With Python & JavaScript
1. Install python
2. Install npm and nodejs
3. Create a folder & enter
4. pip install django djangoframework
   1. django-admin startproject 'project_name'
   2. cd project_name
      1. django-admin startapp 'app_name'
5. Link the app to the controler on settings.py

## Django & React Tutorial #2 - Django REST Framework
 1. Added Room Class In models & Def to random tokens users
 2. Added RoomView Class
 3. Added Serializers
   Rest example:
``` json
[
    {
        "id": 1,
        "code": "ABCD",
        "host": "Jhon",
        "guest_can_pause": true,
        "votes_to_skip": 1,
        "created_at": "2022-12-01T21:37:18.113972Z"
    }
]
```