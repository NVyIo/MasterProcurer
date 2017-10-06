# Procurement Tool and Web Interface

##### Designed in theory: September 21, 2017
## Overview
## Basic Concept
    ### This tool will be a device management and reporting utility providing visibility into an organizations allocation of inventory.
## Functionality

### Tasks the program should do:
s#### Display a user Dashboard with relevant info
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

#### Issue assets by 
    a assignment 
    b reassignment

#### Load all assets by 
    a json
    b bson
    c api

#### Reflect changes to
    a owner
    b deptartment
    c manager
    d costs (straight cut off e no partial months)

#### Remove 
    a owner
    b removals should result in clean reassignment to manager unless otherwise specificied

#### Assign as Retired device    
    a remove and suppress 
    b future charges
    c remove owner
    d remove manager
    e remove cost center/dept
    f assign "Retired" status reflect in Red

#### MACD
    a Moves - see above

#### Considerations
-- Consider adding a Parallax image to the background of the main dashboard.