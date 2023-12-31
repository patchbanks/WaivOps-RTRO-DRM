<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## RTRO-DRM Dataset

RTRO-DRM is an open audio dataset composed of a series of drum recordings in the style of 1980s electronic music. The dataset comprises 2138 raw, unedited audio clips recorded in uncompressed stereo WAV format. These recordings were curated using an internal drum sample dataset and MIDI files sourced from a code-based music generation system, along with a MIDI transformer model trained on more than 30,000 MIDI files. The files primarily consist of recordings that may not meet conventional audio quality standards but can still be valuable for a range of applications and research projects.

## Dataset

The primary objective of this dataset is to provide accessible content for machine learning applications in music and audio research. Some potential use cases for this dataset include tempo detection and classification, drum rhythm analysis, audio-to-MIDI conversion, source separation, automated mixing, music information retrieval, AI music generation, sound design, and signal processing.

**Specifications**

- 2138 audio loops (4.3 hours)
- 24-bit WAV format
- BPM labeled
- Tempo range: 100-145bpm
- Variational drum patterns
- Electronic drum machine sound (circa 1980s)

## Examples

See examples folder to preview mp3 demos.


## License

This dataset is developed by WaivOps, a crowdsourced music project managed by sound label company Patchbanks. All recordings have been compiled by verified sources for copyright clearance.

The RTRO-DRM dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
## Download

The audio files are provided in 24-bit WAV format and encoded at 44.1kHz.

Direct Download (3.7GB) [rtro_drm_id_001.tar.gz](https://zenodo.org/record/8327650/files/rtro_drm_id_001.tar.gz?download=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8327650.svg)](https://doi.org/10.5281/zenodo.8327650)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| rtro | Main genre (retro)|
| drm | instrument (drums)|
| id | Identification number|
| _00 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@misc{RTRO-DRM,
author = {WaivOps},
title = {WaivOps RTRO-DRM: Open Audio Resources for Machine Learning in Music},
year = {2023},
doi = {10.5281/zenodo.8327650},
url = {https://doi.org/10.5281/zenodo.8327650},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
