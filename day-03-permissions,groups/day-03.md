# Day 03 - Permissions, Users and Groups

## Objective

Understandin types of permissions and user/group

## Commands Practiced

* chmod - change mode 
  * chmod [mode] [file-name]
  * modes:
     * read(r), write(w), execute(x)
     * x = 1, w = 2, r = 4 (7 = rwx, 6 = rw-, 1 = --x, 0 = --- )
     * +x or -x (add or remove execution)

* whoami - tells which user you are currently log in

* id - detaild view of user and group id
  * uid: userID, gid: groupID, groups: all groups you belong to 

## what I did

* Created a folder with different files and changed their permissions
* Checked multiple combinations
* Checked my user name and groups

## Problems Faced

* Difficulty in understanding the permission types and numerical values

## How I fixed

* Searched the web for better understanding
* Created a separate folder to check various combinations and usig "ls -l" command

## Key Learnings

* Permissions and modes
* Users and Groups
