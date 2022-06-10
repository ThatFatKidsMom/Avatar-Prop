# Avatar prop

Derivative work of [contact trackers](https://github.com/VRLabs/Contact-Tracker) to create a props on an avatar that remote players can grab, rotate, and drop in the world.
#### Requires Final IK.

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

## **How it works**
A physbone and series of constraints control position of the prop. Contact trackers are placed on the hand of whoever grabs the prop and aimik references the contacts being tracked in order to orient the prop as if it were being held in the hand.

## **Download**
[Latest release](https://github.com/ThatFatKidsMom/Gesture-Tracker/releases/tag/1.0.0)

## **Credit**
[VRLabs](https://github.com/VRLabs)  

## **License**
[MIT](https://github.com/ThatFatKidsMom/Avatar-Prop/blob/main/LICENSE)

## **Contact**
If you need help with something you can message me on discord at ThatFatKidsMom#6462
