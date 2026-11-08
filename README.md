# MG5
## Devlog
### 1. NavMesh and Physics Movement

NavMesh finds paths around obstacles. It is useful for villagers walking between houses in a farming game. Physics movement is better for a platform game where the character needs to jump, fall with gravity, and collide with platforms.

### 2. Fixing the Bird Loop

I uncommented the loop and changed it to `for (int i = 0; i < _birds.Length; i++)`. It now checks every bird instead of only the second bird. `Vector3.Distance` measures the distance between each bird and Pudu. Every bird within 3 units runs away. Birds farther away are not triggered.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
