# SupportDesk Lab Network Design 

## Overview 

The SupportDesk Lab simulates the IT environment of a small business with 25 employees. 

the environment contains several departments: 

- IT 
- Finance 
- Sales 
- Human Resources 
- Management 

## Network Architecture 

```text
                         INTERNET
                            |
                         ROUTER
                            |
                         SWITCH
                            |
        +-------------------+-------------------+
        |          |          |          |       |
        |          |          |          |       |
     FINANCE      SALES       HR      MANAGEMENT  IT
     5 users     8 users    4 users     3 users   5 users
        |          |          |          |       |
        +----------+----------+----------+-------+
                            |
                     WINDOWS SERVER
                            |
              +-------------+-------------+
              |             |             |
             DNS           DHCP     ACTIVE DIRECTORY