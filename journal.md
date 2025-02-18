Made by: @JystBird
Repository link: https://github.com/Jyst7/NonLinear/tree/main
Total hours so far: 7

- [x] I have a Bambu P1S

** Goals

1. Has a toolhead that moves on the x,y,z
2. Has a rotating base
3. stable and precise

Feb 17 2025:

7 hours

- came up with name
- started research and brainstorm
- started drawing ideas
- resources found
    - https://www.youtube.com/watch?v=o8VBw_Q0OWE&t=2s
    - https://www.youtube.com/watch?v=GocP5EajSRM&t=788s

idea
- have the toolhead move on the x y and z but nozzle stays on the same plane and angle the whole time
- the base is able to rotate so that the head can reach any part of it

limitations
- printer turns off motors dont stay in position printer falls and destroys itself
- slicer

how to do
- find constraints
    - $300
    - may 21st
    - how much can i get 3d printed while still being precise
    - sizing(the larger the build volume the longer the nozzle has to be)

my thinking to still get a largeish build volume is that i would always have the small build plate and just a crap ton of supports which i dont like but the parts i would be printing on this wont be that big to begin thats what the p1s is for

im just thinking that to make it precise i would need to have an almost 0 backlash system and so how would i do that, the methods i know for that are cycloidal drive, ballscrews and thats about it

the simple part will be the larger body of the printer so lets keep it to a smaller design that for eyballing has a volume of maybe 10-15 cm for the length height and depth but that might be generous

i want the rotation to be on its own as it should be the most stable part as it has the most moving parts i think

new source: https://www.artificialintelligence.wiki/3d-printing/imperial-college-london-microsoft-propose-a-cheap-and-accessible-method-for-upgrading-3d-printers-to-5-axes/

so im thinking stepper motor for the precision and then a cycloidal gearbox right on top and then with a belt that should be precise enough otherwise ballscrewing around might be neccesary but hopefully not and i can leave that for the toolhead i guess im gonna find examples of that now

through very minimal research linear motor and cycloidal drive would be useful for the extra torque might do some more research but i wonder if it would be more worth it to just buy a more powerful linear motor as the cycloidal gearbox would need a bunch of little bearings etc

i think that my preliminary idea is to use either 2 powerful linear motors or 2 linear motors with cycloidal gearboxes. for the i guess pitch and then 1 or 2 just linear motors for the yaw

I think ill make the most basic outline for the rotational part and then fully design the main body and then finish up the base
I am also realizing i have no clue about how physics works but whatever

for the main body it would be a exoskeleton thats just like a box with only edges and vertecies and then the rest is like filled with plastic or acrylic if possible, something like the cheaper bambu p1s also build plate would be g10 its the only one i could think of that is cheap and could be cut with not too much difficulty

exoskeleton would prob have 4 threaded rods with a rounded linear rail to accompany each one for the stable y axis using ballscrews i think for the most precision
then there would be a motion system on top of this to get the x and z axis like the p1s would just be a bunch of belt and a couple linear rails for stability
then the base would have an elevated platform prob a circle at two opposite ends of the circle a gear/ linear motor will be connected for the pitch and then under this buildplate or something will be another linear motor for the yaw this should allow for control over the roll with some fancy kinimatics that I will never understand but im just asking for my hopes and dreams to be crushed

ok so ive seen things like a core xyz but that mechanism seems too complicated and i feel wouldn't be super precise i am going to read more on it so core xyz looks complicated and im not smart enough for that so as i was thinking before it would more be like a CoreXY + Gantry Z-Axis

currently i am making some base design drawings for the main body not the wierd base thingy
this seems very expensive so the build volume would prob be at most 10x10x10
most the price would prob go to the linear motors and lead screws or something mcmaster-carr to the rescue

ok so if i have $300 and i have 3 motors for base, and 2 for core xy, and 4 for z axis thats 9 motors lets say $30 each thats 9*30 so 270 uhhh ok we gotta find cheaper motors or less prob both ok so i think that website was overpriced on amazon and robot shop they are more so $20 so thats $180 that leaves some money for belts lead screws and linear rails and the rest will be bearings and hopefully just 3d print the rest


bom
total limit $500
grant limit $300
- 4 motors for z
- 2 motors for xy
- 2 motors for pitch
- 1 motor for yaw
- 9 motors $6(welcome bonus) each(completely wrong must find good one for like $15 later)
= $54

vslot is $2 with welcom deal
least 4x, most 12x $8-$24
v slot :https://www.aliexpress.com/item/1005003367614421.html?algo_pvid=ede12625-4f86-4bb8-93ea-521c2b577cc0&algo_exp_id=ede12625-4f86-4bb8-93ea-521c2b577cc0-5&pdp_ext_f=%7B%22order%22:%2237%22,%22eval%22:%221%22%7D&pdp_npi=4@dis!CAD!17.88!2.03!!!12.34!1.40!@2101c59817398320206561562e66c5!12000025449760566!sea!CA!0!ABX&curPageLogUid=tLjlhsCfaOR6&utparam-url=scene:search%7Cquery_from:

8mm linear rods
4x $1.5 each $6
linear rod: https://www.aliexpress.com/item/1005006293171727.html?algo_pvid=8c974eb5-c1d1-4c9a-acdb-27f8d2245784&algo_exp_id=8c974eb5-c1d1-4c9a-acdb-27f8d2245784-1&pdp_ext_f=%7B%22order%22:%223884%22,%22eval%22:%221%22%7D&pdp_npi=4@dis!USD!7.11!3.98!!!7.11!3.98!@2101c5ac17396768963603218ed2cf!12000036638889805!sea!CA!3877050385!X&curPageLogUid=e8iNtRMiNKKF&utparam-url=scene:search%7Cquery_from:

shaft coupler
least 4x $2 each $8
shaft coupler: https://www.aliexpress.com/item/1005006293171727.html?algo_pvid=8c974eb5-c1d1-4c9a-acdb-27f8d2245784&algo_exp_id=8c974eb5-c1d1-4c9a-acdb-27f8d2245784-1&pdp_ext_f=%7B%22order%22:%223884%22,%22eval%22:%221%22%7D&pdp_npi=4@dis!USD!7.11!3.98!!!7.11!3.98!@2101c5ac17396768963603218ed2cf!12000036638889805!sea!CA!3877050385!X&curPageLogUid=e8iNtRMiNKKF&utparam-url=scene:search%7Cquery_from:

feb 18 2025

a new day and new existential dread about schoolwork that i aint doing now on to some cadding

i looked at some more examples and I think i can get away with only using one motor for the pitch so that should make it a bit cheaper for the time being