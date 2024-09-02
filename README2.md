**# rkwebr2**
---

**Prompt:**

**Framework Name:** `rkwebr`

**Owner:** `RK Riad`

**Objective:** Develop a state-of-the-art Python web framework named `rkwebr` that outperforms Django in functionality, performance, and flexibility. The framework must be engineered with absolute precision. Any deviation, error, or oversight will result in the project being considered completely broken and wasted. Ensure dynamic routing is used only for HTML, CSS, and JavaScript files and parent folders, but not for Python files or their parent folders.

### **Core Requirements:**

1. **Error-Free Execution:** ChatGPT 4.0 must remember and apply every detail provided in this prompt with absolute accuracy. Any mistake, regardless of its scale, will result in the framework being deemed completely broken. Precision is imperative.

2. **Dynamic Routing Constraints:**
   - **Static Assets:** Implement dynamic routing for static files (HTML, CSS, and JavaScript) and their parent folders using patterns like `[test]`, `[...test]`, `(test)`, `_test`, etc.
   - **Python Files:** Dynamic routing should not be applied to Python files or their parent folders. Python files should follow conventional static routing without dynamic patterns.
   - **Examples:**
     - `example_project/templates/[test]/index.html` for dynamic HTML routes
     - `example_project/static/css/[...test].css` for dynamic CSS routes
     - `example_project/static/js/(test).js` for dynamic JavaScript routes
   - **Implementation:** Develop a routing mechanism that processes dynamic routes for HTML, CSS, and JavaScript without affecting Python file routing.

3. **Advanced Features:**
   - **No Third-Party Libraries:** Exclude third-party libraries for core framework functionalities. Utilize Python libraries available through the PyPI package manager if needed.
   - **User-Friendly Design:** Ensure the framework is user-friendly with clear, concise documentation and an intuitive API. Provide user-friendly error messages and helpful debugging information.
   - **Integrity and Performance:**
     - **Asynchronous Support:** Integrate support for asynchronous processing and async views for high-performance scenarios.
     - **Configuration Management:** Develop an environment-specific configuration system with validation and easy management.
     - **Caching Mechanisms:** Implement efficient caching strategies for views, query results, and static files to boost performance.
     - **Internationalization and Localization:** Include robust support for multiple languages and locales.
     - **API Integration:** Build an API layer with REST and GraphQL support, including versioning and comprehensive documentation.

4. **File Structure:** Adhere to the following file structures 
```
rkwebr/
├── rkwebr/
│   ├── __init__.py                # Initializes the rkwebr package
│   ├── core/
│   │   ├── __init__.py            # Initializes the core module
│   │   ├── router.py              # Contains routing logic, including handling dynamic routes for static files
│   │   ├── views.py               # Defines view functions and their logic for handling HTTP requests
│   │   ├── models.py              # Defines ORM models and database schema management
│   │   ├── orm.py                 # Handles ORM operations, including queries and relationships
│   │   ├── middleware.py          # Contains middleware components for request/response processing
│   │   ├── utils.py               # Utility functions used across the framework
│   │   └── security.py            # Implements security features like XSS and CSRF protection
│   ├── templates/
│   │   └── base.html              # Base template file, used for rendering HTML with dynamic content
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css        # CSS files for styling static assets; can include dynamic routes
│   │   ├── js/
│   │   │   └── script.js         # JavaScript files for client-side scripting; can include dynamic routes
│   │   └── images/
│   │       └── logo.png          # Static image files
│   └── management/
│       ├── __init__.py            # Initializes the management module
│       └── commands.py            # Defines custom management commands and utilities
├── tests/
│   ├── __init__.py                # Initializes the tests package
│   ├── test_router.py             # Tests for the routing logic, including dynamic route handling
│   ├── test_views.py              # Tests for view functions and their behavior
│   ├── test_models.py             # Tests for ORM models and database operations
│   ├── test_middleware.py         # Tests for middleware components and their functionality
│   └── test_security.py           # Tests for security features and protections
├── example_project/
│   ├── __init__.py                # Initializes the example project package
│   ├── settings.py                # Configuration settings for the example project
│   ├── urls.py                    # URL routing configuration for the example project
│   ├── views.py                   # Defines view functions for the example project
│   ├── models.py                  # Defines ORM models for the example project
│   ├── templates/
│   │   └── example.html           # Template file for the example project, demonstrating HTML rendering
│   ├── static/
│   │   ├── css/
│   │   │   └── example_styles.css # CSS file for the example project; can include dynamic routes
│   │   ├── js/
│   │   │   └── example_script.js  # JavaScript file for the example project; can include dynamic routes
│   │   └── images/
│   │       └── example_image.png  # Static image files for the example project
└── manage.py                      # Command-line utility for administrative tasks, like running the server and migrations
```

### Comments on File Working System:

- **`rkwebr/` Directory:**
  - **`core/` Folder:** Contains core components like routing, views, ORM, middleware, and utilities.
  - **`templates/` Folder:** Stores base HTML templates for rendering views.
  - **`static/` Folder:** Contains static assets like CSS, JavaScript, and images. Supports dynamic routes for these files.
  - **`management/` Folder:** Holds management commands for administrative tasks.

- **`tests/` Directory:** Contains unit and integration tests for various components of the framework.

- **`example_project/` Directory:** Provides an example project demonstrating the use of the `rkwebr` framework, including templates, static files, and configuration.

- **`manage.py` File:** Utility for managing and running the framework, similar to Django's manage.py.


5. **Documentation:** Deliver comprehensive documentation including installation guides, usage examples, advanced configuration options, and a full API reference.

6. **Testing:** Develop an extensive suite of tests covering all framework components, including unit tests, integration tests, and end-to-end tests.

7. **Memory and Precision:** ChatGPT 4.0 must retain and faithfully apply every instruction in this prompt. Ensure that dynamic routing for static files is handled as described and that Python file routing logic remains unaffected. Any errors or deviations will render the framework broken or wasted. Ensure that the implementation is exact and flawless.

8. **Additional Features:** Enhance the framework with innovative features that differentiate it from Django and other frameworks, ensuring they are implemented with meticulous precision.

---
