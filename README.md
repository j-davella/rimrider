# Rimrunner

A trophy truck that grows glider wings and has no engine in the air. Drive it flat out across a red-rock mesa cut up by side canyons and slot crevices, launch off a rim, press C, and glide. Stay up on thermals.

Play: https://j-davella.github.io/Rimrunner/

One HTML file, three.js r128 from a CDN, no build step. Open `index.html` in a browser, or serve the folder.

## Games

1. **Thermal Hunter**: start high with the wings out and stay up as long as you can. Thermals have a cloud on top and hawks circling in them; circle tight in the core to climb. One point per second and one per 10 m flown; it ends when the wheels touch.
2. **Rim to Rim**: six landing pads on the mesa tops with a canyon or crevice between each pair. Drive at the rim flat out, get the wings out, glide across and stop on the next pad. Fall short and you go back to the last pad, +10 s.
3. **Tumble Drop**: five drops, each 300 m up, upside down and tumbling, near a landing pad. Points for how high you are when you get it upright, how close to the pad you land, and how softly.

0. **Free Roam**: no clock, no score. Tab opens a map to teleport anywhere.

Yellow lift beams and red sink beams stand all over the map, in new random spots every time you load. Fly into a yellow one and it hauls you up 500 ft; a red one drops you 500 ft (never closer than about 80 ft to the ground). They show on the map as yellow and red dots.

Fly off the edge of the map and you get dropped somewhere random, 280 m up, upside down.

## Phones

On a phone the game switches to tilt controls (pick Keyboard or Phone on the menu to change it). Hold the phone sideways like a steering wheel: turn it to steer on the ground and to roll in the air, and tip it toward or away from you for nose up or down. Start (or LEVEL) sets the neutral position. On-screen buttons cover gas, brake, wings, flaps, road lock, view and pause. iPhones ask for motion permission when you tap Start. With no tilt sensor you get arrow buttons instead.

## The truck

- Trophy-truck size: about 5.2 m long and 2.4 m across the tires, on a 2.76 m wheelbase.
- Long-travel suspension on big 39-inch-style tires, ~400 kW, about 408 km/h flat out.
- Two downforce fans pull it into the ground while the wings are folded, so it corners and climbs like nothing else. The fan suction has a slider in the Tweaks panel (O).
- With the wings folded it has no lift and falls at about 1.8 g, so jumps come back down instead of floating. Jump gravity has a slider too.
- Two wings to pick on the menu. **Glider**: big, floaty and stable, best for hunting thermals. **Speed**: an aerobatic wing. Shorter and swept, about half the drag, a symmetric section so it flies the same upside down, and rate controls: the stick sets how fast it rolls, pitches or yaws, it stops dead when you let go and holds whatever attitude you leave it in. Nothing levels itself, and the fuselage will hold a knife edge on rudder. A red V-tail trails rainbow airshow smoke. A symmetric wing makes no lift sitting level, so take off like a real plane: get going with the wings out and pull back (Down arrow, or tilt back on a phone) to rotate onto the rear wheels.
- **C** grows the glider wings and folds them again. Flaps go to 50° in 10° steps on **F** / **R**; **T** / **G** trim the nose down / up.
- It rights itself and shrugs off hard landings, but not a canyon wall.

## Keyboard

W A S D drive (and fly once airborne) · I gas with road lock · J K L steer and brake · B handbrake · C wings · F R flaps · T G trim · V views · N map · O tweaks · H every control.

Started as a fork of Drop Zone, keeping only the Glide Buggy.
