# NFT Art Generator

Welcome to the NFT Art Generator! This tool is designed to create unique digital artworks by combining various layers such as backgrounds, hairstyles, eyes, noses, mouths, and beards. The generator outputs images and corresponding metadata as part of an NFT collection.

## Features

- Generate up to 18,900 unique face combinations.
- Outputs both SVG and PNG formats.
- Random name generation for each NFT.
- JSON metadata generation for each NFT.

## Installation

To get started with this project, you need to have Node.js installed on your machine. After that, you can clone this repository and install the necessary dependencies.

```bash
git clone [your-repo-link]
cd [your-repo-directory]
npm install sharp
```

## Usage

1. Prepare your SVG layer files and place them in the `layers` folder.
2. Run the script to start generating your NFTs:

```bash
node index.js
```

The script will create a new directory named `out`, where all generated SVGs, PNGs, and JSON metadata files will be stored.

## Customization

You can customize the generation process by modifying the SVG layer files in the `layers` directory. The generator is set up to randomize several attributes including:

- Background (`bg`)
- Hairstyle (`hair`)
- Eyes (`eyes`)
- Nose (`nose`)
- Mouth (`mouth`)
- Beard (`beard`), which has a random chance of being included.

Each attribute layer file should be named according to the convention `attribute[value].svg`. For example, `hair1.svg`, `eyes2.svg`, etc.

## Contributing

Feel free to fork this repository and submit pull requests to enhance the functionalities of the NFT Art Generator. You can also open issues to report bugs or suggest improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgments

- Node.js community
- Everyone who has contributed to the development of the `sharp` library

Enjoy creating your own unique NFTs!

```

This markdown covers all the necessary sections for a GitHub project README, including installation, usage, features, customization, contributing, license, and acknowledgments. Adjust the `[your-repo-link]` and `[your-repo-directory]` placeholders to fit your actual repository details.
```
