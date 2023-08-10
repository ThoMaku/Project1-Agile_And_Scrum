# CMPG-323-Overview-35804068.
1. The CMPG 323 Overview-35804068 repository will be created and used for Project 1.
2. CMPG 323 Project 2-35804068 repository will be created and used for Project 2.
3. CMPG 323 Project 3-35804068 repository will be created and used for Project 3.
4. CMPG 323 Project 4-35804068 repository will be created and used for Project 4.
5. CMPG 323 Project 5-35804068 repository will be created and used for Project 5.

# Repository and project context.
![Screenshot 2023-08-10 153105](https://github.com/ThoMaku/CMPG-323-Overview-35804068/assets/139887787/680dccee-4048-4a74-8e62-f955544ca5dd)


# Branching factors for each project.
1. Project1: Trunk-Based development: changes are made on the main branch.
2. Project2: Feature Branch Workflow work on each story on feature branch and merge with main branch.
3. Project3: Forking workflow will be used to access an existing repository.
4. Project4: Gitflow Workflow there will be main branch, deploy and on-going development branches.
5. Project5: Gitflow Workflow there will be main branch, deploy and on-going development branches, this will allow for bug fixes if any exist.

# .gitignore files
1. Project2: '*.config' this files should  be ignored because they have configuration files that contain database connection strings or credentials.
'*.bak' this are sql files that should not be version controlled.
2. Project3: '*.sql' this has SQL dump files used to back up the database.
'*.tmp' these are temporary files generated during database operations.
'*.db' data base files generated during development.
3. Project4: 'project.json' this is a file auto-generated by UiPath and contains machine-specific data, so it's best not to version control it.
'/bin/' this directory containes compiled output files and can be safely ignored.
'*.txt' text files that contain sensitive information like API keys
4. Project5: '*.pbix' contain the reports, including data connections and visuals, they are binary an not suitable for version control, as they can become large and change frequently

# Storage of credentials and sensitive information
1. By using environment variables to store sensitive information rather than hard codding them.
2. The use of encryption when storing data in databases.
3. Using role-based access control to restrict access to sensitive data based on user roles.
4. Using '.gitignore' to exclude sensitive files from version control.

# Project 1 burndown chart
![Screenshot 2023-08-10 142417](https://github.com/ThoMaku/CMPG-323-Overview-35804068/assets/139887787/3f8a1218-4648-48c3-9190-9a6b0dec2639)
