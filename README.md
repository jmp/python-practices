# Python Practices & Resources

This is a collection of books, articles, videos, repos and other resources related good practices in Python, including hexagonal architecture, domain-driven design, etc.. Some of them may not be specific to Python, but all of them should be applicable to Python development.

# Domain-Driven Design

* Evans, E. (2003). *Domain-Driven Design: Tackling Complexity in the Heart of Software* (1st ed.). Addison-Wesley Professional.
* Vernon, V. (2013). *Implementing Domain-Driven Design* (1st ed.). Addison-Wesley Professional.
* [Architecture Patterns with Python](https://www.cosmicpython.com/book/preface.html) - A book about Domain-Driven Design, event-driven microservices and related topics in Python.
* [Django API Domains](https://github.com/phalt/django-api-domains) - An attempt to apply Domain-Driven Design principles to Django apps.

## Criticism

* [Against service layers in Django](https://www.b-list.org/weblog/2020/mar/16/no-service/) - A criticism against using a "service layer" approach with Django.
* [More on service layers in Django](https://www.b-list.org/weblog/2020/mar/23/still-no-service/) - A follow-up to the above blog post.

# Ports & Adapters (Hexagonal Architecture)

* [BasicWolf/hexagonal-architecture-django](https://github.com/BasicWolf/hexagonal-architecture-django) - One way of doing hexagonal architecture with Django
* [Oscar-Garcia/django-hexarch-example](https://github.com/Oscar-Garcia/django-hexarch-example) - Slides and example code for applying hexagonal architecture to Django projects
* [GArmane/python-fastapi-hex-todo](https://github.com/GArmane/python-fastapi-hex-todo) - A todo list application in Python using FastAPI and hexagonal architecture.
* [slimovich/Realworld-fastapi-gino-template](https://github.com/slimovich/Realworld-fastapi-gino-template) - A web app skeleton in Python using FastAPI and hexagonal architecture.

## Criticism

* [rklyne/hexagonal-django](https://github.com/rklyne/hexagonal-django) - An experiment with two approaches to doing ports and adapters with Django. The conclusion is that fighting the [Active Record](https://www.martinfowler.com/eaaCatalog/activeRecord.html) pattern used by Django ORM is not worth it.

# Clean Architecture

* [Implementing the Clean Architecture](https://leanpub.com/implementing-the-clean-architecture) by Sebastian Buczyński
