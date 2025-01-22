# k6 - Performance Testing with k6

This repository provides a basic example of how to install and run performance tests using [k6](https://k6.io/), an open-source tool for load and performance testing.

## Table of Contents

1. [Overview](#overview)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Running Tests](#running-tests)

---

## Overview

k6 is a powerful tool for load testing web applications, allowing you to simulate multiple users accessing an application simultaneously, measure performance, and identify bottlenecks.

---

## Prerequisites

- [k6](https://k6.io/docs/getting-started/installation/)
- (Optional) [Node.js](https://nodejs.org/) if you want to integrate with custom scripts.

---

## Installation

1. **Install k6**:

   - **Linux**: `sudo apt install k6`
   - **macOS**: `brew install k6`
   - **Windows**: Download the installer [here](https://k6.io/docs/getting-started/installation/).

2. **Clone the Repository**:

   ```bash
   git clone https://github.com/YOUR_USER/k6-performance-tests.git
   cd k6-performance-tests

## Running Tests

The repository contains the script `testScripts/scenarios(0).js`, which performs a simple HTTP GET request.

To run the test:

```bash
k6 run scripts/scenarios(0).js

