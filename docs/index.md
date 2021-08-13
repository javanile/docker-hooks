# Docker Hooks

Learn how to use pre-commit hooks, post-commit hooks, post-receive hooks, and more. | 

Matthew Hudson 

Git Hooks Open source on GitHub. 

Made with by Matthew Hudson What are Git hooks? 

Git hooks are scripts that Git executes before or after events such as: commit, push, and receive. 

Git hooks are a built-in feature - no need to download anything. 
Git hooks are run locally. 
These hook scripts are only limited by a developer's imagination. 
Some example hook scripts include: pre-commit: Check the commit message for spelling errors. 
pre-receive: Enforce project coding standards. 
post-commit: Email/SMS team members of a new commit. 
post-receive: Push the code to production. 
How do git hooks work? Every Git repository has a .git/hooks folder with a script for each hook you can bind to. 
You're free to change or update these scripts as necessary, and Git will execute them when those events occur. 
Here's a full list of hooks you can attach scripts to: 
applypatch-msg pre-applypatch post-applypatch pre-commit prepare-commit-msg
commit-msg post-commit pre-rebase post-checkout post-merge pre-receive update
post-receive post-update pre-auto-gc post-rewrite pre-push 

Why should I care? Fair question! Git hooks can greatly increase your productivity as a developer. 
For example, being able to push to your staging or production environment without ever leaving Git is just plain awesome. 
Update your code, make a commit and push, and your code can be running in any environment you specify. 
No need to mess with ssh or ftp. How do I implement Git hooks?
The short and easy: Overwrite (or create) one of the scripts in .git/hooks and make it executable. 
Reading Deploying websites with a Git hook The missing Git hooks documentation Git Hooks (Part I): 

The Basics Git Hooks (Part II): Implementing Git Hooks using Python Tips for using Git pre commit hook 
Use a bootstrap shell script to use Git Hooks in Mac with PowerShell and with IntelliJ Using direnv to Automatically Manage Git Hooks Projects overcommit - 
A well-maintained, up-to-date, flexible Git hook manager. 
Lolcommits - Takes a snapshot with your webcam every time you git commit code, and archives a lolcat style image with it. 
podmena - Enhance your commit messages adding random emoji to it. 
pre-commit - A framework for managing and maintaining multi-language pre-commit hooks. Hooks is a command line git hook management tool.
Git Build Hook Maven Plugin - A maven plugin for managing client side (local) git configuration and installing hooks for those working on your project.
Git::Hooks - A framework for implementing Git (and Gerrit) hooks. git-pre-commit-hook - Hook that blocks bad commits. Useful for Python-development. 
App::GitHooks - A modular and easy to configure git hooks framework, supporting many plugins. Jig - A pre-commit hook on steroids GitPHPHooks - 
Write your hooks in PHP, manage and organize them on a task and project level. Has an additional Hooks library on GitHub Grunt GitHooks - Setup, 
manage and update your hooks with Grunt. Can be used with all languages, supports templates. git-hooks - Hook manager. node-git-hooks - Automated,
cross-platform, deployment-friendly Git hooks installation. Husky - Git hooks for Node.js, manage your hooks from your package.json. git-hooks-php - 
Git hooks for PHP based projects. commandbox-githooks - Git hooks for CommandBox CFML based projects. Autohook - 
A very, very small Git hook manager with focus on automation. autohooks - A library for managing and writing git hooks in Python. hooks4git - A simple,
flexible and language agnostic git hook management approach. Githooks - Auto-install Git hook, that supports hooks in any language checked into Git and 
also shared repos. Awesome Git Hooks - A collection of awesome Git Hooks ghooks - Simple git hooks for Javascript. Manage your hooks via package.json.
ghooks.cr - Simple git hooks for Crystal. Keep your hooks in a versioned ".githooks/" directory ghooks.gradle - Simple git hooks for Gradle. 
Keep your hooks in a versioned ".githooks/" directory Lefthook - The fastest polyglot Git hooks manager Git Hooks List - List of Git hooks. .githooker - 
Eases setup, maintenance, handling of git-hooks across teams/projects for virtually all languages + common git-hook-ish tasks as declarative configuration
inside your repo! GJira - Automatically add Jira task ID and story ID to the body of the commit message
