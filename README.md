[![YouTube](https://gseth.com/images/YouTube_Logo_2017?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@controlaltai)

# ComfyUI ControlAltAI Nodes

This repository contains custom nodes designed for the ComfyUI framework, focusing on quality-of-life improvements. These nodes aim to make tasks easier and more efficient. Currently, two Flux nodes are available that enhance functionality and streamline workflows within ComfyUI.

## Nodes

![ComfyUI Screenshot](https://gseth.com/images/SNAG-3894.png)

### Flux Resolution Calculator

The Flux Resolution Calculator is designed to work with the Flux model, which operates based on megapixels rather than standard SDXL resolutions. This node calculates the resolution according to the defined megapixels and the selected aspect ratio.

- **Supported Megapixels:** 0.1 MP, 1.0 MP, 2.0 MP, 2.1 MP, 2.2 MP, 2.3 MP, 2.4MP, 2.5MP
- **Note:** Generations above 1 MP may appear slightly blurry, but resolutions of 3k+ have been successfully tested on the Flux1.Dev model.

### Flux Sampler

The Flux Sampler node combines the functionality of the CustomSamplerAdvance node and input nodes into a single, streamlined node.

- **CFG Setting:** The CFG is fixed at 1.
- **Conditioning Input:** Only positive conditioning is supported.
- **Compatibility:** Only the samplers and schedulers compatible with the Flux model are included.

## License

This project is licensed under the MIT License.
