# Done-ish Testing Repository

This repository contains testing artifacts and examples created to validate the **Done-ish productivity application**.

Done-ish is an Android application built using **Kotlin and Jetpack Compose** that focuses on reducing task paralysis by encouraging users to complete small, achievable actions.

The purpose of this repository is to demonstrate how testing activities can be organized for a mobile application, including planning, test case design, defect documentation, and automation exploration.

---

# Testing Objectives

Testing efforts for Done-ish focus on validating the following areas:

- Core user workflows
- Task tracking functionality
- Timer behavior
- UI interaction logic
- Data persistence
- Error handling
- Application stability across user actions

---

# Repository Structure

## test-strategy
Documents outlining the testing approach used for the Done-ish application.

Topics include:

- testing scope
- risk areas
- entry and exit criteria
- overall testing approach

---

## functional-testing
Manual test cases validating key user workflows such as:

- creating tasks
- starting micro-commit timers
- logging completed actions
- navigating between screens

---

## regression-testing
Regression test scenarios used to ensure core features continue to work after updates.

Example focus areas:

- timer functionality
- task completion logging
- UI navigation behavior
- user interaction flows

---

## integration-testing
Scenarios that validate how different components of the application interact.

Examples include:

- timer logic interacting with task tracking
- navigation behavior between screens
- state updates across user actions

---

## automation-testing
Exploration of potential automation approaches for repetitive UI workflows.

Focus areas include:

- validating navigation flows
- verifying timer behavior
- confirming UI state changes

Automation examples reference tools such as:

- Selenium
- UI automation concepts

---

## defect-management
Sample defect reports demonstrating how issues would be documented during testing.

Examples include:

- UI interaction issues
- timer inconsistencies
- navigation errors
- data persistence problems

---

# Technologies Referenced

- Kotlin
- Jetpack Compose
- Selenium
- Git

---

# Purpose

This repository demonstrates how testing can be structured for a real application by documenting test planning, execution scenarios, and defect reporting.

It serves as a practical example of applying software testing concepts to the **Done-ish application**.
