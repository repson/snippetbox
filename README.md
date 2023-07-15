# snippetbox

## Description

This application lets people paste and share snippets of text, abit like Pastebin or Github's Gists.

![snippetbox](./ui/static/img/screenshot.png)

## Prerequisites

* Go (v1.20)
* MySQLDB

## Run

`$ go run cmd/web/*`

## Features

### General

* Command-line flags
* Dependency injection

### UI

* User interface using HTML template composition
* Dynamic HTML templates
* Caching templates
* Processing forms
* Automatic form parsing

### HTTP

* HTTP status codes
* Serving static files
* Directory listing disabled
* Chaining HTTP handlers
* Stateful HTTP
* Session manager
* HTTPS connection
* HTTP/2 connections

### API

* REST API
* Isolated application routes
* Use of middleware
* Composable middleware chains
* Advanced routing

### Logging & Errors

* Centralized error handling
* Leveled logging
* Request logging
* Panic recovery
* Custom error handlers

### Database

* Database connection with MariaDB
* SQL injection prevention
* Use of transactions to execute multiple SQL statements in one atomic action
* Database connection pools
* Use of prepared statements

### Security

* Secure HTTP headers
* Security headers
* Validating form data
* TLS versions restricted
* Cipher suites restricted
* Connection timeouts
* Sign up
* Authentication
* Logout