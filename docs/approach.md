# Approach
## 1. Set Architecture
MTON files are UTF-8 text files interpreted by exchange plugins for each compatible application.  The exchange plugins create native materials from the instructions contained in the `.mton` file.

![](./img/mton-flowchart.png)

## 2. Set Schema
PBR support is present in most 3D applications which provides an ideal starting point for cross-application compatibility.

Basic PBR parameters include:
- Abledo (base color)
- Transparency
- Roughness
- Metalness
- Normal
- Ambient Occlusion

See [schema](/mton/schema.json) for the current schema.

## 3. Prioritize Features

## 4. Define MTON Keys, Definitions, and Namespaces

## 5. Document Classes

## 6. Define MTON File Format Standards

## 7. Plan Exchange Plugins