# OpenMediaVault Theme
Beautiful Theme For OpenMediaVault 5.x

<br/>

## Installation
Connect to the omv server via SSH and type the following command:

<br/>


```shell
cd /var/www/openmediavault/css
wget https://raw.githubusercontent.com/VMatrices/openmediavault-theme/main/theme-custom.scss
sassc -t compressed theme-custom.scss theme-custom.css
chown openmediavault-webgui:openmediavault-webgui *
rm -f theme-cuntom.scss
```

<br/>

## Preview

<br/>

Login:

![Login](https://raw.githubusercontent.com/VMatrices/openmediavault-theme/main/Screenshots/login.png)

<br/>

Desktop:

![Desktop](https://raw.githubusercontent.com/VMatrices/openmediavault-theme/main/Screenshots/desktop1.png)

<br/>

Desktop:

![Desktop](https://raw.githubusercontent.com/VMatrices/openmediavault-theme/main/Screenshots/desktop2.png)

<br/>

Phone:

![Phone](https://raw.githubusercontent.com/VMatrices/openmediavault-theme/main/Screenshots/phone.png)
