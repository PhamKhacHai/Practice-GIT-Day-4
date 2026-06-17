# RELEASE NOTE v1.0

## Project

RB Git Day 4 - Project Workflow & GitHub Collaboration

## Version

v1.0

## Release Date

2026-06-17

## Summary

This release includes the first version of the web demo project.
The project applies Git/GitHub workflow in a practical development environment, including Issue Management, Feature Branch Strategy, Pull Request, Code Review, QA Testing and Release Note.

The release contains the following main updates:

* Login Page
* User Profile Page
* Navigation Flow Documentation
* QA Test Report

---

## Features

### 1. Login Page

A basic login page was added to the web demo project.

**File added:**

```text
web-demo/login.html
```

**Main changes:**

* Added Login Page structure
* Added username input field
* Added password input field
* Added login button
* Added basic HTML layout for login screen

**Related branch:**

```text
feature/login-page
```

**Related Pull Request:**

```text
PR #5 - feat/login: create login page
```

---

### 2. User Profile Page

A basic user profile page was added to display user information.

**File added:**

```text
web-demo/profile.html
```

**Main changes:**

* Added User Profile Page structure
* Displayed user name
* Displayed user email
* Displayed user role
* Added basic HTML layout for profile screen

**Related branch:**

```text
feature/user-profile-page
```

**Related Pull Request:**

```text
PR #6 - feat/profile: create user profile page
```

---

## Bug Fixes

### 1. Navigation Bug

Navigation flow documentation was added to clarify the expected flow between the Login Page and User Profile Page.

**File added:**

```text
web-demo/navigation.md
```

**Main changes:**

* Added navigation flow documentation
* Described the flow from `login.html` to `profile.html`
* Documented expected navigation behavior
* Listed related files for the navigation flow

**Related branch:**

```text
fix/navigation-bug
```

**Related Pull Request:**

```text
PR #7 - fix/nav: document navigation flow
```

---

## QA Testing

Manual QA testing was completed for the release.

**Test report file:**

```text
TEST_REPORT.md
```

### Test Scope

The following items were tested:

* Login Page
* User Profile Page
* Navigation Flow

### Test Result Summary

| Test Area         | Result |
| ----------------- | ------ |
| Login Page        | Passed |
| User Profile Page | Passed |
| Navigation Flow   | Passed |

### Test Summary

| Total Test Cases | Passed | Failed | Blocked |
| ---------------- | ------ | ------ | ------- |
| 8                | 8      | 0      | 0       |

---

## Pull Requests Included

| Pull Request | Source Branch             | Target Branch | Description              |
| ------------ | ------------------------- | ------------- | ------------------------ |
| PR #5        | feature/login-page        | develop       | Create Login Page        |
| PR #6        | feature/user-profile-page | develop       | Create User Profile Page |
| PR #7        | fix/navigation-bug        | develop       | Document Navigation Flow |

---

## Issues Included

| Issue | Description              | Status    |
| ----- | ------------------------ | --------- |
| #1    | Create Login Page        | Completed |
| #2    | Create User Profile Page | Completed |
| #3    | Fix Navigation Bug       | Completed |

---

## Known Issues

No known issues in this release.

---

## Risk Assessment

This release has low risk because the changes mainly include static HTML pages and documentation.
No existing business logic or production system was modified.

---

## Release Status

Status: Ready for release

---

## Conclusion

Version v1.0 has completed the required development workflow, including feature implementation, pull request creation, code review, QA testing and release note preparation.

The release is ready to be merged from `develop` into `main` for final release.
