### Repository cleanup and wiring diagram

This session, I cleaned up my repository by adding the source files and making a wiring diagram.

I probably made the wiring diagram the hard way I created it in CAD using sketches and extrusions instead of a dedicated wiring tool

<img width="642" height="445" alt="Screenshot 2026-11-09 232810" src="https://github.com/user-attachments/assets/9b8ebae9-d1bf-415c-9e13-091b13b409a3" />


# all brushles

**Time spent:** 1.1h

I decided to make the robot fully brushless. This meant that the arm motor also had to be brushless.

For the arm, I used a 1204 brushless motor coupled to a 16 mm planetary gearbox. I have used this motor in some of my previous robots, so I know it is reliable and should provide enough power for the arm.
<img width="381" height="349" alt="Screenshot 2026-11-09 232451" src="https://github.com/user-attachments/assets/0f764110-9be7-4e64-8dbf-0eb195cd4763" />

# ading the deteils

**Time spent:** 1.3h

This session, I made space for the wires, added bearings to the arm gears, and integrated the switch into the design.

<img width="650" height="288" alt="Screenshot 2026-11-09 232016" src="https://github.com/user-attachments/assets/097747db-2a35-4bf1-b239-b333cf1da9d3" />


# ground game

**Time spent:** 0.8h

Now I made the front configuration for horizontal spinners. This is known as a beiline.

The purpose of this design is to absorb hits from horizontal weapons

<img width="650" height="441" alt="Screenshot 2026-11-09 231900" src="https://github.com/user-attachments/assets/1908e043-556a-494a-990f-719d33d38d65" />


# ground game

**Time spent:** 0.8h

Now I made the front configuration for horizontal spinners. This is known as a beiline.

The purpose of this design is to absorb hits from horizontal weapons

# wheels

**Time spent:** 0.7h

This session, I designed the wheels. They are very similar to the previous version, but they will now run on 4×8×3 mm bearings.

For traction, I am using 20A silicone because it is easily available to me and should provide good grip

<img width="648" height="363" alt="Screenshot 2026-11-09 231753" src="https://github.com/user-attachments/assets/733ecf8d-0ad7-4e10-a5a5-11152cf37ca8" />


# topplates and electronics

**Time spent:** 0.7h

This session, I made the top plates and installed the electronics.

The top plates will be made out of carbon fiber but in cad there clear

<img width="527" height="409" alt="Screenshot 2026-11-09 231641" src="https://github.com/user-attachments/assets/76d8e1b9-8fad-484f-95b8-eaec92e2ecc0" />


# chasis

**Time spent:** 2.3h

I decided to make the robot wider and shorter. This should make it easier to control opponents and reduce the number of angles where I do not have the advantage. The robot is now mainly made from TPU for the front and armor sections, while the drive pods are made from PA12-CF.

I chose PA12-CF for the drive pods because they need to be stiff and rigid. A softer material could flex and cause the drivetrain to bind or lose efficiency.


<img width="446" height="358" alt="Screenshot 2026-11-09 231317" src="https://github.com/user-attachments/assets/5266007c-536a-4237-ba08-eed609eb5c28" />
<img width="613" height="504" alt="Screenshot 2026-11-09 231308" src="https://github.com/user-attachments/assets/f2ca1de0-256f-4903-abcf-8c036b10e1d9" />

# more driwe

**Time spent:** 1h

This session, I worked on the drive pods. I wanted them to be removable and interchangeable, making maintenance easier

<img width="636" height="416" alt="Screenshot 2026-11-09 224448" src="https://github.com/user-attachments/assets/04b3eca1-0564-4911-8fc8-7585c0e44ba3" />

# the driwe

**Time spent:** 2.5h

With as much power as the Blitz Lite motors provide, the biggest limitation would likely be traction. Many hammersaw robots use four-wheel drive to improve traction and control. The Blitz Lites also have far more power than a typical 1 lb robot needs, and they are a bit expensive for my budget.

Because of this, I started looking for other solutions that would provide strong drive power while remaining lightweight and making a 4WD setup easy to implement.

