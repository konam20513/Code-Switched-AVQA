# Towards Code-Switched Audio-Visual Question Answering


1. codebase directory:
a. This is the directory that contains foundational models .ipynb files for embedding extraction (New_embeddings.ipynb, text_embeddings.ipynb file).
b. ir-baselinecnn-video.ipynb consists of code for English and Hinglish VQA.
c. Transformer and cnn downstream for same stage fusion for Hinglish AVQA - ir-midterm-cnn.ipynb and ir-midterm-xmer.ipynb.
d. hierarchical, baseline.ipynb consists of the hierarchical (modality order) fusion with CNN and transformer downstream for Hinglish AVQA.

2. data directory:
data_with_hinglish.csv is the newly created hinglish (code switched) questions for code switched AVQA.

3. Embeddings directory:
The embeddings directory consists of the audio, video and text embeddings in the .npy format for easier loading and compilation.

Project presentation video: https://youtu.be/eSwS11x5ZUM

