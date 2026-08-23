# Attribution notice

FUSS Baseline Model, Google Research Sound Separation team.

Upstream code: https://github.com/google-research/sound-separation/tree/master/models/dcase2020_fuss_baseline

Original checkpoint: https://zenodo.org/records/3743844

This release freezes the trained TensorFlow checkpoint at its source-mask and source-presence outputs, converts that subgraph to a dynamic-duration TFLite model, and performs waveform reconstruction outside the model. No endorsement by the original authors is implied.