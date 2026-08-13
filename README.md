# JacVimDojo

A gamified VIM practice simulator designed to build muscle memory and improve VIM proficiency through interactive, timed challenges.

## Overview

JacVimDojo is a web-based learning tool that makes practicing VIM commands engaging and fun. Whether you're a VIM beginner or looking to sharpen your skills, this simulator helps you develop the muscle memory needed to navigate and edit code efficiently.

## Features

- **19 Missions**: Progressive challenges ranging from basic navigation to advanced editing techniques
- **Timed Challenges**: Built-in timer adds urgency and gamification to make practice engaging
- **Muscle Memory Training**: Repeated, targeted exercises help internalize VIM command combinations
- **Interactive Feedback**: Real-time validation as you complete each mission

## Getting Started

1. Open `JacVimDojo.html` in your web browser
2. Start with Mission 1 and progress through the challenges
3. Complete each mission within the time limit to advance
4. Track your progress and improve your VIM skills

## What You'll Learn

- VIM navigation (h, j, k, l, word jumps, line jumps)
- Text editing (insert, append, delete, change, copy, paste)
- Search and replace operations
- Advanced editing patterns and combinations
- Efficient workflows for common coding tasks

## Best Practices

- **Practice Regularly**: Short, consistent practice sessions build better muscle memory than occasional long sessions
- **Focus on Accuracy**: Speed will come naturally once your movements are accurate
- **Repeat Missions**: Don't move to the next mission until you feel comfortable with the current one
- **Challenge Yourself**: Try to beat your previous completion times

## Tips for Success

- Start slow and focus on precision
- Use the keyboard only—no mouse clicking
- Review VIM help documentation (`:help`) if you get stuck
- Take breaks to avoid fatigue

## Deployment

The site is deployed to GitHub Pages at: https://zunit.github.io/vim-simulator/

### Making Changes

To update the simulator and deploy changes to the live site:

**Step 1: Make your changes**
```bash
# Edit index.html with your changes
```

**Step 2: Stage your changes**
```bash
git add index.html
```
Or stage all changes:
```bash
git add .
```

**Step 3: Commit with a descriptive message**
```bash
git commit -m "Description of your changes"
```

**Step 4: Push to main**
```bash
git push origin main
```

**Step 5: Wait for deployment**
- GitHub Pages automatically rebuilds and deploys when you push to `main`
- Deployment typically completes within 30-60 seconds
- Check the deployment status at: https://github.com/zunit/vim-simulator/deployments

**Step 6: Verify the changes**
- Visit https://zunit.github.io/vim-simulator/ in your browser
- Hard refresh (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows) to clear cache
- Test your changes to confirm they work as expected

### Using lazygit for Deployment

If you prefer to use lazygit in lazyvim:

1. Open lazygit: `:LazyGit`
2. Stage files: `Space` on files or `a` to stage all
3. Commit: `c` → type message → Enter
4. Push: `P` (shift+p)
5. Verify at the live URL

### Troubleshooting

- **Changes not appearing**: Clear your browser cache (hard refresh) or wait a few minutes for the deployment to complete
- **Check deployment status**: Visit https://github.com/zunit/vim-simulator/deployments to see if the build succeeded
- **Rollback changes**: Use `git revert <commit-hash>` to undo a specific commit and push the changes
