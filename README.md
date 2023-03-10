## Student Exam Performance End to End ML Project
```

Steps:
Setup Project With GitHub
1. Data Ingestion
2. Data Transformation
3. Model Trainer
4. Model Evaluation
5. Model Deployment

CI/CD Pipelines - GitHub Actions
Deployment - AWS

## --------------------------------------------------------------------

STEP 1:	Setup a GitHub Repository  "mlproject"			

STEP 2: Create a New Folder in your Drive and need to Place all the Project Resources overe thhere

STEP 3: Open VS Code Editor from Anaconda Prompt , prior give the Project Path::   use:  "code ."

STEP 4: Open the Terminal in VS CODE editor  [Short cut key: CTRL + SHIFT + P]

STEP 5: CREATE New Environment Inside the Same Project Folder  name as "venv"		in VS Code CMD Terminal					
        conda create -p venv python==3.8 -y
          
STEP 6: Activate the Terminal:    
	conda activate venv/

the next thing what we are going to do is that we are going to clone this entire repository and we need to sync this with the GitHub so that we'll be able to commit all our code!!

STEP 1:  git init

  We will follow the GitHub Command Rule Actions

STEP 2: Create a "README.md" file /It is just like a file where you can probably write your descriptions,steps you performed
        git add README.md

STEP 3: COMMIT the FIle
        git commit -m "First commit"
        
        
If you really want to see that what is the status with respect to the commit, so I can just try to get status and here you can basically see!!
STEP 4: git status


the next step will be that I have to push this file  into my GitHub repository

STEP 5: git remote add origin https://github.com/saikiran123456/mlproject.git

STEP 6: you'll be able to see that I have actually synced it with my own git repository over here right wrt origin 
      git remote -v 


Before Doing the last Step command, Makesure your GitHub Username and EmailID is Linked in VSCode Editor
git config --global user.name "xyz"				
git config --global user.email xyz@example.com				

STEP 7: git push -u origin Machine-learning		
        // that basically means from the origin to the Machine-LEarning the commit will basically happen
         // NOTE: "Machine-learning" is my main branch name, yours might differ
         
OUTPUT:	and this is how quickly I will be able to see the files in GitHub 
       readme file has got updated, this is how I have made sure that all my sync with respect to this particular code and          the GitHub repository is done
         
```
        
## --------------------------------------------------------------------        
        
	## Create NEW File ".gitignore" inside GitHub:

![image](https://user-images.githubusercontent.com/37768258/224252446-2228bd91-b973-4f0d-b046-7a6f1b27427e.png)

![image](https://user-images.githubusercontent.com/37768258/224252478-2eca5551-7722-4bd1-bc14-a10d4a94346a.png)

![image](https://user-images.githubusercontent.com/37768258/224252509-3e36065a-41b3-4f70-8084-9bf8951a3d1d.png)

![image](https://user-images.githubusercontent.com/37768258/224252556-104d8211-8f07-4350-be55-953967e1d195.png)


## --------------------------------------------------------------------


    ## Back to VS Code Editor:

so for this, in order to make sure that everything is updated on my Local Repository(Project Folder), so I'll just clear VS Code CMD screen & write "git pull", so all the updation will happen now WE have this gitignore file also !!

STEP 1: git pull
 
create a New File name it as: setup.py

STEP 2: setup.py

STEP 3: requirements.txt	

Your Repository should look like this:

![image](https://user-images.githubusercontent.com/37768258/224260905-cd61b1af-221c-46f3-ad34-9f8f1d6ce7e3.png)


STEP 4: Open the "setup.py" file and Code:
![image](https://user-images.githubusercontent.com/37768258/224261160-0f39a9df-f21c-47d5-9805-1a221b10b1d3.png)
						

STEP 5: Create a New Folder "src"

STEP 6: Create a file inside it "__init__.py":

![image](https://user-images.githubusercontent.com/37768258/224261299-9aa721dd-676f-4b20-b690-72a4514fe172.png)


Step 7: Add some Libraries in "requirements.txt" file:

![image](https://user-images.githubusercontent.com/37768258/224261434-f39b38ba-6360-4f8a-be1a-1b97b3f24ffa.png)



Step 8: Code in "setup.py" file:

![image](https://user-images.githubusercontent.com/37768258/224261680-fb8ba033-81f3-411f-9387-8ea9e8cce053.png)


STEP 9:  Install the "requiremets.txt" file

	pip install -r requirements.txt	
	

Your Local Repository should look like this:
![image](https://user-images.githubusercontent.com/37768258/224261990-0dfb7521-b35e-47ec-a5cd-dd74c290945c.png)

   
   
      ## COMMIT all the Changes to GitHub
      
STEP 1:   git add .

STEP 2: git status     //to see what all things has got added

STEP 3:  git commit -m "setup"

STEP 4: git push minus -u origin Machine-learning 

## -----------output--------------------------------------------

  Reload the GutHub Repository:
  
![image](https://user-images.githubusercontent.com/37768258/224262606-d51f6514-03f0-423d-b9aa-af2ce1d9b8d8.png)

so this was the project GitHub setup that we have basically done!!

```
## ---------------2: Setup Files----------------------

I will continue forward and Explain further steps on: 
Now, we are creating all the folder manually to understand better

"components" folder: 
init.py fle inside it, 
All the process will be present
data_ingestion.py, 
data_transformation.py, 
model_trainer.py

Creating "pipeline" folder
There are 3 files inside pipeline: train_pipeline.py, predict_pipeline.py, init.py				


Writing:

own Custom exception.py file and logger.py file
	  
Running the above 2 files and validating the output changes
and finally commiting the changes to GitHub

```
Pipeline:
	     
