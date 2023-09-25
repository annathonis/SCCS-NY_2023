# SCCS-NY_2023
## Interactive, reproducible, and accessible species distribution modeling for conservation with Wallace    

---

## Organizers 
- Anna Thonis, Stony Brook University [anna.thonis@stonybrook.edu]          
- Daniel Lopez Lozano, American Museum of Natural History [dlopezlozano@amnh.org]    
- Bethany A. Johnson, City College of New  York, CUNY [wallaceecomod@gmail.com]      
  
--- 
  
## Logistics     
- Date: Wednesday, October 4      
- Time: 12:30 - 3:30 pm EST     
- Location: AMNH (room TBD)
   
---  
  
## Description  
Species distribution modeling (SDM) is an important tool for conservation scientists, as it enables us to estimate present species range limits and make predictions about ranges for other areas and time periods. Advances in model-building and evaluation theory are common in the ecology and evolution literature. However, most cutting-edge methods are only accessible to those scientists who can read and write computer code, which results in a 'barrier to use' for many potential users. The Wallace ecological modeling application, implemented in the R programming language as the CRAN package wallace, provides a graphical user interface allowing any user to implement advanced SDM methods. Additionally, Wallace provides extensive guidance text and references key papers from the literature to help both new and experienced users learn best practices. Each model-building session can be exported as a fully documented R Markdown script file, to ensure reproducibility, ease of reporting, and for more advanced users, an easily modifiable code that extends Wallace's functionality. In this workshop, we will go through the basics of SDM using Wallace. We will demonstrate the key features of the modular software, show applications to conservation science, and specifically the utility of SDM outputs for formal IUCN assessments.    
   
---  
   
## Workshop Schedule  
* 12:30 - 12:45: Who we are and why are we here  
* 12:45 - 1:30: Introduction to species distribution modeling  
* 1:30 - 2:00: Introduction to R and Wallace  
* 2:00 - 2:15: Break / troubleshootting  
* 2:15 - 2:45: Wallace live demo and walkthrough  
* 2:45 - 3:15: Using Wallace with your own data  
* 3:15 - 3:30: Preview of new V3 features for conservation  
   
---  
   
## Workshop surveys
Please take the pre- and post-workshop surveys. They help us learn what we did well and what we can do better in the future!
* Before the workshop: [Pre-workshop survey](https://docs.google.com/forms/d/e/1FAIpQLScIxiO97VFdrzhVdA4z0eNz4aL7qpRhyq15KyTI6VvvRViF2Q/viewform?usp=sf_link)  
* After the workshop: [Post-workshop survey](https://docs.google.com/forms/d/e/1FAIpQLSf9RI8A5pArlhGs-GiK-MPgGNxWurfHqE4ulo87SGfy7ef94g/viewform?usp=sf_link)   

---

## Getting started  
Please install R and Wallace prior to this Workshop. Downloading Wallace in R can take a while depending on your computer.   
   
1. Install R (version ≥ v.3.5.0) Download for [Windows](https://cran.r-project.org/bin/windows/base/) or [Mac](https://cran.r-project.org/bin/macosx/) We also recommend downloading [Rstudio](https://posit.co/download/rstudio-desktop/#download), which makes running R visually easier.
Alternatively, you can use [Rstudio cloud](https://posit.cloud/) with a Google or Github account.   
  
2. Install the 'wallace' package from CRAN (version #)  
   * Open Rstudio.   
   * Enter the following code into the terminal and hit Run. This may take a several minutes.   
         
```     
install.packages("devtools")  
devtools::install_github("wallaceecomod/wallace@master")  
library(wallace)  
run_wallace()   
```
        
---   
    
## Data for workshop    
During the workshop, we will allow you to choose your own species to work with during the demo portion. However, in the event of internet connectivity issues or issues with GBIF during the workshop, we have included a dataset you can work with here.    
    
This [canned data](https://drive.google.com/drive/folders/1YwgKWt5J5VOvsro4lsXjb2uf4EfbLU5L?usp=drive_link) includes the following:    
* Occurrence data for two species 
* Environmental data at 2.5 arcmin resolution 
* A binary SDM 
* A shapefile of Colombia 
   
---   
    
## Wallace-specific resources    
[Wallace homepage](https://wallaceecomod.github.io/)     
[Link to Wallace How-To vignette](https://wallaceecomod.github.io/wallace/articles/tutorial-v2.html)     
    
---   
    
## Issues    
If you encounter a bug while using Wallace, you can report it using this [Bug Reporting Form](https://docs.google.com/forms/d/e/1FAIpQLSd4giDOteMbzOkyN-rLghMqWFeVjxjjL1AAWxIt-7qyAQDcbA/viewform)    
