---
title: API Portal 7.7 November 2020 Release Notes
linkTitle: API Portal November 2020
weight: 60
date: 2020-11-05
---

## Summary

API Portal provides an API consumer-facing interface that you can customize to match your corporate brand. API Portal is a layered product linked to API Manager, and requires both API Manager and API Gateway. For more information, see the API Gateway and API Manager documentation.

## Installation

API Portal is available as a software installation or a virtualized deployment in a Docker container. For more information, see the following options:

* If you are installing API Portal for the first time using this update, see [Install API Portal](/docs/apim_installation/apiportal_install/)
* If you are already using API Portal (7.5.x, 7.6.x, 7.7.x) and want to install this update, see [Upgrade API Portal](/docs/apim_installation/apiportal_install/upgrade_automatic/)
* If you want to deploy API Portal in Docker containers, see [Deploy API Portal in containers](/docs/apim_installation/apiportal_docker/)

## New features and enhancements

### placeholder

placeholder

## Limitations of this update

This update has the following limitations:

* API Portal 7.7.20200930 is compatible with API Gateway and API Manager 7.7.20200930 only.
* Upgrade directly to API Portal 7.7.20200930 is supported from [API Portal 7.7](/docs/apim_relnotes/201904_release/apip_relnotes/) only.
* To upgrade from earlier versions (for example, 7.5.5, 7.6.2) you must first upgrade to API Portal 7.7. For more information see [API Portal single version upgrade](/docs/apim_installation/apiportal_install/upgrade_automatic/#upgrade-from-api-portal-7-6-2) to upgrade versions incrementally.
* You can use the [cumulative upgrade script](/docs/apim_installation/apiportal_install/upgrade_automatic/#upgrade-api-portal-using-the-cumulative-upgrade-script) to upgrade directly from earlier versions (for example, 7.5.5, 7.6.2) to API Portal [7.7 July](/docs/apim_relnotes/20200730_apip_relnotes/), then apply this upgrade package to update your API Portal to the September release.
* The ready-made API Portal Docker image 7.7.20200730 is strictly for development environments only, and it is not recommended for use in production environments.

    It is not recommended to use the image in production environments because the image is built with CentOS as a base OS, and our Axway security scans have detected multiple security concerns with this OS. We continue to monitor the latest versions of this base OS to determine if these issues have been resolved, but until we can ship a hardened image that passes our security concerns, we cannot advise customers to use this image in a production environment. A Docker image for production use is already planned in the [API Portal 2020 roadmap](https://community.axway.com/s/api-portal).
* Upgrading from previous API Portal Docker image is not supported.
* This update is not available as a virtual appliance or as a managed service on Axway Cloud.

## Important changes

It is important, especially when upgrading from an earlier version, to be aware of the following changes in the behavior or operation of the product in this update.

### placeholder heading for Important changes

placeholder text for Important changes

## Deprecated features

<!-- Add features that are deprecated here -->

As part of our software development life cycle we constantly review our API Management offering. As part of this review, no capabilities have been deprecated.

## Removed features

<!-- Add features that are removed here -->

To stay current and align our offerings with customer demand and best practices, Axway might discontinue support for some capabilities. As part of this review, no capabilities have been removed.

## Fixed issues

This version of API Portal includes:

* Fixes from all 7.5.5, 7.6.2, and 7.7 service packs released prior to this version. For details of all the service pack fixes included, see the corresponding *SP Readme* attached to each service pack on [Axway Support](https://support.axway.com).
* Fixes from all 7.7 updates released prior to this version. For details of all the update fixes included, see the corresponding [release note](/docs/apim_relnotes/) for each 7.7 update.

### Fixed security vulnerabilities

Insert table of issues here

### Other fixed issues

Insert table of issues here

## Known issues

The following are known issues for this update.

### placeholder heading for know issues

placeholder text for know issues

## Documentation

This section describes documentation enhancements and related documentation.

### Documentation enhancements

The latest version of API Gateway, API Manager, and API Portal documentation has been migrated to Markdown format and is available in a [public GitHub repository](https://github.com/Axway/axway-open-docs) to prepare for future collaboration using an open source model. As part of this migration, the documentation has been restructured to help users navigate the content and find the information they are looking for more easily.

Documentation change history is now stored in GitHub. To see details of changes on any page, click the link in the **Last modified** section at the bottom of the page.

### Related documentation

To find all available documentation for this product version:

1. Go to [Manuals on the Axway Documentation portal](https://docs.axway.com/bundle).
2. In the left pane Filters list, select your product or product version.

Customers with active support contracts need to log in to access restricted content.

The following reference documents are also available:

* [Supported Platforms](https://docs.axway.com/bundle/Axway_Products_SupportedPlatforms_allOS_en) - Lists the different operating systems, databases, browsers, and thick client platforms supported by each Axway product.
* [Interoperability Matrix](https://docs.axway.com/bundle/Axway_Products_InteroperabilityMatrix_allOS_en) - Provides product version and interoperability information for Axway products.

## Support services

The Axway Global Support team provides worldwide 24 x 7 support for customers with active support agreements.

Email [support@axway.com](mailto:support@axway.com) or visit [Axway Support](https://support.axway.com/).

See [Get help with API Gateway](/docs/apim_administration/apigtw_admin/trblshoot_get_help/) for the information that you should be prepared to provide when you contact Axway Support.
