This application will classify the password wheather it is a strong one or weak one
to make this project work we need two models files model1_pickle and vectorise_pickle

the output of those model will be 0,1 and 2
In this 0 refers to weak, 1  refers to average and 2 refers to strong
If we want to change 1 as weak we need to change the logic in base_gui.py


DESCRIPTION
	We had took the exisiting algo from kaggle and converted the model into pickle object.pickle is used in tkinter gui file 
by using the object we can get the value as 0,1 and 2 and tkinter will display the result as weak,average and strong according
the given condition
