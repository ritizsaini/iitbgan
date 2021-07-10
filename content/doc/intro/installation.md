---
title: Installation
linktitle: Installation
type: book
date: "2021-07-08T00:00:00+01:00"
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

Download the MMIC from the link below if you havn't downloaded it yet!
{{< cta cta_text="👉 MMIC IITB" cta_link="https://github.com/ritizsaini/iitbgan/blob/main/assets/MMIC_IITB.zip?raw=true" >}}


## Import in ADS

You must have Keysight's [Advanced Design System](https://www.keysight.com/in/en/lib/resources/miscellaneous/software-versions-computer-platforms-and-operating-systems-1486421.html) installed on your OS to use our MMIC. Follow these steps to import this process design kit to your workspace;

### Option 1: Add while creating a workspace

{{< figure src="2.png" id="unzip1" caption="Click on the change libraries while creating workspace">}}

{{< figure src="3.png" id="unzip2" caption="Click on Add user fav library/PdK">}}

{{< figure src="4.png" id="unzip3" caption="Select the zip file that you have downloaded">}}

ADS will will then ask you the location where you want to extract this library.

### Option 2: Add after creating a workspace

{{< figure src="5.png" id="unzip4" caption="Go to DesignKits -> Manage Libraries...">}}

{{< figure src="6.png" id="unzip5" caption="Click on Add design kits from favourites...">}}

{{< figure src="7.png" id="unzip6" caption="Click on Add user fav library/PdK">}}

{{< figure src="4.png" id="unzip3" caption="Select the zip file that you have downloaded">}}

### Add component to schematic

{{< figure src="8.png" id="unzip7" caption="Click on Open the library browser">}}

{{< figure src="9.png" id="unzip8" caption="Under read only libraries, you can find components of our MMIC">}}

{{< figure src="10.png" id="unzip9" caption="Search MMIC in components and you will get this window">}}

---
If you have any doubts, then follow this video for more information
{{< youtube zsjrSuQKZnQ >}}
<br>

{{% callout warning %}}
Don't change anything inside the MMIC, that would result in a series of errors during simulations
{{% /callout %}}

