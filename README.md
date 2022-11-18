# MaterialX Object Notation README
![](https://img.shields.io/badge/License-MIT-brightgreen)

MaterialX Object Notation (MTON) is a simplified partial build of the [MaterialX](http://materialx.org) open standard for material exchange. MTON converts PBR portions of the MaterialX XML library to simplified key:value pairs in a JSON object structure.  By simplifying how MaterialX data is encoded, we hope to simplify the creation of exchange plugins for popular rendering packages.

## Prerequisites
MTON is built on Python 3. 
Because MTON is designed to bridge two 3D applications or renderers, having two different 3D applications is encouraged to get the most out of MTON. MTON may also be used as an archival format to store material data in an application agnostic, human-readable format.

## Usage
### Material Exchange
MTON works by saving PBR material data from 3D software, like Cinema 4D or Unity, to a human-readable JSON object structure saved in a `.mton` file.  Once the `.mton` file is saved, it can be archived as-is, or imported and/or modified by a different 3D application, like Unreal Engine or Maya.  Currently, MTON does not store binary data, like textures used by the material, but rather contains relative paths to such data.  Textures and other bitmap dependencies will need to be stored with the `.mton` file to be read by other applications.  MTON does store numerical data like RGB or roughness values that are used by various material channels.

## Contributing to MTON
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

To see areas where contributions are most needed, see our [contributing](CONTRIBUTING.md) page.


## Resources
- [Material X Website](https://www.materialx.org)
- [Material X Specification](https://materialx.org/assets/MaterialX.v1.38.Spec.pdf)
- [JSON Specification](https://www.json.org/json-en.html)
- [Physically Base Rendering, 3rd ed.](https://www.pbr-book.org/)

## License
MTON is open source.  You may use, modify, build, or contribute to the codebase subject to the terms of the MIT license.
[MIT](https://choosealicense.com/licenses/mit/)