After a lot of research, I found the Repeat Robotics Tangent Drive Motor, which fit all of my requirements. It has around 15% more stator volume than the Blitz Lite while weighing less than one-third as much. Since it does not use a gearbox and instead relies on the wheel diameter for reduction, it is both lighter and mechanically simpler. After selecting the motors, I started implementing them into the design. This is my first version of integrating the motors

I also changed the battery to a Tattu 450mAh 4S 75C 14.8V pack since I already have one available.

In addition, I switched back to a larger weapon motor and changed the weapon to a grinding disk. This should be more effective against metal armor, and since I already have a 70 mm grinding disk, there is no need to order a custom weapon

<img width="647" height="446" alt="Screenshot 2026-11-09 224319" src="https://github.com/user-attachments/assets/cb4cd428-99aa-4993-afb8-ff321b2ff40e" />

<img width="640" height="353" alt="Screenshot 2026-11-09 224324" src="https://github.com/user-attachments/assets/02023f1d-b90f-463e-8ddd-4ef500968a5e" />

# ADDISHONS TO THE ARM

**Time spent:** 0.4h

I reinforced the arm by adding a connecting spacer, which should improve its strength and rigidity.

I also improved the arm limiter by attaching it directly to the arm. This design looks cleaner and should function more reliably.



<img width="501" height="538" alt="Screenshot 2026-11-09 224119" src="https://github.com/user-attachments/assets/40aaacc4-df6c-483c-9404-05f9a8e61f01" />
<img width="462" height="428" alt="Screenshot 2026-11-09 224115" src="https://github.com/user-attachments/assets/503fb193-88fc-4a75-aaf9-6e86a8c99ee2" />

# screw swich

**Time spent:** 0.6h

Instead of buying a screw switch, I designed my own. It uses two M3 heat-set inserts that are 3 mm long and an M3 screw. When the screw is tightened, it makes electrical contact and turns the robot on.

I chose to use a screw switch because it is better suited for combat robots than a traditional rocker switch. Screw switches can handle higher currents and are generally more resistant to impacts, making them more reliable in a combat environment.

<img width="580" height="413" alt="Screenshot 2026-11-09 224031" src="https://github.com/user-attachments/assets/4e8fa039-9d87-44ac-b9bb-0f7ab29e0101" />
<img width="327" height="315" alt="Screenshot 2026-11-09 224037" src="https://github.com/user-attachments/assets/b6a66d30-a027-4a65-b8ec-bef1eb6b9bd0" />

# forks

**Time spent:** 0.5h

I designed several different fork options for the robot. One set is made from steel and has a rounded shape that is better suited for deflecting drum and eggbeater weapons. I also designed normal fork design with weight-reduction pockets, allowing it to be manufactured from steel while still keeping the weight low. steel alows the forks to remain sharper for longer

<img width="497" height="483" alt="Screenshot 2026-11-09 223918" src="https://github.com/user-attachments/assets/e13b52d2-b965-4f71-82b0-5d0d1c76a2c5" />
<img width="502" height="258" alt="Screenshot 2026-11-09 223913" src="https://github.com/user-attachments/assets/bd3634ce-b750-4d94-b8ef-ec280ed3a1fd" />

# changing the driwe

**Time spent:** 1.5h

I did some research for my other robot and found that the Just Cuz Robotics Blitz Lite motors were better suited for the drive system. They have better support, a larger output shaft, and more torque due to their larger gear reduction. Since they weigh about the same and cost roughly the same as my previous choice, I decided to use the Blitz Lite motors instead

I also made some changes to the robots armor. I decided to make the main body from nylon because of its rigidity and durability. In addition, I added TPU side armor to help absorb impacts from the sides
<img width="566" height="350" alt="Screenshot 2026-11-09 223809" src="https://github.com/user-attachments/assets/c218ccc1-1b14-4bf5-9a03-f1ae02735db1" />
<img width="663" height="602" alt="Screenshot 2026-11-09 223815" src="https://github.com/user-attachments/assets/a0fe9fb3-5006-426e-a28f-87100846857c" />


# REENFORCING THE ARM

**Time spent:** 1.5h

