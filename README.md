# QKD_image_encryption
This encryption technique is implemented in the context of a hybrid quantum-classical cryptosystem in which a Quantum Key Distribution protocol is combined with the logistic sine map to establish a secure image transmission scheme. The QKD scheme derived from <sup>[1]</sup> employs a tripartite entangled state to double the key length compared to the conventional E91 protocol and can effectively detect any eavesdropping activities through the CHSH inequality violation. The increased quantum key is then utilized to generate a chaotic sequence employing the logistic sine map. Besides, the image is converted into grayscale before performing the XOR operation. Finally, Bob decrypts the image using the same initial seed and control parameter.

---

## 🔍 Key Outcomes
- The encryption system is reliable and robust
- An eavesdropper can not hide his presence while intercepting the keys due to the violation of CHSH inequality
- Highly Resistant to Differential Attacks
- The encryption uniformly distributes the pixel intensities over the image, thus concealing the statistical properties of the original image.
- After encryption, the adjacent pixel correlation becomes drastically reduced to zero, removing any discernible pattern.


---

## 📚 References

[1] D. Pastorello, “A quantum key distribution scheme based on tripartite entanglement and violation of chsh
 inequality,” International Journal of Quantum Information. DOI: [10.48550/arXiv.1707.06645](https://doi.org/10.48550/arXiv.1707.06645)


---
