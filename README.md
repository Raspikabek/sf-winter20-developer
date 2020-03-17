# Platform Developer I Certification Maintenance (Winter '20)

## Get Hands-on Creating Custom Tabs for Lightning Web Components

Components needed for [this trailhead](https://trailhead.salesforce.com/content/learn/modules/platform-developer-i-certification-maintenance-winter-20/get-handson-creating-custom-tabs-for-lightning-web-components)

1. Make sure you're connected to your Playground Trailhead org (or destination org selected to Check the challenge)

1. Deploy the LWC `myComponent` into your Play org with sfdx
1. Deploy the custom tab `Words` into your org sfdx

OR

Use the following command:

```
# If your Playground Trailhead org is the default one
sfdx force:source:deploy -m "LightningComponentBundle, CustomTab"

# Specifying the target org alias/usename
sfdx force:source:deploy -a YOUR_ORG_ALIAS -m "LightningComponentBundle, CustomTab"
```
