# Rick and Morty GraphQL API Explorer

A multi-phase learning project that teaches GraphQL fundamentals and how to integrate GraphQL into a modern TypeScript + React application using Next.js, Apollo Client, and Tailwind CSS. The project uses the Rick and Morty GraphQL API as the data source.

## Table of Contents
- Project overview
- Learning objectives
- Key concepts
- Tools & libraries
- Project layout
- Getting started
- Real-world use cases

## Project overview
This repository is split into progressive directories (alx-graphql-0x00 to alx-graphql-0x02), each increasing in complexity:

- Level 0: Core GraphQL query writing and understanding.
- Level 1: Frontend integration with Next.js, Apollo Client, and TypeScript.
- Level 2: Enhanced UI, state management, pagination, and best practices.

## Learning objectives

### Level 0 — GraphQL fundamentals
- Write precise GraphQL queries to request only necessary fields.
- Use arguments (e.g., id, page) to filter and paginate results.
- Distinguish single-item queries from paginated list queries.

### Levels 1 & 2 — Frontend integration
- Set up a Next.js app with TypeScript, Apollo Client, and Tailwind CSS.
- Configure Apollo Client and provide it via ApolloProvider.
- Use useQuery to fetch data inside React components.
- Manage component state (pagination, refetching) and structure app code (queries, types, components).

## Key concepts
- GraphQL query language: request flexible, specific data from a single endpoint.
- Schema & types: entities like Character, Episode, and Info define available fields.
- Arguments & pagination: use arguments to filter results and Info for navigation (pages, next, prev).
- Apollo Client: caching, loading & error states, and local/remote state management.
- TypeScript: static typing for safer code and better developer tooling.

## Tools & libraries
- Node.js (runtime)
- Next.js (React framework)
- TypeScript
- Apollo Client
- graphql (core library)
- Tailwind CSS (styling)
- ESLint (linting)
- API: https://rickandmortyapi.com/graphql

## Project layout (example)
- alx-graphql-0x00/ — GraphQL queries and exercises
- alx-graphql-0x01/ — Basic Next.js + Apollo integration
- alx-graphql-0x02/ — Full app with pagination, types, and components
- README.md — Project overview and instructions

## Getting started
1. Install dependencies:
    - npm install
    - or yarn
2. Run the development server:
    - npm run dev
    - or yarn dev
3. Browse the app at http://localhost:3000 and explore queries against the Rick and Morty API.

## Real-world use cases
The skills from this project translate to many applications:
- E-commerce catalogs (product by id, paginated lists)
- Blogs or CMS (posts and paginated archives)
- Social feeds (paginated posts and user lists)
- Data dashboards (filtered, paginated views of complex datasets)

The progression from simple query files to a typed frontend demonstrates a professional workflow: efficient queries, clear separation of concerns, type safety, and a scalable app structure.