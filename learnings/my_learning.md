# Learnings

1. Put all the files & folder that you don't want to send on git remote in the .gitignore folder. We added folders: 
```\env, \model_files\input & \CLAUDE.md```

2. In order to create a conda virtual environment at a specific location usinf cluade terminal (i.e. bash), we need to create a create_env.sh script
and keep it in the root folder. Then execute the shell script: ```bash create_env.sh``` in the bash terminal of claude code from the IDE.

3. To activate the environment in claude bash terminal we need to execute the command: 
```source /c/ProgramData/anaconda3/etc/profile.d/conda.sh && conda activate "./env"```. Or conversely, we can also add this command in the *create_env.sh* shell script.