## 📓 Description
  - Very basic REST API that preforms the following HTTP requests
      - get
      - put
      - delete
      - post
    
## 🏃 How to run
  - terminal: npm i 
  - terminal: nodemon index.js
  - GET : localhost:3000/api/courses
    - displays all the courses
  - GET : localhost:3000/api/courses/:id
    - displays the course with the id you provide  
  - POST : localhost:3000/api/courses
      - allows you to create a new item in the courses object
      - in the JSON { "name": "name for item" }
      - the id will be the # elements in the object + 1
  - PUT : localhost:3000/api/courses/:id
      - allows you to make changes to the item with the id you provide
      - in the JSON: { "name": "new name" }
  - DELETE : localhost:3000/api/courses/:id
       - deletes the item with the id you provide
