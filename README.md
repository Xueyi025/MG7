# MG7
## Devlog
I put the birds in an array so the script could check them one by one instead of writing separate code for each bird. Every frame, the loop checks how far each bird is from the player. Their positions are vectors, and I use Vector3.Distance to measure the distance between them. When the player is close enough, the bird becomes active.

## Open-Source Assets
- [Forest Nature Pack](https://kaylousberg.itch.io/kaykit-forest) - environment 3D models
- [Quirky Series](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235) - animal 3D models
