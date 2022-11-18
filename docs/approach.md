# Approach
## Architecture
MTON files are UTF-8 text files interpreted by exchange plugins for each compatible application.  The exchange plugins create native materials from the instructions contained in the `.mton` file.

![](./img/mton-flowchart.png)

## Schema
PBR support is present in most 3D applications which provides an ideal starting point for cross-application compatibility.

Basic PBR parameters include:
- Abledo (base color)
- Transparency
- Roughness
- Metalness
- Normal
- Ambient Occlusion

See [schema](/mton/schema.json) for the current schema.