---
description: Steps that describe how to escape classification data in the classification file.
seo-description: Steps that describe how to escape classification data in the classification file.
seo-title: Escape classification data
solution: Analytics
subtopic: Classifications
title: Escape classification data
topic: Admin tools
uuid: a1b6071e-3f63-4fad-adc9-00c10de7733c
index: y
internal: n
snippet: y
---

# Escape classification data

Steps that describe how to escape classification data in the classification file.

1. Ensure that the classification file format is v2.1.

   If v2.1 is enabled, you will see a line similar to:

   ```
   ## SC SiteCatalyst SAINT Import File v:2.1
   ```

   >[!NOTE]
   >
   >To specify a format of v2.1, enable **[!UICONTROL Quoted Output]** when exporting the file on the [!UICONTROL Classification Importer] page ( [!UICONTROL Browser Export] or [!UICONTROL FTP Export]).

   See [Browser Export](browser_export.md#concept_3D930F03840A491D8B37FAAE9C90F5DF). 

1. Surround the field containing special characters in double quotes (").

   A double quote character can appear in an escaped cell by replacing it with two double quote characters (""). For example:

   ```
   My String "of data"
   ```

   Escaped would be:

   ```
   "My String ""of data"""
   ```
