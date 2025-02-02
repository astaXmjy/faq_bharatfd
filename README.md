# Multilingual FAQ System

This project is a multilingual FAQ system built using Django with Redis for caching and Google Translate for automatic translations. The system supports multiple Indian languages and provides a rich text editor for formatting FAQ answers.

## Features

- **Multilingual Support**: FAQs can be translated into multiple Indian languages.
- **Rich Text Editor**: Integrated using `django-ckeditor`.
- **Caching**: Implemented using Redis for improved performance.
- **API**: RESTful API for managing FAQs with language selection support.
- **Docker Support**: Docker and Docker Compose for containerized deployment.
- **Unit Tests**: Comprehensive tests for models and API responses.

## Installation

### Prerequisites

- Docker
- Docker Compose

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/multilingual-faq-system.git
   cd multilingual-faq-system

2.docker-compose build
docker-compose up

3.docker-compose exec web python manage.py migrate

4.docker-compose exec web python manage.py createsuperuser


5. Access the application:

 *The Django application will be running at http://localhost:8000/api/faqs

 *The Django admin interface will be available at http://localhost:8000/admin