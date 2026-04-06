
# Lab 01: Users, Groups, and Permissions

## Overview
This lab focuses on basic Linux access control through users, groups, and file permissions. These are foundational concepts for both administration and security.

## Objective
To understand how Linux controls access to files and commands, and why proper permission management matters for security.

## Topics Covered
- users
- groups
- file ownership
- read, write, and execute permissions
- least privilege

## Basic Concepts

### Users
A user account represents an identity on the system.

### Groups
Groups are used to organize users and apply shared permissions.

### Permissions
Linux permissions define who can:
- read
- write
- execute

Permissions are usually viewed for:
- owner
- group
- others

## Why this matters in security
Permissions directly affect attack surface and misuse risk. Poor permissions can expose sensitive files, allow unauthorized changes, or make privilege escalation easier.

## Example commands
```bash
whoami
id
ls -l
chmod
chown
groups
