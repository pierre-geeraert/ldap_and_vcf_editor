# convert-csv-to-ldif
python script to convert csv to ldif for openldap

previous I take a .vcf file from phone, then I use this website https://www.aconvert.com/document/ to make a csv, I remove some unused tabs then I use the python script.
It's not compulsary to modify csv files because python use index to retrieve data 


You have to create a "ignore" folder and put a "ldap_credential" in this folder.
In this file, put your credential:
{"id": "cn=admin,dc=ldap,dc=fr", "password": "PASSWORD", "server": "ldap.fr", "token_pushbullet":  "TOKEN", "baseDN":  "dc=ldap,dc=fr"} 

##to do:
send email when new contact found in VCF
automatically create contact with VCF infos and ask by mail if we need to change
finish birthday script and push to prod
(python) web interface (django ??)
