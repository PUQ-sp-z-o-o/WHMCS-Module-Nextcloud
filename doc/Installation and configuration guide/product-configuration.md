# Product Configuration

#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-nextcloud) | [Dowload](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Nextcloud/) | [FAQ](https://faq.puqcloud.com/)

##### Add new product to WHMCS

```
System Settings->Products/Services->Create a New Product
```

In the **Module settings** section, select the **"PUQ Nextcloud"** module

[![image-1660028835238.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660028835238.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660028835238.png)

- **License key:** A pre-purchased license key for the **"PUQ Nextcloud"** module. For the module to work correctly, the key must be active
- **Unit:** Packet disk space units
- **Disk space size:** Disk size in this product
- **Notification disk limit email template:** Email template that will be sent when the disk quota is exceeded in %
- **Notification, used disk space X %:** Sets a percentage parameter, after exceeding this parameter a notification will be sent to the user
- **Username prefix/Username suffix:** Necessary in order to generate a username for the service, in the format: **prefix&lt;cliet\_id&gt;-&lt;service\_id&gt;suffix**
- **Group:** The group that will be assigned to the user on the server side of the Nextcloud
- **Save usage history (days):** The number of days it takes to save user disk usage statistics
- **Link to instruction:** Link to the instruction, if filled out, it will be reflected in the client area