# 🚀 AI Agent Development Curriculum
## From Zero to Production-Ready AI Agents

**Total Duration:** 33 Hours | **Level:** Beginner to Advanced | **Prerequisites:** None

---

## 📊 Course Overview

| Phase | Duration | Content Hours | Project Hours | Total |
|-------|----------|---------------|---------------|-------|
| Phase 1: Python Foundations | 9 hrs | 6 hrs | 3 hrs | 9 hrs |
| Phase 2: FastAPI Development | 9 hrs | 6 hrs | 3 hrs | 9 hrs |
| Phase 3: Docker & Deployment | 4 hrs | 2 hrs | 2 hrs | 4 hrs |
| Phase 4: LangGraph AI Agents | 6 hrs | 6 hrs | 0 hrs | 6 hrs |
| Phase 5: Capstone Project | 5 hrs | 0 hrs | 5 hrs | 5 hrs |
| **TOTAL** | **33 hrs** | **20 hrs** | **13 hrs** | **33 hrs** |

---

## 📚 PHASE 1: Python Foundations
**Duration:** 9 Hours (6 hrs learning + 3 hrs project)

### Module 1.1: Setup & Basics
**Duration:** 1 hour

**Topics Covered:**
- Python installation and environment setup
- VS Code configuration and extensions
- Running your first Python program
- Variables and data types (int, float, str, bool)
- Basic operators (arithmetic, comparison, logical)
- Input/output operations with `input()` and `print()`

**Hands-On Exercises:**
- Calculator program
- User input validator
- Type conversion exercises

---

### Module 1.2: Control Flow
**Duration:** 1 hour

**Topics Covered:**
- Conditional statements (if, elif, else)
- Logical operators (and, or, not)
- Loop structures (for, while)
- Loop control (break, continue, pass)
- Nested loops and pattern printing

**Hands-On Exercises:**
- Number guessing game
- Pattern printing (pyramids, diamonds)
- Menu-driven program structure

---

### Module 1.3: Data Collections
**Duration:** 1.5 hours

**Topics Covered:**
- **Lists:** Creation, indexing, slicing, methods (append, extend, insert, remove, pop, sort)
- **Tuples:** Immutable sequences, packing/unpacking
- **Sets:** Unique collections, set operations (union, intersection, difference)
- **Dictionaries:** Key-value pairs, methods (get, keys, values, items, update)
- List/dict comprehensions
- Iteration techniques (enumerate, zip)

**Hands-On Exercises:**
- Student grade management system
- Inventory tracker with dictionaries
- Data filtering and transformation

---

### Module 1.4: Functions & Scope
**Duration:** 1.5 hours

**Topics Covered:**
- Function definition and calling
- Parameters and arguments (positional, keyword, default, *args, **kwargs)
- Return values and multiple returns
- Variable scope (local, global, nonlocal)
- Recursive functions
- Lambda functions
- Basic decorators

**Hands-On Exercises:**
- Mathematical utility functions
- Recursive problem solving (factorial, fibonacci)
- Function decorator practice

---

### Module 1.5: Object-Oriented Programming
**Duration:** 1 hour

**Topics Covered:**
- Classes and objects fundamentals
- Attributes (instance and class variables)
- Methods (instance, class, static methods)
- The `__init__` constructor
- Encapsulation (private attributes with `_` and `__`)
- Inheritance and method overriding
- Polymorphism basics
- Abstract classes and methods

**Hands-On Exercises:**
- Create a simple class hierarchy
- Implement inheritance patterns
- Practice encapsulation

---

### 🎯 PROJECT 1: Simple Banking System
**Duration:** 3 hours

**Project Overview:**
Build a console-based banking system that demonstrates core Python and OOP principles.

**Features to Implement:**
1. **Account Management** (1 hour)
   - Create new accounts with customer details
   - Store account information (name, account number, balance)
   - Implement Account and Customer classes

2. **Transactions** (1 hour)
   - Deposit functionality with validation
   - Withdrawal with insufficient funds checking
   - Balance inquiry
   - Transaction history tracking

3. **Data Persistence & Error Handling** (1 hour)
   - Save account data to JSON file
   - Load existing accounts on startup
   - Input validation and error handling
   - Professional transaction receipts

**Technical Requirements:**
- Use OOP principles (classes, inheritance, encapsulation)
- Implement proper error handling with try-except
- File I/O for data persistence
- Input validation for all user inputs

**Expected Deliverables:**
- Working Python application
- Clean, commented code
- Test cases covering main functionality
- README with usage instructions

---

## 🌐 PHASE 2: FastAPI Web Development
**Duration:** 9 Hours (6 hrs learning + 3 hrs project)

### Module 2.1: API Fundamentals
**Duration:** 1 hour

