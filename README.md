MalSFF: Multi-Architecture Malware Detection Using Multi-Static Feature Fusion Based
on Image Visualization and Transfer Learning. Firstly, it extracts bytecodes and assembly
code (ASM) through reverse-engineering before transforming them into grayscale images.
This research strategically _ne-tunes the MobileNet architectures (V1, V2, V3-Small, and
V3-Large) for feature extraction of both _le types. Thereafter, it performs feature stacking
through early fusion, late fusion, and ensemble voting to obtain a single feature map, and
then utilizes a _lter-based feature selection algorithm. Finally, it employs k-NN,
SVM, RFC, MLP, EXT, and GNB classifiers, with optimized hyperparameters using gridsearch
algorithm. For better generalization, this research uses four datasets: i) Microsoft BIG,
ii) MalImg, iii) Dumpware10, and iv) Real-world samples. It achieved 98.72% accuracy
for the MalImg and 96.93% accuracy, 97% precision, 97% recall, and 97% F1-score, 0.012
milliseconds of response time in case of BIG dataset. For memory-resident malware, it
achieved 93.84% accuracy, 92% precision, 91% recall, and a 91% F1-score, with 0.05 seconds
response time. The MalSFF demonstrates resilience against FGSM, PGD, and DeepFool
adversarial attacks. The MalSFF is a lightweight and computationally efficient, well-suited
for resource-constrained IIoT networks.

