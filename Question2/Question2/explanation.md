1. mkdir documents – Creates a directory for project-related files.
2. cd documents – Navigates into the newly created directory.
3. touch plan.txt – Creates an empty file named plan.txt.
4. echo "This is my project plan file." > plan.txt – Adds sample text to the file.
5. ls -l plan.txt – Shows permissions, owner, file size and details.
6. cp plan.txt plan_copy.txt – Creates a duplicate copy of the file.
7. mv documents project_documents – Renames the directory.
8. mkdir project_documents/archive – Creates an archive subfolder.
9. mv plan_copy.txt archive/ – Moves copied file to archive.
10. ls -R project_documents – Displays folder structure recursively.
11. readlink -f project_documents/archive/plan_copy.txt – Shows the absolute path of plan_copy.txt.
