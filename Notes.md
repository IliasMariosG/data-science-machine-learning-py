# Course content
----------------
Sections:
<ol>
  <li>Course Introduction</li>
  <li>Environment Set-Up</li>
</ol>

## Notes
--------
Each number below indicates the respective Section from the Course Content:

2. One of the objectives of this section is to install python with Anaconda. The instructor suggests downloading and installing Anaconda, however I knew that Anaconda is kind of "heavy". Since I do not want to occupy more space in the memor than what I need, I thought to give a chance to a different approach. Through my researched I decided to go with miniconda which
    > is a free minimal installer for conda

    as Conda documentation page states.
    
    ### Basic commands in terminal (I am using zsh):
    
    * ```conda info --envs``` or ```conda env list```
    
    * ```conda create --name <name-environment>``` e.g ```conda create --name test```
    
    * ```conda activate <name-environment>```
    
    * ```conda deactivate <name-environment>```