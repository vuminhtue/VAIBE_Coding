# VAIBE_Coding
## V(AI)BE Coding for Data Science
#### Instructor: Dr. Tue Vu (tuev@smu.edu)

### Vibe Coding
- AI-assisted software development technique that helps user to code from prompt
- Introduced by Andrej Karpathy in 02/2025, a Director of AI and Autopilot vision at Tesla, also cofounder of AI research group at OpenAI
  
### Goal:
- Use Vibe Coding to do an end-2-end Data Science workflow using AI
- Tools: VSCode. Download free version here: [https://code.visualstudio.com]
________________________________________
### 1. Download and setup  (3 min): 
- Download and setup **Miniconda** for your system (Window/MacOS/Linux): https://www.anaconda.com/download/success#download
- Download and install **VSCode** for your system (Window/MacOS/Linux): [https://code.visualstudio.com]
- Create Github account and register with FREE Github copilot pro [https://docs.github.com/en/copilot/how-tos/manage-your-account/get-free-access-to-copilot-pro]
  - With Github copilot pro, you can have access to best/latest LLMs for vibe coding
  - This takes 72 hours to activate, in the mean time you can use free Github version for VSCode login

________________________________________
### 2. Introduce VSCode Integrated Development Environment (IDE) GUI (2 min)
- File/Open Folder, default to Documents
- Open **Terminal**
<img width="245" height="147" alt="image" src="https://github.com/user-attachments/assets/c3d5b503-f007-49ac-b8f8-93c138f32080" />

- In the terminal, Clone the material from github:

```
$ git clone https://github.com/vuminhtue/VAIBE_Coding.git
$ cd VAIBE_Coding
```

________________________________________
### 3. Install conda environment (3 min)
- In terminal:
```
$ conda create -n ds1 python=3.10 -y
$ conda activate ds1
$ pip install -r requirements.txt
```

________________________________________

### 4. Run the Prompt (5 min)
- In VSCode, open Folder VAIBE_Coding that you just clone and start VAIBE Coding using given csv file
- Use the ***AmesHousing.csv*** as the tabular data used for this Data Science workflow
- Click on Prompt.txt and start chatting, for example, if you want to have a better prompt before apply Vibe coding:

```
From the prompt, create a comprehensive prompt for me
```

________________________________________
### 5. Create AI report (2 min)
________________________________________
- The prompt also has option to create AI report in Latex format.
- The report in separate chapters are saved in report folder
- Once the main.tex created, we can convert that to pdf using **pdflatex**:

```
$ pdflatex report/main.tex
```

**Note:** if you do not have pdflatex installed, you can do that for your system:
- Window: Download the installer from miktex.org/download
- MacOS: Download the MacTeX.pkg installer from tug.org/mactex

### Recording:
- The recording below is for Cursor, it is the same as using VSCode:

https://www.youtube.com/watch?v=bVye4ZYCblM

