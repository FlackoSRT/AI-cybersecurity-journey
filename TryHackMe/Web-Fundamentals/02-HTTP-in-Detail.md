# HTTP in Detail

## 🧠 What I Learned

In this section, I learned how the HyperText Transfer Protocol (HTTP) is the backbone of the web, responsible for communication between clients (like browsers) and servers. It is a stateless protocol that uses requests and responses to transfer data.

Key concepts included:
- The structure of HTTP requests and responses
- The different HTTP methods (GET, POST, PUT, DELETE, etc.)
- Status codes (e.g., 200 OK, 404 Not Found, 500 Internal Server Error)
- Headers and their role in requests/responses
- The difference between HTTP and HTTPS

## 💡 Key Concepts

- **HTTP Request Structure:**
  - `Request Line` (e.g., `GET /index.html HTTP/1.1`)
  - `Headers` (e.g., `Host`, `User-Agent`, `Accept`)
  - `Optional Body` (used in POST requests)

- **HTTP Methods:**
  - `GET`: Retrieve data
  - `POST`: Send data to the server
  - `PUT`: Update existing data
  - `DELETE`: Remove data

- **Status Codes:**
  - `1xx`: Informational
  - `2xx`: Success (200 OK, 201 Created)
  - `3xx`: Redirection (301 Moved Permanently, 302 Found)
  - `4xx`: Client errors (403 Forbidden, 404 Not Found)
  - `5xx`: Server errors (500 Internal Server Error)

- **Headers Examples:**
  - `Content-Type`: Tells what type of data is being sent
  - `User-Agent`: Identifies the client making the request
  - `Cookie`: Contains stored session data
  - `Authorization`: Handles access credentials

- **Stateless Protocol:**
  - Each request is independent and doesn’t retain data from previous requests.
  - This is why cookies and sessions are used to maintain state.

## 🧪 Hands-On / Tasks

1. 📡 **Captured HTTP Traffic** using TryHackMe’s web simulator.
2. 🧾 **Examined raw requests and responses**, identifying status codes and headers.
3. 🛠️ **Modified headers** to test behavior (e.g., using `User-Agent: curl/7.68.0`).
4. 🔐 **Identified HTTPS** as secure HTTP, using SSL/TLS encryption.
5. 🔍 **Decoded cookies and payloads** to understand session handling.

## 🧩 Reflections / Notes

- Realized how **headers** can reveal a lot about both client and server.
- Understanding **status codes** is essential for both web development and pentesting.
- Will revisit this topic again when using **Burp Suite** to intercept and manipulate HTTP requests.

## 🏁 Completed: ✅
