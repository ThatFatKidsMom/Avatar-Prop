# Avatar prop
[![Twitter URL](https://img.shields.io/twitter/follow/ThatFatKidsMom?style=social)](https://twitter.com/ThatFatKidsMom)

Derivative work of [contact trackers](https://github.com/VRLabs/Contact-Tracker) to create a prop on an avatar that remote players can grab, rotate, and drop in the world.

## **Installation**
[Video](https://www.youtube.com/watch?v=iwcO_gyoL68)

- Import the latest VRChat SDK, prerequisites listed below, and most recent [release](https://github.com/ThatFatKidsMom/Avatar-Prop/releases/latest)
- Drag the "Avatar prop" prefab into the heirarchy from the Modular avatar or VRCFury folder depending on your preferred installation tool 
- Move the "Reset position" to the base of your avatar
- Enable the "object container" game object and place your desired prop into it
- Position your prop to be grabbed at the same location of the handle of the example sword and oriented in the same way
- Move the "Reset position" to determine where you want the prop to be placed when initially enabled
- Hide the "object container"game object.

## **How it works**
A physbone and series of constraints control position of the prop. Contact trackers are placed on the ring and middle finger of the hand of whoever grabs the prop and aimik references the contacts being tracked in order to orient the prop as if it were being held in the hand.
>That means the other person needs to have a ring and middle finger contact on their hand

## **Prerequisites**
[VRLabs FinalIK stub](https://github.com/VRLabs/Final-IK-Stub) or Final IK  
[Modular avatar](https://modular-avatar.nadena.dev/) or [VRCFury](https://vrcfury.com/)

## **Credit**
[VRLabs](https://github.com/VRLabs)  
[Sophia](https://github.com/sophia1000)

## **License**
[MIT](https://github.com/ThatFatKidsMom/Avatar-Prop/blob/main/LICENSE)

## **Contact**
If you need help with something you can message me on discord at ThatFatKidsMom
