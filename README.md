---
author:
- "By: Anthony Sasso"
date: 2022-12-11
title: Sasso_C\_Cpp_GenNetLib
---

# Introduction

Collection of generic networking libraries in C/C++ ideally simplifying
use and allowing quicker project builds.

# Getting Started

## Software Dependencies

1.  Ensure C17, Cxx20, CMake, Ninja, Clang, Doxygen are present on
    target machine for development and compilation.

2.  Docker desktop / docker instance exists on your target machine for
    using docker compose & docker functions.

3.  Have an active internet connection for pulling the server base
    images, etc during compose.

4.  Optionally have VSCode or some automation tool for using CMake \>
    Ninja-Multi-Config generation (please ensure to use the Multi-Config
    version for testing etc. **before** pushing back to your branch).

# Build & Test

1.  Download / Clone Target Branch (by default would recommend the
    latest one).

2.  Have Docker up / running.

3.  Run the appropriate CMake build for the target (Ninja-Multi-Config).

4.  Run **''docker-compose up -d''** to run the test server.

5.  Access at test output file.

# Contribute!

To Contribute to the project follow these rules:

-   First create an issue / feature request notifying any changes that
    are wanted.

-   Wait to hear the initial response / accepting of that issue before
    you begin coding.

-   Fork or Branch (dependent on scope, membership in core development
    team, etc.) the repo and code any necessary fixed to fulfill this
    new feature / fix the bug.

-   Issue a pull request back to the main repo with your latest released
    version and attach a text file or description within the pull
    request detailing your changes, additions, considerations with this
    pull request. In addition, follow the ''LatexToMarkdownNoted.md''
    within the ''.README'' Source folder to update the README listing
    any necessary changes, and have this as your final commit before the
    pull request.
