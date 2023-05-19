# SAM-2-Label-Studio

This script helps to create segementation mask with the segment anything model form Facebook AI via the Hugging Face Transformers Library for pictures uploaded to Label Studio.

Preuploading of the images increases the network throughput and thus reduces efficiency, but this way the file renaming of Label Studio can be neglected.

This script is not yet tuned for performance and a threshold for the scores could be implemented in a future update.
