Made by: @JystBird
Repository link: https://github.com/Jyst7/NonLinear/tree/main
Total hours so far: 2

- [x] I have a Bambu P1S

** Goals

1. Has a toolhead that moves on the x,y,z
2. Has a rotating base
3. stable and precise

Feb 17 2025:

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