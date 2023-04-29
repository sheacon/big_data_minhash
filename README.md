# Genomic Alignment
## Efficiency by Lower Dimensional Representation

Genome alignment plays a crucial role in cancer research, enabling scientists to identify genetic variations associated with cancer. Sequencing technologies have generated vast amounts of genomic data, making it important to develop efficient computational methods for aligning reference genomes with samples from individuals. This project explores a simple approach to genomic alignment by applying k-mers, MinHash, and Jaccard similarity techniques.

![image](https://user-images.githubusercontent.com/89158603/235321301-edc33956-895d-453f-97db-993e592fa1df.png)

Of the combinations tried, using a k-mer length of 10 with 1000 hash functions resulted in the best MSE performance. The correlation with the benchmark was 0.999997175 with an MSE of 872.6645.

![image](https://user-images.githubusercontent.com/89158603/235321319-d8614ace-15df-4f6a-8f9d-a4d8e37b5a38.png)
