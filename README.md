
# PS-1 Fullstack Project

A full-stack application consisting of a backend service and a frontend user interface, hosted in the [ps-1-fullstack](https://github.com/codingfreshie/ps-1-fullstack) repository.

## About the Project

The application is split into a client-side interface and a server-side backend to manage and process data efficiently.

## Project Structure

### 1. `PS-1-DGRC-Backend-main`

- **Purpose:** The core backend application, built with C# and .NET. It handles API endpoints, database connections, business logic, and request routing.
- **Key responsibilities:**
  - Processing incoming client requests.
  - Interacting with databases or external data sources.
  - Exposing RESTful APIs for the frontend.

### 2. `PS-1-DGRC-Frontend-main`

- **Purpose:** The client-side JavaScript application that users interact with in their browsers.
- **Key responsibilities:**
  - Rendering UI components and views.
  - Managing user state and client-side routing.
  - Communicating with the backend API to fetch and display data.

## Tech Stack

- **Frontend:** JavaScript (77.1%)
- **Backend:** C# (22.9%) / .NET

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [.NET SDK](https://dotnet.microsoft.com/)
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/codingfreshie/ps-1-fullstack.git
cd ps-1-fullstack
```

### Step 2: Run the Backend

Navigate to the backend directory:

```bash
cd PS-1-DGRC-Backend-main
```

Restore dependencies and start the application:

```bash
dotnet restore
dotnet run
```

Note the local URL and port printed by the server, such as `https://localhost:5001`.

### Step 3: Run the Frontend

Open a **new terminal** from the repository root and navigate to the frontend directory:

```bash
cd PS-1-DGRC-Frontend-main
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

Ensure any required environment variables or API base URLs point to your running backend instance.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests with improvements.