I was looking at some other hammersaw robots and noticed that many of them use double-sided support for their weapon assembly. I thought that mounting the weapon motor on both sides would make the design more durable, so I redesigned the weapon mount the other side is supported by a 2by9bu5 flanged bearing

This change also allowed me to create a more symmetrical robot and use thicker gears, which should improve the strength and reliability of the weapon system.

<img width="726" height="422" alt="Screenshot 2026-11-09 223721" src="https://github.com/user-attachments/assets/3cb20037-48ef-43a7-a8a9-a0ea751c4195" />


# final tuches

**Time spent:** 0.7h

I added the top plates, screw holes, and chamfers where needed Then I consider the robot finished. Here are some final renders of the completed design.

<img width="728" height="511" alt="Screenshot 2026-11-09 223622" src="https://github.com/user-attachments/assets/ea65021d-9f68-4bfd-b450-a79de24d0ca8" />
<img width="659" height="640" alt="Screenshot 2026-11-09 223617" src="https://github.com/user-attachments/assets/16cc21ca-ee50-4ed4-b6ae-4f5ac1a7f10f" />

# forks

**Time spent:** 0.7h

I restricted the fork movement so they can't get stuck underneath the robot.

I also added a fork in the middle. The idea is that when I drive head-on into an eggbeater spinner, the fork will deflect the weapon and hopefully cause it to stall.

Finally, I reinforced the fork mounts with fillets to make them stronger and reduce stress concentrations around the joints.

<img width="687" height="435" alt="Screenshot 2026-11-09 223530" src="https://github.com/user-attachments/assets/b4ea7761-84f1-45d0-84d3-b664c9ce3675" />
<img width="693" height="433" alt="Screenshot 2026-11-09 223525" src="https://github.com/user-attachments/assets/b94cd203-556f-4f49-b690-a2095f4edc33" />

# wheels

**Time spent:** 1.2h

i decided to make custom silicone wheels to mount the wheels to the motor i am going to use custom aluminum wheel hub atached to a tpu wheel for absorbing hits
<img width="658" height="450" alt="Screenshot 2026-11-09 223350" src="https://github.com/user-attachments/assets/df028e00-718d-4b5d-9457-8cb5287a645e" />
<img width="453" height="332" alt="Screenshot 2026-11-09 223345" src="https://github.com/user-attachments/assets/114dc8d3-b7fa-4de7-a507-a7e85f0b4cf4" />
<img width="738" height="532" alt="Screenshot 2026-11-09 223342" src="https://github.com/user-attachments/assets/1166f288-d7d6-4986-a7fe-4b134f7e0438" />


# hamersaw

**Time spent:** 1.5h

I switched the motor to the Repeat Robotics 2004 because I feel like I am going to have weight problems.

Then I looked at weapon designs from other hammersaws What I saww was that they have very aggressive attack angles and that they have a tooth on the counterweiight and I made my blade It weighs 20 g but with the motor mounting plate and the screws it will be around 40 g.

addet this thing to the arm so the weapon does not hit the ground

<img width="421" height="485" alt="Screenshot 2026-11-09 223109" src="https://github.com/user-attachments/assets/e7680b33-f753-427b-a528-b7aaa344d9b5" />
<img width="552" height="501" alt="Screenshot 2026-11-09 223105" src="https://github.com/user-attachments/assets/4460cbda-f072-4e38-ae7e-ff56c3898ccd" />
<img width="765" height="724" alt="Screenshot 2026-11-09 223114" src="https://github.com/user-attachments/assets/373975a2-125e-435b-aefc-0024dd345302" />


# rear armot mootor guard

**Time spent:** 0.7h

i added rear armor and a guard to stop any think frpm yaming in to the motor
<img width="333" height="527" alt="Screenshot 2026-11-09 223053" src="https://github.com/user-attachments/assets/53d6a878-b5c3-40c9-91f2-2526e2c4c407" />
<img width="751" height="472" alt="Screenshot 2026-11-09 223045" src="https://github.com/user-attachments/assets/db755669-fe1f-41c1-bf11-dc4780480c98" />


