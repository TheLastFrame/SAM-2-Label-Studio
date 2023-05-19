# SAM-2-Label-Studio

This script helps to create segementation mask with the segment anything model form [Meta AI](https://segment-anything.com/) via the [Hugging Face Transformers Library](https://huggingface.co/docs/transformers/index) for pictures uploaded to [Label Studio](https://labelstud.io/).

Preuploading of the images increases the network throughput and thus reduces efficiency, but this way the file renaming of Label Studio can be neglected.

This script is not yet tuned for performance and a threshold for the scores could be implemented in a future update.
