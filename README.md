# GUIDE-OF-TELECOMMUNICATION-LAB-OF-SCIENCES-AND-TECHNOLOGIES-FACULTY-ABOUBAKER-BELGUAID-TLEMCEN
This repo is a guide for the use of the 3D printing machine in the lab of telecommunications in the ST faculty / Aboubacker Belgaid in Tlemcen. The use must be perfect to reduce waste of materials, time, and costs. Please read it carefully and follow the steps for a better experience. 



In this repo, you need to do two key things:
  1/ install the file of the programme you find attached to this repo:
  

  the file is for the program you'll use to turn the 3D project into a G-code that the machine can understand and print using it. The program is calld Simplify3D,
  <img width="284" height="177" alt="images" center src="https://github.com/user-attachments/assets/e058ba99-bbce-454a-b1f6-85f6f61c8ac7"  />

  Due to testing many programs, we found that this program is the most compatible one with the specifications of the machine you use suposetly. This program is 
  not free, so you need to follow these steps to make it work.
    1/ enter the file and search for Simplify3D-4.0.0-windows-installer.exe / Simplify3D-4.0.0-windows-x64-installer.exe ( it depend on what's the version that 
    suits your pc ) and install the file. 
    <img width="378" height="80" alt="image" src="https://github.com/user-attachments/assets/ee110664-d83d-44a9-8099-cb87e70cb055" />
    2/ follow the steps of installation until you finish and close the pannel.
    3/ ones you finish go to the location where you installed the app. there , look for the " Interface.dll " file and rename it to "Interface.dl1".
    4/ copy the "Interface.dll" you find in the crack file that's attached to this repo into the same location and paste it there. 
    5/ ones you finished you can now open it with now issues. 
    <img width="1919" height="1017" alt="image" src="https://github.com/user-attachments/assets/b8d59e69-4c0c-4cea-931d-79414d08434c" />
    P.S. : if you find a problem in installation reed the reed me files that is attached in the cruck file . 


  2/ regulate the 3D printer :


  The printer that you use is CoLiDo Cubic , this version is a standard FDM printer using 1.75mm filament and a 0.4mm nozzle.The printer officially supports PLA, ABS, and TPU filament at 1.75mm diameter and we can propose for you these settings :
                                              
                                                
                                                Setting                        ValueLayer 
                                                Height                  0.2mm (balanced quality/speed)
                                                Print Speed                  40–50 mm/s
                                                Nozzle Temp                  200–210°C (PLA) 
                                                Bed Temp                        55–60°C
                                                Infill                          15–20% for normal parts
                                                Cooling Fan                  100% for PLA
                                                Supports                  Enable only if needed


follow these steps to use it 
    1/ after connecting and setting the printer as the manual provided by the manufacturer, turn it on 
    2/ ones it tuned on, go to preheat and click on cool. 
    3/ after that, go to control and set it to home posiition.
    4/ use the setings to make the gup between the nozzle and the plate of print to 1mm in the Z axis.
    5/ there is mode of motor control, use it to configur the plate in every corner of the plate. keep the distance between the nozzle and the plate les then 1mm and to verify that, use a thin paper and the screws bellow the plate, when the paper is fixed release the screw up the pont the paper starts to move, keep doing that until you finish.
    6/Now the plate is calibrated, you can start printing.

3/ guide of printing:
  To print, you need first to create the 3D object you want, to do that you have to use one of the 3D conception tools and programs, for example, there is the SolidWorks program.
  <img width="442" height="619" alt="image" src="https://github.com/user-attachments/assets/346f80da-4bd3-45f5-833d-b5bdf0a5b8de" />
in the end of the work you have to do:
    1/ save your file for any modification in the future.
    <img width="461" height="110" alt="image" src="https://github.com/user-attachments/assets/c7279e21-13f6-4cc4-b6cf-c1e6cb0aa602" />
    2/ export the file as an .stl file format , that make it legible to Simplify3D or any other 3D printor software. 
    <img width="922" height="609" alt="image" src="https://github.com/user-attachments/assets/729e76d7-4a44-4b79-9288-bbc4f5c8c434" />
    3/ open simplify3D and go click on the import button. Select the file you want and click on select.
    <img width="235" height="137" alt="image" src="https://github.com/user-attachments/assets/1d7b7554-8c3d-4e1c-b4b4-c46fa1b3576b" />
    4/ choose the position that you want the object to be printed on and take on considiration to choose the best postion that make the worke faster and wastless of the metiral , eviod using supports only in case where you need to. the higher there is a meterial in the air need to be printer or farest than a continues point from top to buttom the more there wil be need to support or the structure you print will collapse.
    then select "prepare to print" 
    <img width="236" height="478" alt="image" src="https://github.com/user-attachments/assets/24d48cb8-a14b-463d-81ae-126ea28c12c3" />
    5/ verify the time, the layers and setings and then, click on "save toolpaths to disk" . it will give you the path to save a Gcode of the project to a specific disck/flash memory disk of your own 
    <img width="191" height="182" alt="image" src="https://github.com/user-attachments/assets/c9b03a2f-792f-471b-9051-f9cc81f65cb9" />


the software is easy to use, if you want to make changes of the setings according to the usage you need you must check more documentation of the program and printer.

hope this repo give you an easy and understandeful way to oppirate the machine.


    