# the arm mecanism

**Time spent:** 1.5h

learned how to make gears and make gear reduction for the arm that is 2.2to 1 then i complethed the arm mecanism!
<img width="701" height="841" alt="Screenshot 2026-11-09 222625" src="https://github.com/user-attachments/assets/3f8d4482-c9ad-45d0-9cab-35109fe0443a" />
<img width="887" height="656" alt="Screenshot 2026-11-09 222630" src="https://github.com/user-attachments/assets/f45e656f-d4e1-4fb6-86da-81177d694cb5" />
<img width="847" height="737" alt="Screenshot 2026-11-09 222636" src="https://github.com/user-attachments/assets/46027c20-6ed7-4f27-a3b9-ee8ba229a557" />

# starting to cad the robot

**Time spent:** 1.5h

i proseeded first rouf cading Started designing the frame aded forks and mounted the droiwe motors

<img width="929" height="708" alt="Screenshot 2026-11-09 222512" src="https://github.com/user-attachments/assets/b95c442b-8e68-4f26-8489-fd459a0d90f5" />


# resharching the electronics and puting them in cad

**Time spent:** 4.5h

I found that the best drive motors for my robot would be the Repeat Robotics Compact 1806 22mm Brushless Planetary Motors because I need a lot of drive power to push opponents around the arena.

https://palmbeachbots.com/products/repeat-robotics-compact-1806-22mm-brushless-planetary-motor-beetle-drive

For the battery, I am going to use a GAONENG GNB LiHV 4S 15.2V 380mAh 90C XT30 LiPo battery.

https://www.gaoneng.shop/products/gaoneng-gnb-lihv-4s-15-2v-380mah-90c-xt30-lipo-battery

For the saw, I am going to use an Axisflying 2207.5 brushless motor. It has a very good power-to-weight ratio.

https://www.aliexpress.com/item/1005006344056844.html

For the arm, I am going to use a Micro 16mm 16GA-050 Metal Gearbox Motor (336 RPM) because I already have this motor at home.

https://www.aliexpress.com/item/1005005905317146.html

For the arm ESC, I am going to use a 20A bidirectional brushed ESC with brake functionality because I already have one available.

https://www.aliexpress.com/item/1005008085017227.html

For the saw ESC, I am going to use a PBB Edition Ready to Sky 35A Brushless ESC. I already have a similar ESC available.

https://palmbeachbots.com/products/ready-to-sky-35a-brushless-esc-with-3-5mm-bullet-connectors

For the drive ESC, I am planning to use the Repeat Robotics Dual AM32 ESC.

https://palmbeachbots.com/products/repeat-robotics-am32-dual-brushless-drive-esc-with-bec

For the receiver and transmitter, I am going to use a FlySky FS-i6 because I already own one.

https://www.aliexpress.com/item/1005012028909932.html

Researching and selecting all of these components took approximately 2 hours.

Finding and Creating CAD Models

Next, I started finding or creating CAD models for all of the components.

I found CAD models for the saw motor and drive motor:

https://grabcad.com/library/pacer-2207-v2-motor-2

https://grabcad.com/library/repeat-drive-compact-1

However, I had to design the arm motor model myself.

Screenshot 2026-06-13 021857

I was also able to find CAD models for some of the electronics:

https://grabcad.com/library/repeat-am32-dual-brushless-drive-esc-1

https://grabcad.com/library/fs2a-radio-receiver-afhds-2a-protocol-1

I designed the battery model myself.

Finding CAD files and creating the missing models took approximately 1.5 hours.

then i started the robots cad proces first step was arange the motors and electronics

it took several tries but i settled on this beacase everything is very compact

this took 1h

<img width="614" height="628" alt="Screenshot 2026-11-09 222206" src="https://github.com/user-attachments/assets/366d86a5-29ed-43c0-9efd-d72255ef0045" />
<img width="672" height="519" alt="Screenshot 2026-11-09 222201" src="https://github.com/user-attachments/assets/41c9ec6f-1e94-4100-9ddc-7e034c75a7bc" />

## Undated notes

### Started zagitis 1lb
