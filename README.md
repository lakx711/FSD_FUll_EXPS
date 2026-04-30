👤 Student Details
Name: Abhishek Chauhan
Section: 23BDA-1(A)
Subject: Full Stack Development-2 (FSD)
Semester: 6
<p align="center">
  <img src="https://img.shields.io/badge/Course-Full%20Stack%20Development-blueviolet?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Experiments-9%20Labs-orange?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Completed%20✓-brightgreen?style=for-the-badge" />
</p>

<h1 align="center">🚀 Full Stack Development — Lab Experiments</h1>

<p align="center">
  <b>A comprehensive collection of hands-on lab experiments covering the complete Full Stack Development lifecycle</b><br/>
  <i>From React fundamentals to Microservices Architecture — built, tested, and deployed.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React%2019-61DAFB?style=flat-square&logo=react" />
  <img src="https://img.shields.io/badge/UI-Material%20UI%207-0081CB?style=flat-square&logo=mui" />
  <img src="https://img.shields.io/badge/Build-Vite%207-646CFF?style=flat-square&logo=vite" />
  <img src="https://img.shields.io/badge/Backend-Flask-000000?style=flat-square&logo=flask" />
  <img src="https://img.shields.io/badge/Auth-JWT-FB015B?style=flat-square&logo=jsonwebtokens" />
  <img src="https://img.shields.io/badge/State-Redux-764ABC?style=flat-square&logo=redux" />
  <img src="https://img.shields.io/badge/Deploy-Render%20%7C%20Netlify-46E3B7?style=flat-square&logo=render" />
