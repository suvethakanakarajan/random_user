# Initial Setup
PowerShell instructions. Change the variable value in `project-name`
```ps1
$projectName='<project-name>' # enter projectname
git clone https://github.com/arunachaleshwaran/class-template.git --bare $projectName;
cd $projectName;
git init
git commit -a -m '🎉 Initial commit';
```
add changes