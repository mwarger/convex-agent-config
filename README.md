# Convex Backend Development Agent

This repository contains a specialized Claude agent configuration for Convex backend development.

## Overview

The Convex agent is an expert system designed to help with:
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
│       └── convex-agent.md    # Convex backend architect agent configuration
└── README.md                   # This file
```

## Agent Configuration

The `convex-agent.md` file contains:
- Agent metadata (name, description, tools, color)
- Technical guidelines for Convex development
- Best practices and code review criteria
- Examples of when to use this agent

## Usage

This agent can be invoked when you need to:
- Design new Convex backend features
- Review Convex mutations, queries, or actions
- Structure database schemas for Convex applications
- Implement real-time functionality
- Migrate from other backend systems to Convex

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

For detailed technical specifications, see the full agent configuration in `.claude/agents/convex-agent.md`.