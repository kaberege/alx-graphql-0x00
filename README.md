# GraphQuest: Exploring and Implementing GraphQL

## 📚 Overview

This repository contains the GraphQL queries and results for the **GraphQuest: Exploring and Implementing GraphQL** project. The tasks focus on querying the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) to retrieve character and episode data using GraphQL syntax.

## 📁 Repository Structure

alx-graphql-0x00/
├── character/
│ ├── README.md
│ ├── character-id-1.graphql
│ ├── character-id-1-output.json
│ ├── character-id-2.graphql
│ ├── character-id-2-output.json
│ ├── character-id-3.graphql
│ ├── character-id-3-output.json
│ ├── character-id-4.graphql
│ ├── character-id-4-output.json
│ ├── characters-page-1.graphql
│ ├── characters-page-1-output.json
│ ├── characters-page-2.graphql
│ ├── characters-page-2-output.json
│ ├── characters-page-3.graphql
│ ├── characters-page-3-output.json
│ ├── characters-page-4.graphql
│ ├── characters-page-4-output.json
├── episode/
│ ├── README.md
│ ├── episode-id-1.graphql
│ ├── episode-id-1-output.json

---

## ✅ Tasks Summary

### Task 0: Query Specific Character by ID

- **Objective:** Use `character(id: ID!)` to retrieve details about characters.
- **Fields Queried:** `id`, `name`, `status`, `species`, `type`, `gender`
- **Files:**  
  - `character-id-1.graphql` → `character-id-1-output.json`  
  - `character-id-2.graphql` → `character-id-2-output.json`  
  - `character-id-3.graphql` → `character-id-3-output.json`  
  - `character-id-4.graphql` → `character-id-4-output.json`

---

### Task 1: Query Paginated List of Characters

- **Objective:** Use `characters(page: Int)` to fetch lists of characters by page.
- **Fields Queried:** `id`, `name`, `status`, `image`
- **Pages Covered:** 1 through 4
- **Files:**  
  - `characters-page-1.graphql` → `characters-page-1-output.json`  
  - `characters-page-2.graphql` → `characters-page-2-output.json`  
  - `characters-page-3.graphql` → `characters-page-3-output.json`  
  - `characters-page-4.graphql` → `characters-page-4-output.json`

---

### Task 2: Query Specific Episode by ID

- **Objective:** Use `episode(id: ID!)` to retrieve episode details.
- **Fields Queried:** `id`, `name`, `air_date`, `episode`
- **Files:**  
  - `episode-id-1.graphql` → `episode-id-1-output.json`

---

## 🔗 GraphQL Endpoint

All queries target the official [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).
