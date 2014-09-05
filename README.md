## Login_3.21

***

###### LineagePLUS did not create L1Login, I am looking for the source-code or to decompile too rebuild

***

### Encode `v3.20`
#### Tab I
###### Left Sife
- Server Name
- IP / Domain Name
- Port 
- Client version

###### Right Side
- Packet Encrytion
- Anti-Plug
- Advanced Plug-In
- Pak version 
- LinHelper
- Mobile Packet not encrypted
- Allow multi open

###### Bottom
- Server #
- Save all the above settings

#### Tab II
###### Section I.
Generates `pack.properties`

	Autoentication=True
	RSA_KEY_E=########
	RSA_KEY_D=#########
	RSA_KEY_N=##########

###### Section II
- Copies data

###### Section III
- Select Client Version
- Creates `ver.pak` from `ver.txt`

#### Tab III

    Line 1 | http://update.domain.name/terms/index.html
    Line 2 | http://update.domain.name/login.ini
    Line 3 | http://update.domain.name/pc/update.ini