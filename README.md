                                                                 Git BASH
1. Check Git version
To check the Git version, run the following command:
- from the command prompt git version
- from git bash $ git –version
2. Check Credentials
To check if Git is configured on your local machine, you can use the following command in the Git console:
$ git config --list
This command will display the Git configuration settings that are currently set. If Git is properly configured, you
should see output similar to the following:
user.name=Your Name
user.email=your-email@example.com
The user.name and user.email settings indicate that Git has been configured with your name and email address,
which are important for identifying your commits.
If you don't see any output or the output does not include the user.name and user.email settings, it means that
Git is either not installed or not configured on your machine. In that case, you can follow the installation
instructions for your operating system and then configure Git by running the following commands:
$ git config --global user.name "Your Name"
$ git config --global user.email "your-email@example.com"
3. Clone GitHub repository
Since you already know how to create repositories on GitHub, go and create a new one.
