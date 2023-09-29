### Purpose
This is a way on how to setup a Workspace & Workset for OpenRoads Deisgner (ORD). This will also go over how to organized the design file structure for the rest of the project.

### Tools Required:
Google Drive Computer 
OpenRoads Designer 

### Setup
1. Check that Google Drive is running on your computer.
2. Download the Caltrans OpenRoads Designer Workspace <https://communities.bentley.com/products/road___site_design/m/road_and_site_design_gallery/276482>
3. Extract the folder and place it in a safe place. When this folder is deleted, the workspace may cease to exist.
4. Open OpenRoads, and be sure you are in the home screen. The home screen will be titled "OpenRoads Deisgner CE" nad allow you to select the workspace and workset below it. The picture below is how it should look like for ORD 2022. 
![alt text](https://github.com/CarbonFlora/senior_project/blob/master/pictures/ord_homescreen.PNG)
5. Under "WorkSpace", select the green arrow with "Create WorkSpace".
6. Name = Caltrans
Description = The stock configuration for Caltrans 2022.
7. Under root folder, Browse. Find the Caltrans OpenRoads Designer Workspace folder you stored safely. When you see a folder titled "WorkSpaces", enter that folder. Select the folder titled, "Caltrans_Standards" and confirm by clicking "Select Folder". 
8. Where it says "\Caltrans" in the directory links, remove "\Caltrans". The picture below highlights where this is located. 
![alt text](https://github.com/CarbonFlora/senior_project/blob/master/pictures/ord_3.PNG)
9. Select "Caltrans" as the WorkSpace and the WorkSet should automatically be set to "Caltrans_Standards".
10. Browse for the file titled, "2023_I10_Basemap_DesignFile.dgn". This is located in The Google Drive DIR: 02.01.03
11. Find the site location and view around. DO NOT SAVE YOUR EDITS ONTO THIS FILE.

---

Best Practices for OpenRoads	
	Microstation files don't contain Civil Elements like alignments and labels. For the purposes of design, we need to convert these Microstation files to OpenRoads files. For every design file, we need to use the "Seed2D - Imperial Design.dgn"[1] file in the Caltrans WorkSpace and Workset. 

[1] A Seed file is a completely blank design file with preset standards and styles.
	
Copy the 2D seed file from inside the Caltrans WorkSpace folder and rename the copy to the file you want created. This can also be done from the OpenRoads Homepage.

Ex. 2d Seed File -> ha_ramp_1_v0.1.0

After opening the newly created and renamed file, you must "civilize" the file. Please see the picture below on where this icon is located.
	
todo!()

Reference all the required files through the "Attach Tools" feature. 

List 1:
	Horizontal Alignment
	Profile
	Edge of Pavement
	Right of Way
	Existing Ground 
	Striping
	
List 2: 
	Corridor		

List 3:
	Superelevation
	Decorations 😊
	