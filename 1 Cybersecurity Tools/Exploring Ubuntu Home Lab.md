## General System Tasks

1. sudo apt update
![alt text](image.png)

2. sudo apt upgrade
![alt text](image-1.png) 

## User Tasks

4. 
![alt text](image-2.png)

5. Useradd doesn't create a home directory or password by itself, but adduser walks you through steps to add a home directory, password, and other info.
![alt text](image-6.png)

6. 
![alt text](image-4.png)

7. Sally cannot create a new user because they are not in the sudo group. In order to give sally more privileges, they would have to be added to the group.
![alt text](image-5.png)

8. The exit command basically logs you out of a user you switch to in the command line, including when you use ssh
![alt text](image-3.png)

9. The passwd commands allows you to change the password of any user
![alt text](image-4.png)

10. Staying logged into root defeats the purpose of security and safety walls

11. The id command shows user id, group id, and also what groups the user is in
![alt text](image-7.png)

## Group Tasks

12. 
![alt text](image-8.png)

13. 
![alt text](image-9.png)

14. The groupadd command allows a user to create a group
![alt text](image-10.png)

15.
![alt text](image-11.png)

16. the groups command provides a list of groups that is easier to view compared to the id command
![alt text](image-12.png)

## Permission and Access Control Lists

17. montasj is the owner. montasj is the group owner. They both have read/write/execute permissions
![alt text](image-14.png)

18. 
![alt text](image-15.png)

19. Owner: read/write/execute, Group: read/write, Other: read
![alt text](image-16.png)

20. The getfacl command displays the access control list of a file/directory
![alt text](image-17.png)

21. The setfacl command gives specific users/groups permissions
![alt text](image-18.png)