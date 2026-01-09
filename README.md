# VAIBE_Coding
## Station 2: V(AI)BE Coding for Data Science
#### Instructor: Dr. Tue Vu

### Goal:
- Use Vibe Coding to do an end-2-end Data Science workflow using AI
- Tools: Cursor. Download free version here: www.cursor.com/download 
________________________________________
### 1. Download and setup  (3 min): 
- Download and setup miniconda for your system (Window/MacOS): https://www.anaconda.com/download/success#download
- Download and install cursor for your system (Window/MacOS): www.cursor.com/download

________________________________________
### 2. Introduce Cursor IDE GUI (2 min)
- Create free Cursor account
- In model, choose GPT-4.1
- Open Folder, default to Documents
- Open terminal
- Clone the material from github:

```
$ git clone https://github.com/vuminhtue/VAIBE_Coding.git
$ cd VAIBE_Coding
```

________________________________________
### 3. Install conda environment (3 min)

```
$ conda create -n ds1 python=3.10 -y
$ conda activate ds1
$ pip install -r requirements.txt
```

________________________________________

### 4. Run the Prompt (5 min)
- In Cursor, open Folder VAIBE_Coding that you just clone and start VAIBE Coding using given csv file
- Use the AmesHousing.csv as the tabular data used for this Data Science workflow
- Open Prompt.txt and Paste prompt to the chat bot.

________________________________________
### 5. Create AI report (2 min)
________________________________________
- The prompt also has option to create AI report in Latex format.
- The report in separate chapters are saved in report folder
- Once the main.tex created, we can convert that to pdf:

```
$ pdflatex report/main.tex
```

### 6. Cursor Pro?
- Cursor provide 1 year Pro plan for edu account: https://cursor.com/students


