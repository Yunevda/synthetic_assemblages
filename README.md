# Synthetic assemblages
The data used to generate realistic avian vocalization ensembles were sourced from the BirdClef 2024 competition, which focuses on biodiversity monitoring in the sky islands of the Western Ghats (India). This dataset comprises 23,528 audio files (.ogg format) spanning 182 bird species, with each recording lasting a minimum of five seconds and sampled at 32kHz. The assemblage creation procedure follows three stages:

1. **Segmentation:** Audio files are partitioned into segments to isolate vocalizations of interest while minimizing silent intervals;
2. **Mixing:** Segments are systematically combined to simulate natural vocalization overlap; and
3. **Noise Isolation:** Background noise profiles are extracted from silent or low-activity portions of recordings to enable controlled noise-introduction experiments.
