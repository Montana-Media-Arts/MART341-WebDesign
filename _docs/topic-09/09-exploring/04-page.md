---
title: Hex Codes
module: topic-09
permalink: /topic-09/color-hex/
---

<div class="divider-heading"></div>

Hexadecimal (or hex) values are written as a single string, prepended with a number sign, with digits for each color. `#RRGGBB`


<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
/* Black as a hex code: */
p {
  color: #000000;
}
```

**The major difference** is that you can represent 256 values with a two-bit hexadecimal number. In hexadecimal numbering, each digit has 16 values (0-f). And, 16 * 16 = 256.

If we were to translate this to binary:


<table style="width: 250px; text-align: center; margin: auto;">
  <thead>
    <tr>
      <th style="text-align: center">Binary</th>
      <th style="text-align: center">Hex</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>4</td>
    </tr>
    <tr>
      <td>5</td>
      <td>5</td>
    </tr>
    <tr>
      <td>6</td>
      <td>6</td>
    </tr>
    <tr>
      <td>7</td>
      <td>7</td>
    </tr>
    <tr>
      <td>8</td>
      <td>8</td>
    </tr>
    <tr>
      <td>9</td>
      <td>9</td>
    </tr>
    <tr>
      <td>10</td>
      <td>a</td>
    </tr>
    <tr>
      <td>11</td>
      <td>b</td>
    </tr>
    <tr>
      <td>12</td>
      <td>c</td>
    </tr>
    <tr>
      <td>13</td>
      <td>d</td>
    </tr>
    <tr>
      <td>14</td>
      <td>e</td>
    </tr>
    <tr>
      <td>15</td>
      <td>f</td>
    </tr>
  </tbody>
</table>

<br/>

<table style="width: 250px; text-align: center; margin: auto;">
  <thead>
    <tr>
      <th style="text-align: center">So, in hex, we write the value:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>000</code> &nbsp;as&nbsp; <code>00</code></td>
    </tr>
    <tr>
      <td><code>010</code> &nbsp;as&nbsp; <code>0a</code></td>
    </tr>
    <tr>
      <td><code>015</code> &nbsp;as&nbsp; <code>0f</code></td>
    </tr>
    <tr>
      <td><code>016</code> &nbsp;as&nbsp; <code>10</code></td>
    </tr>
    <tr>
      <td><code>017</code> &nbsp;as&nbsp; <code>11</code></td>
    </tr>
    <tr>
      <td><code>031</code> &nbsp;as&nbsp; <code>1f</code></td>
    </tr>
    <tr>
      <td><code>032</code> &nbsp;as&nbsp; <code>20</code></td>
    </tr>
    <tr>
      <td><code>050</code> &nbsp;as&nbsp; <code>32</code></td>
    </tr>
    <tr>
      <td><code>100</code> &nbsp;as&nbsp; <code>64</code></td>
    </tr>
    <tr>
      <td><code>150</code> &nbsp;as&nbsp; <code>96</code></td>
    </tr>
    <tr>
      <td><code>200</code> &nbsp;as&nbsp; <code>c8</code></td>
    </tr>
    <tr>
      <td><code>250</code> &nbsp;as&nbsp; <code>fa</code></td>
    </tr>
    <tr>
      <td><code>255</code> &nbsp;as&nbsp; <code>ff</code></td>
    </tr>
  </tbody>
</table>
