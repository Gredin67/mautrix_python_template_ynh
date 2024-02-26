<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Matrix-Facebook bridge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mautrix_facebook.svg)](https://dash.yunohost.org/appci/app/mautrix_facebook) ![Working status](https://ci-apps.yunohost.org/ci/badges/mautrix_facebook.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/mautrix_facebook.maintain.svg)

[![Install Matrix-Facebook bridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mautrix_facebook)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Matrix-Facebook bridge quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A puppeting bridge between Matrix and Facebook packaged as a YunoHost service. Messages, notifications (and sometimes media) are bridged between a Facebook user and a Matrix user. Currently the Matrix user can NOT invite other Matrix user in a bridged Facebook room, so only someone with a Facebook account can participate to Facebook group conversations. The ["Mautrix-Facebook"](https://docs.mau.fi/bridges/python/facebook/index.html) bridge consists in a Synapse App Service and relies on postgresql (mysql also possible). Therefore, [Synapse for YunoHost](https://github.com/YunoHost-Apps/synapse_ynh) should be installed beforehand.


**Shipped version:** 0.5.1~ynh1
## Documentation and resources

* Official user documentation: <https://docs.mau.fi/bridges/python/facebook/index.html>
* Official admin documentation: <https://docs.mau.fi/bridges/python/setup/index.html?bridge=facebook>
* Upstream app code repository: <https://github.com/mautrix/facebook>
* YunoHost Store: <https://apps.yunohost.org/app/mautrix_facebook>
* Report a bug: <https://github.com/YunoHost-Apps/mautrix_facebook_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mautrix_facebook_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/mautrix_facebook_ynh/tree/testing --debug
or
sudo yunohost app upgrade mautrix_facebook -u https://github.com/YunoHost-Apps/mautrix_facebook_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>