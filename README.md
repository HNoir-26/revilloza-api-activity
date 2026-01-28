# RESTful API Activity - [Your Name]
## Best Practices Implementation
**1. Environment Variables:**
- Why did we put `BASE_URI` in `.env` instead of hardcoding it?
- Answer: We put the BASE URI in the environment file so it is easier to change when needed.using an environment variable is more practical because it separates configuration from the actual logic of the program.
**2. Resource Modeling:**
- Why did we use plural nouns (e.g., `/dishes`) for our routes?
- Answer: Using plural nouns makes the routes consistent and clearer for users and developers. It also helps us easily identify when we are accessing all resources or just a specific one using an ID.
**3. Status Codes:**
- When do we use `201 Created` vs `200 OK`?
    - Answer: We use 201 Created when a new resource is successfully added, such as creating a new record using a POST request. We use 200 OK when the request is successful but does not create something new, like fetching or updating existing data.
- Why is it important to return `404` instead of just an empty array or a generic error?
- Answer: Using the correct status code like 404 makes error handling better and more accurate. It helps the client understand what went wrong and allows the system to respond properly.

**4. Testing:**
- (Paste a screenshot of a successful GET request here)
<img width="1366" height="738" alt="Screenshot 2026-01-28 145409" src="https://github.com/user-attachments/assets/705fd190-b9d2-4c0a-99b1-6f00f4be44d4" />
