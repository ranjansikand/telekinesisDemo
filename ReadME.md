# Telekinesis Demo in Unity

This is a quick demo of a telekinetic power system in Unity (C#).

## Inspiration
I've been playing Tears of the Kingdom lately, which reminded me of power systems like Control and InFamous 2, as well as minor features in games like Dishonored. It was always fun to be able to lift and launch objects.

## Implementation
The power is applied in a central script (Telekinesis) that calls public functions on the interacted objects. I used assets for the player controller and effects, though the implementation does not rely on them.

A couple of interesting things:
- Sound effects on the blocks are scaled by force of impacts
- The powers are interface-based, so it could easily be changed to operate differently on different objects
- The effects are recipient-side, so they are also easy to change for different desires outcomes
- Forces are applied to the objects directly, so you could ride the floating objects and launch them out from beneath yourself

