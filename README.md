All experimental notebooks used in the thesis: 
Experiment_1_Whisper+LLM.ipynb,
Experiment_2_hybridllm:ipynb; 
Experiment_3_Spec_Asr.ipynb:
• The winning model notebook: Final_Model_Hindi_English_ASR.ipynb.
• Dataset analysis/validation notebook: Analysis_Dataset.ipynb 
(segment stats, Devanagari ratio, integrity and timing checks).
• Scripts/utilities for metrics (WER/CER/MER, SPA/BCS) and plotting,
plus configuration blocks for prompts, gates, and decoding.
Dataset (external link).The Hindi–English corpus used is OpenSLR-104 (train 89.9 h;
test 5.2 h; 16 kHz, 16-bit). The dataset is too large to include in this repository. Download
from: www.openslr.org/104/. After download and extraction, set your local path in the notebooks
where indicated (Kaldi-style manifests: segments, text, utt2spk, spk2utt, wav.scp).
