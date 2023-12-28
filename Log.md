REF  DATE    AUTHOR  Changes Made

000  2023-12-27 JG Added this change log file.

001  2023-12-28 SV Added possible features to include README file.

002  2023-12-28 SV Created gitignore file.

003  2023-12-28 SV Installed 'django<4' and upgraded pip.

004  2023-12-28 SV django-admin startproject shop and allow Host

005 2023-12-28 SV Installed Allauth version: 'django-allauth==0.41.0'. 
- In settings.py : imported os, added authentification backend, installed Apps (allauth account, socialmedia...), site_id 1.
- In urls.py : added path and imported include.

006 2023-12-28 SV added in settings.py: email backend and users email authentication

007  2023-12-28 KK Added 3 template files for index.html, style.css and form.html, taken from Code Inst Coders' Coffee House walkthrough

008 2023-12-28 SV created superuser and secret.md with user details, added requirements.txt
I have tried to do this command to copy recursively allauth but it is not working I leave you the command if you can see the error: cp -r /workspace/.pip-modules/lib/python3.12.1/site-packages/allauth/templates/* ./templates/allauth/ 