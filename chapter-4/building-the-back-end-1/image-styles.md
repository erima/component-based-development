# Image Styles

### Create the following **Image Styles**:

| Name | Machine name | Dimensions | Effect |
| :--- | :--- | :--- | :--- |
| 16:9 285x160 | `16_9_285x160` | 285 x 160 | Scale and Crop |
| 16:9 450x253 | `16_9_450x253` | 450 x 253 | Scale and Crop |
| 16:9 570x320 | `16_9_570x320` | 570 x 320 | Scale and Crop |
| 16:9 900x506 | `16_9_900x506` | 900 x 506 | Scale and Crop |
| 16:9 1200x675 | `16_9_1200x675` | 1200 x 675 | Scale and Crop |
| 16:9 2200x1238 | `16_9_2200x1238` | 2200 x 1238 | Scale and Crop |

### Create the following **Responsive Image Styles**:

| Name | Machine name | Breakpoint Group | Fallback Image |
| :--- | :--- | :--- | :--- |
| Movie Card | `movie_card` | Responsive Image | 16:9 1200x675 |
| Hero | `hero` | Responsive Image | 16:9 450x253 |

### Apply the following configuration under **1X Viewport Sizing**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Movie Card</b>
      </th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Type</td>
      <td style="text-align:left"><em>Select multiple image styles and use the sizes attribute</em>.</td>
    </tr>
    <tr>
      <td style="text-align:left">Sizes</td>
      <td style="text-align:left"><em><code>(min-width: 768px) 50vw, (min-width: 1025px) 25vw, 100vw</code></em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Image Styles</td>
      <td style="text-align:left">
        <p><em>16:9 285x160</em>
        </p>
        <p><em>16:9 450x253</em>
        </p>
        <p><em>16:9 570x320</em>
        </p>
        <p><em>16:9 900x506</em>
        </p>
      </td>
    </tr>
  </tbody>
</table>| _Hero_ |  |
| :--- | :--- |
| Hero | Select multiple image styles and use the sizes attribute. |
| Sizes | `100vw` |
| Image Styles | All 16:9 images styles |

{% hint style="info" %}
The beauty of these image styles is that they are aspect ratio-based rather than specific image dimensions.  When possible, this is recommended as this makes the image styles more reusable and therefore reduces the number of image styles to be created and maintained.
{% endhint %}
