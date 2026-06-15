# MongoDB Practice Queries

## Overview

This repository contains a collection of MongoDB practice queries designed for beginners to learn and understand fundamental database operations. The examples focus on querying student records using MongoDB's `find()` and `findOne()` methods.

## Topics Covered

- Retrieving all documents
- Filtering documents with conditions
- Querying specific fields
- Using projections
- Finding single documents
- Excluding `_id` fields
- Working with course, city, and age-based filters

## Sample Queries

```javascript
// Find all students
db.students.find()

// Find students from Chennai
db.students.find({ city: "Chennai" })

// Display only student names
db.students.find({}, { name: 1, _id: 0 })
```

## Learning Objectives

- Understand MongoDB query syntax
- Practice document filtering
- Learn field projections
- Build a strong foundation in NoSQL databases
- Prepare for MERN Stack development

## Technologies Used

- MongoDB
- MongoDB Shell (mongosh)

## Repository Structure

```
mongoDB-queries.docx
README.md
```

## Connect with Me 🤝 :
- LinkedIn : [HARSHAA SG](https://www.linkedin.com/in/harshaasg)  
- Gmail : harshaavardhan8@gmail.com

⭐ Feel free to fork this project and improve it!

---

## License

This project is intended for educational and learning purposes.
