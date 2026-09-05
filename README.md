DecodeLabs DevOps Internship --- Project 1

Linux & Command Line Basics 🐧

Batch: 2026
Organization: DecodeLabs
Project: 1 --- Linux & Command Line Basics

📌 Project Overview

This project is the foundation phase of the DecodeLabs DevOps
internship. The objective is to build practical Linux command-line
skills required in DevOps environments.

The project focuses on:

Navigating the Linux filesystem

Creating and managing directories and files

Reading and monitoring files from the terminal

Understanding the Linux directory structure

Practicing basic permissions and ownership concepts

Building a small application-style directory structure from the
command line

The DecodeLabs project guide identifies file and directory
operations, basic commands such as ls, cd, mkdir, rm, and
cat, and understanding the Linux directory structure as key
requirements.

🎯 Objectives

By completing this project, I practiced:

Linux terminal navigation

Working with absolute and relative paths

Creating nested directories

Creating, reading, copying, moving, and removing files

Listing files with useful options

Viewing files using cat, less, head, and tail

Monitoring a log file using tail -f

Inspecting file permissions with ls -l

Understanding basic Linux ownership and permission concepts

Verifying the final filesystem structure

🛠️ Commands Practiced

1. Navigation

pwd
ls
ls -l
ls -a
ls -la
cd /path/to/directory
cd ..
cd ~

2. Directory Operations

mkdir app
mkdir -p app/src/main
ls -R app

3. File Creation

touch index.html
touch /app/config.conf

4. Writing File Content

echo "Started" > /app/logs/server.log

5. Reading and Monitoring Files

cat /app/config.conf
less /app/logs/server.log
head /app/logs/server.log
tail /app/logs/server.log
tail -f /app/logs/server.log

Press Ctrl+C to stop tail -f.

6. Copy and Move

cp source destination
mv old new
mv /app/logs/server.log /app/logs/server.bak

7. Delete

Use deletion carefully:

rm -i filename

For directories/files recursively:

rm -rf directory

⚠️ Always verify your location with pwd and check the target with
ls before using destructive commands.

8. Permissions and Ownership --- Practice

ls -l
chmod 754 filename
chown user:group filename

The permission pattern -rwxr-xr-- corresponds to 754: - Owner:
rwx - Group: r-x - Others: r--

🚀 Project Mission

The main hands-on exercise is to create and verify the following
application-style structure.

Step 1 --- Create the directory

mkdir -p /app/logs

Step 2 --- Create the configuration file

touch /app/config.conf

Step 3 --- Create the log file with initial content

echo "Started" > /app/logs/server.log

Step 4 --- Verify the structure

pwd
ls -R /app

Step 5 --- Create a backup

mv /app/logs/server.log /app/logs/server.bak

Step 6 --- Audit permissions

ls -l /app/config.conf

📂 Expected Structure

After completing the mission, the important structure should look
similar to:

/app/
├── config.conf
└── logs/
    └── server.bak

🔎 Linux Filesystem Concepts

The project guide introduces the Linux filesystem hierarchy, including:

/
├── bin
├── boot
├── dev
├── etc
├── home
├── root
├── tmp
├── usr
└── var

Some important directories:

Directory   Purpose

/         Root of the Linux filesystem
/home     User data/home directories
/root     Root user's home directory
/etc      System-wide configuration
/var      Variable data and logs
/tmp      Temporary files
/bin      Essential command binaries
/sbin     System/administrative binaries
/usr      User-space programs and data

🔐 Safety Practices

Linux commands can directly modify the system. Before destructive
operations:

pwd
ls

For safer deletion:

rm -i filename

Avoid using rm -rf on important system paths unless you completely
understand the target.

📸 Evidence / Screenshots

The following screenshots should be included as project evidence:

Screenshot 1 --- Current location and basic listing

Show:

pwd
ls -la

Screenshot 2 --- Directory creation

Show:

mkdir -p /app/logs
ls -R /app

Screenshot 3 --- Configuration file

Show:

touch /app/config.conf
ls -l /app/config.conf

Screenshot 4 --- Log creation

Show:

echo "Started" > /app/logs/server.log
cat /app/logs/server.log

Screenshot 5 --- Final verification

Show:

pwd
ls -R /app

Screenshot 6 --- Backup and audit

Show:

mv /app/logs/server.log /app/logs/server.bak
ls -l /app/config.conf /app/logs/server.bak

Optional Screenshot 7 --- Permissions practice

Show:

ls -l
chmod 754 filename
ls -l filename

🧪 Practice Checklist

pwd

ls

ls -l

ls -a

cd

cd ..

cd ~

mkdir

mkdir -p

touch

cat

less

head

tail

tail -f

cp

mv

rm -i

ls -R

ls -l

Basic chmod practice

Basic chown practice

💡 Key Learning

The most important lesson from this project is to become comfortable
operating Linux through the command line rather than relying on a
graphical interface.

A good DevOps workflow requires being able to:

Navigate → Create → Inspect → Modify → Verify → Monitor

The project also emphasizes precision, visibility, safety, and a
command-line mindset.

🏁 Conclusion

DecodeLabs Project 1 provided hands-on practice with Linux filesystem
navigation and command-line operations. I created and managed
directories and files, inspected file contents and permissions,
practiced safe file operations, and verified the final application-style
directory structure.

This project establishes the Linux foundation needed for later DevOps
work such as automation, CI/CD, containers, cloud infrastructure, and
system administration.
