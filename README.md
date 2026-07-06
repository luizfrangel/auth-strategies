# Auth Strategies

_Authentication strategies implemented from scratch in TypeScript, one branch per strategy_

## About the project

This project implements different authentication patterns, one per branch.

- main: Base for strategies with user model, main http framework and project structure.
- feature/jwt-auth: JWT-based authentication (email + password).
- feature/google-oauth: authentication with Google OAuth.

## Decisions

The implementation will use DB with document orientation, because we need flexibility between the branches (features) and the relationships between models are not strong. For the JWT-based implementation: keep the user logged in (Refresh Token) and rrecover the user's password.

## Stack

TypeScript, Express, MongoDB

## Phase 1 (In Progress)

- Main branch structure
- JWT-based branch: register, login, refresh token, protected route and demo on Postman (production)

## Phase 2 (TODO)

- JWT: password recovery
- Google OAuth
- App Interface
- Demo with both branches in production
