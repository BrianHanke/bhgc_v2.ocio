# bhgc_v2.ocio

Simplified OCIO config for CG by Brian Hanke. Based on the new ASWF CG config.

**Features**

- Streamlined to include only the core items needed for CG rendering and compositing.
- Updated role and transform names to be more friendly and descriptive. 
- Baked sRGB output transform for exporting to video formats, PNG, JPG, etc.
- Now includes SDR, Cinema, and HDR views.
- Finally free from the LUTs required by OCIO v1. This single config file is all you need!

**Installation**

- Copy bhgc_v2.ocio to a location of your choice and point your system or application OCIO environment variable to it.
