***###chatgpt_prompt_rkwebr2**
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

4. **File Structure:** Adhere to the following file structure:

    ```
    rkwebr/
    ├── rkwebr/
    │   ├── __init__.py
    │   ├── core/
    │   │   ├── __init__.py
    │   │   ├── router.py
    │   │   ├── views.py
    │   │   ├── models.py
    │   │   ├── orm.py
    │   │   ├── middleware.py
    │   │   ├── utils.py
    │   │   └── security.py
    │   ├── templates/
    │   │   └── base.html
    │   ├── static/
    │   │   ├── css/
    │   │   │   └── styles.css
    │   │   ├── js/
    │   │   │   └── script.js
    │   │   └── images/
    │   └── management/
    │       ├── __init__.py
    │       └── commands.py
    ├── tests/
    │   ├── __init__.py
    │   ├── test_router.py
    │   ├── test_views.py
    │   ├── test_models.py
    │   ├── test_middleware.py
    │   └── test_security.py
    ├── example_project/
    │   ├── __init__.py
    │   ├── settings.py
    │   ├── urls.py
    │   ├── views.py
    │   ├── models.py
    │   ├── templates/
    │   │   └── example.html
    │   ├── static/
    │   │   ├── css/
    │   │   │   └── example_styles.css
    │   │   ├── js/
    │   │   │   └── example_script.js
    │   │   └── images/
    └── manage.py
    ```

5. **Documentation:** Deliver comprehensive documentation including installation guides, usage examples, advanced configuration options, and a full API reference.

6. **Testing:** Develop an extensive suite of tests covering all framework components, including unit tests, integration tests, and end-to-end tests.

7. **Memory and Precision:** ChatGPT 4.0 must retain and faithfully apply every instruction in this prompt. Ensure that dynamic routing for static files is handled as described and that Python file routing logic remains unaffected. Any errors or deviations will render the framework broken or wasted. Ensure that the implementation is exact and flawless.

8. **Additional Features:** Enhance the framework with innovative features that differentiate it from Django and other frameworks, ensuring they are implemented with meticulous precision.

---
