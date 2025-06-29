<h3 align="center">
    <img src="https://raw.githubusercontent.com/phosphortheme/assets/refs/heads/main/icons/icon-bright.svg" width="100" alt="icon"/>
    <br>
    Phosphor
</h3>

<h4 align="center">
    Terminal nostalgia for the modern eye.
</h4>

<h5 align="center">
    <s><a href="https://phosphor.srp.life/palettes">Palettes</a></s>
    &ndash;
    <s><a href="https://phosphor.srp.life/ports">Ports</a></s>
    &ndash;
    <a href="https://github.com/phosphortheme/phosphor/wiki">Wiki</a>
</h5>

<hr>

### ⚠️ Work-in-Progress

Phosphor is in its baby phases, with major design choices still being made and stability being relatively low. This is a work-in-progress and currently carries more ambition than result. Please keep this in mind until we feel comfortable enough to release a proper version.

The following can be used as our rough roadmap until things become more concrete:

1. Implement Phosphor Dark Amber
    - [x] Establish core theme
    - Ports
        1. [ ] .Xresources / kitty / alacritty
        2. [ ] Visual Studio Code
        3. [ ] Chromium (and derivatives)
        3. [ ] {neo}vim
        4. [ ] tmux
2. Implement Phosphor Light Amber
    - [ ] Establish core theme
    - Ports
        1. [ ] .Xresources / kitty / alacritty
        2. [ ] Visual Studio Code
        3. [ ] Chromium (and derivatives)
        3. [ ] {neo}vim
        4. [ ] tmux

### 💭 Design Philosophy

- **The aesthetic of old CRT terminals, with a modern touch.**  
   While not an attempt to totally recreate the experience of using a CRT terminal<sup><a href="#user-content-design-goal-fn1">[1]</a></sup>, the primary goal is to take the aesthetic of those terminals and derive a modern colorscheme from it. This means that the core color choice will be based around those classic ambers (and maybe greens eventually).

- **Accessible, ergonomic, and therapeutic.**  
   Phosphor aims to create color palettes that are accessible to those with low vision or colorblindness<sup><a href="#user-content-design-goal-fn2">[2]</a></sup> as well as one that's easy on the eyes, reducing the amount of blue light as much as possible. We're here for the engineers, designers, students, and whoever else uses screens for an extensive amount of time in a day, hoping to improve ocular health.

