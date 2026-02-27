# Changelog

### Docker NextCloud module **[WHMCS](https://puqcloud.com/link.php?id=77)**

##### [Order now](https://puqcloud.com/whmcs-module-docker-nextcloud.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-NextCloud/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### v2.0 Released 27-02-2026

1. **Module Settings:** Added a new integrated product settings UI in WHMCS admin with unified package option handling and backward compatibility with previous option formats.
2. Product module settings have been redesigned  
   ⚠️ **Product reconfiguration is required after update (open the product settings → module configuration, re-check all settings, and click Save)**
2. **Credentials Rules:** Added template-based username/password rules (macros, random patterns, custom charset) with automatic uniqueness handling.
4. **Client Area & Stability:** Refreshed client area templates (status/app/ACL/reinstall), improved loaders and usage formatting, and improved API error handling/logging.

<p class="callout warning">Product reconfiguration is required after update</p>

- - - - - -

##### v1.2 Released 17-11-2025

1. **Security:** Enabled \_\_Host- cookie prefix; added key security headers in NGINX.
2. **Docker Compose:** Removed deprecated version field; improved MariaDB/Redis healthchecks; switched dependencies to service\_started.
3. **Container Management:** Updated Terminated script with full cleanup and explicit container removal.
4. **Result:** Faster deployments, stronger security, cleaner container lifecycle.

- - - - - -

##### v1.1 Released 30-04-2025

1. Support for multi-service docker backend
2. Support custom domain names via PowerDNS
3. Support configuration options, CPU, RAM, DISK

- - - - - -

##### v1.0 Released 28-03-2025

First version
