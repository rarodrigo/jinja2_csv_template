# Executing Validation Test about Jinja2 inside Ansible using csv file
The whole process about this developer action were declared inside my BLOG which is better to explain all process, as well as, print screen and explaining each code part.

I explained the role process inside my BLOG and until now are in 5 steps doing test and making validation in different situation. Follow the 4 steps explaining this implementation:

[Part 1 - CSV Configuration File](https://ciscoredes.com.br/2018/03/08/ansible-configuracao-via-csv-file-loops/)<br>
[Part 2 - Configuration inside Jinja2](https://ciscoredes.com.br/2018/03/13/ansible-script-configuracao-usando-jinja2-parte-2/)<br>
[Part 3 - Variable Loop inside Jinja2](https://ciscoredes.com.br/2018/04/02/ansible-loop-de-variaveis-usando-jinja2-parte-3/)<br>
[Part 4 - Loop using variable validation](https://ciscoredes.com.br/2018/04/26/ansible-loop-com-validacao-de-variaveis-parte-4/)<br>

There are many resource used in this script, however all modules are inside Ansible documentation using `roles`, `group_vars`,`jinja2`,`csv file database` and `conditionals`.

We can follow description to execute those tasks:

- Create CSV File Database adding all information are necessary or information are received from another database.
- Making a dictionary in order to populate all variables.
- Splitting in different roles to segregate process and putting clear code.
- Execute Jinja2 template inserting variables and using conditionals to execute different actions.
- Making some validation based in condition ( if, else, while ) to make sure if loopback ids should be implemented
- Generate template script based in your inventory hostname.
- Apply in your device.

PS.: The explanation in BLOG Channel was executed in Portuguese, however there are facilities inside of channel to make a translation.
