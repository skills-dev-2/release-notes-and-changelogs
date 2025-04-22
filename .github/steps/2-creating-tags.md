## Step 2: Creating Git Tags

Git tags allow you to mark specific points in your repository's history as important. They're perfect for marking version releases.

### :keyboard: Task: Create Your First Git Tag

You can create tags through the GitHub interface or using Git commands.

#### Using GitHub Web Interface:

1. Navigate to your repository's "Code" tab
2. Click on "Releases" in the right sidebar
3. Click "Create a new release"
4. Enter `v0.1.0` as your tag version
5. Target the main branch
6. Title your release "Initial Release"
7. Add a description: "This is the first release of our project."
8. Click "Publish release"

#### Using Git Command Line (Alternative Method):

```bash
git tag -a v0.1.0 -m "Initial Release"
git push origin v0.1.0
```

### 🔖 Tag Naming Conventions

Best practices for tag names:

- Prefix with `v` (e.g., `v1.0.0`)
- Use semantic versioning format
- Avoid spaces or special characters
- Be consistent across releases

### :keyboard: Task: Make Changes for New Version

1. Edit the `app.js` file again
2. Add a simple function at the end:
```javascript
function newFeature() {
  console.log("This is a new feature!");
}
```
3. Update the version comment at the top to `// Version 0.2.0 - Added new feature`
4. Commit your changes to a new branch
5. Comment "tags-created" on this PR when complete
