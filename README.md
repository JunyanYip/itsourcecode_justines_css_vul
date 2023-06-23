# itsourcecode_justines_xss_vul

#### Some information

CVE ID: CVE-2023-34486

Vendor of Product: https://itsourcecode.com/

Affected Product: justines(https://itsourcecode.com/free-projects/php-project/hotel-management-system-project-php/) - v1.0.0

Vulnerability type: xss

Attack Type: Remote

Description: itsourcecode Online Hotel Management System Project In PHP v1.0.0 is vulnerable to Cross Site Scripting (XSS). Remote code execution can be achieved by entering malicious code in the date selection box.

Position: "body"

ParamKey: "to"

payload: "<script>alert(document.cookie)</script>"

#### Process description

Enter payload in the date selection box.

![xss_1](xss_1.JPG)

The code executes successfully, displaying the user's cookie.

![xss_2](xss_2.JPG)

Packet capture data.

![xss_3](xss_3.JPG)



