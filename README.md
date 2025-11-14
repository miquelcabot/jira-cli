# Jira CLI

A terminal-based Jira clone built in Rust for managing Epics and Stories.

## Overview

This project implements a command-line interface (CLI) version of Jira with core functionality for creating, reading, updating, and deleting (CRUD) Epics and Stories. It provides a practical way to learn Rust while building a real-world application.

## Features

- **Epic Management**: Create, view, update, and delete Epics
- **Story Management**: Create, view, update, and delete Stories linked to Epics
- **Persistent Storage**: Data saved to disk using JSON format
- **Interactive Navigation**: Terminal-based UI for easy navigation between pages

## Learning Objectives

This project is designed to help you learn and practice:
- Building CLI applications in Rust
- File I/O operations (reading & writing to disk)
- Using popular Rust crates (`serde`, `anyhow`, `itertools`, etc.)
- Writing testable and maintainable code
- Organizing code with Rust modules
- Working with an existing codebase

## Prerequisites

- Rust and Cargo installed (visit [rustup.rs](https://rustup.rs/))

## Installation

```bash
# Clone the repository
git clone <repository-url>
cd jira-cli

# Build the project
cargo build --release

# Run the application
cargo run
```

## Usage

Launch the CLI application:

```bash
cargo run
```

Navigate through the interface using the terminal prompts to:
- Create new Epics and Stories
- View existing Epics and their associated Stories
- Update Epic and Story details
- Delete Epics and Stories

## Development

### Running Tests

```bash
cargo test
```

### Building for Release

```bash
cargo build --release
```

The compiled binary will be available at `target/release/jira-cli`.
