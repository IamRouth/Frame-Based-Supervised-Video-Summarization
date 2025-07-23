# Frame-Based-Supervised-Video-Summarization
Video summarization aims to produce compact summaries of long videos by extracting
key frames or segments, ensuring the essential content and narrative are preserved. This
project focuses on using the TVSum dataset, which contains 50 YouTube videos annotated
with shot-level importance scores, as a benchmark for evaluating summarization techniques.
We explore both classical and deep learning-based methods, including feature extraction
using pre-trained convolutional neural networks (CNNs), and the 0/1 Knapsack algorithm
to maintain a summary length constraint of 15%. The project emphasizes the use of all video
frames without downsampling, extracting 2048-dimensional features using GoogLeNet, and
sets the stage for advanced summarization models leveraging LSTM, attention mechanisms,
and other architectures.