<small><span id="design-goal-fn1">[1]</span>: See [cool-retro-term](https://github.com/Swordfish90/cool-retro-term) for a project with those goals in mind.
<br>
<span id="design-goal-fn2">[2]</span>: To this end, we are seeking to comply with level AAA of the WCAG 2.2, where the [ideal contrast of text to background is at least 7:1](https://www.w3.org/TR/WCAG22/#contrast-enhanced).</small>

### Palettes

<details>
    <summary>Phosphor Dark Amber</summary>
    <table>
        <tr>
            <th></th>
            <th>Label</th>
            <th>Hex</th>
            <th>RGB</th>
            <th>HSL</th>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #2E2100;border-radius: 50%;display: inline-block;"></span>
            <td>Black Swan (bg)</td>
            <td><code>#2E2100</code></td>
            <td><code>rgb(46, 33, 0)</code></td>
            <td><code>hsl(43, 100%, 9%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #452F00;border-radius: 50%;display: inline-block;"></span>
            <td>Night in the Woods</td>
            <td><code>#452F00</code></td>
            <td><code>rgb(69, 47, 0)</code></td>
            <td><code>hsl(41, 100%, 14%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #634400;border-radius: 50%;display: inline-block;"></span>
            <td>Notorious Neanderthal</td>
            <td><code>#634400</code></td>
            <td><code>rgb(99, 68, 0)</code></td>
            <td><code>hsl(41, 100%, 19%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #FFACA5;border-radius: 50%;display: inline-block;"></span>
            <td>Patient Pink</td>
            <td><code>#FFACA5</code></td>
            <td><code>rgb(255, 172, 165)</code></td>
            <td><code>hsl(5, 100%, 82%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #00E05A;border-radius: 50%;display: inline-block;"></span>
            <td>Malachite</td>
            <td><code>#00E05A</code></td>
            <td><code>rgb(0, 224, 90)</code></td>
            <td><code>hsl(144, 100%, 44%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #EDED00;border-radius: 50%;display: inline-block;"></span>
            <td>Saint Seiya Gold</td>
            <td><code>#EDED00</code></td>
            <td><code>rgb(237, 237, 0)</code></td>
            <td><code>hsl(60, 100%, 46%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #00FAD2;border-radius: 50%;display: inline-block;"></span>
            <td>Plunge Pool</td>
            <td><code>#00FAD2</code></td>
            <td><code>rgb(0, 250, 210)</code></td>
            <td><code>hsl(170, 100%, 49%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #FF9FFF;border-radius: 50%;display: inline-block;"></span>
            <td>Pinkalicious</td>
            <td><code>#FF9FFF</code></td>
            <td><code>rgb(255, 159, 255)</code></td>
            <td><code>hsl(300, 100%, 81%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #00D2FF;border-radius: 50%;display: inline-block;"></span>
            <td>Vivid Sky Blue</td>
            <td><code>#00D2FF</code></td>
            <td><code>rgb(0, 210, 255)</code></td>
            <td><code>hsl(191, 100%, 50%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #D19200;border-radius: 50%;display: inline-block;"></span>
            <td>Elysium Gold</td>
            <td><code>#D19200</code></td>
            <td><code>rgb(209, 146, 0)</code></td>
            <td><code>hsl(42, 100%, 41%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #FFB700;border-radius: 50%;display: inline-block;"></span>
            <td>Sunflower Mango (fg)</td>
            <td><code>#FFB700</code></td>
            <td><code>rgb(255, 183, 0)</code></td>
            <td><code>hsl(43, 100%, 50%)</code></td>
        </tr>
    </table>
</details>
&nbsp;
<details>
    <summary>Phosphor Light Amber</summary>
    <table>
        <tr>
            <th></th>
            <th>Labels</th>
            <th>Hex</th>
            <th>RGB</th>
            <th>HSL</th>
        </tr>
    </table>
</details>

### ⚖️ License

Phosphor is released under [Creative Commons Attribution 4.0 International](https://github.com/phosphortheme/phosphor/blob/main/LICENSE). You are generally free to do as you like, as long as credit (see copyright notice at the bottom) is given where necessary.

### 🫂 Special Thanks

- [Catppuccin](https://catppuccin.com) and [Nord](https://nordtheme.com) for Markdown inspirations.

&nbsp;
<hr>
&nbsp;

<p align="center">Copyright &copy; 2025 <a href="https://srp.life" target="_blank">Seraphim Pardee</a> and contributors.</p>

<p align="center">
    <a href="https://github.com/phosphortheme/phosphor/blob/main/LICENSE"><img alt="Static Badge" src="https://img.shields.io/badge/License-CC_BY_4.0-452f00?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAwIiBoZWlnaHQ9IjEwMDAiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmYjcwMCIgY2xhc3M9InNpemUtNiI%2BCiAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMi4yNSA2YTMgMyAwIDAgMSAzLTNoMTMuNWEzIDMgMCAwIDEgMyAzdjEyYTMgMyAwIDAgMS0zIDNINS4yNWEzIDMgMCAwIDEtMy0zVjZabTMuOTcuOTdhLjc1Ljc1IDAgMCAxIDEuMDYgMGwyLjI1IDIuMjVhLjc1Ljc1IDAgMCAxIDAgMS4wNmwtMi4yNSAyLjI1YS43NS43NSAwIDAgMS0xLjA2LTEuMDZsMS43Mi0xLjcyLTEuNzItMS43MmEuNzUuNzUgMCAwIDEgMC0xLjA2Wm00LjI4IDQuMjhhLjc1Ljc1IDAgMCAwIDAgMS41aDNhLjc1Ljc1IDAgMCAwIDAtMS41aC0zWiIgY2xpcC1ydWxlPSJldmVub2RkIiAvPgo8L3N2Zz4K&logoColor=%23ffb700&logoSize=auto&labelColor=%23452f00&color=%23ffb700"></a>
</p>