# Lab 3 Report
## Part 1: Documentation
1.  
This part is in the wiki of this repo.


3.  
The LaTex Code:
$\sqrt{1+2\sqrt{1+3\sqrt{1+4\sqrt{1+\cdots}}}}$  
\newline  
$\sqrt{2}^{\sqrt{2}^{\sqrt{2}^{\sqrt{2}\cdots}}}$  
  
![powslatex](https://user-images.githubusercontent.com/44532905/151681489-c9294eda-81e8-4632-81b7-b16c2ad6c456.png)  
4.  
The LaTex Code:  
\usepackage{amsmath}  
$\begin{bmatrix}  
1 & 1 & 1 & 1\\  
-1 & 1 & -1 & 1\\  
-1 & -1 & 1 & 1\\  
1 & -1 & -1 & 1\\  
\end{bmatrix}$  
  
![matrix latex](https://user-images.githubusercontent.com/44532905/151681506-fd048a4b-f914-4b5d-b8c5-4ba5ba892159.png)

## Part 2: Community
4.  
| Project Name | contributors | lines of code | first commit | latest commit | current branches |
| --- | --- | --- | --- | --- | --- |
| ARAS | 1 |  56794 | 4da6754 09/22/2015 | 8cf1d31 12/04/2017 | master |
| Aris | 14 | 13118 | 69945fe 04/05/2017 | 03819f8 10/22/2021 | master, Key_Palette, proof-generate-solver, Disjunctive_syllogism, gh-pages|
| Article Aggregator | 2 | 543,664 | a3e586a 09/20/2019 | 0f8d55a 12/10/2019 | master |
| Astro.IQ | 1| 195608| bc1107c 01/28/2017 | 4e2df67 05/03/2017 | master, renovate/configure|

5.   
![unknown](https://user-images.githubusercontent.com/44532905/151682162-e110e5b1-624b-4a43-843d-0a074763892c.png)
![unknown](https://user-images.githubusercontent.com/44532905/151682176-d7ccf3bb-a7f4-44d7-b2e6-b4eb2140d3e8.png)
![unknown](https://user-images.githubusercontent.com/44532905/151682172-f5a5347e-ff19-41e3-8bcc-11f7492d2173.png)
![gitstats](https://user-images.githubusercontent.com/44532905/151682173-f4f220d2-63fc-45f4-8a2b-fe41e6eb4b80.png)
  
I noticed that the gitstats were slightly different than the stats we had collected from the github pages ourselves. I noticed specifically for the project I analyzed, Astro.IQ that the contributor numbers were different. I only found one contributor but gitstats managed to pull out 3. Additionally the number of lines were vastly different and gitstats answer was also significantly more detailed including removed line and added line counts. However, gitstats did not have statistics on different branches, so there are limits to its data collection. I tried reading the code for gitstats but I'm not really sure where some of the differences come from.
  
6.  
When I installed Gource and tried to run it on the repository it caused a Segmentation Fault.  

![errormessage](https://user-images.githubusercontent.com/44532905/151904368-92c150ce-6ea1-49cb-b21f-9346a8f5948c.PNG)  
  
On watching the youtube video of running gource, I noticed that it showed who was working on what branch at different times. It was also very cool to watch the project just ballooned out at different times. One question I have is why the different nodes have different colors.
