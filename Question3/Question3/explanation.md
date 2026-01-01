## Question 3 – Command Explanations

1. echo "..." > sample_data.txt – Creates file with sample content.
2. ln sample_data.txt sample_hard.txt – Creates a hard link (shares same inode with original file).
3. ln -s sample_data.txt sample_soft.txt – Creates symbolic/soft link (different inode, pointer to file).
4. ls -i – Shows inode numbers of files.
5. Hard link and original share same inode because both reference same data.
6. ls -l sample_data.txt – Displays detailed file info.
7. du -h ~ – Shows disk usage of home directory in human readable form.
8. du -ah ~ | grep -v "/$" – Displays size of each file clearly.
9. rm sample_soft.txt – Deletes only soft link, original file remains unchanged.
10. du -sh & df -h – du shows directory size usage, df shows filesystem disk space usage.
