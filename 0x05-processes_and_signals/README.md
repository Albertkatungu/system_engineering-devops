This project provides an introduction to Linux processes and signals, covering the basics of managing process lifecycles, monitoring running processes, and using signals to control process behavior. Through hands-on tasks, learners will practice identifying process IDs, using commands to manipulate processes, and handling signals to start, stop, and modify processes. By the end of this project, learners will have a strong foundation in process management and be able to control processes within the Linux command line.

Instructions
You can see the activity tasks, mentioned in these instructions, below. Once you have completed all the lessons, you should start working on them.
Complete the tasks one by one and follow the submission instructions below to submit your solution to the tasks.
How to Submit
1. Repository and Directory Setup

Ensure you have a GitHub account set up. If you are new to GitHub, use the GitHub website (https://github.com) to create your repository and upload files.
Create a new repository named system_engineering-devops.
Inside this repository, create a directory called 0x05-processes_and_signals where all your script files for this project will be stored.
2. Adding Files for Each Task

Each task requires a unique script file. Create each script in the 0x05-processes_and_signals directory, using the exact file names provided in each task description (e.g., 0-what-is-my-pid, 1-list_your_processes).
3. Submitting Your Project - Once all files are uploaded to the GitHub repository, verify that your directory structure and filenames match the requirements.

4. Using GitHub UI (Preferred Method)

You can easily upload files through GitHub’s web interface by clicking “Add file” > “Upload files” in your project directory.
For learners comfortable with the command line, feel free to use git commands to interact with GitHub.
Auto-Checking Process
At the end of the submission deadline, the auto-checker will review the tasks for correctness and award points. Ensure each script functions as expected, follows the naming conventions, and includes required permissions.

Important!
All your files must have this as the first line. This will enable the checker to execute your files.
 #!/usr/bin/env bash
The second line of all your Bash scripts should be a comment explaining what the sript script doing.

#!/usr/bin/env bash
# A Bash script that displays current time in 24-hour format
The next line should contain your response. You can leave a line before the code for neatness.

#!/usr/bin/env bash
# A Bash script that displays current time in 24-hour format

date +"%T"
