# 👨‍💻 AI Code Review Assistant

An AI-powered code review platform that analyzes source code, detects potential issues, generates detailed feedback, and assigns a quality score automatically.

---

## ✨ Features

- 🤖 AI-powered code reviews
- 📊 Automatic quality scoring (1–10)
- 🐞 Detects potential bugs and issues
- 🚀 Suggests code improvements
- 💾 Automatically saves review history
- 🌐 REST API support
- 💻 Multi-language code analysis

---

## 🗄️ Database Schema

| Field | Type |
|---------|---------|
| id | int |
| code_snippet | string |
| language | string |
| review_text | string |
| quality_score | int |
| created_at | string |

---

## 🚀 API Endpoint

### Submit Code for Review

```http
POST /code/review
```

### Request

```json
{
  "code_snippet": "print('Hello World')",
  "language": "Python"
}
```

### Response

```json
{
  "id": 1,
  "review_text": "Code is correct and readable. Consider adding comments for larger projects.",
  "quality_score": 8,
  "created_at": "2026-06-13T15:30:00Z"
}
```

---

## 🛠 Tech Stack

- Python
- Flask / FastAPI
- SQLite / PostgreSQL
- OpenAI API
- REST APIs

---

## 🎯 Future Improvements

- User Authentication
- Review Dashboard
- GitHub Integration
- PDF Export
- Team Collaboration Features

---

## 👨‍💻 Author

**Zafir Ahmed**

---

⭐ If you like this project, consider giving it a star!