**Topics Covered:**
- Understanding APIs and REST architecture
- HTTP methods (GET, POST, PUT, PATCH, DELETE)
- Status codes and their meanings
- Request/response cycle
- FastAPI installation and project structure
- Creating your first endpoint
- Automatic API documentation (Swagger UI)

**Hands-On Exercises:**
- Hello World API
- Basic CRUD endpoints
- Testing with FastAPI docs

---

### Module 2.2: Dynamic Routing & Parameters
**Duration:** 1 hour

**Topics Covered:**
- Path parameters with type hints
- Path parameter validation
- Query parameters (optional and required)
- Multiple parameter handling
- Request validation with Pydantic
- URL path operations and naming conventions

**Hands-On Exercises:**
- User profile endpoint with path params
- Search endpoint with query params
- Filtering and pagination logic

---

### Module 2.3: Request & Response Handling
**Duration:** 1.5 hours

**Topics Covered:**
- Request body processing
- JSON data handling
- Pydantic models for data validation
- Response models and serialization
- HTTP status codes in responses
- Error responses and exception handling
- Response model customization

**Hands-On Exercises:**
- Create complex data models
- Implement validation rules
- Custom response formatting

---

### Module 2.4: Authentication & Security
**Duration:** 1.5 hours

**Topics Covered:**
- User registration and login flow
- Password hashing with bcrypt/passlib
- JWT (JSON Web Tokens) fundamentals
- Token creation and validation
- Protected routes with dependencies
- Role-based access control (RBAC)
- Security best practices

**Hands-On Exercises:**
- User registration system
- Login endpoint with JWT
- Protected route implementation

---

### Module 2.5: Database Operations & File Handling
**Duration:** 1 hour

**Topics Covered:**
- JSON file-based storage
- Reading and writing JSON files
- CRUD operations implementation
- Data relationships and references
- Error handling for file operations
- Logging setup and usage
- Data validation and sanitization

**Hands-On Exercises:**
- Implement file-based database
- CRUD operations with persistence
- Error handling scenarios

---

### 🎯 PROJECT 2: Advanced Todo API with Authentication
**Duration:** 3 hours

**Project Overview:**
Build a production-ready Todo API with user authentication, role-based permissions, and comprehensive CRUD operations.

**Features to Implement:**

1. **User Management** (1 hour)
   - User registration endpoint
   - Login with JWT token generation
   - Password hashing and validation
   - User profile endpoints

2. **Todo CRUD Operations** (1 hour)
   - Create todo (authenticated users)
   - Read todos (user-specific and all)
   - Update todo (owner only)
   - Delete todo (owner or admin)
   - Todo filtering and searching

3. **Authorization & Data Persistence** (1 hour)
   - Role-based access control (User/Admin)
   - Protected routes with JWT validation
   - JSON file-based data storage
   - Comprehensive error handling

**Technical Requirements:**
- RESTful API design principles
- JWT authentication implementation
- Pydantic models for validation
- Proper HTTP status codes
- API documentation with examples

**Expected Deliverables:**
- Fully functional API with all endpoints
- Comprehensive API documentation
- Postman/Thunder Client collection
- README with setup instructions

---

## 🐳 PHASE 3: Docker & Containerization
**Duration:** 4 Hours (2 hrs learning + 2 hrs project)

### Module 3.1: Docker Fundamentals
**Duration:** 0.5 hours

**Topics Covered:**
- Containers vs Virtual Machines
- Docker architecture (daemon, client, registry)
- Docker installation on different platforms
- Basic Docker commands
- Docker Hub and image repositories
- Understanding images and containers

**Hands-On Exercises:**
- Pull and run official images
- Basic container management
- Exploring running containers

---

### Module 3.2: Working with Containers
**Duration:** 0.5 hours

**Topics Covered:**
- Container lifecycle (create, start, stop, remove)
- Port mapping and networking
- Volume mounting for data persistence
- Environment variables
- Container logs and inspection
- Interactive vs detached mode

**Hands-On Exercises:**
- Run web servers in containers
- Mount volumes for persistence
- Configure environment variables

---

### Module 3.3: Creating Custom Images
**Duration:** 0.5 hours

**Topics Covered:**
- Dockerfile syntax and instructions
- Base images and FROM instruction
- COPY vs ADD commands
- RUN, CMD, and ENTRYPOINT
- Layer caching and optimization
- Multi-stage builds
- .dockerignore files

**Hands-On Exercises:**
- Write Dockerfiles for Python apps
- Build and tag custom images
- Optimize image size

---

### Module 3.4: Docker Compose
**Duration:** 0.5 hours

**Topics Covered:**
- Multi-container applications
- docker-compose.yml structure
- Service definitions
- Networks and volumes in Compose
- Environment variables and secrets
- Scaling services
- Docker Compose commands

