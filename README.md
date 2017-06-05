# AEM Mobile Starter Project

This a content package project generated using the AEM Multimodule Lazybones template.

## Building

This project uses Maven for building. Common commands:

From the root directory, run ``mvn -PautoInstallPackage clean install`` to build the bundle and content package and install to a CQ instance.

From the bundle directory, run ``mvn -PautoInstallBundle clean install`` to build *just* the bundle and install to a CQ instance.

## Notes

The com.adobe.cq.mobile.dps.impl.service.AdobeDPSClient config has been added to the ignore list to prevent checkin of secret keys.


