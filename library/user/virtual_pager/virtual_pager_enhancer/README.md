# Virtual Pager Enhancer - v2.0

## Overview

Virtual Pager Enhancer is a lightweight client-side enhancement for the Virtual Pager web interface that improves both **loot management** and **visual customization**.

## Functionality


* 📂⬇️ **Loot Enumeration & Selective Downloads** 

    Discovers available loot folders from `/root/loot` and allows downloading individual folders using the existing `/api/files/zip/root/loot/{FOLDER}` endpoint. While the Virtual Pager UI only exposes this API for `/root/loot/handshakes`, the enhancer extends its use to any loot folder, eliminating the need to download the entire loot directory.

* 🎨 **Pager Skinner**
  Enables customization of the Virtual Pager interface by:

  * Changing background colors
  * Setting custom background images
