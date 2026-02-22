# Stage, Commit and Push

Add all files to git stage, create a commit with an automatic message in English, and push to the remote repository.

## Instructions

1. **Stage all files**: Run `git add .` to add all modified, new, and deleted files to the staging area.

2. **Generate commit message**: 
   - If the user provided a message in their prompt, use it as the base and ensure it's in English (translate if necessary).
   - If no message was provided, run `git status` and `git diff --staged --name-only` to inspect the staged changes, then generate a clear commit message in English that describes the changes (e.g., "Add user authentication", "Fix login validation bug", "Update dependencies").

3. **Commit**: Run `git commit -m "your_generated_message"` with the generated or provided message.

4. **Push**: Run `git push` to push the commit to the remote repository.

If any step fails (e.g., nothing to commit, push rejected), report the error clearly and suggest next steps.
