## SIB Biodiversity Bioinformatics 2023 


## Teachers

* [Natasha Glover](https://lab.dessimoz.org/people/natasha_glover)
* [Yannis Nevers](https://lab.dessimoz.org/people/yannis_nevers)
* [Sina Majidian](https://sinamajidian.github.io/)
* [Christophe Dessimoz](https://lab.dessimoz.org/people/yannis_nevers)



## Learning outcomes

This course is centered around comparative genomics. After the course, you will be able to:

* Define orthology, paralogy and their subtypes
* Retrieve orthology information from the OMA database
* Map sequences quickly to their Hierarchical Orthologous Groups
* Infer orthologs on custom genomes using the FastOMA pipeline
* Construct and interpret phylogenetic species trees using OMA data

## Course lectures

The pdf for the slides of the course can be found [here](https://github.com/DessimozLab/SIBBiodiversityBioinformatics2023/blob/b905b11c92d06be967a7fca4aa4389f8bf78ed02/Biodiversity%20bioinformatics%202023.pdf).

## The OMA Academy

To complete the course, you will follow the exercises of the OMA Academy on https://oma-stage.vital-it.ch/oma/academy/ for this course. OMA Academy is an e-learning website with a suite of self-learning modules centered around comparative genomics and phylogenetics. The modules are specifically designed to help computational biologists use OMA, a method and database for inferring orthologs. Each module is stand-alone, with a basic introduction and a series of exercises with hints and answers.


## Prerequisites


### _UNIX_

Participants should have a fundamental knowledge of utilizing the command line on UNIX-based systems. To assess your UNIX skills, you can take a quiz available [here](https://docs.google.com/forms/d/e/1FAIpQLSd2BEWeOKLbIRGBT_aDEGPce1FOaVYBbhBiaqcaHoBKNB27MQ/viewform?usp=sf_link). If you lack experience with the UNIX command line or are uncertain about meeting the prerequisites, we recommend completing the SIB [online UNIX tutorial](https://edu.sib.swiss/pluginfile.php/2878/mod_resource/content/4/couselab-html/content.html). 


### _Software_

We will be mainly working on an [GitPod](https://gitpod.io/), an online integrated development environment (IDE) that allows users to write, edit, and run code directly in a web browser. GitPod is cloud-based, meaning that all software, code, and files needed for the course are stored and processed on remote servers; you will not need to install or configure anything locally.

You can access the GitPod here: [https://gitpod.io/#https://github.com/DessimozLab/SIBBiodiversityBioinformatics2023](https://gitpod.io/#https://github.com/DessimozLab/SIBBiodiversityBioinformatics2023) 

Participants need to sign up for a GitPod account via Github and/or LinkedIn to access 50 hours per month for free, which is ample time to complete the exercises. After logging in, create a new workspace by choosing SIBBiodiverstyGenomics2023, Browser Editor, and Large configuration (8 cores, 16 GB RAM, 50 GB storage). 

Notes: 
GitPod might ask you for permission when it comes to pasting in GitPod terminal, You can click on Allow on the top left corner in Google Chrome. The Safari browser is not recommended. 
You can click on OK if you see a box about changes in the git repository.

If you mistakenly close the browser window, you can go to the GitPod Dashboard and enter your workspace again.
As each user has limited CPU hours, please make sure that you stop the workspace, once you finish the analysis.   


## Schedule Aug 30 2023 


<table>
  <tr>
   <td><strong>Time</strong>
   </td>
   <td><strong>Activity</strong>
   </td>
   <td><strong>In charge</strong>
   </td>
  </tr>
  <tr>
   <td>9:00-9:30
   </td>
   <td>Welcome, Introductions
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>9:30-10:00
   </td>
   <td>Lecture: Overview, objectives, motivation, concept of orthologs, HOGs
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>10:00-10:45
   </td>
   <td><strong>Module 1</strong>: genes, groups, and genomes in the OMA Browser 
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>10:45 - 11:15
   </td>
   <td>Coffee break
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>11:15-11:25
   </td>
   <td>Go over results
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>11:25 - 11:30
   </td>
   <td>Lecture: introduce OMAmer
   </td>
   <td>Yannis Nevers
   </td>
  </tr>
  <tr>
   <td>11:30 - 11:55
   </td>
   <td><strong>Module 2</strong>: Fast placement with OMAmer 
   </td>
   <td>Yannis Nevers
   </td>
  </tr>
  <tr>
   <td>11:55-12:00
   </td>
   <td>Go over results
   </td>
   <td>Yannis Nevers
   </td>
  </tr>
  <tr>
   <td>12:00-12:10
   </td>
   <td>Lecture: FastOMA
   </td>
   <td>Sina Majidian
   </td>
  </tr>
  <tr>
   <td>12:10-12:30
   </td>
   <td><strong>Module 3 part 1</strong>: FastOMA (launch it before lunch)
   </td>
   <td>Sina Majidian
   </td>
  </tr>
  <tr>
   <td>12:30-13:30
   </td>
   <td>Lunch
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>13:30-14:00 
   </td>
   <td><strong>Module 3 part 2</strong>: FastOMA
   </td>
   <td>Sina Majidian
   </td>
  </tr>
  <tr>
   <td>14:00-14:15
   </td>
   <td>Go over results
   </td>
   <td>Sina Majidian
   </td>
  </tr>
  <tr>
   <td>14:15-14:30
   </td>
   <td>Lecture: Gene trees and species trees
   </td>
   <td>Christophe Dessimoz
   </td>
  </tr>
  <tr>
   <td>14:30-15:00
   </td>
   <td>Coffee Break 
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>15:00-16:00
   </td>
   <td><strong>Module 4</strong>: Building Species Trees 
   </td>
   <td>Christophe Dessimoz
   </td>
  </tr>
  <tr>
   <td>16:00-16:15
   </td>
   <td>Go over results
   </td>
   <td>Christophe Dessimoz
   </td>
  </tr>
  <tr>
   <td>16:15-16:45
   </td>
   <td>OMA Clinic
   </td>
   <td>Natasha, Yannis, Christophe
   </td>
  </tr>
  <tr>
   <td>16:45-17:00
   </td>
   <td>Wrap up
   </td>
   <td>Natasha, Yannis, Christophe
   </td>
  </tr>
</table>


