# basicbilliards
Unity Example Billiards Project for Music 257

This is a BASIC Billiards example project for Unity

Feel free to lift code snipits for your projects

Controls: WASD - move cue, RF for up/down
          Arrow keys - rotate cue
          Space bar - shoot

Intersting things happening:
Physics engine (balls) vs. trigger collider behavior (bumpers)
Raycasting for target on cueball
AddForce for hitting cue ball - vector from raycast point through center of cue ball
Pocket trigger collisions for destroying balls, resetting cue ball position
Floor has DestroyObject for balls that fly off table

