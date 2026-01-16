Environment
Infrastructure: AWS EC2 Instance
Operating System: Linux.
Tools:Git, GitHub

Implementation Details
1. Configuration: Configured global user identity on the EC2 instance
2. Repository Management:Initialized a local repository and linked it to GitHub
3.Branching: Created a branch `br1` to practice isolated development
4. Merge Conflict Resolution:Encountered a conflict in `example.txt` while merging `br1` into `main`
   Manually resolved the conflict markers, staged the file, and committed the resolution.

Rollback Practice 
Used `git log` to identify a previous stable commit
Performed a `git reset --hard` to roll back the local repository to a previous state
Demonstrated history management by force-pushing the rolled-back state to GitHub.

