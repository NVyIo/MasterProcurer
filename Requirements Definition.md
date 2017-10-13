# Procurement Tool and Web Interface

* Designed in theory: September 21, 2017*

## Overview

## Basic Concept

    ### This tool will be a device management and reporting utility providing visibility into an organizations allocation of inventory.

## Functionality

### Tasks the program should do

* Display a user Dashboard with relevant info *

#### Display a landing page with relevant info cards

#### House inventory

 1. Display in inventory list
 1. Display in employee device list
 1. Display everywhere needed with links to master
 1. Display in manager view

#### House employee table

1. Show employee name where necessary
1. Show as a link

#### Associate employees to the following

    1. Dept
    1. Cost center (CC)
    1. Asset
    1.  Manager

#### Associate Inventory Item

1. Dept
1. CC
1. Manager
1. Employee

#### Issue Monthly Charge Report

#### - Email to Employee [if mail deamon added]

#### - Views / buckets by Inventory item and by Name

        a users
        b department managers
        c cost center managers
        d procurement managers

#### Issue Assets By

    a. assignment
    b. reassignment
    c. unassignment and reassignment to manager

#### Load All Assets By

    a json
    b bson
    c api

#### Reflect Changes To

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

#### MACD [CRUD]

    a Moves - see above
    b Adds - see above
    c Change - see above
    d Delete - see above

#### Considerations

-- Consider adding a Parallax image to the background of the main dashboard