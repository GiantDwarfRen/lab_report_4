# Lab Report 4
## set up before start
Note, I won the champion of "done quick" competition. TA said no bash script, but I used `alias` to help me run command quick. I demostrated how I did to TAs and after discussion they accepted me using `alias`. 

`alias` is a tool in command line that can create personal command short cuts to run complex command. 

I added alias in `.bash_profile`, a file that will run when starting bash. Thus, each time I connected to the remote ieng6, I can use my customize command. 

Type in `alias` can show all added `alias`. But here I used `nano .bash_profile` to show my alias.

![alias1](./images/alias1.png) 

![alias2](./images/alias2.png)

I'll explain each `alias` in each step. 

## Step 4
Thanks to adding public key to ieng6, I can directly log in from my terminal without password. 

I run the following command to quickly log in:`<^R>ssh <enter>`

`<^R>` stands for "ctrl+R". It's a terminal search command. By typing in "ssh ", it would search historical command containning "ssh ". In my command line history, there is only one match: "ssh cs15lwi23ajc@ieng6.ucsd.edu". By hitting `<enter>`, it will run that command, saving me much more time.

![step4.1](./images/step4.1.png)

![step4.2](./images/step4.2.png)

## Step 5
