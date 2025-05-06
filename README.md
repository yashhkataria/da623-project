## Applications of Discrete Cosine Transform (DCT)
**By: Yash Kataria**

---

### Motivation

I chose the Discrete Cosine Transform (DCT) because it is fundamental to many technologies we use daily, such as image compression (JPEG), audio processing, and even watermarking. Its ability to efficiently represent signals with fewer coefficients makes it a critical tool in digital signal processing and data compression.

---

### Historical Perspective

The DCT was introduced in the 1970s as a solution to the limitations of the Discrete Fourier Transform (DFT), particularly its low energy compaction. DCT's energy compaction property allows most of a signal's information to be represented by a small number of coefficients, which is essential for efficient storage and transmission.

---

### What I Learned

- **Energy Compaction:** DCT concentrates most of the signal's energy into a few coefficients, unlike DFT, which spreads it out. This is crucial for compression.
- **Orthogonality:** DCT basis functions are orthogonal, allowing for efficient and lossless reconstruction.
- **Applications:** DCT is the backbone of JPEG image compression, audio coding, and even steganography and watermarking.
- **Visualization:** By experimenting with signals and images, I observed how DCT transforms, compresses, and reconstructs data with minimal loss.

---

### Code / Notebook Highlights

- Demonstrated DCT on 1D and 2D signals, showing energy compaction and reconstruction.
- Visualized DCT basis functions and their orthogonality.
- Applied DCT to images, performed coefficient thresholding, and demonstrated JPEG-like compression using quantization matrices.
- Calculated and compared compression ratios for different strategies.
- Illustrated real-world applications, including watermarking and steganography concepts.

---

### Reflections

- **Surprises:** The dramatic reduction in data size with minimal visual quality loss in images using DCT-based compression was striking. Also, the orthogonality of DCT basis functions is visually and mathematically elegant.
- **Scope for Improvement:** Exploring more advanced applications like video compression, real-time audio processing, or implementing robust watermarking/steganography algorithms could further deepen understanding.

---

# References : 
1. Wikipedia [https://en.wikipedia.org/wiki/Discrete_cosine_transform]
2. Computer Vision and Image Processing Fundamentals and Applications by Manas Kamal Bhuyan.
3. Spectral Methods for Partial Differential Equations by John P. Boyd
4. Nasir Ahmed’s paper
