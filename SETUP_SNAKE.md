# Setup Instructions for Snake Game

## Steps to Enable Snake Animation:

1. **Create GitHub Repository**
   - Go to https://github.com/new
   - Repository name: `KamranBaig1122` (MUST match your username exactly)
   - Make it PUBLIC
   - Click "Create repository"

2. **Push Your Files**
   ```bash
   cd c:\Users\Kamran\Desktop\profile
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/KamranBaig1122/KamranBaig1122.git
   git push -u origin main
   ```

3. **Enable GitHub Actions**
   - Go to your repo: https://github.com/KamranBaig1122/KamranBaig1122
   - Click "Actions" tab
   - Click "I understand my workflows, go ahead and enable them"
   - Click on "Generate Snake Animation" workflow
   - Click "Run workflow" > "Run workflow"

4. **Wait 5 Minutes**
   - The action will generate the snake SVG files
   - Refresh your profile to see the animated snake!

## Alternative: Remove Snake Section

If you don't want to wait, remove these lines from README.md:

```markdown
## 🐍 Contribution Snake Game

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KamranBaig1122/KamranBaig1122/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KamranBaig1122/KamranBaig1122/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/KamranBaig1122/KamranBaig1122/output/github-contribution-grid-snake.svg">
  </picture>
</div>
```
