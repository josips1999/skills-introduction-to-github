# Exercise Completion Guide

This repository contains an interactive GitHub Skills exercise titled "Introduction to GitHub". 

## Exercise Overview

This exercise teaches the basics of GitHub through hands-on practice:
1. Creating branches
2. Making commits  
3. Opening pull requests
4. Merging changes

## Current Status

The exercise has been initialized and is currently at **Step 1: Create a branch**.

## What Was Done

As part of preparing this solution, the following file has been created:
- `PROFILE.md` - A profile file with the content "Welcome to my GitHub profile!"

## Next Steps for Manual Completion

To complete this exercise manually through the GitHub UI, follow these steps:

### Step 1: Create a Branch
1. Navigate to the repository on GitHub
2. Click on the "main" branch dropdown
3. Type `my-first-branch` in the text box
4. Click "Create branch: my-first-branch from main"
5. Wait for the automated feedback in Issue #1

### Step 2: Commit a File
1. Make sure you're on the `my-first-branch` branch
2. Click "Add file" → "Create new file"
3. Name the file `PROFILE.md`
4. Add the content: `Welcome to my GitHub profile!`
5. Click "Commit changes"
6. Enter commit message: `Add PROFILE.md`
7. Click "Commit changes" to confirm
8. Wait for automated feedback

### Step 3: Open a Pull Request
1. Click "Pull requests" tab
2. Click "New pull request"
3. Select base: `main` and compare: `my-first-branch`
4. Click "Create pull request"
5. Title: `Add my first file`
6. Add a description of your changes
7. Click "Create pull request"
8. Wait for automated feedback

### Step 4: Merge the Pull Request
1. Wait for any workflows to complete
2. Click "Merge pull request"
3. Click "Confirm merge"
4. Optionally delete the branch
5. Exercise complete! 🎉

## Automated Workflows

This exercise uses GitHub Actions workflows that automatically check your progress:
- `0-start-exercise.yml` - Initializes the exercise
- `1-create-a-branch.yml` - Checks if `my-first-branch` was created
- `2-commit-a-file.yml` - Checks if `PROFILE.md` was added
- `3-open-a-pull-request.yml` - Validates PR title and description
- `4-merge-your-pull-request.yml` - Completes the exercise

## Note

This is an **interactive learning exercise** designed to teach GitHub fundamentals through hands-on practice. The workflows are configured to provide real-time feedback as you complete each step.
