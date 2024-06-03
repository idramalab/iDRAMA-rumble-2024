
![iDRAMA-rumble-2024 Header](https://huggingface.co/datasets/iDRAMALab/iDRAMA-rumble-2024/resolve/main/iDRAMA-rumble-2024.jpeg?download=true)

# Dataset Summary

`iDRAMA-rumble-2024` is a large-scale dataset of 6,735 podcast videos from Rumble, an alternative Youtube-like platform. Using state-of-the-art models, we extract information across three modalities: 1) text, 2) audio, and 3) video. We detail the methodology for extracting information from podcast videos in the paper and release a first-of-its-kind dataset including data from different modalities:
- **Metadata:** Details about podcast videos, e.g., channel name, video name, video description, and more.
- **Text:** Transcription (i.e., speech-to-text) of podcast videos.
- **Audio:** Speaker diarization information providing speaker detection over time for each video.
- **Video:** Sampled representative video frames from each video, totaling 200K images. We also detect more than 400K non-unique faces from these images and release face embeddings.
  
  | Repo-links | Purpose |
  |:------|:--------------|
  | [Zenodo](https://zenodo.org/records/10515991) | Coming soon |
  | [Github](https://github.com/idramalab/iDRAMA-rumble-2024) | The main repository of this dataset, where we provide code-snippets to get started with this dataset. |
  | [Huggingface](https://hf.co/datasets/iDRAMALab/iDRAMA-rumble-2024) | On Huggingface, we provide a dataset that can be accessed through Huggingface APIs. |

- **Rumble platform:** [Rumble](https://rumble.com)
- **Link to paper:** [CySoc 2024](https://workshop-proceedings.icwsm.org/abstract.php?id=2024_07)
- **License:** [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)

# Quick start with Datasets

Install `Datasets` module by `pip install datasets` and then use the following code:

```python
from datasets import load_dataset

# Download & Load complete dataset
dataset = load_dataset("iDRAMALab/iDRAMA-rumble-2024")

# Load dataset with specific config
dataset = load_dataset("iDRAMALab/iDRAMA-rumble-2024", name="transcripts")
```

# Dataset Info

Dataset is organized by modalities -- transcripts, representative-images, speaker-diarization, and face-embeddings.

<table style="width:50%">
  <tr>
    <th style="text-align:left">Config</th>
    <th style="text-align:left">Data-points</th>
  </tr>
  <tr>
    <td>Podcast videos</td>
    <td>6,735</td>
  </tr>
  <tr>
    <td>Representative images</td>
    <td>252,387</td>
  </tr>
  <tr>
    <td>Face embeddings</td>
    <td>399,333</td>
  </tr>
  <tr>
    <td>Transcripts & Speaker diarization</td>
    <td>6,735</td>
  </tr>
</table>
<br>

# Version

- **Maintenance Status:** Active
- **Version Details:**
  - *Current Version:* v1.0.0
  - *First Release:* 06/03/2024
  - *Last Update:* 06/03/2024

# Authorship
This dataset is published at "Workshop Proceedings of the 18th International AAAI Conference on Web and Social Media" hosted at Buffalo, NY, USA.

- **Academic Organization:** [iDRAMA Lab](https://idrama.science/people/)
- **Authors:** Utkucan Balci, Jay Patel, Berkan Balci, Jeremy Blackburn
- **Affiliation:** Binghamton University

# Licensing
This dataset is available for free to use under terms of the non-commercial license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en).

# Citation

```bibtex
Coming soon
```
