# Executing Validation Test about Jinja2 inside Ansible using csv file
The whole process about this developer action were declared inside my which is bette to explain all process as well as print screen shot and explainig each code part.

I would like to explain the role process inside my BLOG was explained in 3 steps doing test and making validation in different situation. Follow the 3 steps explaining this implementation:

[Part 1 - CSV Configuration File](https://ciscoredes.com.br/2018/03/08/ansible-configuracao-via-csv-file-loops/)<br>
[Part 2 - Configuration inside Jinja2](https://ciscoredes.com.br/2018/03/13/ansible-script-configuracao-usando-jinja2-parte-2/)<br>
[Part 3 - Variable Loop inside Jinja2](https://ciscoredes.com.br/2018/04/02/ansible-loop-de-variaveis-usando-jinja2-parte-3/)<br>

There are many resource used in this script, however all modules are inside Ansible documentation using `roles`, `group_vars`,`jinja2`,`csv file database` and `conditionals`.

We can follow description to execute those tasks:

- Create CSV File Database adding all information are necessary or information are received from another database.
- Making a dictionary in order to populate all variables.
- Splitting in different roles to segregate process and putting clear code.
- Execute Jinja2 template inserting variables and using conditionals to execute different actions.
- Generate template script based in your inventory hostname.
- Apply in your device.

PS.: The explaination in BLOG Channel was executed in Portuguese, however there are facilities inside of channel to make a translation.
