# Lab 10

## Checkpoint 1
![lab11part1](https://user-images.githubusercontent.com/44532905/162596188-12bd8453-4b38-472d-bd8d-f7181ed894ab.PNG)

## Checkpoint 2
![lab11part2](https://user-images.githubusercontent.com/44532905/162596202-a88e144a-e55b-444a-a533-55e3c21cb0d8.PNG)  

## Checkpoint 3 
I ran your examples first to see that I was doing it correctly and got the results below:  

![small_shirt3](https://user-images.githubusercontent.com/44532905/162596217-9e01cccd-9579-455e-b1d9-00e09903e571.png)  
Test accuracy: 0.8628000020980835
(1, 28, 28)
[[2.1112149e-07 3.8408770e-13 3.9186165e-05 6.8479932e-07 4.8304084e-03
  6.5922250e-12 9.9512947e-01 3.3665822e-15 5.0119568e-11 4.6098569e-11]]    
6
Shirt  

![small_shirt2](https://user-images.githubusercontent.com/44532905/162596223-6e93c521-aedf-427a-8597-2e1b3c9cbcd3.png)  
Test accuracy: 0.857699990272522
(1, 28, 28)
[[6.8188226e-03 2.4978658e-07 8.4141664e-02 1.6425502e-02 5.9973633e-01
  1.6326277e-02 2.7647847e-01 2.6469190e-05 2.0885103e-05 2.5293666e-05]]  
4
Coat
  
My Results were not nearly as acccurate:  

![download](https://user-images.githubusercontent.com/44532905/162596234-9aea349c-19ce-41ce-96dd-127fd6cb355d.jpg)  
![shirti](https://user-images.githubusercontent.com/44532905/162596237-6b62752b-3f8a-4be9-a15a-5293403ba1d6.jpg)  

Test accuracy: 0.8686000108718872
(1, 28, 28)
[[7.3216055e-05 3.9273104e-08 6.8892376e-05 5.6528634e-06 3.9281214e-05
  3.2763374e-08 1.2481889e-04 3.1260570e-09 9.9968803e-01 7.1830737e-09]]  
8
Bag
  
![ogbag](https://user-images.githubusercontent.com/44532905/162596243-958c18ad-40d9-4a73-8772-36cf61240315.jpg)  
![bagi](https://user-images.githubusercontent.com/44532905/162596246-7562417a-1e68-4f0d-80a0-d5d115ee0698.png)  

Test accuracy: 0.8567000031471252
(1, 28, 28)
[[2.0981865e-01 1.7561149e-02 9.1947941e-03 4.0684620e-01 1.4843353e-03
  2.3021412e-01 6.2279057e-02 1.6077119e-04 5.9564229e-02 2.8767099e-03]]
3
Dress

    
But when I run it on the noninverted one I get:  
![bag](https://user-images.githubusercontent.com/44532905/162596364-fa2996a4-64c6-4364-ab73-e217de369c3f.png)  
Test accuracy: 0.8695999979972839
(1, 28, 28)
[[1.56339178e-10 1.71980363e-13 4.50139614e-09 4.05112657e-13
  1.38356725e-14 3.39661689e-26 4.68681748e-07 2.26024853e-23
  9.99999523e-01 4.08346067e-28]]
8
Bag

![newbooties](https://user-images.githubusercontent.com/44532905/162596253-f35f5782-a4c2-434f-9182-36de4fb9c5d0.jpg)  
![newbootieslittle](https://user-images.githubusercontent.com/44532905/162596256-089cbcd8-195a-4f39-8ad0-95063d9eff28.jpg)  

Test accuracy: 0.8783000111579895
(1, 28, 28)
[[3.2869391e-11 1.1275747e-12 3.4240423e-11 2.7574587e-14 6.8376232e-10
  2.9257636e-14 5.7457011e-10 2.1777187e-16 1.0000000e+00 3.7569889e-19]]
8
Bag

None of my images were accurately predicted when put through the image processing in the lab so I do think it is difficult to do.
