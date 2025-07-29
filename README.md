# Convex Development Agents

This repository contains a collection of Claude subagents to help with Convex development tasks.

## Overview

This repository provides a set of specialized subagents for Convex development:
- `convex-schema-agent` for database schema design and migrations
- `convex-api-model-agent` for queries, mutations, and actions
- `convex-frontend-agent` for client integration

Together these agents help with:
- Designing and implementing Convex backend systems
- Creating efficient database schemas with proper indexes
- Writing type-safe queries, mutations, and actions
- Implementing real-time features
- Reviewing existing Convex code
- Guiding migrations from other backends to Convex

## Directory Structure

```
.
├── .claude/
│   └── agents/
│       ├── convex-schema-agent.md     # Schema specialist
│       ├── convex-api-model-agent.md  # API and model specialist
│       └── convex-frontend-agent.md   # Frontend integration specialist
└── README.md
```

## Agent Configuration

Each subagent file describes a focused role for Convex development:
- Agent metadata (name, description, tools, color)
- Technical guidelines for Convex development
- Best practices and code review criteria
- Examples of when to use this agent

## Usage

Invoke the subagent that matches your task:
- Use **convex-schema-agent** for schema design or migrations
- Use **convex-api-model-agent** for implementing backend logic
- Use **convex-frontend-agent** when updating UI code that talks to Convex

## Key Features

- **Modern Syntax**: Uses the latest Convex function syntax with explicit validators
- **Type Safety**: Enforces proper TypeScript and validator usage
- **Performance**: Emphasizes efficient query patterns and proper indexing
- **Security**: Distinguishes between public and internal functions
- **Best Practices**: Follows established Convex patterns and conventions

## Technical Guidelines

The agent follows strict guidelines including:
- Always using indexes instead of filters in queries
- Proper function registration (query/mutation/action)
- Type-safe ID handling with `Id<'tableName'>`
- Efficient pagination for large datasets
- Proper error handling and edge case consideration

For detailed technical specifications, see the agent files under `.claude/agents/`.
