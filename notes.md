Notes



The part in the podcast where Professor Wattrell talks about thoughtfulness open as a spectrum was important to me as it reframed open data from a simple technical problem to a design challenge. Wattrell is arguing that the model where you build a wall and just put a fate on it(where the data is neither inside or outside) is just insufficient for the real world. There's not just one dataset but multiple views of the same data. I noticed this connects to our work with Gabbi data. When I noticed that stratigraphic units like 1135 and 1170 were part of a structural system, I was thinking like a data analyst seeing a foreign key relationship. But from Wattrell's perspective, that relationship itself might be sensitive. The podcast helped 


- Going through the workbook activity
- Launch new notebook powered by R
- Wouldn’t let me create a new R book. I’m not sure but i have issues when using R in the lab so I’ll always use my R console on my mac and upload the code into the notebook
- Was able to download the libraries but my R console wouldn’t continue with the rest of the code(picture of error)
<img width="963" height="69" alt="Screenshot 2025-11-26 at 12 55 30" src="https://github.com/user-attachments/assets/3d62d93b-df35-4fd0-8ce3-aadc9a677b26" />

- I decided to look up what was wrong with my R notebook. Downloaded through https://cran.r-project.org/ and ran commands in the terminal(install.packages('IRkernel') IRkernel::installspec(user = TRUE). After restarting JupyterLab my R notebook started to appear. Go forward with R code in Week 11
- I had a hard time trying to understand the glass table and how Cone Beaker gets filtered as when we run the code, Cone beaker is not the only that appears but things like Bowl, Jar, etc.
- An observation I made when running the Bar plot is that it’s really vague and doesn't explain the data unless you pair it together with the code we ran before but by itself it's hard to tell what's going on. 
- Going through the old workbooks to retrieve the R codes we learned and apply it to this week's exercise.
- Some questions that popped when doing this exercise were if there are certain glass forms that are statistically associated with specific time periods. I decided to use chi square to test and see if it is (conclusion was that it was as per workbook)
- Another question I had was seeing what were the most common glass forms in the dataset and how often do they appear.
- When it comes to selecting your own ADS database, I spent a while but I was not able to find one where I could properly translate it into R code as I kept getting errors no matter how I formatted it. I decided to spend more time analyzing the chosen database in the workbook instead and interpreting the data. 

- Moving onto the next exercise about Marwick’s paper. Marwick basically argues that the two sites show different stages of stone toolmaking. Tham Lod Area 1 has more flakes with cortex still on them. Ban Rai Area 3, on the other hand, has way less cortex. So Tham Lod Area 1 looks more like a place where people were starting the reduction process, and Ban Rai Area 3 looks like a spot focused on finer shaping or finishing work.
- We created a new notebook called conclusion and ran the R code to see our findings. Had to comment out the library tidyverse as I would keep getting errors and have added the ggplot library.
- After running the code we end up with two plots.
- In the first plot: Tham Lod shows lower median values compared to Ban Rai which shows that Tham Lod flakes generally have less cortex remaining.

- In the second plot: Tham Lod has a higher proportion of flakes with zero dorsal cortex 

- After reading Loiselle's conclusion, her results line up with Marwick's findings. When I ran the same code she used, I ended up with the same pattern as well. Tham Lod Area 1 has more flakes with cortex, and Ban Rai Area 3 has more flakes without cortex.
She also noticed her numbers didn't match Marwick's completely when using the same dataset. Even with the difference her results support his interpretation with the main takeaway staying consistent.
