# Avatar prop

Derivative work of [contact trackers](https://github.com/VRLabs/Contact-Tracker) to create a props on an avatar that remote players can grab, rotate, and drop in the world. Requires Final IK.

## **Installation**
[Video](https://youtu.be/cCnQug_tGXs)

- Drag the "Gesture Tracker" prefab into the heirarchy  
- Right click on the prefab to unpack it and then drag it onto the base of your avatar  
- Select all objects that start with "Left" and drag in your right wrist bone into the empty source on the parent constraint  
- Select all objects that start with "Right" and drag in your left wrist bone into the empty source on the parent constraint  
- Merge the provided FX controller with yours using the [VRLabs Avatar 3.0 manager](https://github.com/VRLabs/Avatars-3.0-Manager)  
- Set WD settings according to your animator  
- Create a toggle in your menu to enable the system   
>Ensure you are using the latest SDK and AV 3.0 Manager

## **How to use**
Place your hands into the hands of another player and enable the system.  
>Ensure that the other player has all finger contacts and is making a fist gesture during calibration for best results. They must not open their hand, loosen their grasp, or do a peace sign until the indicator on their hand disappears. 

## **How it works**
[Video](https://youtu.be/ANdXGCluxoI)
-  Proximity sensors measure distance between contacts and use that information to drive parameters.
-  Those same sensors also scale themselves down and animate a float prior to driving parameters to accommodate for hand variation between players until a certain value is reached. The float being animated is used in the motion time field of every state after calibration in order to maintain the same scale when switching between states for WD on users.

## **Download**
[Latest release](https://github.com/ThatFatKidsMom/Gesture-Tracker/releases/tag/1.0.0)

## **Credit**
[VRLabs](https://github.com/VRLabs)  

## **License**
[MIT](https://github.com/ThatFatKidsMom/Gesture-Tracker/blob/main/LICENSE)

## **Contact**
If you need help with something you can message me on discord at ThatFatKidsMom#6462
