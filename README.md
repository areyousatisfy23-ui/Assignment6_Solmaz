# assignment_6_aig230
Assignment 6 - Part B: Neural Language Model
Student Name: Solmaz Misaghi
Date: March 1, 2026

1. Model Configuration
Embedding Dimension: 256

Hidden Dimension: 512

Number of Layers: 2

Learning Rate: 0.001

Sequence Length: 32

2. Training Results
Final Validation Perplexity: 941.51


Final Test Perplexity: 887.88 

3. Text Generation Samples (Temperature: 0.8)
Sample 1: <bos> the transition <eos>

Sample 2: <bos> he was city council to working to the soviet leader <eos>

Sample 3: <bos> put play while it yesterday and retiring <unk> <eos>

4. Discussion and Comments
The generated samples show some basic grammatical structure and thematic grouping (e.g., "city council" and "Soviet leader"). However, the relatively high perplexity scores indicate that the model is still highly uncertain about word sequences, leading to incoherent or very short phrases. To improve coherence, the model would benefit from more training data, more epochs, or a larger hidden dimension.
