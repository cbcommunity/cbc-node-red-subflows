# VMware Carbon Black Cloud subflows for Node-RED

A collection of [Node-RED](https://nodered.org/) subflows for integrating with VMware Carbon Black Cloud

## Overview

This is a collection of subflows to help interact with the VMware Carbon Black Cloud APIs.

For more information on these endpoints visit our VMware Carbon Black Cloud [Developer Documentation](https://developer.carbonblack.com/).

To use these subflows, copy the JSON blob from one of the JSON files in this repo into your Node-RED instance. Do this by going to Node-RED and in the upper right menu, select Import. Paste the JSON for the subflows you want into the Import section and a new Flow will be created with the available subflows.

All subflows require the [VMware Carbon Black Cloud Platform subflows](https://github.com/cbcommunity/cbc-node-red-subflows/blob/master/subflows/cbc-platform-subflows.json) to instantiate the intance.

# Subflows
Copy/paste these JSON blobs into Node-RED to import the subflows:

- [Platform APIs](https://github.com/cbcommunity/cbc-node-red-subflows/blob/master/subflows/cbc-platform-subflows.json)
- [Endpoint Standard](https://github.com/cbcommunity/cbc-node-red-subflows/blob/master/subflows/cbc-endpoint-standard-subflows.json)
- [Enterprise EDR](https://github.com/cbcommunity/cbc-node-red-subflows/blob/master/subflows/cbc-enterprise-edr-subflow.json)
- [Live Response](https://github.com/cbcommunity/cbc-node-red-subflows/blob/master/subflows/cbc-live-response-subflows.json)
- [Audit and Remediation](https://github.com/cbcommunity/cbc-node-red-subflows/blob/master/subflows/cbc-audit-and-remediation-subflows.json)
