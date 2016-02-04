---
layout: default
title: Test page
---

#### Table of contents

* [Titolo1](#titolo1)
	* [Titolo2](#titolo2)
		* [Titolo3](#titolo3)
			* [Titolo4](#titolo4)
				* [Titolo5](#titolo5)


# Titolo1

Bacon ipsum dolor amet elit eu drumstick qui in ribeye ball tip chuck prosciutto
tri-tip cupim commodo picanha ipsum aliquip. Ea nisi tri-tip jowl aute cupim
duis sausage. Hamburger incididunt shankle pork ham hock, sunt proident et
t-bone pork loin. Tempor kielbasa adipisicing fugiat pork ea laborum.

Officia alcatra sed aliquip, labore minim consequat anim picanha in kielbasa. Adipisicing in meatloaf, enim esse tenderloin pork belly tail ball tip sed nisi minim proident. Tempor eiusmod frankfurter dolore. Ham laboris laborum kielbasa quis dolore brisket in. Landjaeger aute jowl sint shank ribeye salami fugiat nostrud aliquip rump laborum minim.

## Titolo2

Turducken nulla consequat, beef ribs chuck drumstick pariatur jowl elit bresaola
non labore tongue qui. T-bone lorem mollit deserunt, irure fugiat jowl magna et
nostrud. Leberkas filet mignon do pastrami enim. Bacon biltong et, bresaola ut
ut meatball culpa swine pork belly cupim tongue minim. Occaecat brisket proident
ibeye tongue sed.

Sausage rump salami spare ribs, magna reprehenderit brisket cow do. Eiusmod laboris short loin minim, ea voluptate kielbasa do anim lorem turducken pastrami meatloaf. Pariatur pork aliqua laborum enim. Pork chop sed mollit in turkey short ribs adipisicing dolore picanha ut boudin in.

### Titolo3

Questa è la prima riga.
Questa riga è a capo.

Questa riga ha una riga vuota prima.


Questa riga ha due righe vuote prima.

	questa riga ha un tab a sinistra e una riga vuota sopra

```bash
questa porzione di codice è tra i tre apici e una riga vuota sopra
```


```bash
questa porzione di codice è tra i tre apici e due righe vuote sopra
```


```bash
	questa porzione di codice è tra i tre apici e due righe vuote sopra e un tab
```


```bash
		questa porzione di codice è tra i tre apici e due righe vuote sopra e due tab
```

~~~bash
questa porzione di codice è tra le tre tilde e una riga vuota sopra
~~~

Questo che segue è un bash script:

~~~bash
#!/bin/bash
# This script clears the terminal, displays a greeting and gives information
# about currently connected users.  The two example variables are set and displayed.

clear				# clear terminal window

echo "The script starts now."

echo "Hi, $USER!"		# dollar sign is used to get content of variable
echo

echo "I will now fetch you a list of connected users:"
echo							
w				# show who is logged on and
echo				# what they are doing

echo "I'm setting two variables now."
COLOUR="black"					# set a local shell variable
VALUE="9"					# set a local shell variable
echo "This is a string: $COLOUR"		# display content of variable
echo "And this is a number: $VALUE"		# display content of variable
echo

echo "I'm giving you back your prompt now."
echo
~~~

Quella che segue è una tabella:

|   Var. Name                           |   Description |
|:--------------------------------------|:--------------|
|STORM_BACKEND_HOST                     |Host name of the StoRM Backend server. **Mandatory**.
|STORM_BACKEND_REST_SERVICES_PORT       |StoRM Backend server REST port. Optional variable. Default value: **9998**
|STORM_BE_XMLRPC_PORT                   |StoRM Backend server XMLRPC port. Optional variable. Default value: **8080**
|STORM\_FRONTEND\_PORT                  |StoRM Frontend server SRM port. Optional variable. Default value: **8444**
|STORM\_GRIDHTTPS\_CERT\_DIR            |Host certificate folder for SSL connector. Optional variable. <br/>Default value: **/etc/grid-security/STORM\_GRIDHTTPS\_USER**
|STORM\_GRIDHTTPS\_HTTP\_ENABLED        |Flag that enables/disables http connections. Optional variable. Available values: true, false. <br/>Default value: **true**
|STORM\_GRIDHTTPS\_HTTP\_PORT           |StoRM GridHTTPs http port. Optional variable. <br/>Default value: **8085**
|STORM\_GRIDHTTPS\_HTTPS\_PORT          |StoRM GridHTTPs https port Optional variable. <br/>Default value: **8443**
|STORM\_GRIDHTTPS\_USER                 |StoRM GridHTTPs service user. Optional variable. <br/>Default value: **gridhttps**
|STORM\_SRM\_ENDPOINT                   |StoRM SRM EndPoint. Optional variable. <br/>Default value: **STORM\_BACKEND\_HOST:<br/>STORM\_FRONTEND\_PORT**
|STORM\_USER                            |StoRM Backend service user. Optional variable. <br/>Default value: **storm**
|X509\_CERT\_DIR                        |The location of certificates truststore. Optional variable. <br/>Default value: **/etc/grid-security/certificates**
|X509\_HOST\_CERT                       |Host certificate location. <br/>Default value: **/etc/grid-security/hostcert.pem**
|X509\_HOST\_KEY                        |Host certificate key location. Optional variable. <br/>Default value: **/etc/grid-security/hostkey.pem**
|CANL\_UPDATE\_INTERVAL                 |Canl truststore update time interval expressed in milliseconds. Optional variable. Default value: **600000** (1 minute)

#### Titolo4

Officia alcatra sed aliquip, labore minim consequat anim picanha in kielbasa. Adipisicing in meatloaf, enim esse tenderloin pork belly tail ball tip sed nisi minim proident. Tempor eiusmod frankfurter dolore. Ham laboris laborum kielbasa quis dolore brisket in. Landjaeger aute jowl sint shank ribeye salami fugiat nostrud aliquip rump laborum minim.

Officia alcatra sed aliquip, labore minim consequat anim picanha in kielbasa. Adipisicing in meatloaf, enim esse tenderloin pork belly tail ball tip sed nisi minim proident. Tempor eiusmod frankfurter dolore. Ham laboris laborum kielbasa quis dolore brisket in. Landjaeger aute jowl sint shank ribeye salami fugiat nostrud aliquip rump laborum minim.

##### Titolo5

Officia alcatra sed aliquip, labore minim consequat anim picanha in kielbasa. Adipisicing in meatloaf, enim esse tenderloin pork belly tail ball tip sed nisi minim proident. Tempor eiusmod frankfurter dolore. Ham laboris laborum kielbasa quis dolore brisket in. Landjaeger aute jowl sint shank ribeye salami fugiat nostrud aliquip rump laborum minim.

Officia alcatra sed aliquip, labore minim consequat anim picanha in kielbasa. Adipisicing in meatloaf, enim esse tenderloin pork belly tail ball tip sed nisi minim proident. Tempor eiusmod frankfurter dolore. Ham laboris laborum kielbasa quis dolore brisket in. Landjaeger aute jowl sint shank ribeye salami fugiat nostrud aliquip rump laborum minim.

Officia alcatra sed aliquip, labore minim consequat anim picanha in kielbasa. Adipisicing in meatloaf, enim esse tenderloin pork belly tail ball tip sed nisi minim proident. Tempor eiusmod frankfurter dolore. Ham laboris laborum kielbasa quis dolore brisket in. Landjaeger aute jowl sint shank ribeye salami fugiat nostrud aliquip rump laborum minim.
