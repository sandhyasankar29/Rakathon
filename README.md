# Rakuten-Hackathon
Enhancing RCA in CI/CD pipelines Failures using Gen-AI

System Requirements
Unix/Linux based system
Any running jenkins pipeline 

For now the solution is plugged to jenkins environment but it can be extended to other CI/CD tools like github actions, azure devops

create a Python Virtual Environment with code

$python3 -m venv env

Activate the environment

$source env/bin/activate

Install required Libraries

$pip install -r requirements.txt

Install wkhtmltopdf library
$brew install wkhtmltopdf

Finally in your pipeline post action 
Write an executable shell command to execute the app with

$python3 getBuildLogs.py


Also add the jenkins url and passkey in getBuildLogs.py

