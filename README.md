# Change-dir-of-jupyter-notebook
1. Under the Windows10 environment, Open Anaconda Prompt and type  jupyter notebook --generate-config ,
2. Type  y  to overwrite the default config,
3. Go to  C:\Users\Administrator\.jupyter   open the jupyter_notebook_config.py  icon choose   Edit with IDLE,
4. Press  Ctrl + F  and find  c.NotebookApp.notebook_dir,
5. Delete the "#", change it to  c.NotebookApp.notebook_dir =  'C:/your/new/path'  and save it.

If you want to change it to the default direction, repeat step 1 & 2.
