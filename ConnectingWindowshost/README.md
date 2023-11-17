Command used in ansible machine:

1. Get-Host : To see the version of powershell
2. python3 --version: To check python installed or not
3. pip3 --version: To check pip3 installed or not
4. pip3 show pywinrm: To check pywinrm is not installed or not
5. pip3 install pywinrm: To install pywinrm

Command used in windows:
6. winrm enumerate winrm/config/Listener: To see which ports are configured in winrm
7. winrm set winrm/config/service '@{AllowUnencrypted="true"}': To allow the unencrypted traffic
8. winrm set winrm/config/service/auth '@{Basic="true"}': To do baisc authentication
9. winrm get winrm/config/service
10.winrm set winrm/config/listener?Address=*+Transport=HTTP '@{Port="5985"}'
11.winrm delete winrm/config/Listener?Address=*+Transport=HTTP
