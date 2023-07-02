# Access Control

## 5 steps to RBAC

**What is Role Based Access Control (RBAC) and why do we care?**

>RBAC is a flexbile system or an approach to control access permissions and authorization for companies and define each user with their permissions inside a working environment.It is important because we've been relying on that system since 1970 and it has the most  properties in controling and managing the required access for each user making it more secure.

**Describe a Role/Permission heirarchy that you might implement using RBAC**

for example in a hospital set environment we can use the following:

1. Hospital Manager: a role that has the highest hierarchy order that can manipulate and access all the permissions of the system, also it can assign other roles and define permission of each role inside the hospital.

2. Department Manager: has a role to lead and define roles for each employee in that department, and has the control permission by the Hospital manager to take decisions and imply it over that department, has access over each employee work overflow and tasks, also can distribute resposibilites and provide budget for medical resources used in that department.

3. Head physician: a role that allows that physician to gain control over all physicians in that department and allow a read/write over the patients records for each other physician working in that department.

4. Physician: the lowest hierarchy role , which only allows the physician to read/write only the patients profile assigned to them.

**What approach might you take to implement RBAC?**

The approach usually has these steps:

1. Inventory your systems
2. Analyze your workforce and create roles
3. Assign people to roles
4. Never make one-off changes
5. Audit

## wiki - RBAC

**If Authentication is “you are who you say you are,” what is Authorization?**

>Authorization is the step that comes after authentication, if you are who you say you are, then this is what you are allowed to do!.

So it's the set of permissions or operations that you are allowed to perform, based on your identity.

**Name three primary rules defined for RBAC.**

>Role assignment, Role authorization, Permission authorization

**Describe RBAC to a non-technical friend.**

>RBAC is like the family heirarchy, your father and mom are those who got to make the decisions, where to go in vacations, what to eat today and the tasks for you and your siblings, so they has the higher order roles and privilages , while you and your siblings got the role of members only for example that allows you to give suggestions, and make notes about the tasks you are allowed to do.

## RBAC tutorial

**What Are access rights Associated with? The User? or The Role? Explain.**

>It is associated with the role, so basically, being a user doesn't grant you the access for operations, but assigning you to a certain role in an RBAC system will give you these permissions, so it's related to the role you have.

**Access Rights, or Authorization, is activated after a user successfully does what?**

>After authentication and successfully has role assignment and auhtorization.

**Explain how RBAC might benefit a business.**

- it has an integrated secure system with low weak points
- the policy doesn't need to be changed after an update on the member sections, so if an employee leaves a company, no need to update the roles system and permissions. just taking off that role of such user and the permissions will be all off. also the same when a new employee joins a company.
- Revisiting least privilege, which make the systen at lower risk of vulnerability.

## Reflection

**What are your learning goals after reading and reviewing the class README?**

> Understand more about how we can implement these apporaching using SQL.

## Things I want to know more about

>About the deep concepts of what is MAC or DAC also LBAC and how RBAC is built or related to them.
