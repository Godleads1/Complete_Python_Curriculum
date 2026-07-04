# 📘 Complete Python Curriculum

## 🟢 BASIC LEVEL

### 1. Introduction & Setup
- What is Python? History, philosophy, and use cases
- Installing Python (Windows, macOS, Linux)
- Setting up IDEs: VS Code, PyCharm, Jupyter Notebook
- Running Python: Interactive shell, scripts, and notebooks
- Understanding the Python interpreter and bytecode

### 2. Core Syntax & Data Types
- Variables, naming conventions, and dynamic typing
- Basic data types: `int`, `float`, `str`, `bool`
- Type checking with `type()` and `isinstance()`
- Comments, docstrings, and code readability (PEP 8)

### 3. Operators & Expressions
- Arithmetic operators (`+`, `-`, `*`, `/`, `//`, `%`, `**`)
- Comparison operators (`==`, `!=`, `<`, `>`, `<=`, `>=`)
- Logical operators (`and`, `or`, `not`)
- Assignment operators (`=`, `+=`, `-=`, `*=`, `/=`, etc.)
- Operator precedence and associativity

### 4. Control Flow
- Conditional statements: `if`, `elif`, `else`
- Ternary conditional expressions
- `for` loops and iteration patterns
- `while` loops and loop control (`break`, `continue`, `pass`)
- `range()`, `enumerate()`, `zip()`
- List comprehensions (introductory)

### 5. Data Structures (Part 1)
- **Lists**: Creation, indexing, slicing, methods (`append`, `extend`, `insert`, `remove`, `pop`, `sort`, `reverse`)
- **Tuples**: Immutability, packing/unpacking, named tuples
- **Dictionaries**: Key-value pairs, methods (`get`, `keys`, `values`, `items`, `update`, `pop`)
- **Sets**: Uniqueness, set operations (`union`, `intersection`, `difference`, `symmetric_difference`)
- Mutability vs. Immutability

### 6. Functions (Part 1)
- Defining functions with `def`
- Parameters vs. arguments
- Return values and multiple returns
- Default parameters and keyword arguments
- Variable-length arguments: `*args` and `**kwargs`
- Scope and the LEGB rule (Local, Enclosing, Global, Built-in)
- Lambda expressions (introductory)

### 7. String Manipulation
- String formatting: f-strings, `.format()`, `%` formatting
- Common string methods (`split`, `join`, `strip`, `replace`, `find`, `count`, `upper`, `lower`)
- String slicing and indexing
- Regular expressions basics with `re` module

### 8. Input/Output
- `print()` with formatting options
- `input()` for user interaction
- Reading and writing text files (`open`, `read`, `write`, `with` statement)
- Working with CSV files using the `csv` module

### 9. Error Handling (Part 1)
- `try`, `except`, `else`, `finally` blocks
- Common built-in exceptions (`ValueError`, `TypeError`, `KeyError`, `IndexError`, `FileNotFoundError`)
- Raising exceptions with `raise`
- Creating custom exceptions

### 10. Modules & Standard Library (Part 1)
- Importing modules (`import`, `from ... import`, `as`)
- The Python Standard Library overview
- Useful modules: `math`, `random`, `datetime`, `os`, `sys`
- Understanding `__name__ == "__main__"`

---

## 🟡 INTERMEDIATE LEVEL

### 1. Object-Oriented Programming (OOP)
- Classes and objects
- `__init__`, `self`, and instance attributes
- Class attributes and methods (`@classmethod`, `@staticmethod`)
- Inheritance, method overriding, and `super()`
- Multiple inheritance and the MRO (Method Resolution Order)
- Encapsulation: public, protected (`_`), private (`__`) attributes
- Property decorators (`@property`, `@setter`, `@deleter`)
- Magic/dunder methods (`__str__`, `__repr__`, `__eq__`, `__len__`, `__getitem__`, etc.)
- Abstract Base Classes (ABC) with `abc` module
- Dataclasses (`@dataclass`)
- Protocols and structural subtyping (Python 3.8+)

