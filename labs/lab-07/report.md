# Lab Report 7
### Checkpoint 1
![checkpoint1lab8](https://user-images.githubusercontent.com/44532905/159103540-f7f56a92-af00-4654-a171-366947d28b36.PNG)

### Checkpoint 2
1. When looking at the Nightly and Experimental sections, you can see the tests run on the build by clicking on the build name and looking under the configure sections. It will show the readout of running which will include the names of tests run in the build.
2. I opened up [Linux-Gentoo-Sparc32-gcc4.9](https://open.cdash.org/build/7804258) and saw it failed -- Performing Curl Test HAVE_BUILTIN_AVAILABLE - Failed. This helps debug the failure because it allows us to view the test which will show us the segment of code executing.
3. I looked at a similar one and it had a clean dashboard with no errors. 

![lab8part2](https://user-images.githubusercontent.com/44532905/159103519-8f1ba291-2531-4d85-8461-e76513b10d31.PNG)
![Capture](https://user-images.githubusercontent.com/44532905/159135589-9866790a-093e-42e2-92e2-581e3419620c.PNG)

### Checkpoint 3
![Capture](https://user-images.githubusercontent.com/44532905/159135614-67f4ac0b-d45b-4de0-a221-41fe354a7dab.PNG)
The build failed because the copyright was wrong. I modified this to reflect the current year, 2022 and it passed the tests.

![Capture](https://user-images.githubusercontent.com/44532905/159135728-71ad6798-607e-4fa4-98fb-81c3c9c8c1d6.PNG)

### Checkpoint 4

![lab8part5](https://user-images.githubusercontent.com/44532905/159185424-ff5eabc6-16ec-4453-b324-3939a9d81c43.PNG)
![Capture](https://user-images.githubusercontent.com/44532905/159185571-eb528a06-9fe0-4dbd-9b17-2c1843724ec0.PNG)

https://github.com/babyspider/CMakeStep5Tutorial--OSSClass
