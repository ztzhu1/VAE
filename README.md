### Variational AutoEncoder

+ The outputs are vague, which can be understood when generating images with VAE.
+ All the outputs have similar hue color. To improve this, we can implement K-means algorithm to segment figure into a finite color set. Then pick colors, according to output values, only from the set. <a href='https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.php'>[Hung-yi Lee]</a>