### 2. Advanced Functions & Functional Programming
- First-class and higher-order functions
- Closures and the nonlocal keyword
- Decorators: creating and chaining decorators
- `functools`: `wraps`, `lru_cache`, `partial`, `reduce`
- `map()`, `filter()`, `reduce()` vs. comprehensions
- Generators with `yield` and `yield from`
- Generator expressions
- Iterator protocol (`__iter__`, `__next__`)
- Coroutines basics

### 3. Advanced Data Structures & Collections
- `collections` module: `Counter`, `defaultdict`, `OrderedDict`, `deque`, `namedtuple`, `ChainMap`
- `heapq` for priority queues
- `array` module for homogeneous sequences
- `dataclasses` and `typing.NamedTuple`
- Deep vs. shallow copying with `copy` module
- Memory views and buffers

### 4. File Handling & Data Formats
- Working with JSON (`json` module)
- XML parsing (`xml.etree.ElementTree`)
- YAML basics (`PyYAML`)
- Binary file I/O and `struct` module
- `pickle` for object serialization (with security warnings)
- Working with Excel files (`openpyxl`, `pandas`)
- `pathlib` for modern path manipulation
- `shutil` for high-level file operations

### 5. Error Handling (Part 2)
- Exception hierarchy and custom exception classes
- Exception chaining with `raise ... from ...`
- Context managers and the `with` statement
- Creating custom context managers (`__enter__`, `__exit__`)
- `contextlib`: `contextmanager`, `closing`, `suppress`
- Logging with the `logging` module (handlers, formatters, levels)

### 6. Testing & Debugging
- Unit testing with `unittest`
- `pytest`: fixtures, parametrization, markers
- Mocking with `unittest.mock` (`patch`, `MagicMock`)
- Code coverage with `coverage.py`
- Debugging with `pdb` and IDE debuggers
- Profiling with `cProfile` and `timeit`
- Type hints and static analysis with `mypy`

### 7. Concurrency (Part 1)
- Threading with `threading` module
- The Global Interpreter Lock (GIL)
- `concurrent.futures`: `ThreadPoolExecutor`, `ProcessPoolExecutor`
- `asyncio` basics: `async`/`await`, event loops
- `asyncio` tasks, gather, and timeouts
- `queue` module for thread-safe communication

### 8. Networking & APIs
- HTTP requests with `urllib` and `http.client`
- `requests` library: GET, POST, headers, authentication
- Building APIs with `Flask` and `FastAPI`
- RESTful API design principles
- Working with WebSockets
- `socket` programming basics

### 9. Database Interaction
- SQL basics and relational databases
- SQLite with the `sqlite3` module
- ORMs: SQLAlchemy (Core and ORM), Django ORM
- Database migrations with Alembic
- NoSQL: MongoDB with `pymongo`
- Connection pooling and transaction management

### 10. Environment & Packaging
- Virtual environments (`venv`, `virtualenv`, `conda`)
- Dependency management with `pip` and `requirements.txt`
- `pyproject.toml` and modern packaging (PEP 518, PEP 621)
- `setuptools`, `poetry`, `pipenv`
- Creating and distributing Python packages
- Dockerizing Python applications

---

## 🔴 ADVANCED LEVEL

### 1. Advanced OOP & Metaprogramming
- Metaclasses: `type()`, custom metaclasses, `__new__` vs `__init__`
- Dynamic class creation and modification
- Monkey patching and its implications
- Descriptor protocol (`__get__`, `__set__`, `__delete__`)
- Slots (`__slots__`) for memory optimization
- Weak references with `weakref` module
- Reflection and introspection (`inspect`, `types`)

### 2. Advanced Concurrency & Parallelism
- Multiprocessing with `multiprocessing` module
- Shared memory, locks, semaphores, and barriers
- `asyncio` advanced: streams, transports, protocols
- `aiohttp` for async HTTP
- Async database drivers (`asyncpg`, `motor`)
- Celery for distributed task queues
- Ray and Dask for distributed computing

### 3. Performance Optimization
- CPython internals and bytecode (`dis` module)
- Profiling and benchmarking strategies
- C extensions with `ctypes` and `cffi`
- Cython for compiled Python
- Numba for JIT compilation
- Memory profiling with `memory_profiler` and `tracemalloc`
- Algorithmic optimization and Big O analysis
- Just-In-Time compilation concepts

