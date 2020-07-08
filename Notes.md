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
    
    <br>* ```conda info --envs``` or ```conda env list```</br> 
    <br>* ```conda create --name <name-environment>``` e.g ```conda create --name test```</br> 
    <br>* ```conda activate <name-environment>```</br> 
    <br>* ```conda deactivate <name-environment>```</br>
    <br>* ```conda remove --name <name-environment> -all``` If you want to delete the environment you made

    The course uses jupyter notebook as part of Anaconda. I worked around it with the use of terminal. I also knew that I wanted to open jupyter notebook on Chrome, since Chrome is the suggested browser for software development. Through my research I figured how to set the default browser to Chrome when opening jupyter:

    <br>* ```jupyter notebook --browser="chrome"```</br>
    <br>* ```jupyter notebook --generate-config``` It creates a configuration file</br>
    <br>The config fie is located in your user directory and should look like:</br>
    <br> ```/Users/User/.jupyter```</br>
    <br>Go to the directory with the ```cd``` commande and open the configuration file:</br>
    <br>* ```code jupyter_notebook_config.py``` or ```open jupyter_notebook_config.py``` (*To add how to add ```code``` in the path on vscode*)</br>
    <br>Once opened, search for:</br>
    <br> ```# c.NotebookApp.browser = ''</br>
    <br> Uncomment the line and change it to:</br>
    <br> ```c.NotebookApp.browser = 'chrome'```</br>
    <br>Save the file. Now, when you start up Jupyter Notebook from the command line it will open with Chrome.<br>
    <br>*source: [DevelopRx!] (http://developrx.com/rx-jupyter-notebook-select-browser/)</br>