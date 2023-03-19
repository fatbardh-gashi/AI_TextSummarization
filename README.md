# AI Text Summarization


## TASK
#### Building a model that can summarize a long piece of text into a shorter one while maintaining its meaning and important information.


## DATASET
#### Andrew Huberman Podcast Transcripts | 95 Episodes

    ------------------------
    Timestamps | Transcripts
    ------------------------
    95 files   | 95 files
    ------------------------

### Timestams Dataset
00:00:00 Endurance: Benefits, Mechanics & Breathing 
00:07:30 Tool: “Exercise Snacks”
00:14:21 Momentous, Levels, LMNT
00:18:01 Endurance Categories
00:22:16 Fat Loss & Respiration; Carbon Cycles & Storage, Metabolism
00:33:08 Exhalation Rates, Exercise & Fat Loss; Calories 
00:41:47 Cardiovascular Adaptations, Cardiac Output & Maximum Heart Rate
00:47:03 AG1 (Athletic Greens)
00:47:55 Excess Post-Exercise Consumption (EPOC); Exercise Intensity & Fat vs. Carbohydrate Energy Utilization
00:59:35 Tool: Training for Fat Loss, Carbohydrate Stores, Liver Glycogen & Fatigue

## PREPROCESSING
#### Before performing text summarization, it is important to preprocess the text data. This can involve tasks such as lowercasing, removing stop words, stemming or lemmatization, and tokenization. Also the datasets have to be split into shorter ones and categorized based on the content for each episode.


## TECHNIQUES
#### Abstractive Summarization: This technique involves generating a summary that is not simply a subset of the original text, but rather a new text that conveys the most important information in a concise and coherent manner. Abstractive summarization algorithms use deep learning models such as neural networks to generate summaries.


## ARCHITECTURE
1. Seq2Seq with Attention: This is a popular deep learning architecture that has been shown to be effective for abstractive text summarization. The architecture involves training an encoder-decoder model with an attention mechanism that can selectively focus on different parts of the input text to generate a summary.
2. Pointer-Generator Networks: This is an extension of the Seq2Seq with Attention architecture that allows the model to copy words from the input text into the summary. This can help preserve important details from the original text and improve the quality of the summary.
3. BERT: BERT is a pre-trained Transformer-based language model that has achieved state-of-the-art results on a wide range of natural language processing tasks, including text summarization. Fine-tuning a pre-trained BERT model on the Andrew Huberman podcast transcript dataset could potentially lead to high-quality summaries.

