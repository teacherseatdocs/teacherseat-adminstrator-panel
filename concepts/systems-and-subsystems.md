# Systems and Subsystems

Systems and subsystems are what give the TeacherSeat learning platform rich functionality that a user will access across the Student and Admin panel. 

> Think of how AWS or Azure has many cloud services (systems) with specific cloud features (subsystems). 

## What is a System?

A System is a collection of features (subsystems) that logically define a specific service offering based on a business or technical domain.

> The term service and system are interchangable and in some cases we'll use the the word service

Examples of notable systems:
- Identity and Access Management
- Student Management
- Content Management
- Payments Management
- Support Management

eg. The Identity and Access Management system is a core system with the following subsystems: Users, Policies and Roles

![](media/concepts-systems-system.png)

### Types of Systems

- Core             — A system that is core to the platform and cannot be deregistered
- Community        — A trusted community system
- Unknown          — A untrusted system, likely custom development of a private system
- Managed          — A system that is supported and maintained by TeacherSeat
- Vendor Managed   — A system that is supported and maintained by a Third Party Vendor

## What is a Subsystem?

A subsystem is a feature that resides within a system.

## What is a System plugin?

A System plugin provides addtional functionality to a subsystem. Generally System plugins are to provide cross-system integrations.

## Systems Management

Systems Management is a core system used to managed the installation and registration of other systems.

### Registering and Deregistering Systems
