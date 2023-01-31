## Magento2 Programmatically add description option for Customizable Options

> Magento2 we are going to learn how to add an extra field named description under Customizable options value in Admin.

## Installation Steps

Step 1 : Download the Zip file from Github & Unzip it
Step 2 : Create a directory under app/code/Binstellar/Option
Step 3 : Upload the files & folders from extracted package to app/code/Binstellar/Option
Step 4 : Go to the Magento2 Root directory & run following commands

php bin/magento setup:upgrade 
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush


## Note : We have tested this option in Magento ver. 2.4.5-p1