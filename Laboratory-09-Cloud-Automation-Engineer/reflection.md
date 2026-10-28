# Mission 9 – Reflection

Completing this Cloud Automation Engineer mission helped me understand why automation is important in cloud computing. When managing hundreds of cloud servers, performing tasks manually can take a lot of time and may lead to human errors. Automation allows administrators to execute repetitive tasks consistently, such as creating backups, checking files, and scheduling maintenance.

However, automation also has potential dangers. If a script contains a destructive command or an incorrect file path, it may delete or damage important data. If that script runs automatically across 1,000 servers, the damage could affect many systems before anyone notices. Because of this, scripts should be reviewed and tested in a safe environment before they are used in production. Backups, appropriate permissions, and monitoring are also important safeguards.

Writing a Bash script was different from creating a Docker Compose YAML file in Mission 6. Bash scripts contain commands that execute tasks step by step, while Docker Compose YAML describes how containers and their services should be configured. In this mission, I used Bash variables, the `tar` command, and `chmod` to create and execute a backup routine. I then used Cron to schedule the script for 2:00 AM every day.

Looking back at Missions 1 through 9, I can see how my understanding of cloud computing has developed. I learned about infrastructure, cloud platforms, application deployment, data, operations, security, and automation. These activities showed me that cloud computing involves more than creating servers; it also requires maintaining, protecting, and managing resources efficiently.

The role I enjoyed most was the Cloud Automation Engineer because I was able to create a script that performs a task automatically. This experience helped me understand how automation can reduce repetitive work and improve consistency. Overall, this mission strengthened my Linux command-line skills and taught me to test scripts carefully before scheduling them for automatic execution.
