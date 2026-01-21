# Collaboration Guide - Auracelle Sprint Suite

## How to Collaborate on GitHub

GitHub makes team collaboration easy! Here's how to work together on the Sprint Suite.

---

## For Repository Owners (You!)

### Adding Team Members

1. **Go to Your Repository**
   - Navigate to your Sprint Suite repository on GitHub

2. **Access Settings**
   - Click "Settings" (top right area of your repo)

3. **Add Collaborators**
   - Click "Collaborators" in the left sidebar
   - Click "Add people" button
   - Enter their GitHub username or email address
   - Click "Add [username] to this repository"

4. **They Get an Email**
   - They'll receive an invitation email
   - They must accept to get access
   - Once accepted, they can push changes directly!

### Setting Permissions

**Collaborator Roles:**
- **Write**: Can push changes directly (most common for teams)
- **Read**: Can only view and suggest changes via pull requests
- **Admin**: Full control (use carefully!)

---

## For Team Members

### Accepting an Invitation

1. Check your email for GitHub invitation
2. Click "Accept invitation"
3. You now have access to the repository!

### Making Changes (Easy Way)

**Option 1: Edit Directly on GitHub**
1. Go to the repository
2. Click on `index.html` (or any file)
3. Click the pencil icon (✏️ Edit)
4. Make your changes
5. Scroll down to "Commit changes"
6. Add a description like "Updated Sprint 45 details"
7. Click "Commit changes"
8. Changes go live in 1-2 minutes!

**Option 2: Upload New Version**
1. Go to repository main page
2. Click "Add file" → "Upload files"
3. Drag your updated file
4. Add commit message
5. Click "Commit changes"

---

## Best Practices for Teams

### Commit Messages
Write clear messages about what you changed:

✅ Good:
- "Added Sprint 110: NATO DIANA proposal prep"
- "Fixed typo in Mozart Sprint 23"
- "Updated daily log export format"

❌ Bad:
- "Update"
- "Changes"
- "asdf"

### Before Making Big Changes
1. Let team know via Issues or chat
2. Consider creating a branch for experiments
3. Test locally before pushing
4. Review changes one more time

### Communication
- **Use Issues** for discussions and feature requests
- **Use Commit Messages** to explain what and why
- **Use Pull Requests** for major changes that need review
- **Tag team members** with @username in discussions

---

## Common Workflows

### Daily Sprint Updates
1. Open the Sprint Suite in browser
2. Mark completed tasks
3. Add daily log entry
4. If you want to share progress:
   - Export as Markdown
   - Share file or create an Issue with update

### Adding New Sprints
1. Go to repository
2. Edit `index.html`
3. Find the `sprints` array in JavaScript
4. Add your new sprint following the existing format
5. Commit with message like "Added Sprint 110"

### Syncing Changes
If multiple people are working:
1. Before starting, click "Sync fork" or "Pull" to get latest
2. Make your changes
3. Commit and push
4. Others should sync before their changes

---

## Protecting Your Work

### Branch Protection (Optional)
For important projects, you can require:
1. Go to Settings → Branches
2. Add rule for "main" branch
3. Require pull request reviews
4. Require status checks

This prevents accidental overwrites!

### Reverting Changes
Made a mistake? No problem!
1. Go to repository
2. Click "Commits" (shows all changes)
3. Find the commit before the mistake
4. Click "< >" to browse that version
5. Can revert or copy old code back

---

## Real-World Team Scenarios

### Scenario 1: PhD Advisor Reviewing Progress
**Setup:**
1. Add advisor as collaborator (Read access)
2. They can view all sprints and progress
3. They can comment via Issues
4. You update based on feedback

### Scenario 2: Research Team Co-Development
**Setup:**
1. Add all team members (Write access)
2. Everyone tracks their own sprints
3. Use commit messages to communicate
4. Weekly sync meetings to review progress

### Scenario 3: Institutional Partner Input
**Setup:**
1. Add partner as collaborator (Write access)
2. They can add Mozart sprints for their needs
3. You coordinate via Issues
4. Both track respective deliverables

---

## Troubleshooting

### "Can't Push Changes"
- Check if you're added as collaborator
- Check if invitation was accepted
- Try refreshing browser

### "Merge Conflict"
- Happens when two people edit same section
- GitHub will show you both versions
- Choose which to keep or combine them
- Save and commit

### "Lost My Changes"
- Check commit history - it's all saved!
- Go to "Commits" and find your version
- Can always recover previous versions

---

## Export & Share Options

### For Presentations
1. Export daily log as Markdown
2. Show live Sprint Suite in meetings
3. Share GitHub Pages URL

### For Reports
1. Export as JSON for data analysis
2. Take screenshots of progress
3. Link to specific commits showing work

### For Publications
1. Cite the Sprint Suite tool
2. Include GitHub repository link
3. Export relevant sprint data
4. Archive version used (git tag)

---

## Security Notes

### What's Private
- Your local browser data (daily logs, checkmarks)
- Until you export, data stays on your machine

### What's Public (if Public Repo)
- The Sprint Suite tool itself
- Any commits and messages you write
- Issues and discussions

### What's Shared (if Private Repo)
- Only with people you add as collaborators
- Perfect for sensitive research projects

---

## Quick Reference

**Add Collaborator**: Settings → Collaborators → Add people  
**View Changes**: Click "Commits" to see history  
**Discuss**: Use "Issues" tab for conversations  
**Edit File**: Click file → Pencil icon → Make changes → Commit  
**Revert**: Commits → Find old version → Revert  
**Download**: Code → Download ZIP (for offline backup)

---

## Need Help?

- **GitHub Docs**: https://docs.github.com/en/github/collaborating-with-pull-requests
- **Team Questions**: Use Issues tab in your repository
- **Technical Support**: GitHub support or Auracelle contact

---

*Happy collaborating! Together we build better AI governance.* 🤝

**Pro Tip**: Start simple - just add one collaborator and try making a small change together. Once comfortable, expand from there!
