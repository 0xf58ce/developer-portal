---
title: Icons
subtitle:
tags: [Build, Container]
category: Embedded Application
redirect_from: /docs/embedded-app/stax-icon/
toc: true
author:
layout: doc
---

There are 2 mandatory icons that should be provided for Ledger to release an app:

-   The Manager icon, displayed in the Manager application list in Ledger Live
-   The Device icon, displayed on the Ledger dashboard (this consists in 1 icon for the Nano S, one Icon for the Nano S Plus and the Nano X, and one for the Ledger Stax)

<!--  -->
{% include alert.html style="important" text="Submitting icons that are not compliant will slow down the process of publishing your embedded App." %}
<!--  -->


## Manager icon

- RGB colors only
- Pictogram color should be white
- Pictrogram stroke should be 4pt

<!-- ------------- Image ------------- -->
<!-- --------------------------------- -->
<figure>
<a href="https://drive.google.com/a/ledger.fr/file/d/1OOAZWlnLlBSpScPnF5NGJ4AfczB3D591/view?usp=sharing" title="Manager template">
<img src="/manager-icon-template.png" class="align-center" alt="Manager icon template (click to access Illustrator file)" /><figcaption aria-hidden="true">Manager icon template (click to access Illustrator file)</figcaption>
</a>
</figure>

## Device icon

<!--  -->
{% include alert.html style="tip" text="You can use <a href='https://www.photopea.com/'>Photopea</a> to create your icons." %}
<!--  -->


### Nano templates

1. Create the 16x16px Nano S icon using the template below
2. Create the 14x14 Nano S Plus and Nano X icon on Linux by installing the **imagemagick** package and running: `convert nanos_app_<token>.gif -crop 14x14+1+1 +repage -negate nanox_app_<token>.gif`


<!-- ------------- Image ------------- -->
<!-- --------------------------------- -->
<figure>
<a href="https://drive.google.com/a/ledger.fr/file/d/1FVUWDGYPvLuyiwDFgGYiwfwk7YGsxzJ0/view?usp=sharing" title="Device template">
<img src="/nano-icon-template.png" class="align-center" alt="Device icon template (click to access Illustrator file)" /><figcaption aria-hidden="true">Ledger Nano S and X icon template (click to access Illustrator file)</figcaption>
</a>
</figure>


### Stax template

<!-- ------------- Image ------------- -->
<!-- --------------------------------- -->
<figure>
<a href="../docs/stax-icons-template.png" title="Device template">
<img src="/stax-icons-template.png" class="align-center" alt="Device icon template (click to download the Illustrator file)" />
</a>
</figure>


## Design Warranty 

Design Warranty
The design of your app must be free from any encumbrances and must not infringe upon any third party intellectual property right, in particular trademark and design rights. You grant Ledger the right to use such design for free with the right to reproduce and exploit the design for the duration of its display on Ledger website.

You represent and warrant that the app you are making available on Ledger Live is in compliance with all relevant laws and regulations.

You agree to hold Ledger harmless of any claim arising out of the use of the design and or distribution of your app .
