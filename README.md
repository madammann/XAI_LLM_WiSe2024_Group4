# About
This repository is used in the course "Explainability of Large Language Models", held by Nohayr Muhammad Abdelmoneim at the University Osnabrück in Winter Semester 2024. This repository belongs to group 4 and the topic "Detecting and Understanding Vulnerabilities in Language Models via Mechanistic Interpretability".

# Getting started
In order to get started you first need to clone this repository to a directory on your drive which has enough space for the code and the model:  
 - 11MB for the cloned repository with data.
 - ~0.7GB for the model.
 - ~1.8-2.0GB for packages (torch mainly).

Then, firstly, clone our group's repository and navigate into it:

```git clone https://github.com/madammann/XAI_LLM_WiSe2024_Group4```

Inside the repository, you need to clone the paper's repository using:

```git clone https://github.com/jgcarrasco/detecting-vulnerabilities-mech-interp```

Then you will need to create a virtual environment and install the packages, for this we start with:

```conda env create -n "XAI_LLM_G4" python=3.12```

Afterwards you need to install pytorch, using either the gpu-accelerated or the cpu version.
For the gpu version, you need to have a graphics card supporting cuda and a recent cuda version installed.
The cuda version does not have to be an exact match, but needs to be as close as possible for the best performance gain.
You can check the installed version using the command:
```nvcc --version```

By checking the official pytorch webpage (here)[https://pytorch.org/], you can find the required cuda installation.
For our purposes we ran, for the gpu version:

```conda install pytorch==2.2.1 pytorch-cuda=11.8 -c pytorch -c nvidia```

And for the cpu version:

```conda install pytorch==2.2.1 -c pytorch```

Finally, you will also need to install the packages from the requirements file.
Simply run:
```pip install -r requirements.txt```

Please verify installation and resolve conflicts manually if needed.  
You may need to disable antivirus or whitelist some packages, you may need to update conda and pip.

# Structure
ADD

# Contact
Fabienne Finas <ffinas@uni-osnabrueck.de>  
Greta Bramow <gbramow@uni-osnabrueck.de>  
Marlon Dammann <mdammann@uni-osnabrueck.de>
