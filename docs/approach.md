# Approach
## 1. Architecture
`.mton` files are UTF-8 text files interpreted by exchange plugins for each compatible application.  The exchange plugins create native materials from the instructions contained in the `.mton` file.

![](./img/mton-flowchart.png)

Any program that supports the creation or editing of PBR materials AND has an MTON Exchange Plugin should be able to read/write `.mton` files.  This democratizes PBR material creation and allows for effortless exchanges between renderers and lightweight archiving.

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

## 3. Key Features
#### Lightweight Material File
#### Human-Readable Text Format
#### Supports PBR Materials
#### Exchange Plugins for Compatible Render Engines

## 4. Reserved MTON Keys, Definitions, and Namespaces

## 5. Document Classes

## 6. MTON File Format Standards

## 7. Exchange Plugins