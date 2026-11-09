# Digital Life Store Engraving Flow

Engraving Flow by Digital Life Store previews how deep an STL relief or a grayscale depth map would cut into a coin blank or flat stock. Set the blank dimensions to see the deepest planned cut and how much material would remain beneath it.

![Warrior coin reference render beside the STL engraving preview, which shows a 2.056 mm cut on a 4 mm coin blank.](media/warrior-coin-overview.jpg)

## Warrior coin example

This example uses a **60 mm diameter, 4 mm thick coin blank** with an STL and its companion 16-bit PNG depth map. In **Automatic** mode, the STL's relief is read in millimeters and the depth map's grayscale tones are scaled to the blank thickness.

### 1. Follow the cut in 3D

In **Result**, drag the depth slider from the untouched blank to the full cut. Use the angle, top, side, and cutaway views to inspect the relief.

<details>
<summary>Watch the engraving preview</summary>

![The untouched coin blank gradually reveals the warrior relief as the depth slider reaches 2.056 mm.](media/warrior-coin-engraving.gif)

</details>

### 2. Find the deepest point

**Detailed Result** marks the deepest point on the top-down cut map. The red line in the cross-section shows the final cut. The dashed gold line marks the bottom of the blank.

![Top-down cut depth map and cross-section through the deepest point, with 1.944 mm of stock remaining.](media/warrior-coin-cut-analysis.png)

### 3. Compare the STL and depth map

Load the STL's companion depth map to compare both designs on the same blank. Both cuts fit within the selected stock.

| Design | Deepest cut | Minimum stock remaining |
| --- | ---: | ---: |
| STL | 2.056 mm | 1.944 mm |
| 16-bit depth map | 2.059 mm | 1.941 mm |

The mean gap across the engraved area is **0.018 mm**. At the point marked below, the planned cut from the depth map is **0.338 mm** deeper than the STL cut. That exceeds the **0.10 mm** preview tolerance, even though the deepest cuts are close.

![Difference map and overlaid STL and depth-map profiles at the largest sampled gap.](media/warrior-coin-comparison.png)

## Plan an engraving

Load an STL or a PNG or PGM depth map. Choose a coin blank or flat stock, enter its dimensions, and use **Manual** mode if you want to set your own maximum cut depth. The preview shows whether the cut fits within the material, reaches the bottom, or passes through. Files are processed locally in your browser.

The figures above are geometric previews. **Suggestions** lists published starting settings and can use your measured test cuts to help estimate settings for a target depth. Verify the settings on a test piece of the same material before engraving the final blank.

[Digital Life Store](https://digitallifestore.net/)
