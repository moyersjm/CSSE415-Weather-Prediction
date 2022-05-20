The folder structure should be like this:
	/top level folder/
		/pickled_models/
		/Global_Weather_Data/
			Events_Conversion.ipynb
			Preprocessing_Day_Selection_Events.ipynb
			All .csv files
		All other Jupyter notebooks

All Jupyter notebooks are documented by markdown cells at the beginning of the notebook.
Make sure to create the file structure above before running any notebooks (even the empty pickled_models folder), otherwise you will get errors and nothing will work.
You should run all model training notebooks on Noether, otherwise they may take an incredibly long time to finish, and you'll probably run out of memory.
Before running the model training notebooks, you should first run Events_Conversion and Preprocessing_Day_Selection_Events, in that order.