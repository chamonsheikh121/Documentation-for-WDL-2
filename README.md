<h1 style="text-align: center">
    Note Module 11
</h1>


<h4 style="text-align:center">
    PH UNIVERSITY
</h4>

<h3>
    Functional Requirements
</h3>

* Authentication
    * Student
        * Login and Logout Securely
        * Update password
    * Faculty
        * Login and Logout securely
        * Update password
    * Admin 
        * Login and logout Securely
        * Update Password
 <h3>
    Profile Management
</h3>

* Student
    * Manage and Update profile
    * Update certain field
* Faculty
    * Manage and Update profile
    * Update certain field
* Admin
    * Manage and Update profile
    * Update certain field

<h3>
    Academic Process
</h3>

* Student
    * can enroll offered courses for a specific semester
    * can view class schedule
    * can view grades
    * can view notice board and events
* Faculty
    * can manage student grades
    * can access student personal and academic information
* Admin
    * can manage
        * semester
        * courses
        * Offered courses
        * sections
        * Rooms
        * buildings

<h3>
    User Management
</h3>

* Admin
    * can manage multiple account
    * can block and unblock user
    * can change user password
    







<hr>

<h3>
    Data Model
</h3>


* **student**: 
    * _id
    * id(gerated)
    * password
    * name
    * gender
    * dataOfBirth
    * email
    * contactNo
    * emergencyContactNO
    * PresentAddress
    * permanenntAddress
    * guardian
    * localGuardian
    * profileImage
    * academicDepartment
    * status
    * isDeleted
    * createdAt
    * updatedAt
* **Faculty**: 
    * _id
    * id(gerated)
    * password
    * name
    * gender
    * dataOfBirth
    * email
    * contactNo
    * emergencyContactNO
    * PresentAddress
    * permanenntAddress
    * profileImage
    * academicFaculty
    * academicDepartment
    * status
    * isDeleted
    * createdAt
    * updatedAt

* **Admin**: 
    * _id
    * id(gerated)
    * password
    * name
    * gender
    * dataOfBirth
    * email
    * contactNo
    * emergencyContactNO
    * PresentAddress
    * permanenntAddress
    * profileImage
    * ManagementDepartment
    * status
    * isDeleted
    * createdAt
    * updatedAt