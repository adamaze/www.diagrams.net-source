---
title: Using draw.io in Confluence Cloud
layout: page
categories: [Confluence Cloud]
---

draw.io is a fully featured diagramming tool, with large shape libraries and templates for a wide range of diagrams. 

**Confluence users** who are new to diagramming can start with the [getting started section](#getting-started) below to learn the basics of draw.io and diagramming. 

**Administrators** can jump to the following sections to see how to [mass-import Gliffy diagrams](#gliffy-mass-import), [customise draw.io](#customising-in-confluence-cloud) with a corporate style, custom libraries or templates, [troubleshooting problems](#troubleshooting), and [managing licenses](#administration-and-licensing).

## Getting started

**Step 1:** Use the [draw.io Board macro](/blog/drawio-board-macro.html) as an online whiteboard. Remote teams find the simpler editor useful for quick collaboration and discussions in meetings.
<br /><img src="/assets/img/blog/confluence-online-whiteboard-drawio.png" style="width=100%;max-width:600px;height:auto;" alt="With the draw.io Board macro, you have a fully featured online whiteboard inside Confluence Cloud">

**Step 2:** Get familiar with the more complex [draw.io Diagram editor layout](/doc/getting-started-editor.html). **Note:** The draw.io layout is almost identical to the editor at [app.diagrams.net](https://app.diagrams.net).
<br /><img src="/assets/img/blog/theme-atlassian-confluence-cloud.png" style="width=100%;max-width:400px;height:auto;" alt="Atlassian theme in draw.io for Confluence Cloud">

**Step 3:** [Create a basic flowchart with the draw.io Diagram macro](/doc/getting-started-basic-flow-chart.html) to learn the most common tools.
<br /><img src="/assets/img/blog/basic-flow-add-labels.gif" style="width=100%;max-width:300px;height:auto;" alt="Draw a basic flowchart to get familiar with the draw.io diagram editor">

**Step 4:** Publish the diagram on your Confluence page. You can also [make your diagram appear larger or smaller](/doc/faq/resize-viewer-confluence-cloud.html).

**Step 5:** [Embed or reuse existing diagrams in your Confluence instance](doc/faq/confluence-cloud-embed-diagram.html). Alternatively, embed diagram files saved in other cloud storage platforms.
   * [Google Drive](/doc/faq/embed-diagram-googledrive-confluence-cloud.html)
   * [OneDrive](/doc/faq/embed-diagram-onedrive-confluence-cloud.html)
<br /><img src="/assets/img/blog/embed-diagrams-confluence-cloud.png" style="max-width:100%;height:auto;" alt="Embedded diagrams in draw.io for Confluence Cloud">



## draw.io for Confluence administrators

### Gliffy mass import

Administrators can convert all of the Gliffy diagrams in a Confluence Cloud instance into draw.io diagrams via the Confluence Settings.

1. Go to the Confluence Settings in your Cloud instance.
2. Select on _draw.io Gliffy Import_ in the left menu.
3. Click on the _Start Import_ button and wait for the import to complete.

<img src="/assets/img/blog/confluence-cloud-start-gliffy-import.png" style="width=100%;max-width:400px;height:auto;" alt="Start the Gliffy mass import to draw.io diagrams in Confluence Cloud">

[Learn how to use the Gliffy to draw.io mass import feature](/doc/faq/mass-import-gliffy-confluence-cloud.html)


### Customising in Confluence Cloud

Confluence Cloud administrators can customise draw.io to make it easier and faster for their users to create diagrams following a consistent style. This is especially useful when they need to use corporate assets, follow corporate style guidelines, or use custom shape libraries and templates.

#### Style draw.io to match your corporate image

By editing the draw.io JSON configuration code, you can set new default shape and connector styles, colour palettes, and fonts, as well as the colour of the UI.

For detailed steps and examples, see the linked documentation for each feature you want to customise.

[**Customise the style palette:**](/doc/faq/custom-styles-confluence-cloud.html) The style palette is displayed at the top of the format panel on the _Style_ tab.

[**Customise the colour palettes:**](/doc/faq/custom-colours-confluence-cloud.html) The colour palettes are displayed whenever you click on a colour button in the format panel. Customise one or more of the palettes to display your corporate colours.

[**Customise the font list:**](/doc/faq/custom-fonts-confluence-cloud.html) The font list appears on the _Text_ tab in the format panel. Set which fonts appear in the draw.io font list by default, add fonts that are hosted on the web (e.g. Google), or add your own custom font file if you need to.

[**Make the draw.io editor UI match your Confluence colours:**](/doc/faq/custom-ui-confluence-cloud.html) If your users are disoriented by opening the draw.io editor when it is a different colour to your Confluence Cloud theme, you can set a new draw.io UI colour for the menu bar.

[**Load plugins by default:**](/doc/faq/custom-plugins-confluence-cloud.html) If your employees regularly use one of the draw.io plugins, for example the anonymize plugin, you can add these plugins to the draw.io JSON configuration and load them by default.
<br />**Note:** that these plugins are provided as-is, as unsupported examples for developers.

1. Open your Confluence Cloud settings.
2. Go to the _draw.io Configuration_ in the _Atlassian Marketplace_ section on the left.
3. Edit the JSON configuration code in the _draw.io Configuration_ tab.

<img src="/assets/img/blog/drawio-configuration-custom-colours.png" style="max-width:100%;height:auto;" alt="Administrators can specify custom colours for draw.io in Confluence Cloud">

#### Provide shapes and corporate assets in custom libraries

[**Make a custom shape library available by default:**](/doc/faq/custom-libraries-confluence-cloud.html) When your users need to add complex or specific shapes to their diagrams, or add images and other corporate assets (like a copyright notice or a logo), you can add a custom shape library to draw.io and make it available by default.

1. Add the custom shape libraries via the _Custom Libraries_ tab in the _draw.io Configuration_ section in your Confluence Cloud Settings.
2. Set it to open by default for all users by editing the JSON code on the _draw.io Configuration_ tab.

<img src="/assets/img/blog/custom-library-confluence-cloud.png" style="width=100%;max-width:400px;height:auto;" alt="Custom libraries appear under the scratchpad in Confluence Cloud">

#### Add custom templates to diagram faster

Custom templates are useful when multiple users need to create a similar set of diagrams, or work from the same foundation. They help users diagram both faster and more consistently in your corporate or departmental styles.

[**Add and categorise custom draw.io templates:**](/doc/faq/custom-templates-confluence-cloud.html) You can custom template categories and diagrams that users will see first when they create a new draw.io diagram.

For example, add your own floorplan template for regularly changing seating arrangements, UML diagram templates for your core application code or databases, network diagram templates, infographic backgrounds, and more.

1. Add the custom templates via the _Custom Templates_ tab in the _draw.io Configuration_ section in your Confluence Cloud Settings.
2. Add template diagrams to your template category pages.

<br /><img src="/assets/img/blog/new-diagram-custom-template-confluence-cloud.png" style="width=100%;max-width:400px;height:auto;" alt="Create a new diagram from a custom template in draw.io for Confluence Cloud">

### Troubleshooting

* [Solve PDF export problems under Confluence Cloud](/doc/faq/pdf-problems-confluence-cloud.html)
* [Resolve a Diagram not Found error](/doc/faq/diagram-not-found-drawio-confluence-cloud.html)

### Administration and licensing

* [See the number of draw.io diagrams in a Confluence instance](/doc/faq/number-of-diagams-in-confluence-instance.html)
* [License draw.io for Confluence Cloud correctly](/doc/faq/license-drawio-confluence-jira-cloud.html)
* [Get a community draw.io license for Confluence or Jira Cloud](/doc/faq/drawio-community-license-cloud.html)
* [Generate a quote for draw.io for Confluence Cloud (annual billing)](/doc/faq/generate-quote-drawio-confluence-cloud.html)
* [Find the draw.io app version and SEN in Confluence Cloud](/doc/faq/app-version-confluence-cloud.html)
* [Open the app management pages in Confluence Cloud](/doc/faq/app-management-pages-confluence-jira-cloud.html)
* [Migrate between Confluence instances](/doc/faq/migrate-drawio-confluence.html)
* [What happens to diagrams when the draw.io app license for Confluence or Jira Cloud becomes invalid](/doc/faq/unlicensed-drawio-app-confluence-jira-cloud.html)
* [Understand how data is stored and how user data flows in draw.io for Confluence and Jira Cloud](/doc/faq/data-flow-confluence-jira-cloud.html)
* [Configure draw.io to use a specific server endpoint region or restrict data transmission](/blog/data-governance-lockdown.html)
