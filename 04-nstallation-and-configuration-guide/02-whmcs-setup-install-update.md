# WHMCS setup(install/update)

### Docker NextCloud module **[WHMCS](https://puqcloud.com/link.php?id=77)**

#####  [Order now](https://puqcloud.com/whmcs-module-docker-nextcloud.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/) | [FAQ](https://faq.puqcloud.com/)

### System requirements

The module is encoded with **ionCube**.

**Requirements:**

- PHP **8.2 or higher**
- WHMCS **9.x or higher**
- ionCube Loader **v13 or newer** (v14, v15)

<p class="callout warning">**Older module versions for WHMCS 8**  
  
Older versions of the module are stored by PHP version in separate directories:  
PHP 7.4  
[https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/php74/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/php74/)  
  
PHP 8.1  
[https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/php81/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/php81/)

To install and update a module, you must perform one and the same action.</p>

#####  

##### 1. Download the latest version of the module.

PHP 8.2

```Powershell
wget http://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/php82/PUQ_WHMCS-Docker-NextCloud-latest.zip
```

All versions are available: [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/)

##### 2. Unzip the archive with the module.

```Powershell
unzip PUQ_WHMCS-Docker-NextCloud-latest.zip
```

##### 3. Copy and Replace "puqDockerNextCloud" from "PUQ\_WHMCS-Docker-NextCloud" to "WHMCS\_WEB\_DIR/modules/servers/"