### 4. System Programming
- Process management (`subprocess`, `os.fork`, `os.exec`)
- Signal handling (`signal` module)
- File system monitoring (`watchdog`)
- Working with Linux/Unix system calls
- Windows-specific APIs with `pywin32`
- `mmap` for memory-mapped files
- `fcntl` and file locking

### 5. Web Development (Advanced)
- WSGI and ASGI specifications
- Django: advanced ORM, middleware, signals, caching
- FastAPI: dependency injection, background tasks, WebSockets
- Authentication: OAuth2, JWT, session management
- SQL injection prevention and security best practices
- Web scraping with `Scrapy` and `BeautifulSoup`
- GraphQL with `graphene` or `strawberry`
- Web frameworks internals

### 6. Data Science & Machine Learning Ecosystem
- NumPy: arrays, broadcasting, vectorization, linear algebra
- Pandas: DataFrames, merging, grouping, time series
- Matplotlib, Seaborn, Plotly for visualization
- Scikit-learn: pipelines, cross-validation, model selection
- Deep Learning: PyTorch or TensorFlow/Keras basics
- Feature engineering and data preprocessing
- Model deployment with Flask/FastAPI or MLflow
- Jupyter ecosystem: notebooks, widgets, extensions

### 7. DevOps & Cloud Integration
- CI/CD pipelines (GitHub Actions, GitLab CI, Jenkins)
- Infrastructure as Code with Python (Pulumi, AWS CDK)
- Cloud SDKs: `boto3` (AWS), `google-cloud-python`, `azure-sdk`
- Serverless: AWS Lambda, Google Cloud Functions
- Kubernetes Python client (`kubernetes`)
- Monitoring and observability (Prometheus, OpenTelemetry)
- Configuration management with Ansible

### 8. Security & Cryptography
- Hashing: `hashlib` (SHA-256, MD5), `bcrypt`, `argon2`
- Encryption: `cryptography` library (symmetric, asymmetric)
- JWT handling with `PyJWT`
- Secure coding practices (OWASP Top 10 for Python)
- Input validation and sanitization
- Secrets management (AWS Secrets Manager, HashiCorp Vault)
- Penetration testing basics with Python tools

### 9. Domain-Specific Advanced Topics
- **Scientific Computing**: SciPy, SymPy, numerical methods
- **Natural Language Processing**: NLTK, spaCy, transformers
- **Computer Vision**: OpenCV, Pillow, image processing
- **Game Development**: Pygame, Panda3D, Ursina
- **GUI Development**: Tkinter, PyQt/PySide, Kivy, Dear PyGui
- **Blockchain**: Web3.py, smart contract interaction
- **IoT**: MicroPython, CircuitPython, Raspberry Pi

### 10. Software Architecture & Design Patterns
- SOLID principles in Python
- Design Patterns: Creational (Singleton, Factory, Builder)
- Design Patterns: Structural (Adapter, Decorator, Facade)
- Design Patterns: Behavioral (Observer, Strategy, Command)
- Clean Architecture and Hexagonal Architecture
- Domain-Driven Design (DDD) concepts
- Event-driven architecture and message queues (RabbitMQ, Kafka)
- Microservices patterns with Python

---

## 📋 Learning Path Recommendations

| Stage | Duration | Focus |
|-------|----------|-------|
| **Basic** | 0–2 weeks | Syntax mastery, problem-solving, small scripts |
| **Intermediate** | 3–7 weeks | OOP, testing, APIs, databases, async |
| **Advanced** | 8– 12 weeks | Specialization, system design, performance, architecture |

## 🛠️ Suggested Projects by Level

**Basic:**
- Calculator, To-Do CLI, Number Guessing Game, File Organizer

**Intermediate:**
- REST API with Flask/FastAPI, Web Scraper, Chat Bot, Personal Finance Tracker

**Advanced:**
- Distributed Task Queue, Real-time Data Pipeline, ML Model Serving API, Custom Framework/Tool

---
