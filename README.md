# python-for-machinelearning

CONFIGURING GIT FOR JUPYTER - 

	git config --global user.name "Swagatika Mahapatra"
	Set your email address: git config --global user.email "swagi88@gmail.com"


CHANGING JUPYTER CONFIGURATIONS TO START FROM A SPECIFIC DIRECTORY -

	Option 1 -
	
	jupyter notebook --notebook-dir='C:\Dev\gitreposSwagi\jupyter'

	You can change the configuration from anaconda command line:

		run anaconda command prompt
		run jupyter notebook --generate-config
		a directory .jupyter/ should have created in your home with a file jupyter_notebook_config.py
		uncomment and edit the field c.NotebookApp.notebook_dir

	Option 2 -
	I'm using windows 7 (64 bit) with Anaconda2. 
	In the start menu, right click Jupyter Notebook -> Properties. In the Target field, change %USERPROFILE% to your new "D:\path". 


SHORTCUTS -

	Shift + Tab = expands signature of the method
	Ctrl + Enter = runs current cell multipletimes
	Ctrl + / = Comments