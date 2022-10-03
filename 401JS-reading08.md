# 5 steps to RBAC

_1. What is Role Based Access Control (RBAC) and why do we care?_

  RBAC is the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. 
  
  Managing access settings maintains security. With proper implementation, the assignment of access rights becomes systemic and repeatable.
  

_2. Describe a Role/Permission heirarchy that you might implement using RBAC._

  If you are a restaurant group owner, managing a few hundred restaurants, you may have members of your organization who need access to store info for one store only, members who need access to store info for a group or different groups of stores, and/or members who need access to store info for all stores. 


_3. What approach might you take to implement RBAC?_

  To implement RBAC, you should 1/ inventory your systems, 2/ analyze your workforce and create roles, 3/ assign people to those roles, 4/ never make one-off changes, 5/ and audit your results and access settings. 


# wiki - RBAC

_1. If Authentication is “you are who you say you are,” what is Authorization?_

  Authorization is "you are allowed to access this information."


_2. Name three primary rules defined for RBAC._

  1/ Role assignment: a subject can exercise a permission only if the subject has selected or been assigned a role.
  2/ Role authorization: a subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
  3/ Permission authorization: a subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.


_3. Describe RBAC to a non-technical friend._

  RBAC is an approach to restricting system access to authorized users. It is an approach to implement mandatory access control (MAC) or discretionary access control (DAC).


# RBAC tutorial

_1. What Are access rights Associated with? The User? or The Role? Explain._

  Access rights are associated with the Role, not the User. We do not have direct access rights for Users - Users must be assigned to a Role to receive access rights.


_2. Access Rights, or Authorization, is activated after a user successfully does what?_

  Access rights are activated once they have authenticated themselves in a Role.


_3. Explain how RBAC might benefit a business._

  1/ Policies do not need to be updated when a certain person with a role leaves the organization
  2/ New employees are able to automatically activate their desired roles
  3/ You are able to continuously review the "least privelege" principle
