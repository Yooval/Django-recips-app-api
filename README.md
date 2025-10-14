# CookWise - Recipe Sharing Platform

## 🚀 [Live Demo](http://ec2-3-83-146-24.compute-1.amazonaws.com/api/docs/)

An API platform for recipe management, deployed on AWS with a CI/CD pipeline. Built with **Python, Django, and PostgreSQL**. Implements Test-Driven Development (TDD) with 75% test coverage using Pytest.

---

## 📖 Overview

CookWise allows users to create and manage their own recipes. Users can register, log in, upload images, and build a personalized collection of recipes. A secure and organized platform for storing and managing your culinary creations.

---

## ✨ Key Features

- **User Authentication**: Secure registration and token-based login
- **Recipe Management**: Create, update, delete, and organize recipes
- **Image Uploads**: Add photos to your recipes
- **RESTful API**: Built with Django REST Framework
- **Test-Driven Development**: 75% test coverage with Pytest
- **Unit & Integration Tests**: Comprehensive testing for reliability
- **Docker Containerization**: Consistent development and deployment environment
- **AWS Deployment**: Hosted on AWS with CI/CD pipeline
- **API Documentation**: Interactive API docs available

---

## 🛠️ Tech Stack

**Backend**: Python, Django, Django REST Framework  
**Database**: PostgreSQL  
**Testing**: Pytest, Unit Tests, Integration Tests  
**DevOps**: Docker, AWS (EC2), CI/CD Pipeline  
**Tools**: Flake8 (code linting)

---

## 🚀 Installation

Want to run it locally? Here's how:

**1. Run with Docker**
```bash
docker-compose run --rm app sh -c "python manage.py test"
docker-compose up
```

**2. For deployment**
```bash
docker-compose -f docker-compose-deploy.yml up
```

That's it! The app will be running locally.

**Note**: Requires Docker, Python, and PostgreSQL. AWS credentials needed for deployment.

---

⭐ **If you'd like to see the code, feel free to reach out!**
