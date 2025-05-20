# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This repository contains GitHub Actions and other default community health files for the organization. It includes reusable GitHub Actions for deploying applications using Kamal (a deployment tool built on top of Docker), managing GitHub deployment statuses, and handling review environments for pull requests.

## Key Components

1. **Kamal Deployment Actions**: 
   - `setup-kamal`: Sets up Ruby and installs the Kamal gem
   - `deploy-review`: Deploys review apps for pull requests 
   - `deploy-production`: Deploys to production environments
   - `cleanup-review`: Removes review apps when PRs are closed

2. **GitHub Deployment Status Actions**:
   - `github-review-deployment`: Creates and updates deployment statuses for review apps
   - `github-production-deployment`: Manages production deployment statuses
   - `github-cleanup-deployment`: Marks deployments as inactive and adds cleanup comments

## Development Workflow

Based on the repository's PR template and documentation:

1. Create branches from GitHub issues/tickets
2. Follow a linear git history (rebase over merging)
3. Fill in the PR template with:
   - Background information
   - Key changes
   - Images if applicable
   - Risk assessment
   - Next steps

## Coding Standards

As described in the profile README:

1. **Naming Conventions**:
   - Use camelCase and PascalCase in TypeScript
   - Use snake_case in Python
   - For denominations, suffix the variable (e.g., `textAreaPx` or `timeoutLengthMs`)
   - Prefer longer, descriptive variable names over shorter, ambiguous ones

2. **Communication**:
   - Over-communicate rather than under-communicate
   - Consider using ADRs (Architecture Decision Records) for big features
   - Ship small end-to-end subsets to reduce uncertainty

3. **PR Reviews**:
   - Prioritize reviewing code over writing code
   - Unblock other developers and help ship code

4. **Branch & Commit Guidelines**:
   - Create branches off GitHub issues/tickets
   - Write detailed commit messages, PR descriptions, and documentation
   - Maintain a linear git history (rebase over merging)
   - Follow the PR template

## Kamal Commands

When working with Kamal deployments:

1. **Setup Kamal**: `gem install kamal`
2. **Deploy with Kamal**: `kamal deploy --config-file=<config-file> --verbose`
3. **Remove a Kamal deployment**: `kamal remove --config-file=<config-file> --verbose`

## Team Culture

1. Blameless - focus on improving systems rather than blaming individuals
2. Help bring things to life and keep each other accountable
3. Constantly do demos and ship fast
4. Follow guidelines to work effectively as a team
5. Take responsibility for keeping Kanban up to date
6. Communicate proactively, especially before starting big features