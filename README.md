# Filter with grep

<h2>Activity Overview</h2>

In this lab activity, you’ll use the grep command and piping to search for files and to return specific information from files.

<h2>Scenario</h2>

In this scenario, you need to obtain information contained in server log and user data files. You also need to find files with specific names.

Here’s how you’ll do this: First, you’ll navigate to the logs directory and return the error messages in the server_logs.txt file. Next, you’ll navigate to the users directory and search for files that contain a specific string in their names. Finally, you’ll search for information contained in user files.

<h2>Task 1. Search for error messages in a log file</h2>

In this task, you must navigate to the /home/analyst/logs directory and report on the error messages in the server_logs.txt file. You’ll do this by using grep to search the file and output only the entries that are for errors.

1. Navigate to the /home/analyst/logs directory.

![image](https://github.com/user-attachments/assets/dfd8f237-9677-4b23-9912-775c69ea6e5f)

2. Use grep to filter the server_logs.txt file, and return all lines containing the text string error.

![image](https://github.com/user-attachments/assets/a1d8390d-b21c-4da2-9d60-215714f8413d)

<h2>Task 2. Find files containing specific strings</h2>

In this task, you must navigate to the /home/analyst/reports/users directory and use the correct Linux commands and arguments to search for user data files that contain a specific string in their names.

1. Navigate to the /home/analyst/reports/users directory.

![image](https://github.com/user-attachments/assets/f18ceb7f-c387-431a-8b90-2aa5497bedcf)

2. Using the pipe character (|), pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names.

![image](https://github.com/user-attachments/assets/3fd7ac65-78c5-4f6e-bbe0-a9acb6e0d7ed)

3. List the files that contain the word access in their names.

![image](https://github.com/user-attachments/assets/25e69202-4c66-41d5-8247-560ec7633d52)

<h2>Task 3. Search more file contents</h2>

In this task, you must search for information contained in user files and report on users that were added and deleted from the system.

1. Display the files in the /home/analyst/reports/users directory.

![image](https://github.com/user-attachments/assets/f77960be-4175-44c3-8c22-a6de130bf44d)

2. Search the Q2_deleted_users.txt file for the username jhill

![image](https://github.com/user-attachments/assets/1cc0a1bc-4366-4939-b6e8-743a176fbb11)

3. Search the Q4_added_users.txt file to list the users who were added to the Human Resources department.

![image](https://github.com/user-attachments/assets/a40feeed-261b-4aed-a520-19a92cafaa93)
