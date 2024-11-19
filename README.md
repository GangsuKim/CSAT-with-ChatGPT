# Humans, are we smarter than ChatGPT?

In this repository, we report on the score and level of ChatGPT on CSAT, a college scholastic ability test in South Korea.

## 🔢Math
### Pipeline (ChatGPT-o1 series)
1. Capture each question and convert to LaTex using ChatGPT-4o  
2. Send a LaTeX text as a prompt to ChatGPT-o1 series
### Pipeline (ChatGPT-4o and older)
1. Capture each question of CSAT.  
2. Send a captured image as a prompt to ChatGPT

> Click 📄 icon next to each subject to check LaTeX prompts. (Korean)  
> Click 📑 icon to check score card of each model and subject.


### Results
|Model|Common[📄](./prompts/1.Math_common.txt)|Different and Integral Calculus[📄](./prompts/1.Math_Different_and_integral_Calculus.txt)|Probability and Staristics[📄](./prompts/1.Math_Probability_and_Staristics.txt)|Geometry|
|:---:|:---:|:---:|:---:|:---:|
|o1 preview[📑](./results/o1-preview.md)|**58**/74|**19**/26|**22**/26|N/A|
|o1 mini|**51**/74|**16**/26|**26**/26|N/A|
|4o|**50**/74|**12**/26|**15**/26|N/A|
|4o mini|**45**/74|**15**/26|**10**/26|N/A|

*Geometry will be update after the limit of the ChatGPT-o1 (Estimate. Nov 21 2024. 11 PM UTC+9)* 
