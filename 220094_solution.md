# Details



Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 

*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***





## Your zeroth approach below



Reasoning - %%% Since zeroth is a .c file, I used cat to run it in linux terminal.

I already had linux(Ubuntu) installed in VirtualBox so I moved on to the next step.

I decoded the hex online and found the solution to be what is displayed when man command is entered.

Then ran man on terminal. %%%



``` 



%%% What manual page do you want?

For example, try 'man man'. %%%

```



---



## Your first approach below (first.txt)



Reasoning - %%% I read the file using cat. Upon seeing the statement about rotation I searched for what cipher it could be.

Then I decoded the rot cipher using online using website dcode. %%%



```

%%% noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT %%%

```



---



## Your second approach below (strings.txt)



Reasoning - %%% First I used unzip to extract the Lamp_Stack_Task.zip

After opening the directory I used find -name "strings.txt" to find its location and then I opened it using cat.

The content was a bunch of strings with one marked as password for next task.

I then used grep command to find all the strings and used * to search for file.

Upon seeing Is a directory I used */* then */*/* to finally get the strings. Each string were contained in two different directories. %%%



```

%%%  ./question_mark/Lamp_Stack/1/5/0/3/strings.txt %%%

```



---



## Your third approach below (fourth.zip)



Reasoning - %%%I used grep to find the location of the string, there were two eleven.txt and final.txt

I tried to unzip fourth.zip and tried eleven.txt as password first which worked.

I opened the get_in directory and then used grep "DevOps" */*/* to finally get the string%%%



```

%%% y0ur3_4w350m3_4nd_0ne_5t3p_c1053r %%%

```



---





- Name : Akarsh Verma

- Roll : 220094

- GitHub username:AkarshVerma737

- Discord username:Nightshade#9049





## Do not tamper below this line



---



Q29yZSB0ZWFtIGtvIGZha2UgZG8=