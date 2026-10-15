---
title: "Table/Product"
figma_file_key: "01imXcjljmBfqXhqFmv4kz"
figma_node_id: "882:231025"
figma_node_type: "COMPONENT_SET"
figma_page_id: "0:1"
documentation_status: "source-verified-structure-with-review-gaps"
observed_date: "2026-10-15"
---

# Table/Product

## Overview

Original Figma name: `Table/Product`. Published node type: `COMPONENT_SET`. Source page: `🥘  nebulaONE.design Docs` ([0:1](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-1)).

Purpose: **Needs design review** — a purpose statement was not exposed by the retrieved structural metadata. Source-linked guidance, where retrieved, appears under Usage.

Figma properties below describe design configuration. They do not establish a code API. Sample visibility/text and variant dimensions describe the observed source, not interaction rules.

## Anatomy

Published descendant instance records; equivalent records may be merged across variants. Each ID is the tool's sample layer. A hidden instance may still be present in the structure.

| Layer | Sample node | Parent path | Main component | Sample visible | Property references | Owning variants |
| --- | --- | --- | --- | --- | --- | --- |
| `TextField` | [1612:120625](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1612-120625) | `stack` | [TextField](input.md) | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `✳️ end adornment` | [I1612:120625;1774:138265](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-120625;1774-138265) | `stack / TextField / wrap / end adornment` | [Button/Icon](button-icon.md) | `false` | `{"visible": "👁️ End Adornment#1670:783", "mainComponent": "↳ end adornment#1670:1073"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `start adornment` | [I1612:120625;1774:147425](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-120625;1774-147425) | `stack / TextField / wrap / select arrow` | `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `{"visible": "👁️ Select Arrow#1774:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `✳️ helper text` | [I1612:120625;1670:167099](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-120625;1670-167099) | `stack / TextField` | [FormHelperText](formhelpertext.md) | `false` | `{"visible": "👁️ Help Text#1670:1218"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `start adornment` | [I2031:147151;1671:105318](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2031-147151;1671-105318) | `stack / TextField / wrap / start adornment` | `icons/solid/ic-eva:search-fill` | `true` | `{"visible": "👁️ Start Adornment#1670:638", "mainComponent": "↳ start adornment#1670:928"}` | `["📱 Mobile=False"]` |
| `Button/Icon` | [2578:486693](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2578-486693) | `stack` | [Button/Icon](button-icon.md) | `true` | `{}` | `["📱 Mobile=False"]` |
| `icons/placeholder` | [I2578:486693;1670:120827](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2578-486693;1670-120827) | `stack / Button/Icon` | `icons/solid/ic-eva:more-vertical-fill` | `true` | `{"mainComponent": "↳ icon#1670:1363"}` | `["📱 Mobile=False"]` |
| `Table/FiltersResults` | [2894:553093](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2894-553093) | `root` | `Table/FiltersResults` | `true` | `{"visible": "👁️ Results#2713:3"}` | `["📱 Mobile=False"]` |
| `Chip` | [I2894:553093;2894:443797](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443797) | `Table/FiltersResults / stack / stack` | `Chip/Filled/Default/S/Enabled` | `true` | `{}` | `["📱 Mobile=False"]` |
| `✳️ icon` | [I2894:553093;2894:443797;1680:123228](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443797;1680-123228) | `Table/FiltersResults / stack / stack / Chip` | [icons/placeholder](icons-placeholder.md) | `false` | `{"visible": "👁️ Icon#1680:559", "mainComponent": "↳ icon#2539:153"}` | `["📱 Mobile=False"]` |
| `action` | [I2894:553093;2894:443797;86:8171](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443797;86-8171) | `Table/FiltersResults / stack / stack / Chip` | [icons/generic/close-2](icons-generic-close-2.md) | `true` | `{"visible": "👁️ Action#1680:270", "mainComponent": "↳ action icon#1680:1426"}` | `["📱 Mobile=False"]` |
| `Chip` | [I2894:553093;2894:443801](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443801) | `Table/FiltersResults / stack / stack` | `Chip/Filled/Default/S/Enabled` | `false` | `{}` | `["📱 Mobile=False"]` |
| `Button` | [I2894:553093;2894:443802](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443802) | `Table/FiltersResults / stack` | `Button/Text/Error/M/Enabled` | `true` | `{}` | `["📱 Mobile=False"]` |
| `start icon` | [I2894:553093;2894:443802;1667:144129](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443802;1667-144129) | `Table/FiltersResults / stack / Button` | `icons/solid/ic-solar:trash-bin-trash-bold` | `true` | `{"visible": "👁️ Start Icon#1667:129", "mainComponent": "↳ start icon#1667:37"}` | `["📱 Mobile=False"]` |
| `end icon` | [I2894:553093;2894:443802;1667:144132](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443802;1667-144132) | `Table/FiltersResults / stack / Button` | [icons/placeholder](icons-placeholder.md) | `false` | `{"visible": "👁️ End Icon#1667:175", "mainComponent": "↳ end icon#1667:83"}` | `["📱 Mobile=False"]` |
| `Table/Product/Head` | [2713:153337](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2713-153337) | `root` | `Table/Product/Head` | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Table/Cell` | [I2713:153337;882:108368](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108368) | `Table/Product/Head` | `Table/Cell` | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `✳️ checkbox` | [I2713:153337;882:108368;1682:118124](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108368;1682-118124) | `Table/Product/Head / Table/Cell / checkbox` | `Checkbox/Primary/S/Enabled/False/False` | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `icons/solid/ic-checkbox-off` | [I2713:153337;882:108368;1682:118124;1676:108287](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108368;1682-118124;1676-108287) | `Table/Product/Head / Table/Cell / checkbox / ✳️ checkbox / icon container` | `icons/solid/ic-checkbox-off` | `true` | `{"mainComponent": "↳ icon#1676:55"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `icons/solid/ic-eva:arrow-downward-fill` | [I2713:153337;882:108368;0:15842](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108368;0-15842) | `Table/Product/Head / Table/Cell / stack` | `icons/solid/ic-eva:arrow-downward-fill` | `true` | `{"visible": "👁️ Sort Arrow#1682:437"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `icons/solid/ic-eva:arrow-downward-fill` | [I2713:153337;882:108369;0:15842](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108369;0-15842) | `Table/Product/Head / Table/Cell / stack` | `icons/solid/ic-eva:arrow-downward-fill` | `false` | `{"visible": "👁️ Sort Arrow#1682:437"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Table/Product/Row` | [882:109167](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=882-109167) | `root` | `Table/Product/Row` | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Table/Cell/Td` | [I882:109167;882:103962](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-103962) | `Table/Product/Row` | `Table/Cell/Td` | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Button/Icon` | [I882:109167;2556:509933](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-509933) | `Table/Product/Row / Table/Cell` | [Button/Icon](button-icon.md) | `false` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Table/Cell` | [I882:109167;2556:503891](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-503891) | `Table/Product/Row` | `Table/Cell` | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `✳️ primary action` | [I882:109167;2556:503891;2556:381845](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-503891;2556-381845) | `Table/Product/Row / Table/Cell` | [Button/Icon](button-icon.md) | `false` | `{"visible": "👁️ Secondary Action#2556:4", "mainComponent": "↳ secondary action#2556:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `✳️ secondary action` | [I882:109167;2556:503891;1682:119254](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-503891;1682-119254) | `Table/Product/Row / Table/Cell` | [Label](label.md) | `true` | `{"visible": "👁️ Primary Action#2878:10", "mainComponent": "↳ primary action#1682:447"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `start icon` | [I882:109167;2556:503891;1682:119254;1682:106515](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-503891;1682-119254;1682-106515) | `Table/Product/Row / Table/Cell / Label` | [icons/placeholder](icons-placeholder.md) | `false` | `{"visible": "👁️ Start Icon#1682:115", "mainComponent": "↳ start icon#1682:213"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `end icon` | [I882:109167;2556:503891;1682:119254;1682:106517](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-503891;1682-119254;1682-106517) | `Table/Product/Row / Table/Cell / Label` | [icons/placeholder](icons-placeholder.md) | `false` | `{"visible": "👁️ End Icon#1682:164", "mainComponent": "↳ end icon#1682:262"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `✳️ secondary action` | [I882:109167;882:103961;1682:119254](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-103961;1682-119254) | `Table/Product/Row / Table/Cell` | [Button/Icon](button-icon.md) | `true` | `{"visible": "👁️ Primary Action#2878:10", "mainComponent": "↳ primary action#1682:447"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `icons/placeholder` | [I882:109167;882:103961;1682:119254;1670:120827](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-103961;1682-119254;1670-120827) | `Table/Product/Row / Table/Cell / ✳️ secondary action` | `icons/solid/ic-eva:more-vertical-fill` | `true` | `{"mainComponent": "↳ icon#1670:1363"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `TablePagination` | [1750:139736](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1750-139736) | `root` | [TablePagination](tablepagination.md) | `true` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Switch` | [I1750:139736;1739:142109](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1739-142109) | `TablePagination` | [Switch](switch.md) | `true` | `{"visible": "Dense#1739:15"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `icons/solid/ic-eva:arrow-ios-downward-fill` | [I1750:139736;1612:130026](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130026) | `TablePagination / select` | `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `{}` | `["📱 Mobile=False"]` |
| `Button/Icon` | [I1750:139736;1612:130029](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130029) | `TablePagination / next/prev` | `IconButton/Default/S/Disabled` | `true` | `{}` | `["📱 Mobile=False"]` |
| `icons/placeholder` | [I1750:139736;1612:130029;1670:145447](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130029;1670-145447) | `TablePagination / next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-back-fill` | `true` | `{"mainComponent": "↳ icon#1670:1397"}` | `["📱 Mobile=False"]` |
| `Button/Icon` | [I1750:139736;1612:130030](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130030) | `TablePagination / next/prev` | `IconButton/Inherit/S/Enabled` | `true` | `{}` | `["📱 Mobile=False"]` |
| `icons/placeholder` | [I1750:139736;1612:130030;1670:139839](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130030;1670-139839) | `TablePagination / next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-forward-fill` | `true` | `{"mainComponent": "↳ icon#1670:1382"}` | `["📱 Mobile=False"]` |
| `TextField` | [2578:486627](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2578-486627) | `stack / stack` | [TextField](input.md) | `true` | `{}` | `["📱 Mobile=True"]` |
| `start adornment` | [I2578:486627;1671:105318](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2578-486627;1671-105318) | `stack / stack / TextField / wrap / start adornment` | `icons/solid/ic-eva:search-fill` | `true` | `{"visible": "👁️ Start Adornment#1670:638", "mainComponent": "↳ start adornment#1670:928"}` | `["📱 Mobile=True"]` |
| `✳️ end adornment` | [I2578:486627;1774:138265](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2578-486627;1774-138265) | `stack / stack / TextField / wrap / end adornment` | [Button/Icon](button-icon.md) | `false` | `{"visible": "👁️ End Adornment#1670:783", "mainComponent": "↳ end adornment#1670:1073"}` | `["📱 Mobile=True"]` |
| `✳️ helper text` | [I2578:486627;1670:167099](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2578-486627;1670-167099) | `stack / stack / TextField` | [FormHelperText](formhelpertext.md) | `false` | `{"visible": "👁️ Help Text#1670:1218"}` | `["📱 Mobile=True"]` |
| `Button/Icon` | [2578:486628](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=2578-486628) | `stack / stack` | [Button/Icon](button-icon.md) | `true` | `{}` | `["📱 Mobile=True"]` |
| `icons/placeholder` | [I2578:486628;1670:120827](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2578-486628;1670-120827) | `stack / stack / Button/Icon` | `icons/solid/ic-eva:more-vertical-fill` | `true` | `{"mainComponent": "↳ icon#1670:1363"}` | `["📱 Mobile=True"]` |
| `icons/solid/ic-eva:arrow-ios-downward-fill` | [I1750:145150;1739:144702](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144702) | `TablePagination / stack / select` | `icons/solid/ic-eva:arrow-ios-downward-fill` | `true` | `{}` | `["📱 Mobile=True"]` |
| `Button/Icon` | [I1750:145150;1739:144705](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144705) | `TablePagination / stack / next/prev` | `IconButton/Default/S/Disabled` | `true` | `{}` | `["📱 Mobile=True"]` |
| `icons/placeholder` | [I1750:145150;1739:144705;1670:145447](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144705;1670-145447) | `TablePagination / stack / next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-back-fill` | `true` | `{"mainComponent": "↳ icon#1670:1397"}` | `["📱 Mobile=True"]` |
| `Button/Icon` | [I1750:145150;1739:144706](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144706) | `TablePagination / stack / next/prev` | `IconButton/Inherit/S/Enabled` | `true` | `{}` | `["📱 Mobile=True"]` |
| `icons/placeholder` | [I1750:145150;1739:144706;1670:139839](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144706;1670-139839) | `TablePagination / stack / next/prev / Button/Icon` | `icons/solid/ic-eva:arrow-ios-forward-fill` | `true` | `{"mainComponent": "↳ icon#1670:1382"}` | `["📱 Mobile=True"]` |
| `Scroll` | [1750:147797](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=1750-147797) | `root` | [Scroll](scroll.md) | `true` | `{}` | `["📱 Mobile=True"]` |

Source text samples (not recommended copy):

| Layer | Sample node | Text | Parent path | References | Owning variants |
| --- | --- | --- | --- | --- | --- |
| `value` | [I1612:120625;1670:167091](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1612-120625;1670-167091) | `Stock` | `stack / TextField / wrap` | `{"visible": "👁️ Label#1707:64"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `value` | [I2707:141872;1670:167091](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2707-141872;1670-167091) | `Publish` | `stack / TextField / wrap` | `{"visible": "👁️ Label#1707:64"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `value` | [I2031:147151;1670:167091](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2031-147151;1670-167091) | `Search...` | `stack / TextField / wrap` | `{"visible": "👁️ Label#1707:64"}` | `["📱 Mobile=False"]` |
| `8 results found` | [I2894:553093;2894:443793](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443793) | `8 results found` | `Table/FiltersResults` | `{}` | `["📱 Mobile=False"]` |
| `Category 1` | [I2894:553093;2894:443796](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443796) | `Stock` | `Table/FiltersResults / stack / stack / label` | `{}` | `["📱 Mobile=False"]` |
| `:` | [I2894:553093;2894:443844](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443844) | ` :` | `Table/FiltersResults / stack / stack / label` | `{}` | `["📱 Mobile=False"]` |
| `label` | [I2894:553093;2894:443797;86:8170](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443797;86-8170) | `In stock` | `Table/FiltersResults / stack / stack / Chip / label container` | `{}` | `["📱 Mobile=False"]` |
| `Category 2` | [I2894:553093;2894:443846](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443846) | `Publish` | `Table/FiltersResults / stack / stack / label` | `{}` | `["📱 Mobile=False"]` |
| `label` | [I2894:553093;2894:443800;86:8170](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443800;86-8170) | `Published` | `Table/FiltersResults / stack / stack / Chip / label container` | `{}` | `["📱 Mobile=False"]` |
| `label` | [I2894:553093;2894:443802;1667:144130](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2894-553093;2894-443802;1667-144130) | `Clear` | `Table/FiltersResults / stack / Button` | `{"visible": "👁️ Label#1720:127"}` | `["📱 Mobile=False"]` |
| `label` | [I2713:153337;882:108368;1682:118124;1676:108289](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108368;1682-118124;1676-108289) | `UnChecked` | `Table/Product/Head / Table/Cell / checkbox / ✳️ checkbox` | `{"visible": "👁️ Label#1676:18"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `th text` | [I2713:153337;882:108368;0:15841](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108368;0-15841) | `Product` | `Table/Product/Head / Table/Cell / stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `th text` | [I2713:153337;882:108369;0:15841](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108369;0-15841) | `Create at` | `Table/Product/Head / Table/Cell / stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `th text` | [I2713:153337;882:108365;0:15841](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108365;0-15841) | `Stock` | `Table/Product/Head / Table/Cell / stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `th text` | [I2713:153337;2556:503608;0:15841](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;2556-503608;0-15841) | `Price` | `Table/Product/Head / Table/Cell / stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `th text` | [I2713:153337;882:108366;0:15841](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;882-108366;0-15841) | `Publish` | `Table/Product/Head / Table/Cell / stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `th text` | [I2713:153337;1750:133316;0:15841](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2713-153337;1750-133316;0-15841) | `Table th` | `Table/Product/Head / Table/Cell / stack` | `{"visible": "👁️ Primary Text#2587:0"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109167;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-103962;1694-164256) | `Nike Air Force 1 NDESTRUKT` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `secondary text` | [I882:109167;882:103962;1694:164257](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-103962;1694-164257) | `Shoes` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109167;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-116195;1694-164256) | `07 Jul 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `secondary text` | [I882:109167;882:116195;1694:164257](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-116195;1694-164257) | `Table td` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:109167;2556:512633](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-512633) | `72 in stock` | `Table/Product/Row / Table/Cell / Progress` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109167;882:103964;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;882-103964;1694-164256) | `$67.55` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:109167;2556:503891;1682:119254;1682:106516](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109167;2556-503891;1682-119254;1682-106516) | `Published` | `Table/Product/Row / Table/Cell / Label` | `{"visible": "👁️ Label#2863:22", "characters": "↳ label#2882:126"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112159;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112159;882-103962;1694-164256) | `Foundations Matte Flip Flop` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `secondary text` | [I882:112159;882:103962;1694:164257](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112159;882-103962;1694-164257) | `Jacket` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112159;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112159;882-116195;1694-164256) | `10 Sep 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:112159;2556:512633](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112159;2556-512633) | `12 in stock` | `Table/Product/Row / Table/Cell / Progress` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112159;882:103964;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112159;882-103964;1694-164256) | `$35.71` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109541;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109541;882-103962;1694-164256) | `Nike Air Zoom Pegasus 37 A.I.R. Chaz Bear` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `secondary text` | [I882:109541;882:103962;1694:164257](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109541;882-103962;1694-164257) | `Jean` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109541;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109541;882-116195;1694-164256) | `03 Sep 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:109541;2556:512633](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109541;2556-512633) | `Out of stock` | `Table/Product/Row / Table/Cell / Progress` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109541;882:103964;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109541;882-103964;1694-164256) | `$52.84` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:109541;2556:503891;1682:119254;1682:106508](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109541;2556-503891;1682-119254;1682-106508) | `Draft` | `Table/Product/Row / Table/Cell / Label` | `{"visible": "👁️ Label#2863:22", "characters": "↳ label#2882:126"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112160;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112160;882-103962;1694-164256) | `Arizona Soft Footbed Sandal` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112160;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112160;882-116195;1694-164256) | `22 Oct 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:112160;2556:512633](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112160;2556-512633) | `42 in stock` | `Table/Product/Row / Table/Cell / Progress` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112160;882:103964;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112160;882-103964;1694-164256) | `$26.92` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109993;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109993;882-103962;1694-164256) | `Boston Soft Footbed Sandal` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109993;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109993;882-116195;1694-164256) | `30 Mar 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I882:109993;2556:512633](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109993;2556-512633) | `22 in stock` | `Table/Product/Row / Table/Cell / Progress` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:109993;882:103964;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-109993;882-103964;1694-164256) | `$58.07` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112161;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112161;882-103962;1694-164256) | `Zoom Freak 2` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:112161;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-112161;882-116195;1694-164256) | `04 Jul 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:111021;882:103962;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-111021;882-103962;1694-164256) | `Gazelle Vintage low-top sneakers` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:111021;882:116195;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-111021;882-116195;1694-164256) | `13 May 2022` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `primary text` | [I882:111021;882:103964;1694:164256](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I882-111021;882-103964;1694-164256) | `$34.30` | `Table/Product/Row / Table/Cell/Td / stack / text` | `{}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I1750:139736;1739:142109;1676:109789](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1739-142109;1676-109789) | `UnChecked` | `TablePagination / Switch` | `{"visible": "👁️ Start Label#1676:94"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `label` | [I1750:139736;1739:142109;1676:109792](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1739-142109;1676-109792) | `Dense` | `TablePagination / Switch` | `{"visible": "👁️ End Label#1676:139"}` | `["📱 Mobile=False", "📱 Mobile=True"]` |
| `Rows per page:` | [I1750:139736;1612:130023](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130023) | `Rows per page:` | `TablePagination` | `{}` | `["📱 Mobile=False"]` |
| `5` | [I1750:139736;1612:130025](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130025) | `5` | `TablePagination / select` | `{}` | `["📱 Mobile=False"]` |
| `6-10 of 11` | [I1750:139736;1612:130027](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-139736;1612-130027) | `6-10 of 11` | `TablePagination` | `{}` | `["📱 Mobile=False"]` |
| `value` | [I2578:486627;1670:167091](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I2578-486627;1670-167091) | `Search...` | `stack / stack / TextField / wrap` | `{"visible": "👁️ Label#1707:64"}` | `["📱 Mobile=True"]` |
| `Rows per page:` | [I1750:145150;1739:144699](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144699) | `Rows per page:` | `TablePagination / stack` | `{}` | `["📱 Mobile=True"]` |
| `5` | [I1750:145150;1739:144701](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144701) | `5` | `TablePagination / stack / select` | `{}` | `["📱 Mobile=True"]` |
| `6-10 of 11` | [I1750:145150;1739:144703](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=I1750-145150;1739-144703) | `6-10 of 11` | `TablePagination / stack` | `{}` | `["📱 Mobile=True"]` |

Dependency identities from the published graph:

| Original name | External | Source node ID | Asset key |
| --- | --- | --- | --- |
| `TextField` | `false` | `194:62777` | `da78f476840d89866b3daab25f4da5317f52c132` |
| `Button/Icon` | `false` | `11:812` | `8b228433cfac383928ea1c87230d866aefa90ef0` |
| `Table/FiltersResults` | `true` | `Not exposed` | `366433cae1ed095bcbb3aa8559fa1760f03e41d0` |
| `Table/Product/Head` | `true` | `Not exposed` | `aba3fdf511216d633a4a7dfc0ab8559dba4cfaa9` |
| `Table/Product/Row` | `true` | `Not exposed` | `561113e08a8d40ee31715cc89956ee7a2b1f1b06` |
| `TablePagination` | `false` | `1612:129994` | `dd5b0f12c6dff9725be3ecca2c77a3390e032710` |
| `Scroll` | `false` | `882:180516` | `6acb345c99492748f5e4538442f96c8bedf245e3` |


## Variants

| Property | Published options | Published default |
| --- | --- | --- |
| `📱 Mobile` | `["False", "True"]` | `False` |

2 member nodes directly observed in metadata. This is not a Cartesian-product estimate. Names and actual dimensions are preserved:

| Original member name | Node | Width | Height |
| --- | --- | --- | --- |
| `📱 Mobile=False` | [0:4843](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-4843) | `1080` | `830` |
| `📱 Mobile=True` | [882:231026](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=882-231026) | `343` | `940` |


## Properties

| Original property name | Figma type | Source key | Default | Additional source metadata |
| --- | --- | --- | --- | --- |
| `👁️ Results` | `BOOLEAN` | `👁️ Results#2713:3` | `true` | `{}` |
| `📱 Mobile` | `VARIANT` | `📱 Mobile` | `False` | `{"variantOptions": ["False", "True"]}` |

Defaults are the published graph values, not defaults inferred from a sampled variant. `SLOT` and `INSTANCE_SWAP` defaults are raw source identifiers; no runtime API is implied.


## States

**Needs design review** — no explicit state property was returned. State-like text in the component name is a source label only.

Transitions, triggers, timing, and keyboard/pointer semantics: **Needs design review**. Named states do not establish runtime behavior.

## Usage

**Needs design review** — authored usage guidance was not retrieved for this node.

External links are separately importable references; their contents have not been imported or verified as N1 requirements. Source sample text under Anatomy is not a usage recommendation.

## Behaviour

Metadata bounds: `1543` × `1020` Figma canvas units.

These are the component-set canvas bounds, not a rendered component size; use member dimensions under Variants.

Source device-labelled properties: `📱 Mobile` = `["False", "True"]`. These labels do not establish breakpoints.

Raw auto-layout mode, sizing/constraint flags, reflow rules, breakpoints, and interactions: **Needs design review**. Metadata coordinates alone do not establish these rules.

## Accessibility

**Needs design review** — no component-specific accessibility specification or compliance test was verified. Semantic roles, accessible names, focus order, keyboard support, contrast, target size, and assistive-technology behavior require explicit evidence. Visual state names and screenshots do not establish compliance.

## Design tokens

Node-scoped definitions returned by `get_variable_defs`; these can include descendant and variant usage. Names and returned values are unchanged:

| Original name | Returned value |
| --- | --- |
| `text/disabled` | `#919eab` |
| `desktop/body2` | `Font(family: "Segoe UI", style: Regular, size: 14, weight: 400, lineHeight: 22, letterSpacing: 0)` |
| `text/secondary` | `#637381` |
| `textfield/[select-arrow]--size` | `20` |
| `textfield/[select-arrow]--mr` | `10` |
| `textfield/[outlined]--px` | `14` |
| `textfield/[outlined][medium]--height` | `54` |
| `textfield/[outlined]--radius` | `8` |
| `components/textfield/outline` | `#c4cdd5` |
| `textfield/[start-adornment]--mr` | `8` |
| `action/active` | `#637381` |
| `icon button/[small]--size` | `36` |
| `icon button/radius` | `500` |
| `text/primary` | `#161c24` |
| `desktop/subtitle2` | `Font(family: "Segoe UI", style: Semibold, size: 14, weight: 600, lineHeight: 22, letterSpacing: 0)` |
| `global/inherit/color` | `#ffffff` |
| `components/chip-text-sm` | `Font(family: "Segoe UI", style: Regular, size: 12, weight: 400, lineHeight: 18, letterSpacing: 0)` |
| `chip/[small]--spacing` | `5` |
| `System/Grey/cf-color-black` | `#000000` |
| `chip/close-icon` | `20` |
| `chip/spacing` | `-2` |
| `chip/[small]--px` | `3` |
| `chip/[small]--height` | `24` |
| `chip/radius` | `8` |
| `global/inherit/bg` | `#212b36` |
| `components/paper/outlined` | `#919eab29` |
| `error/main` | `#d82934` |
| `components/button-medium` | `Font(family: "Segoe UI", style: Bold, size: 14, weight: 700, lineHeight: 24, letterSpacing: 0)` |
| `button/spacing` | `8` |
| `button/[text][medium]--px` | `8` |
| `button/[medium]--height` | `36` |
| `button/radius` | `8` |
| `button/min-width` | `64` |
| `spacing-1,5` | `12` |
| `spacing-2,5` | `20` |
| `spacing-2` | `16` |
| `background/paper` | `#ffffff` |
| `checkbox/[small]--icon` | `20` |
| `checkbox/p` | `8` |
| `radius-50%` | `500` |
| `spacing-1` | `8` |
| `components/table-head` | `Font(family: "Segoe UI", style: Semibold, size: 14, weight: 600, lineHeight: 24, letterSpacing: 0)` |
| `spacing-0,5` | `4` |
| `background/thead` | `#dfe2e8` |
| `success/main` | `#0f913b` |
| `success/24%` | `#22c55e3d` |
| `desktop/caption` | `Font(family: "Segoe UI", style: Regular, size: 12, weight: 400, lineHeight: 18, letterSpacing: 0)` |
| `System/Blue/cf-color-blue-900` | `#0a3c73` |
| `components/label-text` | `Font(family: "Segoe UI", style: Semibold, size: 14, weight: 600, lineHeight: 20, letterSpacing: 0)` |
| `label/spacing` | `6` |
| `label/px` | `6` |
| `label/height` | `24` |
| `label/radius` | `6` |
| `label/min-width` | `24` |
| `info/16%` | `#37c5f029` |
| `border/divider` | `#919eab33` |
| `warning/main` | `#e88310` |
| `warning/24%` | `#ffab003d` |
| `error/24%` | `#ff56303d` |
| `System/Grey/cf-color-grey-700` | `#454f5b` |
| `grey/16%` | `#919eab29` |
| `white/main` | `#ffffff` |
| `grey/48%` | `#919eab7a` |
| `switch/[medium]--spacing` | `9` |
| `action/disabled` | `#919eab` |
| `card/radius` | `16` |
| `shadow/card` | `Effect(type: DROP_SHADOW, color: #919EAB33, offset: (0, 0), radius: 16, spread: 0)` |
| `grey/600` | `#637381` |
| `[layout]/container/[mobile]--width` | `343` |
| `_local-docs/[components]--p` | `40` |
| `_local-docs/[components]--radius` | `24` |
| `_local-docs/[components]--color` | `#637381` |


See the [shared token snapshot](../tokens/README.md). Mode IDs, alias targets, and individual property-to-variable bindings were not verified here. Equal observed values do not prove alias relationships.

## Figma reference

File key: `01imXcjljmBfqXhqFmv4kz`.

Component: [Table/Product](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=882-231025) — node `882:231025`.

Page: [🥘  nebulaONE.design Docs](https://www.figma.com/design/01imXcjljmBfqXhqFmv4kz/nebulaONE.design?node-id=0-1) — node `0:1`.

Published asset key: `cd1d1e1610c78c8fe6b4cdfa82009809449ff495`.

Observation date: 15 October 2026 (Australia/Melbourne).

Evidence: [get_metadata-0-1.json](../sources/figma/component-evidence/get_metadata-0-1.json) — `get_metadata`, observed `2026-10-15T03:33:43.568997+00:00`.

Evidence: [get_variable_defs-882-231025.json](../sources/figma/component-evidence/get_variable_defs-882-231025.json) — `get_variable_defs`, observed `2026-10-15T03:41:18.857403+00:00`.

Evidence: [list_file_components_for_code_connect-file.json](../sources/figma/component-evidence/list_file_components_for_code_connect-file.json) — `list_file_components_for_code_connect`, observed `2026-10-15T03:32:20.521071+00:00`.

## Implementation reference

**Needs design review** — component-level Code Connect mapping has not been queried for this entry. Page-level empty responses do not establish the absence of a component mapping.

MCP-generated React/Tailwind examples are not a verified project implementation or public component API. No generated runtime API has been imported into this documentation.

## Known gaps

- **Needs design review**: authored purpose/usage rules not retrieved beyond the explicitly cited source descriptions.
- **Needs design review**: raw auto-layout flags, constraints, and responsive behavior.
- **Needs design review**: interaction transitions and accessibility specifications.
- **Needs design review**: complete token bindings, mode-specific values, and alias graph.
- **Needs design review**: implementation API unless independently verified through source code.

Coverage: published identity, properties, nested-instance/text samples, and available metadata geometry. Variant names/dimensions are observed, not synthesized. Unpublished components, external dependency internals, and opaque instance/vector contents are not fully enumerated by the published graph.
