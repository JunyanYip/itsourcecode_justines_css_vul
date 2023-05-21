# itsourcecode_justines_css_vul

##### Some information

Vulnerability type: xss

Position: "body"

ParamKey: "to"

payload: "<script>alert(document.cookie)</script>"

##### Process description

Enter payload in the date selection box.

![xss_1](xss_1.JPG)

The code executes successfully, displaying the user's cookie.

![xss_2](xss_2.JPG)

Packet capture data.

![xss_3](xss_3.JPG)



