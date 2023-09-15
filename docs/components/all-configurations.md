# All Configurations

Below is a table that list all configuration for this add-on.

Name | Type | Web Location | CLI Location\* | Description
---- | ---- | ------------ | ------------- | -----------
Rapid7 Assets - Lookup Gen | Saved Search | Settings > Searches reports, and alerts | savedsearches.conf | Populates the lookup file `sa_rapid7_assets`.
sa_rapid7_assets | lookup | Settings > Lookups > Lookup definitions | transforms.conf | Lookup definition for the KVStore collection `sa_rapid7_assets_collection`.
sa_rapid7_assets_collection | KVStore collection | n/a\*\* | collections.conf | KVStore configuration.
sa_rapid7_index | Search macro | Settings > Advanced Search > Search Macros | macros.conf | Index definition for the rapid7 index that contains the sourcetype `rapid7:insightvm:asset`.
identity_manager://sa_rapid7_assets | Asset lookup configuration | Enterprise Security > Configure > Data Enrichment > Asset and Identity Management > Asset Lookups | inputs.conf | Asset configuration lookup to load Rapid7 Assets into the asset database.

> \*CLI locations are relative to `../default`. Any update to CLI configuration files should be done in the local directory.

!!!info
**If you have the [Splunk App for Lookup File Editing <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" }, the KVStore collection `sa_rapid7_assets_collection` is viewable within the Web interface.
!!!
