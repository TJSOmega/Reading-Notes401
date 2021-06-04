# Notes 11

### Why is Access Control important:

Access Control allows you to at various parts of your application 
tier access to certain users so that all Data isn't controlled by 
everyone who accesses the application.

### Describe an application that would need access control:

An application such as a blog site where their are admins, editors, 
and readers. You may want all users to be able to login, however
you wouldn't want your readers to be able to create or delete blog
posts. While you may want your editors to be able to create blog posts
but not delete them.

### What is a role used for:

A role is used to determine the level of access a user has to an application
It simultaneously acts as a grouping for users of the application allowing you to assign
them all under the same umbrella.

### Why is role based access control more scalable than discretionary or mandatory access control:

Role based access control allows for a wider degree of jobs to be set and assigned roles, and new roles can be created all the time as well as removed all the time. Unlike MAC or DAC which are controlled by the OS Users.


## Vocabulary:


**Authorization:** Authorization is the function of specifying access rights/privileges to resources, which is related to general information security and computer security, and to access control in particular.

**Role Based Access Control:** Role-based access control (RBAC), also known as role-based security, is an access control method that assigns permissions to end-users based on their role within your organization. RBAC provides fine-grained control, offering a simple, manageable approach to access management that is less error-prone than individually assigning permissions. 

**Capabilities:** The abilites granted to an RBAC Group that can then be carried out by every user that is apart of that particular group.