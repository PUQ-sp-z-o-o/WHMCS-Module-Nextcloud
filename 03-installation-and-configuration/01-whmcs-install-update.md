# WHMCS Installation and Update

### Nextcloud module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-nextcloud.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/) | [Community](https://community.puqcloud.com/)

## System requirements

| Requirement | Minimum |
|-------------|---------|
| **WHMCS** | 8.x+ |
| **PHP** | 8.1+ |
| **ionCube Loader** | v15+ |

> **Note:** The module uses ionCube encoding. Make sure ionCube Loader is installed and active on your server.

---

## Download

The module can be ordered and downloaded from PUQ Cloud:

- **Order / Download:** [https://puqcloud.com/whmcs-module-nextcloud.php](https://puqcloud.com/whmcs-module-nextcloud.php)
- **Community:** [https://community.puqcloud.com/](https://community.puqcloud.com/)
- **Direct download link for the latest version:**

```
wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/PUQ_WHMCS-Nextcloud-latest.zip
```

> All versions can be found at this link:
> [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/)
>
> Older module versions for WHMCS 8 are available in the archive directory:
> [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/archive/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/archive/)

After downloading, extract the archive:

```
unzip PUQ_WHMCS-Nextcloud-latest.zip
```

---

## Installation

### Upload files

Extract the module archive and copy the `puqNextcloud` directory to the WHMCS servers module directory:

```
WHMCS_WEB_DIR/modules/servers/puqNextcloud
```

Once the files are uploaded, proceed to the WHMCS Setup Guide to configure the server and product.

---

## Update

The update procedure is the same as installation — replace the existing files with the new version:

1. Download the latest version as described in the Download section.
2. Unzip the archive.
3. Replace the existing `WHMCS_WEB_DIR/modules/servers/puqNextcloud` directory with the new one.
4. Verify the version number in the module interface matches the new release.

> **Important (v3.0):** Product reconfiguration is required after updating to version 3.0.
