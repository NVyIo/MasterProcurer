
# Procurement Tool and Web Interface

##### Designed in theory: September 21, 2017

## Overview
## Basic Concept

## Functionality

### Tasks the program should do:
#### Display a user Dashboard with relevant info
#### Display a landing page with relevant info cards
#### House inventory:
    1 Display in inventory list
    2 Display in employee device list
    3 Display everywhere needed with links to master
    4 Display in manager view
#### House employee table:
    1 Show employee name where necessary
    2 Show as a link
#### Associate employee table to:
    1 Dept
    2 Cost center (CC)
    3 Asset
    4 Manager
#### Associate device to:
    1 Dept
    2 CC
    3 Manager
    4 employee

#### Issue monthly charge report:
#### - email to employee if mail deamon added
#### - issue for view on screeen
        a users
        b department managers
        c cost center managers
        d procurement managers

Issue assets by 
    assignment 
    reassignment

Load all assets by json/bson /// api

Reflect changes to
    owner
    deptartment
    manager
    costs (straight cut off no partial months)

Remove 
    owner
    removals should result in clean reassignment to manager unless otherwise specificied

Assign as Retired device    
    remove and suppress future charges
    remove owner
    remove manager
    remove cost center/dept
    assign "Retired" status and reflect in Red

    MACD
    Moves - see above

