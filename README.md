# GUIHousekeepingManagementProgram

## Description

This program is made in order to classify and save informations of our house things with GUI program. A lot of data structure (such as stack, queue, heap, binary search tree, linked list, etc) are used to implement storage and container systems. Most of all, the goal of this program is to realize OOP, so that quite systematic classes are established in this program.

## Environment

This program can only be executed in Windows OS.

## Prerequisite

This program can be executed alone, so just download it and click 'Housekeeping.exe'!

## Usage

When you execute this program, you can see many input boxes, such as 'id', 'Name', 'Kinds', 'Count', etc.. Now I give you explanations what this boxes mean.

1. id : You can fill the target object id in this box. 'id' must be integer and must not be null or duplicated with other objects' id.
2. Name : You can fill the target object name in this box.
3. Kinds : You can fill the target object kinds in this box. 'Kinds' must be **integer**, so I recommend you to establish your own 'Kinds number', such as '1 is about stationery, 2 is about home appliances, 3 is about toiletries, ...
4. Count : You can fill the number of target objects in this box. 
5. Date : You can fill the date when you bought or got the object in this box, like '20221101'.
6. Container id, Storage id : In this systems, the storage means bigger storing place than the container. These categories must be **integer**. If you fill the container id with '3' and storage id with '1', the system creates the logical storage '1' with the logical container '3'. If you add other objects with container '4' and storage '1', the system adds the logical container '4' into the storage '1'. As a result, the system show us the storage '1' with the containers '3' and '4'.
7. Photo name : This category need to be updated. In this version, this category is meaningless.

<br/>

For example, if you want to input the data of pencil,

1. You may input '1' in id box. If any objects already inserted in masterlist, the id must be different.
2. You may input 'Pencil' in Name box.
3. You may input '2' in kinds box, if number '2' is meaning 'stationery' in your own kinds classification.
4. You may input '5' in count box.
5. You may input '20201015' in date box.
6. You may input '7' in container id box, and '2' in storage id box.

<br/>

You can add the input data in masterlist by clicking 'Add Item'. If you want to modify it, click the id of it in masterlist (if then, the values of it will be shown), change some values, and click 'Replace Item'. If you want to delete it, click the id of it in masterlist, and click 'Delete Item'.

<br/>

If you don't decide the container and storage id of the object yet, you can input other values (except the two categories) and click 'Enqueue Tempitem', so that you can save the data in templist. If you want to complete it, click 'Dequeue Tempitem', and follow the instruction of popup message.

<br/>

Look at the right-upper side of program. You can see three white boxes. The boxes show existing storage id, container id (when one of storage id is double-clicked), and object id (when one of container id is double-clicked). If you eventually click the object id (in third box), the data of the object will be shown.  
