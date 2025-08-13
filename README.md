###Setup###

truegear's video (https://www.youtube.com/watch?v=Tfzr4xWiWZ0)

i recommend you watch the official truegear video first

first make sure OSC is enabled in vrchat you'll need the action menu, navigate to options, OSC and make sure it is enabled and then click the vrchat mod in the truegear app and check if the osc settings are ready (see picture 670 to 675)  


![Capture d’écran (670)](https://github.com/user-attachments/assets/b72ec6f3-7557-4d16-a39c-b0d536482bec) ![Capture d’écran (672)](https://github.com/user-attachments/assets/b573085a-52d7-444b-9855-1c5e0ede68c9) ![Capture d’écran (673)](https://github.com/user-attachments/assets/0495a173-bda8-4e28-8f56-342798e79447) ![Capture d’écran (674)](https://github.com/user-attachments/assets/a22fbd66-568e-4248-81e1-82a78ae1838a) ![Capture d’écran (675)](https://github.com/user-attachments/assets/4c7893ca-b5e0-4ea1-8396-20c627406336)




the vrchat mod only starts when you click on it from the app, this will activate the app and launch an instance of the game, you can wait until you're already in steamvr/vrchat to activate it (activating the mod on the app if you're already in vrchat will activate the mod and won't create a new instance)

you'll need your avatar ready in unity, the truegear prefab and vrcfury (https://github.com/vr-commiter/VRChat/releases/tag/VRChat-Prefab , and 
https://vrcfury.com/download)



when you'll start with the avi, do not resize the suit at all until you've unchecked the parent constraint (shift click before and after then unlock and unfreeze the position, you'll have to recheck everything once you've finished with any resizing/positioning and if you're wondering that's the lights effect for the suit ![Capture_decran_549](https://github.com/user-attachments/assets/4dd4799a-aa08-42a2-93f4-0a7c71786367)




you're gonna want to have the collision points be on your avi's skin, if it's too big or too small you can always resize them 
you're also gonna want to open torso and other and select all the contacts then resize them however you want, A1 to B5 G1 to H5 are the frontal contacts C1 to F5 are the back contacts
![Capture_decran_546](https://github.com/user-attachments/assets/a7b727de-25fe-4fb4-adbe-76c86af4940c) ![Capture_decran_510](https://github.com/user-attachments/assets/d699479e-baf2-4f4f-a712-a24b86715092)

to use the "lights on touch" feature, disable (torso)



if you need further help join the official truegear discord server and ask in the support feedback channel
https://discord.gg/ByTGRvCYmx



###Troubleshoot###


the suit oftentime comes dead on arrival, (less than 0% battery, battery on safe mode), you're gonna have to charge it without the ems (until the suit lights up) for the whole day, the charging stops when the suit stops "breathing"


if the suit powers on but not the ems, place the EMS on the charging dock and hold the button for 2 seconds, if not ask for help in the discord


if the vrchat mod doesn't install verify in settings if your game directory is steam/common/truegear_##### (as long as it's truegear it's good), else uninstall and reinstall the mod, if it still doesn't work wipe and reinstall the app

if you have another OSC app in the background like eye/face tracking, you're going to need Vor (https://github.com/SutekhVRC/VOR), that will allow you to use multiple OSC instances

the dongle can say driver error, it will still work without any issue as long as you don't have your pc too far or cluttered, if it does not work you can use any 2.4 dongle
