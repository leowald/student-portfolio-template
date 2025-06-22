# Portfolio: [Student Name]'s Contributions to [Project Name]

Welcome! This repository showcases the work I completed as part of the Yesh Tikvah Team Project.

---

## 🛠 Project Overview

[Briefly describe the overall project. What is it? What problem does it solve? What technologies were used?]

Example:  
This project makes use of modern web development to create a highly optimized sharing platform, both in terms of performance and exceptional user experience.
his project is built with React, Node, headless Wordpress and uses the following technologies and libraries:

Auth0
Sass
Bootstrap
RadixUI
React Router
Axios
JSON Server
Express
Docker Containers
Vitest
React Testing Library
Storybook
Docusaurus.io

---

## 👩‍💻 My Contributions

Below is a summary of the specific tasks I worked on during the project, along with links to related pull requests (if available).
Don't put the intro tasks here

| Task Description                    | Technologies Used       | GitHub PR / Commit Link       |
|-----------------------------------|------------------------|------------------------------|
| Implemented user authentication flow | React, Firebase Auth    | [PR #15](https://github.com/your-org/project/pull/15) |
| Developed Task Assignment feature   | React, Node.js          | [PR #27](https://github.com/your-org/project/pull/27) |
| Wrote unit tests for API endpoints   | Jest, Supertest         | [PR #30](https://github.com/your-org/project/pull/30) |

*If pull request links are private, you can contact the instructor for verification.*

---

## 🔍 Code Samples

Here are some key snippets of code I wrote as part of my tasks:

```javascript
// Sample: User login component (React)
function Login() {
  const handleSubmit = async (e) => {
    e.preventDefault();
    // login logic here
  };

  return (
    <form onSubmit={handleSubmit}>
      {/* form fields */}
    </form>
  );
}
```

```python
# Sample: API endpoint for task creation (Node.js/Express)
app.post('/tasks', async (req, res) => {
  try {
    const task = await Task.create(req.body);
    res.status(201).json(task);
  } catch (error) {
    res.status(400).json({ error: error.message });
  }
});
```

---

## 📸 Screenshots / Demo

(Include screenshots or GIFs of the features you worked on here.)

![Task Assignment Screen](./screenshots/task-assignment.png)

---

## 📖 What I Learned

- Implemented authentication and authorization in a React app.
- Improved skills with REST APIs and backend development.
- Collaborated using GitHub Issues and Pull Requests to manage tasks and code reviews.

---

## 📞 Contact & Verification

For verification of this work or more details, please contact:  
**Team Leader:** Leora Waldman — [instructor.email@example.com]  
**Your Name:** [Your Email or LinkedIn]

---

Thank you for reviewing my work!
