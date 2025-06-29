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
    - [ ] Establish core theme
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
   While not an attempt to totally recreate the experience of using a CRT terminal<sup><a href="#design-goal-fn1">[1]</a></sup>, the primary goal is to take the aesthetic of those terminals and derive a modern colorscheme from it. This means that the core color choice will be based around those classic ambers (and maybe greens eventually).

- **Accessible, ergonomic, and therapeutic.**  
   Phosphor aims to create color palettes that are accessible to those with low vision or colorblindness<sup><a href="#design-goal-fn2">[2]</a></sup> as well as one that's easy on the eyes, reducing the amount of blue light as much as possible. We're here for the engineers, designers, students, and whoever else uses screens for an extensive amount of time in a day, hoping to improve ocular health.

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
            <td><span style="height: 23px;width: 23px;background-color: #452f00;border-radius: 50%;display: inline-block;"></span>
            <td>bg</td>
            <td><code>#452f00</code></td>
            <td><code>rgb(69, 47, 0)</code></td>
            <td><code>hsl(40.87, 100%, 13.53%)</code></td>
        </tr>
        <tr>
            <td><span style="height: 23px;width: 23px;background-color: #ffb700;border-radius: 50%;display: inline-block;"></span>
            <td>fg</td>
            <td><code>#ffb700</code></td>
            <td><code>rgb(255, 183, 0)</code></td>
            <td><code>hsl(43.06, 100%, 50%)</code></td>
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

&nbsp;
<hr>
&nbsp;

<p align="center">Copyright &copy; 2025 <a href="https://srp.life" target="_blank">Seraphim Pardee</a> and contributors.</p>

<p align="center">
    <a href="https://github.com/phosphortheme/phosphor/blob/main/LICENSE"><img alt="Static Badge" src="https://img.shields.io/badge/License-CC_BY_4.0-452f00?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAwIiBoZWlnaHQ9IjEwMDAiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmYjcwMCIgY2xhc3M9InNpemUtNiI%2BCiAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBkPSJNMi4yNSA2YTMgMyAwIDAgMSAzLTNoMTMuNWEzIDMgMCAwIDEgMyAzdjEyYTMgMyAwIDAgMS0zIDNINS4yNWEzIDMgMCAwIDEtMy0zVjZabTMuOTcuOTdhLjc1Ljc1IDAgMCAxIDEuMDYgMGwyLjI1IDIuMjVhLjc1Ljc1IDAgMCAxIDAgMS4wNmwtMi4yNSAyLjI1YS43NS43NSAwIDAgMS0xLjA2LTEuMDZsMS43Mi0xLjcyLTEuNzItMS43MmEuNzUuNzUgMCAwIDEgMC0xLjA2Wm00LjI4IDQuMjhhLjc1Ljc1IDAgMCAwIDAgMS41aDNhLjc1Ljc1IDAgMCAwIDAtMS41aC0zWiIgY2xpcC1ydWxlPSJldmVub2RkIiAvPgo8L3N2Zz4K&logoColor=%23ffb700&logoSize=auto&labelColor=%23452f00&color=%23ffb700"></a>
</p>