**Hands-On Exercises:**
- Create multi-service applications
- Configure service dependencies
- Manage application lifecycle

---

### 🎯 PROJECT 3: Dockerized Todo API
**Duration:** 2 hours

**Project Overview:**
Containerize the Todo API from Phase 2 for production deployment.

**Features to Implement:**

1. **Dockerfile Creation** (0.5 hours)
   - Multi-stage Dockerfile for optimization
   - Production-ready Python image
   - Dependency installation
   - Security best practices

2. **Docker Compose Setup** (1 hour)
   - Service configuration for API
   - Volume mounting for data persistence
   - Environment variable management
   - Port mapping and networking
   - Health checks

3. **Testing & Documentation** (0.5 hours)
   - Test containerized application
   - Create deployment documentation
   - Environment setup guide
   - Troubleshooting guide

**Technical Requirements:**
- Optimized multi-stage Dockerfile
- Complete docker-compose.yml
- Environment variable configuration
- Volume persistence strategy
- Production-ready setup

**Expected Deliverables:**
- Dockerfile and docker-compose.yml
- .dockerignore file
- Environment template (.env.example)
- Deployment documentation

---

## 🛠 PHASE 4: LangGraph AI Agents
**Duration:** 6 Hours (Learning Only - No Project)

### Module 4.1: LLM Fundamentals & LangChain
**Duration:** 1 hour

**Topics Covered:**
- Understanding Large Language Models (GPT, Claude, Gemini)
- Model capabilities and limitations
- Token limits and context windows
- Prompt engineering basics
- LangChain framework introduction
- Setting up API keys (OpenAI, Anthropic)
- Basic LLM integration
- Chat models and completion models
- Memory systems (Buffer, Summary)

**Hands-On Exercises:**
- Connect to different LLM providers
- Experiment with prompts
- Build simple chat interface
- Implement conversation memory

---

### Module 4.2: LangGraph Fundamentals
**Duration:** 1.5 hours

**Topics Covered:**
- Graph-based agent architecture
- Nodes, edges, and state
- State graphs vs traditional chains
- LangGraph vs LangChain comparison
- Setting up LangGraph
- Creating your first graph
- Conditional edges

**Hands-On Exercises:**
- Build simple state graphs
- Implement conditional routing
- Visualize graph execution

---

### Module 4.3: State Management & Memory
**Duration:** 1.5 hours

**Topics Covered:**
- State definition and typing
- State updates and persistence
- Short-term vs long-term memory
- Checkpointing mechanisms
- Memory optimization strategies
- Context window management
- State versioning

**Hands-On Exercises:**
- Implement stateful agents
- Add checkpointing
- Manage conversation history

---

### Module 4.4: Tool Integration
**Duration:** 1 hour

**Topics Covered:**
- Creating custom tools
- Tool schemas and descriptions
- Function calling fundamentals
- Tool selection strategies
- Error handling in tools
- Tool result processing
- Building tool ecosystems

**Hands-On Exercises:**
- Create custom tools
- Implement tool calling
- Handle tool errors

---

### Module 4.5: Advanced Agent Patterns
**Duration:** 0.5 hours

**Topics Covered:**
- Multi-agent systems
- Agent communication protocols
- Human-in-the-loop patterns
- Interrupt handling
- Approval flows
- Agent collaboration strategies

**Hands-On Exercises:**
- Build multi-agent system
- Implement human oversight
- Create approval workflows

---

### Module 4.6: Production Considerations
**Duration:** 0.5 hours

**Topics Covered:**
- LangSmith integration
- Monitoring and logging
- Debugging agent decisions
- Performance optimization
- Error recovery strategies
- Deployment best practices

**Hands-On Exercises:**
- Set up monitoring
- Debug agent flows
- Optimize performance

---

## 🎓 PHASE 5: Capstone Project
**Duration:** 5 Hours (Pure Project Work)

### 🎯 CAPSTONE: Intelligent Telegram Bot
**Duration:** 5 hours

**Project Overview:**
Build a production-ready intelligent Telegram bot that integrates all learned concepts into a comprehensive AI agent system. This is the culmination of all phases, bringing together Python, FastAPI, Docker, and LangGraph into one complete application.

**Implementation Breakdown:**

#### Part 1: Foundation Setup (1 hour)
- Telegram bot setup and configuration
- Project structure organization
- Environment configuration
- Basic bot commands and handlers
- FastAPI webhook setup (optional)

#### Part 2: LangGraph Agent Core (1.5 hours)
- LangGraph agent architecture design
- State management implementation
- LangChain LLM integration
- Memory system setup
- Basic conversation handling
- Tool definition and registration

#### Part 3: Advanced Features (1.5 hours)
- **Multi-modal capabilities:**
  - Voice message transcription (STT) OR
  - Image understanding with vision models
