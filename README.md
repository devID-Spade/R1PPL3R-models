# Offline Audio Models

## FUSS Baseline Mask

Mobile TFLite conversion of Google's four-source FUSS baseline separator.

- Input: mono 16 kHz audio, dynamic duration
- Output: four source masks plus source-presence probabilities
- SHA-256: `0786445ef841a25f0ccbe905e9a461a04ba4b9e568f449273f6f5036c5eb3e68`
- Upstream: https://github.com/google-research/sound-separation/tree/master/models/dcase2020_fuss_baseline
- Checkpoint: https://zenodo.org/records/3743844
- License: CC BY 4.0; see `LICENSE.md` and `NOTICE.md`

## pyannote Segmentation 3.0 int8

ONNX conversion of pyannote's speaker-segmentation model.

- Input: mono 16 kHz audio, 10-second window
- Output: local speaker activity (up to 3 speakers per window)
- SHA-256: `d582f4b4c6b48205de7e0643c57df0df5615a3c176189be3fc461e9d18827b5d`
- Upstream: https://huggingface.co/pyannote/segmentation-3.0
- Conversion: https://github.com/k2-fsa/sherpa-onnx/tree/master/scripts/pyannote/segmentation
- License: MIT; see `LICENSE-PYANNOTE.md` and `NOTICE-PYANNOTE.md`
