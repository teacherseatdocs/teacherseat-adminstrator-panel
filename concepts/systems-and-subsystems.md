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

Systems Management is a core system used to manage the installation and registration of other systems and subsystems.

### Registering and Deregistering Systems

In Systems Management an admin has the option to register or unregister a systems:

**Registering** a system will enable the service for use in your learning platform. If the system is a Vendor Managed pr TeacherSeat Managed system for the TeacherSeat marketplace, you may be required to provide addtional information such as payment information in order to the use service.

**Unregistering** a system will disable the service for use in your learning platform

#### System and Subsystem Indentifer

Systems and Subsystems have a unique identifer that follows the following format:
- Provider.Namespace.System *eg. TeacherSeat.Student.TeamInsights*
- Provider.Namespace.System.Subsystem *eg. TeacherSeat.Admin.IAM.Policies*

#### System Versions

System Versions follow the following format:
- major
- minor
- tiny
- release_type eg. final, alpha, beta, release candidate
  - release_version_number (for types other eg. beta, alpha, rc)
  - patchlevel (only when release type is final)

eg. `2.3.4-a1` Major: 2, Minor: 3, Tiny: 4, Release Type: Alpha, Release Version Number: 1
