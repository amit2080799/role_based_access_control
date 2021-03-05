# Role Based Access Control

This system is able to assign a role to user and remove a user from the role.

Entities are USER, ACTION TYPE, RESOURCE, ROLE

ACTION TYPE defines the access level(Ex: READ, WRITE, DELETE)

Access to resources for users are controlled strictly by the role. One user can have multiple roles. Given a user, action type and resource system should be able to tell whether user has access or not.
