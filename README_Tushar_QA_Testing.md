# 🧠 Testing React Applications — QA + Web Testing Suite
**Author:** [Tushar Mishra](https://github.com/tm33976)

### 🎯 Objective
Learn and demonstrate **React Testing Fundamentals**, **QA methodologies**, and **Automation Practices** by building and testing modern React 18 components.  
This project combines my interest in **Web Development** and **Quality Assurance**, aligning perfectly with roles that involve **product testing, debugging, and reliability validation**.

---

## 🚀 Project Overview
This hands-on project explores:  
- Writing **unit and integration tests** using [Jest](https://jestjs.io/) + [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)  
- Designing **manual test cases** and validating real user flows  
- Practicing **bug tracking** and documentation (Jira-style workflow)  
- Building confidence to **ship tested React applications** in production environments

---

## ⚙️ Tech Stack & Tools

| Area | Tools / Libraries |
|------|-------------------|
| **Frontend Stack** | React 18 • JavaScript • HTML • CSS • NodeJS |
| **Testing Frameworks** | Jest • React Testing Library • Testing Playground |
| **QA Workflow Tools** | Jira (simulated) • Postman • Manual Test Cases Excel |
| **Environment / CI** | Git • npm • GitHub Actions • Docker (optional) |

---

## 🧩 Features & Learning Highlights
✅ Built & tested React components with **Jest watch mode**  
✅ Wrote **40 + automated tests** validating UI behavior, state updates & API responses  
✅ Created manual test cases and logged bugs (simulated Jira workflow)  
✅ Practiced **SDLC-aligned QA** – requirement analysis, testing, bug reporting, regression  


---

## 🖥️ Quick Start

```bash
# Clone the project
git clone https://github.com/tm33976/react-jest-testing-framework.git
cd react-jest-testing-framework

# Install dependencies
npm install

# Run setup validation
npm run validate

# Start local development server
npm start
```

Open `http://localhost:3000` to view the app in your browser.  

To run the test suite:  
```bash
npm test
```
Jest will run in watch mode, automatically showing test results as you develop.

---

## 📘 Exercises / Folder Structure

| Folder | Purpose |
|---------|----------|
| `src/__tests__/exercise/` | Core exercises — write your own test cases |
| `src/__tests__/final/` | Reference solutions and final implementations |
| `qa-documentation/` | Manual test cases, bug reports & regression plans (added by me) |

Each exercise includes helpful emojis and comments to guide you through testing concepts.

---

## 📋 QA Documentation (Added by Me)
🧪 **Manual Test Cases:** Covers component rendering, form validation & API flows.  
🐞 **Bug Reports:** Tracked bugs with reproduction steps and expected vs actual behavior.  
🔁 **Regression Plan:** Ensured consistent results after code changes.  
🧠 **AI Testing Extension:** Experimental tests for evaluating AI responses accuracy (aligning with Zoop Live JD).

---

## 🧠 What I Learned

| Skill Area | Key Takeaway |
|-------------|--------------|
| **QA Fundamentals** | Learned test design techniques, bug documentation, and validation processes |
| **React Testing** | Practiced component testing using Jest & React Testing Library |
| **Debugging** | Used test failures to understand root cause and fix logic issues |
| **Automation Readiness** | Built confidence in writing maintainable automated tests |
| **AI Testing Interest** | Explored how QA can apply to AI features and LLM output validation |

---

## 📜 Example Test Case

```javascript
test('renders login form correctly', () => {
  render(<LoginForm />);
  const input = screen.getByLabelText(/email/i);
  expect(input).toBeInTheDocument();
});
```

---

## 🧩 Future Improvements
- Add Cypress/Playwright E2E testing suite  
- Integrate bug tracking API with Jira REST API  
- Add AI-based test case generation module (GPT evaluation)

---





## 💬 Connect with Me
🌐 Portfolio: [tushar-mishra-cse-portfolio.vercel.app](https://tushar-mishra-cse-portfolio.vercel.app)  
💻 GitHub: [tm33976](https://github.com/tm33976)  
🔗 LinkedIn: [tushar-mishra-5253ab311](https://www.linkedin.com/in/tushar-mishra-5253ab311)

---

### ✅ Summary
By adapting and extending this project, I demonstrate both **developer competence (React)** and **QA mindset (Testing, Bug Reporting, Process)**
