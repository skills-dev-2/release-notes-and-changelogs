# Step 2: GitHub Release Notes

GitHub Releases are a way to package and provide software to your users. They're built on Git tags but offer more features like release notes and binary attachments.

### 📦 Anatomy of a GITHUB Release

A well-crafted GitHub release includes:

- **Tag**: The semantic version tag for this release
- **Title**: A concise name (usually the version)
- **Description**: Release notes explaining what changed
- **Attachments**: Optional compiled binaries, documentation, or other files

### :keyboard: Task: Create a GitHub Release

1. Make a small change to your repository (e.g., add a README.md file or update an existing file)
2. Go to your repository's "Code" tab
3. Click on "Releases" in the right sidebar
4. Click "Create a new release"
5. Enter `v0.1.0` as your tag version
6. Target the main branch
7. Title your release "Initial Release"
8. Write release notes that include:
   - **What's New** section
   - **Bug Fixes** section (mention "none" if applicable)
   - **Breaking Changes** section (mention "none" if applicable)
9. Click "Publish release"

### 📝 Release Notes Best Practices

Good release notes:
- Group changes by type (features, fixes, breaking changes)
- Use bullet points for clarity
- Reference issue numbers when applicable
- Include upgrade instructions if needed
- Stay professional but personable

### 🏷️ Managing Releases

Some best practices for managing your releases:

- **Be Consistent**: Follow semantic versioning principles for all releases
- **Pre-releases**: Use tags like `v1.0.0-beta.1` for pre-release versions
- **Build Metadata**: Add build information with `+` (e.g., `v1.0.0+20130313144700`)
- **Version Control**: Never delete or move tags once published

### :keyboard: Task: Update Your Changelog

1. Update your CHANGELOG.md file to include information about the release you just created
2. Make sure the date matches your release date
3. Commit these changes to your repository
4. Go to the issue you created earlier and comment "release-created"

Once you've completed these steps, I'll guide you to the next part of the course.
