### Repository cleanup and wiring diagram

This session, I cleaned up my repository by adding the source files and making a wiring diagram.

I probably made the wiring diagram the hard way I created it in CAD using sketches and extrusions instead of a dedicated wiring tool

![Robot wiring diagram made in CAD](journal-images/zagitis-232810.png)

# all brushles

**Time spent:** 1.1h

I decided to make the robot fully brushless. This meant that the arm motor also had to be brushless.

For the arm, I used a 1204 brushless motor coupled to a 16 mm planetary gearbox. I have used this motor in some of my previous robots, so I know it is reliable and should provide enough power for the arm.

![Brushless arm motor next to the arm gearbox](journal-images/zagitis-232451.png)

# ading the deteils

**Time spent:** 1.3h

This session, I made space for the wires, added bearings to the arm gears, and integrated the switch into the design.

![Arm gears and mounting details inside the chassis](journal-images/zagitis-232016.png)

# ground game

**Time spent:** 0.8h

Now I made the front configuration for horizontal spinners. This is known as a beiline.

The purpose of this design is to absorb hits from horizontal weapons

![Front attachment for the horizontal-spinner configuration](journal-images/zagitis-231900.png)

# ground game

**Time spent:** 0.8h

Now I made the front configuration for horizontal spinners. This is known as a beiline.

The purpose of this design is to absorb hits from horizontal weapons

# wheels

**Time spent:** 0.7h

This session, I designed the wheels. They are very similar to the previous version, but they will now run on 4×8×3 mm bearings.

For traction, I am using 20A silicone because it is easily available to me and should provide good grip

![Revised silicone wheels with bearing seats](journal-images/zagitis-231753.png)

# topplates and electronics

**Time spent:** 0.7h

This session, I made the top plates and installed the electronics.

The top plates will be made out of carbon fiber but in cad there clear

![Transparent top plates over the battery and electronics](journal-images/zagitis-231641.png)

# chasis

**Time spent:** 2.3h

I decided to make the robot wider and shorter. This should make it easier to control opponents and reduce the number of angles where I do not have the advantage. The robot is now mainly made from TPU for the front and armor sections, while the drive pods are made from PA12-CF.

I chose PA12-CF for the drive pods because they need to be stiff and rigid. A softer material could flex and cause the drivetrain to bind or lose efficiency.

![Wider chassis and four-wheel drive layout](journal-images/zagitis-231308.png)

![Close-up of the revised side armor and drive pod](journal-images/zagitis-231317.png)

# more driwe

**Time spent:** 1h

This session, I worked on the drive pods. I wanted them to be removable and interchangeable, making maintenance easier

![Removable drive pod with two wheels](journal-images/zagitis-224448.png)

# the driwe

**Time spent:** 2.5h

With as much power as the Blitz Lite motors provide, the biggest limitation would likely be traction. Many hammersaw robots use four-wheel drive to improve traction and control. The Blitz Lites also have far more power than a typical 1 lb robot needs, and they are a bit expensive for my budget.

Because of this, I started looking for other solutions that would provide strong drive power while remaining lightweight and making a 4WD setup easy to implement.

After a lot of research, I found the Repeat Robotics Tangent Drive Motor, which fit all of my requirements. It has around 15% more stator volume than the Blitz Lite while weighing less than one-third as much. Since it does not use a gearbox and instead relies on the wheel diameter for reduction, it is both lighter and mechanically simpler. After selecting the motors, I started implementing them into the design. This is my first version of integrating the motors

I also changed the battery to a Tattu 450mAh 4S 75C 14.8V pack since I already have one available.

In addition, I switched back to a larger weapon motor and changed the weapon to a grinding disk. This should be more effective against metal armor, and since I already have a 70 mm grinding disk, there is no need to order a custom weapon

![Early four-wheel drive layout](journal-images/zagitis-224319.png)

![Grinding disk mounted on the weapon arm](journal-images/zagitis-224324.png)

# ADDISHONS TO THE ARM

**Time spent:** 0.4h

I reinforced the arm by adding a connecting spacer, which should improve its strength and rigidity.

I also improved the arm limiter by attaching it directly to the arm. This design looks cleaner and should function more reliably.

![Revised arm limiter](journal-images/zagitis-224115.png)

![Connecting spacer between the arm plates](journal-images/zagitis-224119.png)

# screw swich

**Time spent:** 0.6h

Instead of buying a screw switch, I designed my own. It uses two M3 heat-set inserts that are 3 mm long and an M3 screw. When the screw is tightened, it makes electrical contact and turns the robot on.

I chose to use a screw switch because it is better suited for combat robots than a traditional rocker switch. Screw switches can handle higher currents and are generally more resistant to impacts, making them more reliable in a combat environment.

![Cross section of the screw switch and threaded inserts](journal-images/zagitis-224031.png)

