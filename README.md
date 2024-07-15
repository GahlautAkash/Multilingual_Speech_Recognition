# Multilingual_Speech_Recognition
Components and tools
•	Multilingual Whisper Model
•	RAG Model
Libraries and packages:
•	Whisper
•	Transformer
•	Datasets
•	Faiss-cpu
•	Torch
Dependencies Installation
!pip install openai-whisper 
!sudo apt update && sudo apt install ffmpeg 
!pip install datasets !pip install faiss-cpu

Model Loading
import whisper
import torch
from transformers import RagTokenizer, RagRetriever, RagSequenceForGeneration


Audio Processing
Text Chunking
Querying RAG model
Sample Execution
