# AEM Asset Selector for Franklin Authoring
Integration between AEM Asset Selector and AEM Franklin to make AEM assets available in Franklin site authoring.

# High level flow

[Link to Diagram Source](https://lucid.app/lucidchart/d6db1b7d-144f-4ac9-94a2-fce760ed2ca4/edit?viewport_loc=-368%2C-403%2C1899%2C1069%2C0_0&invitationId=inv_cd6848d0-dfc0-4be9-b0cb-3cae5a1ba757)

![High Level Flow](/resources/using-asset-selector-with-franklin.jpeg)

## Environments
- Preview: https://main--{repo}--{owner}.aem.page/
- Live: https://main--{repo}--{owner}.aem.live/

## Documentation

Before using the aem-boilerplate, we recommand you to go through the documentation on https://www.aem.live/docs/ and more specifically:
1. [Developer Tutorial](https://www.aem.live/developer/tutorial)
2. [The Anatomy of a Project](https://www.aem.live/developer/anatomy-of-a-project)
3. [Web Performance](https://www.aem.live/developer/keeping-it-100)
4. [Markup, Sections, Blocks, and Auto Blocking](https://www.aem.live/developer/markup-sections-blocks)

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)

## Extending the Assets Selector Capabilities

To extend the capabilities of the Assets Selector, you can look at the following sample configurations and GitHub repository as a reference. These configurations are hosted on Adobe IO Runtime through App Builder and can be adapted to fit your project needs and extension requirements.

- [Sample Configuration Hosted on Adobe IO Runtime][0]
- [Sample Configuration with Web Path][1]
- [GitHub Reference Implementation][2]

This configuration is particularly useful for extending the Assets Selector capabilities documented [here][3]. Feel free to integrate and customize it as per your project’s use cases.

[0]: https://245265-extensionconfig.adobeioruntime.net/api/v1/web/extension-config/extension-config
[1]: https://245265-extensionconfig.adobeioruntime.net/api/v1/web/extension-config/extension-config?webPath=snorkling
[2]: https://github.com/Adobe-Marketing-Cloud/assets-selector-extension
[3]: https://www.aem.live/developer/configuring-aem-assets-sidekick-plugin#extend-aem-assets-sidekick-plugin
1. Open the `{repo}` directory in your favorite IDE and start coding :)
