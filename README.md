# kkdevopsom-test

1. ls – List Files

Syntax:

ls [options]


Example:

ls -la


Use Case: View all files (including hidden) with details.

2. cd – Change Directory

Syntax:

cd <directory>


Example:

cd /var/log


Use Case: Navigate into log directory.

3. pwd – Present Working Directory

Syntax:

pwd


Use Case: Check your current directory path.

4. mkdir – Create Directory

Syntax:

mkdir <directory>


Example:

mkdir devops-project


Use Case: Create a new project directory.

5. rm – Remove Files/Directories

Syntax:

rm <file>
rm -r <directory>


Example:

rm -rf temp/


Use Case: Delete files or directories safely.

6. cp – Copy Files

Syntax:

cp <source> <destination>


Example:

cp app.conf /backup/


Use Case: Backup config files.

7. mv – Move/Rename Files

Syntax:

mv <source> <destination>


Example:

mv test.txt prod.txt


Use Case: Rename files or move between folders.

8. cat – View File Content

Syntax:

cat <file>


Example:

cat /etc/os-release


Use Case: Display file contents.

9. tail – View Last Lines

Syntax:

tail <file>
tail -f <file>


Example:

tail -f /var/log/messages


Use Case: Monitor logs in real-time.

10. head – View First Lines

Syntax:

head <file>


Example:

head /etc/passwd

11. grep – Search Text

Syntax:

grep <pattern> <file>


Example:

grep "ERROR" app.log


Use Case: Find error messages in logs.

12. find – Search Files

Syntax:

find <path> -name <filename>


Example:

find / -name nginx.conf

13. top – Monitor Processes

Syntax:

top


Use Case: Real-time CPU/memory monitoring.

14. htop – Advanced Process Viewer

Syntax:

htop


Use Case: Colorful, interactive process viewer.

15. ps – List Processes

Syntax:

ps aux


Example:

ps aux | grep nginx

16. kill – Terminate Process

Syntax:

kill <PID>
kill -9 <PID>


Use Case: Stop unresponsive processes.

17. systemctl – Manage Services

Syntax:

systemctl <action> <service>


Examples:

systemctl status nginx
systemctl restart docker

18. journalctl – Systemd Logs

Syntax:

journalctl -u <service>


Example:

journalctl -u docker

19. df – Disk Usage Overview

Syntax:

df -h


Use Case: Check available disk space.

20. du – Directory Disk Usage

Syntax:

du -sh <directory>


Example:

du -sh /var/log

21. free – Memory Usage

Syntax:

free -h


Use Case: Check RAM usage.

22. chmod – Change Permissions

Syntax:

chmod <permissions> <file>


Example:

chmod 755 script.sh

23. chown – Change Ownership

Syntax:

chown <user>:<group> <file>


Example:

chown root:root /etc/config

24. ssh – Remote Login

Syntax:

ssh user@host


Example:

ssh ec2-user@3.110.20.1

25. scp – Secure File Copy

Syntax:

scp <file> user@host:/path


Example:

scp backup.tar ubuntu@server:/tmp

26. tar – Archive/Extract

Syntax:

tar -cvf file.tar directory/
tar -xvf file.tar

27. wget – Download File

Syntax:

wget <url>

28. curl – Test APIs

Syntax:

curl <url>


Example:

curl -I http://localhost

29. crontab – Schedule Tasks

Syntax:

crontab -e


Example (backup at 2 AM):

0 2 * * * /backup/script.sh

30. env – Environment Variables

Syntax:

env


Use Case: Debug CI/CD environments.
