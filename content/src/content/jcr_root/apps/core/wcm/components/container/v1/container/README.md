<!--
Copyright 2019 Adobe Systems Incorporated

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
Container (v1)
====
Container component written in HTL.

## Features

* Allows to configure a background color and a background image
* Allows components can be configured through policy configuration.
* Allows addition of custom color swatches for background color.
* Allows hide/show for background color and background images.
* Allows hide/show for color picker properties

### Use Object
The Container component uses the `com.adobe.cq.wcm.core.components.models.GenericContainer` Sling model as its Use-object.

### Component Policy Configuration Properties
The following configuration properties are used:

1. `./isColorsDisabled` - defines whether or not display background color picker option.
2. `./showProperties` -  defines whether or not display color picker properties tab.
3. `./cq:swatches` - defines list of custom swatches list.
3. `./imageDisabled` - defines whether or not display background image option.

It is also possible to define the allowed components for the Container.

### Edit Dialog Properties
The following properties are written to JCR for this Container component and are expected to be available as `Resource` properties:

1. `./backgroundColor` - defines background color of container component.
2. `./fileReference` - defines background image of container component.

## BEM Description
```
BLOCK cmp-container
```


## Information
* **Vendor**: Adobe
* **Version**: v1
* **Compatibility**: AEM 6.5
* **Status**: production-ready
* **Documentation**: [https://www.adobe.com/go/aem\_cmp\_container\_v1](https://www.adobe.com/go/aem_cmp_container_v1)
* **Component Library**: [http://opensource.adobe.com/aem-core-wcm-components/library/container.html](http://opensource.adobe.com/aem-core-wcm-components/library/container.html)