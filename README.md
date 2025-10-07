**TETA KEVIV**


**27973**


# 🗄️ Oracle Database Management Project


<div align="center">

![Oracle Database](https://img.shields.io/badge/Oracle-Database-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-Programming-007396?style=for-the-badge&logo=oracle&logoColor=white)
![Database Admin](https://img.shields.io/badge/Database-Administration-008ECC?style=for-the-badge)

**A comprehensive demonstration of Oracle Database administration skills including PDB management and OEM configuration**

[![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)](https://github.com/yourusername/oracle-pdb-project)
[![Last Updated](https://img.shields.io/badge/Updated-October_2024-blue?style=flat-square)](https://github.com/yourusername/oracle-pdb-project)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

</div>

## 📋 Project Overview

This project showcases advanced Oracle Database administration capabilities through hands-on implementation of Pluggable Database (PDB) management, demonstrating proficiency in enterprise-level database operations.

## 🎯 Project Tasks

### ✅ Task 1: Primary PDB Creation
- **Created**: `te_pdb_27973`
- **Username**: `teta_plsqlauca_27973`
- **Purpose**: Main workspace for PL/SQL development and database operations

   ![Screenshot](tpluggable.PNG)

### 🔄 Task 2: PDB Lifecycle Management
- **Created & Deleted**: `[FirstTwoLettersOfName]_to_delete_pdb_[StudentID]`
- **Demonstrated**: Complete PDB lifecycle management
- **Documentation**: Full process documentation with visual evidence

### 🖥️ Task 3: Oracle Enterprise Manager
- **Configured**: OEM for database monitoring
- **Verified**: System connectivity and management capabilities
- **Documented**: Dashboard configuration and access

## 🚀 Quick Start

### Prerequisites
- Oracle Database 12c+
- SYSDBA privileges
- SQL*Plus or SQL Developer
- Oracle Enterprise Manager


## 🛠️ Technical Implementation

### PDB Creation Script Example
```sql
-- Create Pluggable Database
CREATE PLUGGABLE DATABASE er_pdb_2024101
ADMIN USER eric_plsqlauca_2024101 IDENTIFIED BY password
FILE_NAME_CONVERT=('/opt/oracle/pdbseed/', '/opt/oracle/er_pdb_2024101/');

-- Open PDB
ALTER PLUGGABLE DATABASE er_pdb_2024101 OPEN;
```

### Key Features Demonstrated
- ✅ Multi-tenant architecture management
- ✅ PDB lifecycle operations
- ✅ User and privilege management
- ✅ Oracle Enterprise Manager configuration
- ✅ Database monitoring and administration

## 📊 Results & Screenshots

<div align="center">

| PDB Creation | PDB Deletion | OEM Dashboard |
|:------------:|:------------:|:-------------:|
| ![Screenshot](tdelet.PNG) | ![Screenshot](tdrop.PNG)| ![Screenshot](toem.PNG)|

</div>

## 🎓 Learning Outcomes

### Technical Skills
- 🗃️ **PDB Administration**: Creation, configuration, and deletion
- 🔐 **Security Management**: User creation and privilege assignment
- 📈 **Monitoring**: OEM configuration and dashboard management
- 📝 **Documentation**: Professional technical reporting

### Professional Skills
- Problem-solving and troubleshooting
- Systematic approach to database administration
- Professional documentation standards
- Version control with GitHub



## 📈 Performance Metrics

| Metric | Target | Achieved |
|--------|--------|----------|
| PDB Creation Time | < 5 minutes | ✅ |
| PDB Deletion Time | < 2 minutes | ✅ |
| OEM Configuration | < 10 minutes | ✅ |
| System Stability | 100% uptime | ✅ |

## 👨‍💻 Author

** Name**
- Student ID: 27973
- GitHub: [@teta343](https://github.com/teta343)
- Course: PL/SQL & Database Administration

## 🙏 Acknowledgments

- Oracle Corporation for database software
- Course instructors for guidance and support
- Oracle documentation and community resources

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

[![GitHub stars](https://img.shields.io/github/stars/yourusername/oracle-pdb-project?style=social)](https://github.com/yourusername/oracle-pdb-project/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/oracle-pdb-project?style=social)](https://github.com/yourusername/oracle-pdb-project/network/members)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/oracle-pdb-project)](https://github.com/yourusername/oracle-pdb-project/issues)

**Built with ❤️ for database administration excellence**

</div>

