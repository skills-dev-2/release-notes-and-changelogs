## Step 3: Creating GitHub Releases

GitHub Releases are a way to package and provide software to your users. They're built on Git tags but offer more features like release notes and binary attachments.

### 📦 Anatomy of a Good Release

A well-crafted GitHub release includes:

- **Tag**: The semantic version tag for this release
- **Title**: A concise name (usually the version)
- **Description**: Release notes explaining what changed
- **Attachments**: Optional compiled binaries, documentation, or other files

### :keyboard: Task: Create Your First Full Release

1. Navigate to your repository's "Code" tab
2. Click on "Releases" in the right sidebar
3. Click "Create a new release" (or "Draft a new release")
4. Enter `v0.2.0` as your tag version
5. Target the main branch
6. Title your release "First Feature Release"
7. Write release notes that include:
   - **What's New** section
   - **Bug Fixes** section (mention "none" if applicable)
   - **Breaking Changes** section (mention "none" if applicable)
8. Click "Publish release"

### 📝 Release Notes Best Practices

Good release notes:
- Group changes by type (features, fixes, breaking changes)
- Use bullet points for clarity
- Reference issue numbers when applicable
- Include upgrade instructions if needed
- Stay professional but personable

### 🏷️ Managing Tags and Releases

Some best practices for managing your versioning workflow:

- **Be Consistent**: Follow semantic versioning principles for all releases
- **Pre-releases**: Use tags like `v1.0.0-beta.1` for pre-release versions
- **Build Metadata**: Add build information with `+` (e.g., `v1.0.0+20130313144700`)
- **Version Control**: Never delete or move tags once published
- **Automate**: Consider setting up CI/CD workflows to create releases automatically

### :keyboard: Task: Make a Bug Fix Change

1. Edit the `app.js` file again
2. Fix a "bug" in your new feature function:
```javascript
function newFeature() {
  // Fixed logging format
  console.log("New feature working correctly!");
}
```
3. Update the version comment to `// Version 0.2.1 - Bug fix for new feature`
4. Commit your changes to a new branch
5. Comment "release-mastered" on this PR when complete
