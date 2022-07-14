# Introduction To Cryptography With Coding Theory

These are my notes on [Introduction To Cryptography With Coding Theory](https://learning.oreilly.com/library/view/introduction-to-cryptography/9780136758181/) by Wade Trappe, Lawrence C. Washington

## Sage & CoCalc

The new (July 2021) CoCalc image is 12GB and include a lot of extras (LaTeX, etc..).
So Sage may be a better choice for now.

```bash
docker run --rm -p 8888:8888 sagemath/sagemath-jupyter
open http://localhost:8888/

# or for just a console
docker run --rm -it sagemath/sagemath

# for CoCalc - NOT WORKING YET - only allows https to localhost, and problems setting up postgres
docker run --rm -v $(pwd)/data:/projects -p 443:443 sagemathinc/cocalc
open https://localhost/
```

## References

- [O'Reilly - Introduction To Cryptography With Coding Theory](https://learning.oreilly.com/library/view/introduction-to-cryptography/9780136758181/)
- [SageMath Crypto Reference](https://doc.sagemath.org/pdf/en/reference/cryptography/cryptography.pdf)
- [Pearson Book site (exercises and erata)](https://media.pearsoncmg.com/ph/esm/esm_trappe_crypt3e_20/trappe_crypt3e_main.html)
- [CoCalc and Docker](https://doc.cocalc.com/docker-image.html)

- Test
