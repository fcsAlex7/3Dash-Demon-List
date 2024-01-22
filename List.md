# How do i add levels to the list?

This guide will be explaining how to add levels to the demon list.
i will be explaining the most efficient way, and explain what to do.

## Prerequisites

you will need the following things to be able to add levels.

- A brain
- Basic coding knowledge
-[Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)

# Adding Levels

To add levels to the list, you first need to make a .json file in the data folder.

when you make it, copy this template below:

```json
{
    "id": ,
    "name": "",
    "author": "",
    "creators": [],
    "verifier": "",
    "verification": "",
    "percentToQualify": ,
    "password": "Not Copyable",
    "records": [
       
    ]
}
```
once you copy it into the json file, add the appropriate stuff and then your done with adding levels.
if its a collab, you need add all of the creators in the "creators" part. If its not, **LEAVE IT BLANK**

and there you go! you added the level!
Note: keep the "password" tab at "Not Copyable" since its impossible to copy levels in 3dash without hacks. This feature will be used in the future once there is a proper password system.

# adding records
Adding records is very simple to the people who worked on the old list, because its the same system.
this is the template for records.

```json
 "records": [
        {
        "user": "",
        "link": "",
        "percent": ,
        "hz": 60
        },
    ]
```
the percent will most likely be either 100%, or somewhere around the minimum needed % to get on the list.

# **IMPORTANT** Adding levels to the list
So, whats currently done with the level your most likely adding, is just a file now. To actually add it to the list, you need to go to the [File](data/_editors.json) and add it to the placement of your choice. and thats it!