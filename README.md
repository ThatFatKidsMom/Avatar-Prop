# Avatar prop
[![Twitter URL](https://img.shields.io/twitter/follow/ThatFatKidsMom?style=social)](https://twitter.com/ThatFatKidsMom)

Derivative work of [contact trackers](https://github.com/VRLabs/Contact-Tracker) to create a prop on an avatar that remote players can grab, rotate, and drop in the world.

## **Installation**
[Video](https://youtu.be/k1rVWK0o95A)

- Install everything in the download tab
- Drag the "Avatar prop" prefab into the heirarchy  
- Right click on the prefab to unpack it and then drag it onto the base of your avatar  
- Move the "Reset position" to the base of your avatar
- Enable the "object container" game object and place your desired prop into it
- Position your prop to be grabbed at the same location of the handle of the example sword and oriented in the same way
- Move the "Reset position" to determine where you want the prop to be placed when initially enabled
- Hide the "object container"game object.
- Merge the provided FX controller with yours using the [VRLabs Avatar 3.0 manager](https://github.com/VRLabs/Avatars-3.0-Manager)  
- Set WD settings according to your animator  
- Create a toggle in your menu to enable the system   
>Ensure you are using the latest SDK, AV 3.0 Manager, and VRLabs Final IK stub

## **How it works**
A physbone and series of constraints control position of the prop. Contact trackers are placed on the ring and middle finger of the hand of whoever grabs the prop and aimik references the contacts being tracked in order to orient the prop as if it were being held in the hand.
>That means the other person needs to have a ring and middle finger contact on their hand

## **Download**
[Latest release](https://github.com/ThatFatKidsMom/Avatar-Prop/releases/tag/1.0.0)  
[VRLabs FinalIK stub](https://github.com/VRLabs/Final-IK-Stub)  
[VRLabs Avatar 3.0 manager](https://github.com/VRLabs/Avatars-3.0-Manager)  

## **Credit**
[VRLabs](https://github.com/VRLabs)  
[Red](https://github.com/hfcRed)  
[Dreadrith](https://github.com/Dreadrith)  
little.sophia#1000

## **License**
[MIT](https://github.com/ThatFatKidsMom/Avatar-Prop/blob/main/LICENSE)

## **Contact**
If you need help with something you can message me on discord at ThatFatKidsMom#6462
