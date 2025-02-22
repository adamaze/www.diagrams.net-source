---
title: Migrate draw.io between Confluence Instances
layout: page
faq: true
categories: [Confluence Data Center and Server, Confluence Cloud]
---

You can migrate from your source Confluence with draw.io installed to your target Confluence instance.

The draw.io data in Confluence consists of two parts:
* attachments on the pages that contain the diagram data
* draw.io macros in the pages that use the attachments

Note that no diagram data is stored outside of your Confluence instance, whether that be Server, DC or Cloud.

Both the macros and attachments will port as part of a standard Confluence to Confluence migration.

**Important:** To ensure links inside diagrams work after migrating, you must perform the export and import steps detailed below. Links in diagrams to Confluence pages contain the page ID of the page. Page names are not used since these break when a page is renamed. Migrating to another Confluence instance will change all of the page ID values, breaking these links.

## Use the draw.io Page IDs Export tool

Save where each link in a diagram points to by exporting the Page IDs.

1. Go to your Confluence administration, and select _draw.io Configuration_ in the left panel, then select the _Page IDs Export_ tab.
2. Select the appropriately target as the _Export target_, then click _Start Export_.
<br /><img src="/assets/img/blog/page-ids-export-confluence-cloud.png" style="max-width:100%;height:auto;" alt="To make sure links in diagrams continue to work, export the page IDs from Confluence to correctly migrate">
3. When the export has finished, you'll see a mapping in the text field below. Select all of this text, copy and paste it into a text editor and save it.

## Import the Page IDs into target Confluence

Restore the link targets in your diagrams by importing the page IDs.

1. As an administrator, click on the gear icon, then on _General configuration_.
2. Under the _draw.io add-on_ heading, select _Configuration_, then select the _draw.io import_ tab.
3. Copy the contents of that text file, then paste it into the large text field to _Import draw.io data from another Confluence instance_, then click _Start import_.
<br /><img src="/assets/img/blog/import-drawio-data-confluence-server.png" style="max-width:100%;height:auto;" alt="Import draw.io diagram data from another Confluence instance">