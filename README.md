# Individual Assignment II – Oracle PDB Management

## Student Information

| Item | Details |
|---|---|
| Student Name | KAYITESI Annet |
| Student ID | 29077 |
| Course | Database Development with PL/SQL (INSY 8311) |
| Instructor | Eric Maniraguha |
| Assignment | Individual Assignment II – Oracle PDB Management |

## 1. Introduction

This assignment is about managing Oracle Pluggable Databases (PDBs).

The main tasks completed in this assignment are:

1. Creating a new Pluggable Database.
2. Creating and deleting a temporary Pluggable Database.
3. Using Oracle Enterprise Manager (OEM).
4. Documenting the work on GitHub.

## 2. Oracle Environment

The assignment was completed using:

- Oracle Database 21c XE
- Oracle SQL Developer
- Oracle Enterprise Manager Express
- Git Bash
- GitHub
- Windows

## 3. Task 1 – Create a New PDB

A new Pluggable Database was created using the required naming format.

### PDB Name

`KA_PDB_29077`

### User Created Inside the PDB

`KAYITESI_PLSQLAUCA_29077`

The PDB was successfully created and opened in `READ WRITE` mode.

The PDB was also checked using SQL commands to confirm that it was working correctly.

### Evidence

Screenshots for this task are available in:

`screenshots/pdb_creation/`

## 4. Task 2 – Create and Delete a PDB

A temporary PDB was created for this task.

### Temporary PDB Name

`KA_TO_DELETE_PDB_29077`

The temporary PDB was created successfully and checked to confirm that it existed.

It was then opened, closed, and completely deleted using the `INCLUDING DATAFILES` option.

After deletion, the database was checked again to confirm that the temporary PDB no longer existed.

### Evidence

Screenshots for this task are available in:

`screenshots/pdb_deletion/`

## 5. Task 3 – Oracle Enterprise Manager

Oracle Enterprise Manager Express was used to view the Oracle database environment.

The dashboard was checked to show the Oracle environment and database information.

### Username

`KAYITESI_PLSQLAUCA_29077`

### Evidence

The OEM dashboard screenshot is available in:

`screenshots/oem_dashboard/`

## 6. Challenges Faced

One challenge was making sure that the PDB names and username followed the required naming format.

Another challenge was verifying the PDB status after creation and confirming that the temporary PDB was completely deleted.

These issues were solved by checking the database using SQL commands and verifying the results after each operation.

## 7. Repository Structure

```text
oracle_pdb_ass_II_29077_kayitesi/
│
├── README.md
│
└── screenshots/
    │
    ├── pdb_creation/
    │
    ├── pdb_deletion/
    │
    └── oem_dashboard/
```

## 8. Main PDB Details

| Item | Details |
|---|---|
| Student Name | KAYITESI Annet |
| Student ID | 29077 |
| Main PDB | KA_PDB_29077 |
| PDB User | KAYITESI_PLSQLAUCA_29077 |
| Temporary PDB | KA_TO_DELETE_PDB_29077 |
| Database | Oracle Database 21c XE |

## 9. Integrity Statement

I confirm that this assignment represents my own work.

The database operations were performed in my Oracle environment, and the screenshots were taken from my own work.

## 10. Conclusion

This assignment helped me understand how to manage Oracle Pluggable Databases.

I learned how to create a PDB, create and delete a temporary PDB, create and manage a user inside a PDB, check the PDB status, and use Oracle Enterprise Manager.

The completed work and evidence are organized in this public GitHub repository.

## Submission Details

**Student Name:** KAYITESI Annet

**Student ID:** 29077

**Repository Name:** `oracle_pdb_ass_II_29077_kayitesi`

**Main PDB:** `KA_PDB_29077`

**Temporary PDB:** `KA_TO_DELETE_PDB_29077`

**PDB User:** `KAYITESI_PLSQLAUCA_29077`

**Repository Visibility:** Public


