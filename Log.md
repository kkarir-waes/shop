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
**We need to add superuser account and migration**