</p>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Technology Stack](#-technology-stack)
- [Architecture Overview](#-architecture-overview)
- [Experiments At a Glance](#-experiments-at-a-glance)
- [Detailed Experiment Breakdown](#-detailed-experiment-breakdown)
  - [Experiment 1 — React Basics & SPA](#experiment-1--react-basics--single-page-application)
  - [Experiment 2 — Material UI Components](#experiment-2--material-ui-components)
  - [Experiment 3 — React Router & Navigation](#experiment-3--react-router--client-side-navigation)
  - [Experiment 4 — State Management](#experiment-4--state-management-local-context-api--redux)
  - [Experiment 5 — Lazy Loading & Code Splitting](#experiment-5--lazy-loading--code-splitting)
  - [Experiment 7 — RESTful APIs with Flask](#experiment-7--restful-apis-with-flask)
  - [Experiment 8 — JWT Authentication](#experiment-8--jwt-authentication)
  - [Experiment 9 — Role-Based Access Control](#experiment-9--role-based-access-control-rbac)
  - [Experiment 10 — Microservices Architecture](#experiment-10--microservices-architecture)
- [Learning Progression](#-learning-progression)
- [Deployment Links](#-deployment-links)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [License](#-license)

---

## 🎯 Overview

This repository contains **9 progressive lab experiments** designed to build expertise across the **entire Full Stack Development spectrum**. Each experiment focuses on a core concept, building on previous knowledge to create a cohesive learning journey — from rendering your first React component all the way to deploying inter-communicating microservices in the cloud.

```
Frontend (React)  ──►  Routing  ──►  State Mgmt  ──►  Backend (Flask)  ──►  Auth (JWT)  ──►  RBAC  ──►  Microservices
```

---

## 🛠 Technology Stack

<table>
<tr>
<td align="center" width="150"><b>Layer</b></td>
<td align="center" width="200"><b>Technology</b></td>
<td align="center" width="120"><b>Version</b></td>
<td><b>Purpose</b></td>
</tr>
<tr>
<td align="center">⚛️ Frontend</td>
<td>React.js</td>
<td><code>v19.2</code></td>
<td>Component-based UI development</td>
</tr>
<tr>
<td align="center">🎨 UI Library</td>
<td>Material UI (MUI)</td>
<td><code>v7.3</code></td>
<td>Pre-built, accessible UI components</td>
</tr>
<tr>
<td align="center">⚡ Build Tool</td>
<td>Vite</td>
<td><code>v7.2</code></td>
<td>Lightning-fast HMR & bundling</td>
</tr>
<tr>
<td align="center">🔀 Routing</td>
<td>React Router DOM</td>
<td><code>v7.12</code></td>
<td>Client-side SPA navigation</td>
</tr>
<tr>
<td align="center">📦 State</td>
<td>Redux Toolkit</td>
<td><code>latest</code></td>
<td>Global state management</td>
</tr>
<tr>
<td align="center">🐍 Backend</td>
<td>Flask (Python)</td>
<td><code>latest</code></td>
<td>REST API development</td>
</tr>
<tr>
<td align="center">🔐 Auth</td>
<td>Flask-JWT-Extended</td>
<td><code>latest</code></td>
<td>Token-based authentication</td>
</tr>
<tr>
<td align="center">🧪 API Testing</td>
<td>Postman</td>
<td>—</td>
<td>API endpoint testing & validation</td>
</tr>
<tr>
<td align="center">☁️ Deployment</td>
<td>Render / Netlify</td>
<td>—</td>
<td>Cloud hosting & CI/CD</td>
</tr>
</table>

---

## 🏗 Architecture Overview

```mermaid
graph TB
    subgraph "🖥️ Frontend Layer"
        A["⚛️ React 19<br/>Vite + JSX"] --> B["🎨 Material UI<br/>Component Library"]
        A --> C["🔀 React Router<br/>Client-Side Navigation"]
        A --> D["📦 Redux / Context API<br/>State Management"]
        A --> E["⏳ React.lazy() + Suspense<br/>Code Splitting"]
    end

    subgraph "🔌 API Layer"
        F["🌐 Axios / Fetch<br/>HTTP Client"]
    end

    subgraph "⚙️ Backend Layer"
        G["🐍 Flask<br/>REST API Server"]
        H["🔐 JWT Auth<br/>Token Verification"]
        I["🛡️ RBAC<br/>Role Permissions"]
    end

    subgraph "🏢 Microservices"
        J["👤 Customer Service<br/>Port 5001"]
        K["📦 Order Service<br/>Port 5002"]
    end

    subgraph "☁️ Cloud Deployment"
        L["Render"]
        M["Netlify"]
    end

    A --> F
    F --> G
    G --> H
    G --> I
    J <-->|"HTTP"| K
    G --> L
    J --> L
    K --> L
    A --> M

    style A fill:#61DAFB,color:#000
    style G fill:#000,color:#fff
    style H fill:#FB015B,color:#fff
    style I fill:#4CAF50,color:#fff
    style J fill:#FF9800,color:#000
    style K fill:#FF9800,color:#000
    style L fill:#46E3B7,color:#000
    style M fill:#00C7B7,color:#000
```

---

## 📊 Experiments At a Glance

| # | Experiment | Domain | Tech Stack | Key Concepts | Complexity |
|:-:|:-----------|:------:|:-----------|:-------------|:----------:|
| 1 | **React Basics & SPA** | Frontend | React, Vite | JSX, Components, Props, SPA vs MPA | ⭐ |
| 2 | **Material UI Components** | Frontend | React, MUI | UI Libraries, Theming, Responsive Design | ⭐⭐ |
| 3 | **React Router** | Frontend | React Router | Client-Side Routing, Navigation, Route Params | ⭐⭐ |
| 4 | **State Management** | Frontend | Redux, Context | Local State, Context API, Redux Store | ⭐⭐⭐ |
| 5 | **Lazy Loading** | Frontend | React.lazy | Code Splitting, Suspense, Performance | ⭐⭐⭐ |
| 7 | **RESTful APIs** | Backend | Flask, Python | CRUD Operations, Blueprints, REST | ⭐⭐⭐ |
| 8 | **JWT Authentication** | Backend | Flask-JWT | Basic Auth, Token Auth, JWT Bearer | ⭐⭐⭐⭐ |
| 9 | **RBAC Authorization** | Full Stack | Flask + React | Role Permissions, Access Control, CORS | ⭐⭐⭐⭐ |
| 10 | **Microservices** | Backend | Flask × 2 | Service Communication, Distributed Systems | ⭐⭐⭐⭐⭐ |

---

## 📝 Detailed Experiment Breakdown

---

### Experiment 1 — React Basics & Single Page Application

> **Objective:** Understand the fundamentals of React.js and differentiate between Single Page Applications (SPA) and Multi-Page Applications (MPA).

```mermaid
graph LR
    subgraph "Single Page Application"
        A["🌐 Browser"] -->|"Initial Load"| B["📄 index.html<br/>+ JS Bundle"]
        B -->|"Client Routing"| C["🏠 Home"]
        B -->|"Client Routing"| D["ℹ️ About"]
        B -->|"Client Routing"| E["📞 Contact"]
    end
    
    style A fill:#61DAFB,color:#000
    style B fill:#282c34,color:#fff
    style C fill:#4CAF50,color:#fff
    style D fill:#2196F3,color:#fff
    style E fill:#FF9800,color:#000
```

**Key Components Built:**
| Component | File | Description |
|-----------|------|-------------|
| `SinglePageApp` | `Spa.jsx` | Root SPA container with React Router |
| `Home` | `Home.jsx` | Landing page component |
| `About` | `About.jsx` | About section component |
| `Contact` | `Contact.jsx` | Contact form component |

**Learning Outcomes:**
- ✅ React.js fundamentals — JSX, components, props
- ✅ SPA vs MPA architecture differences
- ✅ Client-side routing with React Router
- ✅ Vite as a modern build tool

---

### Experiment 2 — Material UI Components

> **Objective:** Build professional, responsive user interfaces using Material UI (MUI) component library with React.

**Key Features:**
| MUI Component | Usage |
|---------------|-------|
| `AppBar` | Top navigation bar with brand color `#7b1c1c` |
| `Toolbar` | Action items container |
| `Button` | Navigation links as styled buttons |
| `Container` | Responsive content wrapper |

```mermaid
graph TD
    A["AppBar<br/>(Sticky Navigation)"] --> B["Toolbar"]
    B --> C["Button → Home"]
    B --> D["Button → About"]
    B --> E["Button → Menu"]
    B --> F["Button → Contact"]
    G["Container (mt: 3)"] --> H["Routes"]
    H --> I["/ → Home"]
    H --> J["/about → About"]
    H --> K["/menu → Menu"]
    H --> L["/contact → Contact"]

    style A fill:#7b1c1c,color:#fff
    style B fill:#9c4146,color:#fff
    style G fill:#e3f2fd,color:#000
```

**Learning Outcomes:**
- ✅ Material UI integration with React
- ✅ `sx` prop for inline styling
- ✅ Component composition with MUI
- ✅ Responsive design patterns

---

### Experiment 3 — React Router & Client-Side Navigation

> **Objective:** Implement client-side routing using React Router to create seamless navigation without full page reloads.

```mermaid
flowchart LR
    subgraph "Client-Side Routing"
        A["URL Change"] --> B{"React Router"}
        B -->|"/"| C["Home Component"]
        B -->|"/about"| D["About Component"]
        B -->|"/menu"| E["Menu Component"]
        B -->|"/contact"| F["Contact Component"]
    end

    subgraph "Server-Side Routing (Traditional)"
        G["URL Change"] --> H["Server Request"]
        H --> I["Full Page Reload"]
        I --> J["New HTML"]
    end

    style B fill:#61DAFB,color:#000
    style H fill:#ff5722,color:#fff
```

| Feature | Client-Side Routing | Server-Side Routing |
|---------|:-------------------:|:-------------------:|
| Page Reload | ❌ No | ✅ Yes |
| Speed | ⚡ Fast | 🐢 Slower |
| SEO | ⚠️ Needs SSR | ✅ Native |
| UX | 🎯 Smooth | 🔄 Flickering |
| Initial Load | 📦 Heavier | 📄 Lighter |

**Learning Outcomes:**
- ✅ React Router DOM setup and configuration
- ✅ `<Routes>`, `<Route>`, and `<Link>` components
- ✅ Client-side vs server-side routing
- ✅ Path-based component rendering

---

### Experiment 4 — State Management (Local, Context API & Redux)

> **Objective:** Explore and compare three state management approaches in React — Local State, Context API, and Redux.

```mermaid
graph TB
    subgraph "🔵 Local State"
        A1["Component A<br/>count: 5"] 
        A2["Component B<br/>count: 3"]
        A1 -.-|"Independent"| A2
    end

    subgraph "🟢 Context API"
        B0["CounterContext<br/>(Shared State)"]
        B1["Counter 1"] --> B0
        B2["Counter 2"] --> B0
    end

    subgraph "🟠 Redux Store"
        C0["Redux Store<br/>(Single Source of Truth)"]
        C1["Counter 1"] --> C0
        C2["Counter 2"] --> C0
        C0 --> C3["Reducer"]
        C3 -->|"dispatch"| C0
    end

    style A1 fill:#e3f2fd,color:#000
    style A2 fill:#e3f2fd,color:#000
    style B0 fill:#e8f5e9,color:#000
    style C0 fill:#fff3e1,color:#000
    style C3 fill:#FF9800,color:#000
```

| Approach | Scope | Complexity | Best For |
|----------|:-----:|:----------:|:---------|
| **Local State** (`useState`) | Component | ⭐ Low | Simple, isolated UI state |
| **Context API** | Subtree | ⭐⭐ Medium | Theme, auth, shared config |
| **Redux** | Global | ⭐⭐⭐ High | Complex apps, many shared states |

**Learning Outcomes:**
- ✅ `useState` for local component state
- ✅ Context API with `createContext` and `useContext`
- ✅ Redux store, reducers, and `dispatch`
- ✅ When to use which state management strategy

---

### Experiment 5 — Lazy Loading & Code Splitting

> **Objective:** Optimize React application performance using `React.lazy()` and `Suspense` for on-demand component loading.

```mermaid
sequenceDiagram
    participant Browser
    participant App
    participant Chunk1 as LocalCounter.chunk.js
    participant Chunk2 as ReduxCounter.chunk.js

    Browser->>App: Initial Load
    App-->>Browser: Render shell + eager components
    
    Note over Browser,App: User scrolls / interacts
    
    Browser->>App: Render lazy section
    App->>Chunk1: Dynamic import()
    Chunk1-->>App: Module loaded
    App-->>Browser: 🔵 LocalCounter rendered
    
    Browser->>App: Render redux section
    App->>Chunk2: Dynamic import()
    Chunk2-->>App: Module loaded
    App-->>Browser: 🟠 ReduxCounter rendered
```

| Loading Strategy | Bundle Size | Initial Load | On-Demand |
|-----------------|:-----------:|:------------:|:---------:|
| **Eager (default)** | 📦 Large | 🐢 Slow | — |
| **Lazy Loading** | 📦 Small chunks | ⚡ Fast | ✅ Yes |

**Key Implementation:**
```jsx
// Lazy imports — loaded only when needed
const LocalCounter = lazy(() => import("./components/localstate/CounterState"));
const CounterReduxParent = lazy(() => import("./components/redux/CounterGlobalReduxParent"));

// Suspense boundary with fallback UI
<Suspense fallback={<h3>Loading...</h3>}>
  <LocalCounter />
</Suspense>
```

**Learning Outcomes:**
- ✅ `React.lazy()` for dynamic imports
- ✅ `Suspense` with fallback UI
- ✅ Webpack/Vite code splitting & chunking
- ✅ Performance optimization strategies

---



### Experiment 6 — Form Handling & Validation

> **Objective:** To understand and implement form handling in React using controlled components, React Hook Form, and Yup validation for building efficient, scalable, and user-friendly forms.

---

## 🧠 Introduction

Forms are a critical part of modern web applications. They are used for:

- User Registration & Login
- Profile Updates
- Data Collection (Surveys)
- Search & Filtering
- Checkout Systems

However, handling forms is challenging due to:

- Managing multiple input states
- Validation complexity
- Error handling
- Performance issues

This experiment focuses on solving these problems using modern React techniques.

---

## 🏗️ Working Flow

```mermaid
flowchart TD
    A["User Input"] --> B["React Form"]
    B --> C["State Management"]
    C --> D{"Validation"}
    D -->|Valid| E["Submit Data"]
    D -->|Invalid| F["Show Errors"]
    E --> G["API / Backend"]
    F --> B
```


### Experiment 7 — RESTful APIs with Flask

> **Objective:** Develop a complete CRUD REST API for student management using the Flask backend framework.

```mermaid
graph LR
    subgraph "Client (Postman)"
        A["📮 POST /students"]
        B["📋 GET /students"]
        C["📋 GET /students/:id"]
        D["✏️ PUT /students/:id"]
        E["🗑️ DELETE /students/:id"]
    end

    subgraph "Flask Backend"
        F["🐍 app.py"]
        G["📁 student_routes.py<br/>(Blueprint)"]
        H["💾 In-Memory Store"]
    end

    A --> F
    B --> F
    C --> F
    D --> F
    E --> F
    F --> G
    G --> H

    style F fill:#000,color:#fff
    style G fill:#333,color:#fff
    style H fill:#4CAF50,color:#fff
```

**API Endpoints:**

| Method | Endpoint | Description | Status Code |
|:------:|:---------|:------------|:-----------:|
| `POST` | `/students` | Create a new student record | `201` |
| `GET` | `/students` | Retrieve all students | `200` |
| `GET` | `/students/<id>` | Retrieve student by ID | `200` / `404` |
| `PUT` | `/students/<id>` | Update student record | `200` / `404` |
| `DELETE` | `/students/<id>` | Delete student record | `200` / `404` |

**🌐 Live Deployment:** [Render Link](https://two3bis70035-experiment-8.onrender.com)

**Learning Outcomes:**
- ✅ Flask application factory pattern
- ✅ Blueprints for modular route organization
- ✅ RESTful API design principles (CRUD)
- ✅ HTTP methods and status codes
- ✅ Cloud deployment on Render

---

### Experiment 8 — JWT Authentication

> **Objective:** Implement and compare three authentication methods — Basic Auth, Token-based Auth, and JWT (JSON Web Token) Auth.

```mermaid
sequenceDiagram
    participant Client
    participant Server
    participant JWT as JWT Engine

    Note over Client,JWT: 🔑 Method 1: Basic Auth
    Client->>Server: GET /basic-protected<br/>Authorization: Basic base64(user:pass)
    Server-->>Client: ✅ Welcome!

    Note over Client,JWT: 🎫 Method 2: Token Auth
    Client->>Server: POST /token-login {user, pass}
    Server-->>Client: {token: base64(username)}
    Client->>Server: GET /token-protected<br/>x-auth-token: <token>
    Server-->>Client: ✅ Token Valid!

    Note over Client,JWT: 🛡️ Method 3: JWT Auth
    Client->>Server: POST /jwt-login {user, pass}
    Server->>JWT: create_access_token(identity)
    JWT-->>Server: Signed JWT
    Server-->>Client: {access_token: <jwt>}
    Client->>Server: GET /jwt-protected<br/>Authorization: Bearer <jwt>
    Server->>JWT: Verify signature
    JWT-->>Server: ✅ Valid
    Server-->>Client: ✅ JWT Auth Success!
```

**Authentication Methods Comparison:**

| Method | Header | Stateless | Security | Token Expiry |
|:-------|:-------|:---------:|:--------:|:------------:|
| 🔑 **Basic Auth** | `Authorization: Basic` | ✅ | 🟡 Weak | ❌ |
| 🎫 **Token Auth** | `x-auth-token` | ✅ | 🔴 Very Weak | ❌ |
| 🛡️ **JWT Auth** | `Authorization: Bearer` | ✅ | 🟢 Strong | ✅ |

**API Endpoints:**

| Method | Endpoint | Description |
|:------:|:---------|:------------|
| `GET` | `/basic-protected` | Basic Authentication protected route |
| `POST` | `/token-login` | Generate simple Base64 token |
| `GET` | `/token-protected` | Access via `x-auth-token` header |
| `POST` | `/jwt-login` | Generate JWT access token |
| `GET` | `/jwt-protected` | Access via JWT Bearer token |

**Learning Outcomes:**
- ✅ Basic HTTP authentication
- ✅ Custom token-based authentication
- ✅ JWT creation, signing, and verification
- ✅ Flask-JWT-Extended library usage
- ✅ Security comparison of auth methods

---

### Experiment 9 — Role-Based Access Control (RBAC)

> **Objective:** Implement a full-stack RBAC system where resource access is controlled based on user roles (Admin vs User).

```mermaid
flowchart TD
    A["👤 User Login"] --> B{"🔐 Authenticate"}
    B -->|"✅ Success"| C{"🏷️ Assign Role"}
    B -->|"❌ Failure"| X["🚫 Access Denied"]
    
    C -->|"role: admin"| D["🛡️ Admin"]
    C -->|"role: user"| E["👤 User"]
    
    D --> F["📖 Read ✅"]
    D --> G["✏️ Write ✅"]
    D --> H["🗑️ Delete ✅"]
    
    E --> I["📖 Read ✅"]
    E --> J["✏️ Write ❌"]
    E --> K["🗑️ Delete ❌"]

    style D fill:#4CAF50,color:#fff
    style E fill:#2196F3,color:#fff
    style X fill:#f44336,color:#fff
    style J fill:#f44336,color:#fff
    style K fill:#f44336,color:#fff
    style F fill:#4CAF50,color:#fff
    style G fill:#4CAF50,color:#fff
    style H fill:#4CAF50,color:#fff
    style I fill:#4CAF50,color:#fff
```

**Permission Matrix:**

| Role | `read` | `write` | `delete` | Scope |
|:-----|:------:|:-------:|:--------:|:------|
| 🛡️ **Admin** | ✅ | ✅ | ✅ | Full control |
| 👤 **User** | ✅ | ❌ | ❌ | Read-only access |

**Architecture:**
```
┌─────────────┐       HTTP/Axios       ┌─────────────────┐
│  React App  │ ◄──────────────────► │  Flask Backend  │
│  (Netlify)  │    role in headers    │   (Render)      │
└─────────────┘                       └─────────────────┘
```

**🌐 Live Links:**
- **Frontend:** [Netlify](https://23bis70035experiment10.netlify.app/)
- **Backend:** [Render](https://two3bis70035-experiment-10.onrender.com)

**Learning Outcomes:**
- ✅ RBAC design pattern implementation
- ✅ Role-permission mapping
- ✅ Full-stack integration (React + Flask)
- ✅ CORS configuration for cross-origin requests
- ✅ Dual-platform deployment (Netlify + Render)

---

### Experiment 10 — Microservices Architecture

> **Objective:** Build a distributed microservices system with independently deployable services that communicate over HTTP.

```mermaid
graph TB
    subgraph "🌐 Client"
        A["📮 API Request<br/>GET /customers/101/orders"]
    end

    subgraph "🔵 Customer Service (Port 5001)"
        B["customer_app.py"]
        C["📋 Customer Data<br/>ID, Name, Email"]
    end

    subgraph "🟠 Order Service (Port 5002)"
        D["order_app.py"]
        E["📦 Order Data<br/>ID, Items, Status, Amount"]
    end

    A -->|"1. Request"| B
    B -->|"2. Lookup"| C
    B -->|"3. HTTP GET<br/>/orders/user/101"| D
    D -->|"4. Lookup"| E
    D -->|"5. Return Orders"| B
    B -->|"6. Combined Response<br/>{customer + orders}"| A

    style B fill:#2196F3,color:#fff
    style D fill:#FF9800,color:#000
    style C fill:#BBDEFB,color:#000
    style E fill:#FFE0B2,color:#000
```

**Service Endpoints:**

| Service | Method | Endpoint | Description |
|:--------|:------:|:---------|:------------|
| 👤 **Customer** | `GET` | `/customers/<id>/orders` | Get customer + their orders |
| 📦 **Order** | `GET` | `/orders/user/<user_id>` | Get orders for a user |
| 📦 **Order** | `PUT` | `/orders/<order_id>/status` | Update order status |

**Sample Data Flow:**
```json
// GET /customers/101/orders → Combined Response
{
  "customer": {
    "id": 101,
    "name": "Customer-1",
    "email": "customer-1@example.com"
  },
  "orders": [
    {
      "id": 1,
      "order_amount": 2500,
      "order_status": "Shipped",
      "items": [
        {"name": "Laptop", "quantity": 1, "price": 2000},
        {"name": "Mouse", "quantity": 2, "price": 250}
      ]
    }
  ]
}
```

**🌐 Live Deployments:**
- **Customer Service:** [Render](https://two3bis70035-experiment-11-customer.onrender.com)
- **Order Service:** [Render](https://two3bis70035-experiment-11-order.onrender.com)

**Learning Outcomes:**
- ✅ Microservices architecture design
- ✅ Inter-service HTTP communication
- ✅ Independent deployment of services
- ✅ Error handling in distributed systems
- ✅ Cloud deployment of multiple services

---

## 📈 Learning Progression

```mermaid
graph LR
    A["1️⃣ React<br/>Basics"] --> B["2️⃣ Material<br/>UI"]
    B --> C["3️⃣ React<br/>Router"]
    C --> D["4️⃣ State<br/>Management"]
    D --> E["5️⃣ Lazy<br/>Loading"]
    E --> F["7️⃣ REST<br/>APIs"]
    F --> G["8️⃣ JWT<br/>Auth"]
    G --> H["9️⃣ RBAC"]
    H --> I["🔟 Micro<br/>services"]

    style A fill:#E3F2FD,color:#000
    style B fill:#BBDEFB,color:#000
    style C fill:#90CAF9,color:#000
    style D fill:#64B5F6,color:#fff
    style E fill:#42A5F5,color:#fff
    style F fill:#2196F3,color:#fff
    style G fill:#1E88E5,color:#fff
    style H fill:#1565C0,color:#fff
    style I fill:#0D47A1,color:#fff
```

| Phase | Experiments | Skills Acquired |
|:------|:------------|:----------------|
| **🎨 Frontend Foundations** | 1, 2, 3 | React, JSX, Components, MUI, Routing |
| **⚙️ Advanced Frontend** | 4, 5 | State Management, Redux, Performance Optimization |
| **🐍 Backend Development** | 7 | REST APIs, Flask, CRUD, Blueprints |
| **🔐 Security** | 8, 9 | Authentication, JWT, Authorization, RBAC |
| **🏢 Architecture** | 10 | Microservices, Distributed Systems, Service Communication |

---

## 🌐 Deployment Links

| Experiment | Platform | URL |
|:-----------|:--------:|:----|
| Exp 7 — REST API | Render | [two3bis70035-experiment-8.onrender.com](https://two3bis70035-experiment-8.onrender.com) |
| Exp 9 — RBAC Backend | Render | [two3bis70035-experiment-10.onrender.com](https://two3bis70035-experiment-10.onrender.com) |
| Exp 9 — RBAC Frontend | Netlify | [23bis70035experiment10.netlify.app](https://23bis70035experiment10.netlify.app/) |
| Exp 10 — Customer Service | Render | [two3bis70035-experiment-11-customer.onrender.com](https://two3bis70035-experiment-11-customer.onrender.com) |
| Exp 10 — Order Service | Render | [two3bis70035-experiment-11-order.onrender.com](https://two3bis70035-experiment-11-order.onrender.com) |

---

## 🚀 Getting Started

### Prerequisites

```bash
node --version    # v18+ required
npm --version     # v9+ required
python --version  # 3.8+ required
```

### Running Frontend Experiments (1–5)

```bash
# Clone the repository
git clone https://github.com/Shubhanshu-ydv/FSD-Experiments.git
cd FSD-Experiments

# Navigate to any frontend experiment
cd Experiment_1

# Install dependencies
npm install

# Start development server
npm run dev
```

### Running Backend Experiments (7–10)

```bash
# Navigate to backend experiment
cd Experiment_7

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python run.py
```

---

## 📁 Project Structure

```
FSD-Experiments/
│
├── Experiment_1/          # ⚛️ React Basics & SPA
│   ├── src/
│   │   ├── components/    # Home, About, Contact, Spa
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── Experiment_2/          # 🎨 Material UI Components
│   ├── src/
│   │   ├── components/    # MUI-styled components
│   │   └── App.jsx
│   └── package.json
│
├── Experiment_3/          # 🔀 React Router Navigation
│   ├── src/
│   │   ├── components/    # Routed pages
│   │   └── App.jsx
│   └── package.json
│
├── Experiment_4/          # 📦 State Management
│   ├── src/
│   │   ├── components/
│   │   │   ├── localstate/      # useState
│   │   │   ├── contextapi/      # Context API
│   │   │   └── redux/           # Redux Toolkit
│   │   ├── store/               # Redux store config
│   │   └── App.jsx
│   └── package.json
│
├── Experiment_5/          # ⏳ Lazy Loading
│   ├── src/
│   │   ├── components/    # Lazy-loaded components
│   │   └── App.jsx        # React.lazy + Suspense
│   └── package.json
│
├── Experiment_7/          # 🐍 RESTful API (Flask)
│   ├── routes/
│   │   └── student_routes.py
│   ├── app.py
│   ├── run.py
│   └── requirements.txt
│
├── Experiment_8/          # 🔐 JWT Authentication
│   ├── app.py             # Basic, Token & JWT Auth
│   └── requirements.txt
│
├── Experiment_9/          # 🛡️ RBAC (Full Stack)
│   ├── backend/
│   │   ├── app.py
│   │   └── requirements.txt
│   └── frontend/
│       ├── src/
│       └── package.json
│
├── Experiment_10/         # 🏢 Microservices
│   └── micro-services-lab/
│       ├── customer-service/
│       │   └── customer_app.py
│       └── order-service/
│           └── order_app.py
│
└── README.md              # 📖 You are here!
```

---

## 📄 License

This project is created for **academic purposes** as part of the Full Stack Development course curriculum.

---

<p align="center">
  <b>Built with ❤️ using React, Flask & a lot of ☕</b><br/>
  <sub>⭐ Star this repo if you found it helpful!</sub>
</p>
