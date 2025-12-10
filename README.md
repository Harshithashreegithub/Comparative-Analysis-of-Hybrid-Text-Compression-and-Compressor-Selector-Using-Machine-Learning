# Comparative-Analysis-of-Hybrid-Text-Compression-and-Compressor-Selector-Using-Machine-Learning
An adaptive text compression system combining RLE, LZW, Huffman coding, and a machine-learning model to automatically select the most efficient compression strategy based on file characteristics.
Text compression plays a vital role in reducing storage requirements, improving transmission efficiency, and enhancing computational performance. Since no single compression algorithm performs optimally across all types of text data, this project explores and evaluates three widely used lossless compression algorithms:

Run-Length Encoding (RLE)

Lempel–Ziv–Welch (LZW)

Huffman Coding

Additionally, a hybrid compression pipeline is implemented, applying these algorithms sequentially to achieve improved compression performance.

To further optimize compression selection, a machine learning–based approach is introduced. File-level statistical and structural features are extracted and used to train a Random Forest classifier that predicts the most suitable compression algorithm for a given input file.
