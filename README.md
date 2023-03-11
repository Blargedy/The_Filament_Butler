# The Filament Butler
In short, this is a manually-operated drop-in replacement for the Prusa MMU2, for use in high(ish) temperature printing. 

![20221014_140138](https://user-images.githubusercontent.com/25805271/205796289-e98aaa03-84ad-496f-9049-b90880ef2254.jpg)

I put my two Prusa Mk3s into enclosures in order to print ABS/ASA without warping. Unfortunately, the control boards of each MMU couldn't handle the elevated temperatures (~50C) and burned out. Instead of moving the electronics of the MMU2 out of the hot chamber, I decided to completely eliminate the automated swapping of filament.  I run the [Tefnut](https://github.com/Blargedy/Tefnut_Filament_Handling) system and wanted to maintain compatibility with it. The Filament Butler uses M10 PC6 pneumatic fittings to attach the 6mm OD tubing of Tefnut and proffers each filament to the operator for easy manual swapping, all without having to open the drybox lids.

![20221014_141030](https://user-images.githubusercontent.com/25805271/205796486-3c3ee25a-f39d-4f88-9de9-0cc5eb253dfe.jpg)

# Instructions
![image](https://user-images.githubusercontent.com/25805271/224463413-5afdc4ea-23c1-4716-adcd-5c4f130d1769.png)

1. Print all parts using the default orientation, without supports.

1. Insert M3 hex nuts in the following locations, using M3 screws to pull them into the pockets. 
![image](https://user-images.githubusercontent.com/25805271/224463752-a4664d68-11c9-4a5d-bf7e-519d0adc2425.png)
![image](https://user-images.githubusercontent.com/25805271/224463850-51178e1b-bffb-4e4f-8cb6-1b87d1cfa2d9.png)

1. insert M3 square nuts in the following locations, aligning their holes with the cylindrical screw holes.
![image](https://user-images.githubusercontent.com/25805271/224463961-e90a7d2d-fb66-4dc1-95b4-8bdbcc52713f.png)

1. Fasten the Pneumatic fitment bar to the main body with three M3x10 SHCS.
![image](https://user-images.githubusercontent.com/25805271/224464098-bbd0f200-e19b-405a-a582-e1b63e52bea7.png)

1. Attach the Frame Brackets with four M3x12 SHCS.
![image](https://user-images.githubusercontent.com/25805271/224464208-f53c7299-dffd-4992-9352-3d3f43fcd3e8.png)

1. Cut five 41.5mm lengths of 4mm OD 2mm ID PTFE tubing, and place them in the Filament Stow Sections.
2. Secure the tubes with the Filament Stow Lid and four M3x22 SHCS.
![image](https://user-images.githubusercontent.com/25805271/224464624-0f932a71-0fd8-4261-9a60-6efbd2cbd9a3.png)

1. Melt in two M3 heatserts into the Selector Body.
![image](https://user-images.githubusercontent.com/25805271/224466860-dc881ac7-9290-401d-9637-552372667bf4.png)

1. Press fit the collar insert into the Selector Collet.
![image](https://user-images.githubusercontent.com/25805271/224467026-f5c57189-a3d7-455c-806a-2bd8bfd64417.png)

1. Attach the Selector Collet to the Selector Body with two M3x10 SHCS.
![image](https://user-images.githubusercontent.com/25805271/224471117-fa2cc535-b8ba-4a90-b255-8337c7b3e959.png)

1. Using a rubber mallet, insert the brass inserts into the tabbed slots on the Selector Body.
![image](https://user-images.githubusercontent.com/25805271/224474608-292a3848-1180-4405-ae23-7ba0c10f3053.png)

1. Slide the Selector Rails through the holes on the side of the Main Body, through the brass inserts, and into the holes on the far side of the Main Body.
![image](https://user-images.githubusercontent.com/25805271/224474801-b6caa38e-1f22-44eb-871c-35fa457ef605.png)

1. Screw on the pneumatic fittings onto the Fitement Bar.
![image](https://user-images.githubusercontent.com/25805271/224475057-b833bb59-844d-4f2e-a669-d9e4b8a04b18.png)

You are now done with the assembly of the Filament Butler itself. Next up is installing it and getting everything ready for printing:

3. Hook the unit onto the frame of the prusa, exactly like the MMU2s
4. Screw on the 4mm OD tubing pneumatic fitment to the collar on the Selector.
5. Push-fit the 6mm OD tubing to the pneumatic fitment bar fittings.
6. Load the filament through until the ends reach the far side of the Filament Stow section