![Screw switch mounted in the chassis](journal-images/zagitis-224037.png)

# forks

**Time spent:** 0.5h

I designed several different fork options for the robot. One set is made from steel and has a rounded shape that is better suited for deflecting drum and eggbeater weapons. I also designed normal fork design with weight-reduction pockets, allowing it to be manufactured from steel while still keeping the weight low. steel alows the forks to remain sharper for longer

![Steel fork design with weight-reduction pockets](journal-images/zagitis-223913.png)

![Rounded steel fork option](journal-images/zagitis-223918.png)

# changing the driwe

**Time spent:** 1.5h

I did some research for my other robot and found that the Just Cuz Robotics Blitz Lite motors were better suited for the drive system. They have better support, a larger output shaft, and more torque due to their larger gear reduction. Since they weigh about the same and cost roughly the same as my previous choice, I decided to use the Blitz Lite motors instead

I also made some changes to the robots armor. I decided to make the main body from nylon because of its rigidity and durability. In addition, I added TPU side armor to help absorb impacts from the sides

![Blitz Lite motor fitted in the chassis](journal-images/zagitis-223809.png)

![Chassis with revised drive motors and TPU side armor](journal-images/zagitis-223815.png)

# REENFORCING THE ARM

**Time spent:** 1.5h

I was looking at some other hammersaw robots and noticed that many of them use double-sided support for their weapon assembly. I thought that mounting the weapon motor on both sides would make the design more durable, so I redesigned the weapon mount the other side is supported by a 2by9bu5 flanged bearing

This change also allowed me to create a more symmetrical robot and use thicker gears, which should improve the strength and reliability of the weapon system.

![Double-sided weapon mount and arm gears](journal-images/zagitis-223721.png)

# final tuches

**Time spent:** 0.7h

I added the top plates, screw holes, and chamfers where needed Then I consider the robot finished. Here are some final renders of the completed design.

![Top view showing the plates and mounting screws](journal-images/zagitis-223617.png)

![Angled render of the first completed design](journal-images/zagitis-223622.png)

# forks

**Time spent:** 0.7h

I restricted the fork movement so they can't get stuck underneath the robot.

I also added a fork in the middle. The idea is that when I drive head-on into an eggbeater spinner, the fork will deflect the weapon and hopefully cause it to stall.

Finally, I reinforced the fork mounts with fillets to make them stronger and reduce stress concentrations around the joints.

![Three front forks and reinforced mounts](journal-images/zagitis-223525.png)

![Fork pivot and movement stop](journal-images/zagitis-223530.png)

# wheels

**Time spent:** 1.2h

i decided to make custom silicone wheels to mount the wheels to the motor i am going to use custom aluminum wheel hub atached to a tpu wheel for absorbing hits

![Early wheel CAD model](journal-images/zagitis-223342.png)

![Custom wheel hub](journal-images/zagitis-223345.png)

![Silicone wheel on the original drive motor](journal-images/zagitis-223350.png)

# hamersaw

**Time spent:** 1.5h

I switched the motor to the Repeat Robotics 2004 because I feel like I am going to have weight problems.

Then I looked at weapon designs from other hammersaws What I saww was that they have very aggressive attack angles and that they have a tooth on the counterweiight and I made my blade It weighs 20 g but with the motor mounting plate and the screws it will be around 40 g.

addet this thing to the arm so the weapon does not hit the ground

![Hammersaw arm and ground clearance stop](journal-images/zagitis-223105.png)

![Weapon assembly side view](journal-images/zagitis-223109.png)

![Weapon blade and mounting plate](journal-images/zagitis-223114.png)

# rear armot mootor guard

**Time spent:** 0.7h

i added rear armor and a guard to stop any think frpm yaming in to the motor

![Rear armor around the drivetrain](journal-images/zagitis-223045.png)

![Motor guard close-up](journal-images/zagitis-223053.png)

# the arm mecanism

**Time spent:** 1.5h

learned how to make gears and make gear reduction for the arm that is 2.2to 1 then i complethed the arm mecanism!

![Arm mechanism installed in the early chassis](journal-images/zagitis-222625.png)

![Arm reduction gears](journal-images/zagitis-222630.png)

![Arm assembly with reduction gears](journal-images/zagitis-222636.png)

# starting to cad the robot

**Time spent:** 1.5h

i proseeded first rouf cading Started designing the frame aded forks and mounted the droiwe motors

![Early chassis with forks and mounted drive motors](journal-images/zagitis-222512.png)

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

Screenshot 2026-06-13 025842 it took several tries but i settled on this beacase everything is very compact

this took 1h

![Original arm motor CAD model](journal-images/zagitis-222206.png)

![Initial layout of the motors and electronics](journal-images/zagitis-222201.png)

## Undated notes

### Started zagitis 1lb
