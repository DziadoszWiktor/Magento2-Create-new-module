# **Create new module in Magento 2**
**An implementation of a new custom Magento 2 module**

<br>

## **Installation**
Clone this repo into your Magento 2 project in `/app/code` folder.

## **After Installation**
Run

    bin/magento setup:upgrade
    bin/magento setup:di:compile
    bin/magento cache: flush

In some cases `setup:upgrade` is enough

Enable the new module

    bin/magento module:enable Wiktor_NewModule


Make sure the new module is enabled

    bin/magento module:status


<br>
Compatible with Magento 2.1.x, 2.2.x, 2.3.x and 2.4.x