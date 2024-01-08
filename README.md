# bhgc_v2.ocio

Simplified ACES 1.3 OCIO config for CG by Brian Hanke. Based on the ASWF cg-config-v1.0.0_aces-v1.3_ocio-v2.0 config.

**Features**

- Streamlined to include only the core items needed for CG rendering and compositing.
- Updated role and transform names to be more friendly and descriptive. 
- Neutral sRGB transforms for exporting and importing video formats, PNG, JPG, etc.
- Finally free from the LUTs required by OCIO v1. This single config file is all you need!

**Installation**

- Copy bhgc_v2.ocio to a location of your choice and point your system or application OCIO environment variable to it.
