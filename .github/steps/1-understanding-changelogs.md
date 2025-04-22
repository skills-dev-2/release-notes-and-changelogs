# Step 1: Understanding Changelogs

Changelogs and release notes are essential tools for communicating changes to users of your software. They help users understand what has changed between versions, which is crucial for making upgrade decisions and finding new features.

## 📝 What is a Changelog?

A changelog is a file which contains a curated, chronologically ordered list of notable changes for each version of a project. A well-structured changelog makes it easier for users and contributors to see precisely what changes have been made between each release of the project.

## 📝 The Keep a Changelog Format

Many projects follow the format defined at [keepachangelog.com](https://keepachangelog.com/), which includes these principles:

- Changelogs are for humans, not machines
- There should be an entry for every version
- The same types of changes should be grouped
- Versions and sections should be linkable
- The latest version comes first
- The release date of each version is displayed

## 📝 Standard Sections

A standard changelog typically groups changes into these categories:

- **Added** for new features
- **Changed** for changes in existing functionality
- **Deprecated** for soon-to-be removed features
- **Removed** for now removed features
- **Fixed** for any bug fixes
- **Security** for vulnerability fixes

## :keyboard: Task: Get Started

Let's begin by setting up our learning environment:

1. Navigate to the Issues tab in your repository
2. Create a new issue titled "Starting my changelog journey"

## :keyboard: Task: Create Your First CHANGELOG.md

After crearting your issue:

1. Create a new file named `CHANGELOG.md` in the root of your repository
2. Add the following content to your file:

```markdown
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Initial project setup
- Basic functionality

## [0.1.0] - YYYY-MM-DD
### Added
- First release
- Feature A
- Feature B

[Unreleased]: https://github.com/username/repository/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/username/repository/releases/tag/v0.1.0
```

3. Replace `YYYY-MM-DD` with today's date
4. Replace `username/repository` with your actual GitHub username and repository name
5. Commit this file to your repository
6. Go to the issue you created earlier and comment "changelog-created"

Once you've completed these steps, I'll guide you to the next part of the course.
