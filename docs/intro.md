---
sidebar_position: 1
---

# What you'll need..

- [IDE with .NET 6 SDK](https://nodejs.org/en/download/)
  - The most popular IDE's, such as Visual Studio and JetBrains Rider, already include (and install) the .NET 6 SDK for you. If you are using a different IDE or editor, please refer to their documentation to see if and how to add .NET 6 SDK support.
- [MSSQL](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) - free versions, such as Developer & EXPRESS, will do just fine!

  - For scaling and flexibility purposes, we will be using two databases:
    - widget_db - to store our application data, such as uploads & chats.
    - identity_db - to store our idp data, such as users, roles, tokens, and tenants.

- [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
  - To connect to and manage our databases.
