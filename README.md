# Challenge 4

# What was the challenge?
## To write a playbook that installs Docker onto the local machine.

# How I expected the challenge to go.
## At first I thought it would have been abit difficult due to the simple nature of the question and knowing that it contained a complex playbook. However I was really pleased how the challenge went. I manage to understand and how to approach the challenge. I felt confident in excuting what was required.

# What went well?
## The use of the tutorial was key to understanding the structure of how to design a playbook.yaml file however the process of installing docker wasn't something I have done on Ansible or on the virtual machine from scratch before. With the understanding of the structure, I had to instruct the playbook to do what I wanted it to do. Given the key information by Ben on teams, I constructed the playbook in a logical order and used ansible documentation as a guide (https://docs.ansible.com/) to preform some of the tasks that wasn't in the tutorials. Having this thought-process was ground-breaking for me as it enabled me to complete the challenege in a successful manner. 

# What didn't go as planned?
## At the final step of the playbook, it was optional to have 'install the python package docker using pip' however this seems to have caused an error on the playbook. To tackle this I took the approach to install pip as a dependency with the other requirements but this route failed, the next step was to turn to ansible documentation which gave me a more complex task to put into the playbook however this path also failed. I then requested for help from Ben and we both came to the conclusion to check the version of Ansible installed and realised the dependency we was installing was python version 3 however the ansible we downloaded was operating on python version 2 which was the reason as to why I kept getting errors in my playbook.

# Possible improvements for future challenges.
## To always check what version software you are using and operational dependencies versions required to run the application. To keep using Ansible documentation as a guide for future uses on Ansible  
