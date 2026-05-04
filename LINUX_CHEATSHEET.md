# 🐧 QA Linux Cheat Sheet

| Command | What it does | Why a QA needs it |
| :--- | :--- | :--- |
| `pwd` | Print Working Directory | Tells you exactly where you are in the server folders. |
| `ls -la` | List all files with details | Checks if files are hidden or what their permissions are. |
| `cd ..` | Move up one folder | Navigation (going back). |
| `mkdir` | Make Directory | Creating folders to organize test reports or logs. |
| `grep "Error"` | Search for "Error" | The fastest way to find a specific failure in a log file. |
| `tail -f file.log` | Follow file in real-time | **Crucial:** Watch errors appear while you click the app. |
| `head -n 20` | View first 20 lines | Checking the header/version of a file. |
| `chmod +x` | Make executable | Turning a text script into a runnable tool. |
| `sudo` | SuperUser Do | Running commands that require admin permissions. |
| `history` | Show past commands | Recalling a complex command you typed earlier. |
| `top` | Task Manager | Seeing if the app is freezing the CPU or using too much RAM. |