- **Tool Integration:**
  - Web search capability
  - Calculator and utilities
  - Custom business logic
- **Agent patterns:**
  - Task routing
  - Agent coordination

#### Part 4: Production & Deployment (1 hour)
- Docker containerization
- Database integration (SQLite for simplicity)
- Basic logging setup
- Error handling
- Environment variable management
- Testing and documentation

**Technical Stack:**
- Python + python-telegram-bot
- LangGraph for agent orchestration
- FastAPI for webhook handling
- Docker for containerization
- PostgreSQL for data persistence
- LangSmith for monitoring

**Features to Implement:**

1. **Core Intelligence**
   - LangGraph agent architecture
   - Task breakdown and execution
   - Context-aware conversations
   - Conversation state persistence

2. **Multi-Modal Capabilities** (Choose 1-2)
   - Text processing and generation
   - Voice message handling (STT) OR
   - Image understanding with vision models

3. **Agent Features**
   - Tool selection and execution
   - Task planning
   - Error recovery

4. **Tool Integration** (Minimum 2-3 tools)
   - Web search functionality
   - Calculator operations
   - Weather API OR custom business logic

5. **Production Features**
   - Database persistence (SQLite)
   - Docker containerization
   - Basic logging
   - Error handling
   - Environment configuration

**Expected Deliverables:**
- Fully functional Telegram bot with core features
- Complete source code with documentation
- Docker deployment configuration (Dockerfile + docker-compose.yml)
- Database schema (SQLite)
- User guide with feature demonstrations
- Deployment guide with setup instructions
- README with architecture overview

**Evaluation Criteria:**
- **Functionality (40%):** Core features working correctly
- **Code Quality (25%):** Clean, organized code
- **Architecture (20%):** Proper LangGraph implementation
- **Documentation (10%):** Clear documentation
- **Deployment (5%):** Docker setup working

---

## 🎯 Learning Outcomes

### Technical Skills Acquired:
- ✅ **Python Programming:** Variables to OOP mastery
- ✅ **Web Development:** RESTful APIs with FastAPI
- ✅ **DevOps:** Docker containerization and deployment
- ✅ **AI/ML:** LLM integration and prompt engineering
- ✅ **Agent Development:** Advanced LangGraph implementations
- ✅ **Production Skills:** Monitoring, logging, and deployment

### Portfolio Projects:
1. Banking System (Python OOP)
2. Todo API (FastAPI + Authentication)
3. Dockerized API (Containerization)
4. **Intelligent Telegram Bot (Complete Integration) - Capstone**

### Professional Competencies:
- Problem-solving and debugging
- Code organization and documentation
- API design and implementation
- Security best practices
- Production deployment strategies

---

## 🛠️ Prerequisites & Setup

### System Requirements:
- Computer with 8GB+ RAM
- Windows 10+(recommended), macOS 10.15+, or Linux
- Stable internet connection

### Software Installation:
1. **Python 3.10+**
2. **VS Code** with extensions (Python, Docker)
3. **Docker Desktop**
4. **Git** for version control

### Account Setup:
- GitHub account
- Docker Hub account
- LangSmith account (for monitoring)
- Telegram account (for capstone)

---

## 📚 Additional Resources

### Documentation:
- Official Python docs
- FastAPI documentation
- Docker documentation
- LangChain documentation
- LangGraph documentation

### Community:
- Discord server for support
- GitHub repository with code examples
- Weekly office hours
- Peer code review sessions

### Tools:
- Code templates and starters
- Debugging guides
- Deployment checklists
- Best practices documents

---

## 🚀 Next Steps After Completion

### Advanced Topics:
- Vector databases and embeddings
- Advanced RAG implementations
- Computer vision agents
- Voice-based AI assistants
- Multi-modal AI systems

### Career Paths:
- AI Engineer
- Agent Developer
- Full-Stack AI Developer
- ML Engineer
- AI Consultant

### Continuous Learning:
- Latest AI research papers
- Advanced LangGraph patterns
- Production MLOps
- AI system architecture

---

## 📊 Time Investment Summary

| Activity Type | Hours | Percentage |
|---------------|-------|------------|
| Learning Content | 20 hrs | 61% |
| Hands-on Projects | 13 hrs | 39% |
| **Total Course** | **33 hrs** | **100%** |

**Recommended Schedule:**
- **Intensive:** 3 days (11 hrs/day)
- **Regular:** 5-6 days (5-6 hrs/day)
- **Part-time:** 11 days (3 hrs/day)
- **Weekend:** 4-5 weekends

---

## 🎓 Certification

Upon completion of all phases and projects, students will receive:
- Certificate of completion
- Portfolio of 6 production-ready projects
- Reference letter (upon request)
- Lifetime access to community and resources

---

**Ready to transform from zero to AI agent developer? Let's begin your journey! 🚀**
