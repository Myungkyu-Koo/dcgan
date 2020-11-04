# DCGAN(Deep Convolutional GAN)
## GAN(Generative Adversarial Network)
GAN(Generative Adversarial Network)이란 2014년 Ian GoodFellow에 의해 제안된 신경망으로,   
독립적으로 학습된 Generator와 Discriminator의 '적대적 학습'을 기반으로 하는 모델이다.   
Generator는 random한 noise를 생성해내는 vector z를 입력받아 fake image를 출력하며,
Discriminator는 특정 image를 입력받아 진위여부를 가려낸다.
즉, discriminator는 

하지만 minimax 최적화 문제를 해결하는 방식의 GAN은 학습 시 oscillation이 발생하여   
모델이 쉽게 불안정해진다는 문제점을 가지고 있다.   
이를 해결한 모델이 DCGAN이다.

## DCGAN(Deep Convolutional GAN)
DCGAN이란, generator network가 deep convolutional layer로 구성되어 있는 모델이다.

---
1. 코드개요
본 코드는 KAIST AI대학원의 AI504 수업에서 제공된 skeleton code를 기반으로 작성되었다.

2. 실험목적
이러이러한걸 해보려고 했다.

3. 실험결과   
| Learning rate | FID score |   
| --- | --- |   
| 123 | 123 |   
| 456 | **456** |   
