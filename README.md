# structure_image_bug
 
This project illustrates a bug in 4D: when you clone or download the zip file then open the database the structure background image will not appear. 

This is image was placed using Structrue Properties. 4D copies the selected image to RESOURCES and renames it "strucure_background.png". After this the image reliably appears when I open the Strucutre Eidtor. However it does not appear when the project is upened on another system unless that user goes through the placing process. 

Since no files change in the Project when the background file is set 4D must be coded to check for that image. For whatever reason this is failing unless the each user makes the assignment. 
