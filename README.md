# Introduction

**Visualizer** is a platform that helps customers to see their consumption and insigths about their data. It uses a RESTful API for all requests, including authentication.

1. Fork this project
2. Read the following sections: [_expectations_](./README.md#expectations) and [_features_](./README.md#features) for better understanding of this project.
3. Read the [backend](./backend/SPECS.md) and/or [frontend](./frontend/SPECS.md) specs
4. Send an email with:

```js
Subject: 
Your name - Seniority Level (Junior/Mid/Senior)

Body:
github.com/<username>/<project>
```

# Expectations

- Remember: Keep your codebases _simple_, yet _robust_.
- Code best pratices and principles.
- You MUST implement all the required features (see specs).
- You MUST provide a README that presents an overview of your implementation and explains how to run it locally.
- You SHOULD write tests.
- You SHOULD use library/framework that have at least 300 github stars and doesn't have a security issue.
- You SHOULD do your best to keep your implementation up to date.

Plus:
- Docker
- Docker-compose
- Deployment setup
- Frontend

# Features

General functionality:

- Authenticate users via JWT (signin, signup, logout)
- CRU- users (signup/users page - no deleting required)
- Dashboard / Insights page
- Import Process (MUST be separate from the API)

