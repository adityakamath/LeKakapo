# LeKakapo

WIP Low-cost mobile manipulator. Inspired by LeKiwi and named after another flightless bird from New Zealand (Okay, I am pretty sure LeKiwi is named after the fruit, not the bird, but the Kakapo is a funny little bird that makes me smile). Will be remixed with the following changes:

1. Base/Top plates that fits the printers I have access to OR get them laser cut (TBD)
2. 48mm omni wheels (since I already have them)
3. NP-F750 battery to power the base, the arm, and the Pi (again, I already have them, and they have the same capacity as the LeKiwi battery)
4. Second motor controller will be skipped, the base motors will be chained to the arm motor controller
5. OAK-D lite on the base (again, since I already have it), but will still have the option to use the camera recommended by LeKiwi

# LeKiwi
<div style="display: flex; justify-content: center; align-items: center; padding: 25px;">
    <img src="media/167040694.png" height="75" style="background-color: white; padding: 10px;"/>
    <img src="media/University-of-Illinois-logo.jpg" height="75" style="background-color: white; padding: 10px;"/>
    <img src="media/hf-logo-with-title.png" height="75" style="background-color: white; padding: 10px;"/>
    <img src="media/lerobot-logo-light.png" height="75" style="background-color: white; padding: 10px;"/>
</div>


> LeKiwi - Low-Cost Mobile Manipulator | Version 1

<img src="./media/lekiwi_cad_v1.png" width=300/> <img src="./media/lekiwi_real.jpg" width=300/> 

## Step by step tutorial
1. [Bill of Materials](BOM.md)
2. [3D Printing](3DPrinting.md)
3. [Assembly](Assembly.md)
4. [Get started with LeRobot](https://github.com/huggingface/lerobot/blob/main/examples/11_use_lekiwi.md)

## Hardware Design
#### Standardized Stacked Base Plates
- Inspired by the [open robotic platform](https://openroboticplatform.com/designrules), our base plates have 3.5mm diameter holes spaced 20mm apart for standardized mounting

#### Power
- (12V version) 12v 5A Li-ion battery
- (5V version) 65W Laptop power bank

> [!TIP]  
> If this is the first time you build robots please choose the 5V version as it’s a little bit easier to assemble. If you are more experienced and want to lift heavier objects choose the 12V version.

#### Compute
- Raspberry Pi 5
- Streaming to a Laptop

#### Drive
- 3-wheel Kiwi (holonomic) drive with omni wheels

#### Robot Arm
- [SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100)

#### Sensors
- Workspace rgb camera
- Wrist rgb camera

## Software Capabilities
Goals:
- Teleoperation with controller or laptop WASD + leader arm
- Data collection pipeline
- Streaming joint angles and camera feed

## CAD Design
[Fusion 360 CAD](https://a360.co/4k1P8yO)

We also provide the [URDF](./URDF/) exported from CAD for simulation.
## Get In Touch!

Join the project on this [Discord server](https://discord.com/channels/1216765309076115607/1318390825528332371)! Let us know if you have any questions, suggestions, or other feedback.

## Main Contributors
Thank you to everyone who helped on the project!

**CAD Design**: Manav Chandaka, Bhargav Chandaka, Pepijn Kooijmans

**Software**: Pepijn Kooijmans, Gloria Wang, Bhargav Chandaka, Advait Patel
