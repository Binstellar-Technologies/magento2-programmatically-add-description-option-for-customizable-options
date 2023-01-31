## Magento2 Programmatically add description option for Customizable Options

> Magento2 an open-source e-commerce platform written in PHP.

> Magento2 Customizable Option is one of the cost effective & powerful functionality available, but still sometimes there is a need to add new extra fields in order to describe the option given to customer in more details. 

> Magento2 we are going to learn how to add an extra field named description under Customizable options value in Admin.

> So, in order to do that we have followed some simple steps & added it in this module.

## Installation Steps

##### Step 1 : Download the Zip file from Github & Unzip it
##### Step 2 : Create a directory under app/code/Binstellar/Option
##### Step 3 : Upload the files & folders from extracted package to app/code/Binstellar/Option
##### Step 4 : Go to the Magento2 Root directory & run following commands

php bin/magento setup:upgrade 

php bin/magento setup:di:compile

php bin/magento setup:static-content:deploy -f

php bin/magento cache:flush

&nbsp;
&nbsp;

![image1](https://user-images.githubusercontent.com/123800304/215668619-e3d7ee7a-6a00-4332-9067-3fe38269407f.png)

&nbsp;
&nbsp;

## Note : We have tested this option in Magento ver. 2.4.5-p1
