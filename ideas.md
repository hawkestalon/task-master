# Chores Ideas

## DB Models
1. User
2. Chore
3. Family
4. Badge

Chore can belong to user or family. Each user will have two lists of chores, a personal list, and a family list. Only a user can mark down a chore as complete. 

#### User: 
* name
* email
* password (hashed)
* chores
* badges`
* role (admin, user, family manager, etc)

#### Chore:
* title
* complete? 
* recurring (daily, weekly) 
* family
* user
* points (level of difficulty) 

Family:
* name
* members
* chores

## Pages
* Main Page
    * snapshot of chores
    * statistics
* List Chores
    * see all chores
* Admin Pages
    * Manage Family
    * Manage Users
* Manage Chores
    * CRUD Actions (some level of priveleges required)
* Stats Page
    * Consistency
    * Points per day, per week, etc.
    * Badges


## Task List

1. DB Models
2. User login
3. Main page
4. Chore management page
5. List chores
6. 