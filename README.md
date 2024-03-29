<h1 align="center">MTW-CANVAS-MALACHITE</h1>

<table>
<td align="center">
<div align="right"><a href="https://github.com/MyThemeWay/mtw-canvas-malachite" title="Stars of Malachite Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/star-solid.svg"/> <img height="17" src="https://img.shields.io/github/stars/MyThemeWay/mtw-canvas-malachite?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-malachite" title="Forks of Malachite Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/code-branch-solid.svg"/> <img height="17" src="https://img.shields.io/github/forks/MyThemeWay/mtw-canvas-malachite?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-malachite#embed-via-jsdelivr" title="jsDelivr Hits of Malachite Canvas" target="_blank"> <img height="17" src="https://img.shields.io/jsdelivr/gh/hy/mythemeway/mtw-canvas-malachite?label=Hits&color=blue&logo=jsdelivr&cacheSeconds=3600" /></a></div>

https://user-images.githubusercontent.com/16251546/146669429-ae1dc399-cd7a-4c6e-9135-2c8a6e298df7.mp4

<img src="https://img.shields.io/github/repo-size/mythemeway/mtw-canvas-malachite?label=RepoSize&cacheSeconds=3600" />
<a title="Check it out" target="_blank" href="https://github.com/mythemeway/mtw-canvas-malachite/blob/main/LICENSE.txt"><img src="https://img.shields.io/badge/License-CC_BY_3.0-blue.svg?color=2A2E30&cacheSeconds=3600" /></a>
<a title="Check it out" target="_blank" href="https://github.com/mythemeway/mtw-canvas-malachite/releases"><img src="https://img.shields.io/github/v/release/mythemeway/mtw-canvas-malachite?label=LastRelease&cacheSeconds=3600" /></a><br>

</td>
</table>

### Note:
> * Preview shows the [boilerplate-website](#directory-boilerplate-website "Check it out") usage
> 
> * Fragment shader is based on [Glare of water](https://www.shadertoy.com/view/ttSGz3 "Check it out") [License: [CC&nbsp;BY&nbsp;3.0](https://www.shadertoy.com/view/ttSGz3 "Go there"); Copyright: © 2019 Jan Mróz; Changes: made]

<br>

## | Usage

E.&nbsp;g. as a 3D animated background 

### Directory: [boilerplate-canvas](https://github.com/MyThemeWay/mtw-canvas-malachite/tree/main/boilerplate-canvas "Check it out")

In this directory, you will find the files for the pure background. You can quickly and easily adapt the GLSLX shader files with [mtw-boilerplate-graphics](https://github.com/mythemeway/mtw-boilerplate-graphics "Check it out") or embed the already minimized canvas bundles directly on a website.

#### Embed via [jsDelivr](https://github.com/jsdelivr/jsdelivr "Check it out")

```html
<canvas id="mtw-canvas" style="width:100vw;height:100vh;left:0;top:0;position:fixed;"></canvas>
<script src="https://cdn.jsdelivr.net/gh/mythemeway/mtw-canvas-malachite@0.0.2/boilerplate-canvas/twgl/canvas.bundle.min.js"></script>
```

#### Self Hosting

```html
<canvas id="mtw-canvas" style="width:100vw;height:100vh;left:0;top:0;position:fixed;"></canvas>
<script src="./canvas.bundle.min.js"></script>
```

> <b>**Warning**</b>: WebGL canvases can make your CPU sweat. For the environment, stop the requestAnimationFrame loop when the canvas isn't visible <b>#GreenCoding</b>. See my [website-boilerplate](https://github.com/MyThemeWay/Dark-Particle/blob/master/src/canvas/mtw-canvas-disks/main.js "Check it out") for an example.

#### <a href="https://github.com/greggman/twgl.js" title="Check it out" target="_blank">TWGL</a> or <a href="https://github.com/mrdoob/three.js" title="Check it out" target="_blank">three.js</a>

There are two types of minimized bundles available. One contains <a href="https://github.com/greggman/twgl.js" title="Check it out" target="_blank">TWGL</a> and one contains <a href="https://github.com/mrdoob/three.js" title="Check it out" target="_blank">three.js</a> instead. I recommend using the TWGL bundle because it is much smaller as you can see in the table below. 

<table>
<tr>
	<th>Bundle Sizes</th>
	<th><a href="https://github.com/greggman/twgl.js" title="Check it out" target="_blank">TWGL</a></th>
	<th><a href="https://github.com/mrdoob/three.js" title="Check it out" target="_blank">three.js</a></th>
</tr>
<tr align="center">
	<th><a href="https://github.com/MyThemeWay/mtw-canvas-malachite" title="Check it out" target="_blank">malachite</a></th>
	<td>
		<a href="https://github.com/MyThemeWay/mtw-canvas-malachite/tree/main/boilerplate-canvas/twgl/canvas.bundle.min.js" title="Get it" target="_blank"><img height="20" loading="eager" alt="&nbsp;pending..." src="https://img.shields.io/github/size/mythemeway/mtw-canvas-malachite/boilerplate-canvas/twgl/canvas.bundle.min.js?label=&color=brightgreen&cacheSeconds=3600" /></a>
	</td>
	<td>
		<a href="https://github.com/MyThemeWay/mtw-canvas-malachite/tree/main/boilerplate-canvas/three/canvas.bundle.min.js" title="Get it" target="_blank"><img height="20" loading="eager" alt="&nbsp;pending..." src="https://img.shields.io/github/size/mythemeway/mtw-canvas-malachite/boilerplate-canvas/three/canvas.bundle.min.js?label=&color=darkred&cacheSeconds=3600" /></a>
	</td>
</tr>
</table>

> <b>**Note**</b>: Badges are clickable and linked to the corresponding minimized bundle.

### Directory: [boilerplate-website](https://github.com/MyThemeWay/mtw-canvas-malachite/tree/main/boilerplate-website "Check it out")

In this directory, you will find the files for the exchangeable WebGL canvas headers of the [MyThemeWay](https://github.com/MyThemeWay "Go there") Website-Boilerplates:

<a href="https://github.com/mythemeway" title="Explore this" target="_blank"><img src="https://repository-images.githubusercontent.com/438165795/0c9f226b-ef34-48db-b2e3-dc138ca86efa" /></a>

#### <b>Explore</b>: [Demo](https://mythemeway.github.io/mtw-canvas-malachite/ "Check it out") with Website-Boilerplate [Light-Particle v4.0](https://github.com/MyThemeWay/Light-Particle "Check it out")

<br>

## | Other WebGL Canvases

<table>
<td align="center" width="500px">
<div align="right"><a href="https://github.com/MyThemeWay/mtw-canvas-disks" title="Stars of Disks Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/star-solid.svg"/> <img height="17" src="https://img.shields.io/github/stars/MyThemeWay/mtw-canvas-disks?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-disks" title="Forks of Disks Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/code-branch-solid.svg"/> <img height="17" src="https://img.shields.io/github/forks/MyThemeWay/mtw-canvas-disks?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-disks#embed-via-jsdelivr" title="jsDelivr Hits of Disks Canvas" target="_blank"> <img height="17" src="https://img.shields.io/jsdelivr/gh/hy/mythemeway/mtw-canvas-disks?label=Hits&color=blue&logo=jsdelivr&cacheSeconds=3600" /></a></div>

https://user-images.githubusercontent.com/16251546/146669386-89b3ad17-6424-47a3-9f23-f779eeb2db2d.mp4

<div><a href="https://github.com/MyThemeWay/mtw-canvas-disks" title="Explore Disks Header" target="_blank"><img height="30" src="https://raw.githubusercontent.com/sitdisch/cloud/master/badges/particle/Explore-2A2E30.svg"/></div>

</td>
</table>

<div align="right">
<table>
<td align="center" width="500px">
<div align="right"><a href="https://github.com/MyThemeWay/mtw-canvas-spiral" title="Stars of Spiral Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/star-solid.svg"/> <img height="17" src="https://img.shields.io/github/stars/MyThemeWay/mtw-canvas-spiral?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-spiral" title="Forks of Spiral Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/code-branch-solid.svg"/> <img height="17" src="https://img.shields.io/github/forks/MyThemeWay/mtw-canvas-spiral?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-spiral#embed-via-jsdelivr" title="jsDelivr Hits of Spiral Canvas" target="_blank"> <img height="17" src="https://img.shields.io/jsdelivr/gh/hy/mythemeway/mtw-canvas-spiral?label=Hits&color=blue&logo=jsdelivr&cacheSeconds=3600" /></a></div>

https://user-images.githubusercontent.com/16251546/146669436-dff614aa-2ce5-46cc-8163-db73b2c2570e.mp4

<div><a href="https://github.com/MyThemeWay/mtw-canvas-spiral" title="Explore Spiral Header" target="_blank"><img height="30" src="https://raw.githubusercontent.com/sitdisch/cloud/master/badges/particle/Explore-grey.svg"/></div>

</td>
</table>
</div>

<table>
<td align="center" width="500px">
<div align="right"><a href="https://github.com/MyThemeWay/mtw-canvas-blacksea" title="Stars of Blacksea Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/star-solid.svg"/> <img height="17" src="https://img.shields.io/github/stars/MyThemeWay/mtw-canvas-blacksea?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-blacksea" title="Forks of Blacksea Canvas" target="_blank"><img src="https://raw.githubusercontent.com/sitdisch/cloud/master/3parties/code-branch-solid.svg"/> <img height="17" src="https://img.shields.io/github/forks/MyThemeWay/mtw-canvas-blacksea?label=&cacheSeconds=3600"/></a> <a href="https://github.com/MyThemeWay/mtw-canvas-blacksea#embed-via-jsdelivr" title="jsDelivr Hits of Blacksea Canvas" target="_blank"> <img height="17" src="https://img.shields.io/jsdelivr/gh/hy/mythemeway/mtw-canvas-blacksea?label=Hits&color=blue&logo=jsdelivr&cacheSeconds=3600" /></a></div>

https://user-images.githubusercontent.com/16251546/146669441-251d9545-0164-442b-8de4-3a6148481e20.mp4

<div><a href="https://github.com/MyThemeWay/mtw-canvas-blacksea" title="Explore Blacksea Header" target="_blank"><img height="30" src="https://raw.githubusercontent.com/sitdisch/cloud/master/badges/particle/Explore-2A2E30.svg"/></div>

</td>
</table>

<br>

## | Appendix
### Note on protected brand names and logos
> * The use of protected brand names, trade names, utility models and brand logos on this website does not constitute an infringement of copyright; rather, it serves as an illustrative note. Even if this is not marked as such at the respective points, the corresponding legal provisions always apply.
> 
> * The brand names and logos used are the property of their respective owners and are subject to their copyright provisions.
> * This offer is in no way related to the legal entities of the protected brand names and logos used.

### Note on liability for links
> * This README contains links to external third-party websites. The README operator has no influence on the content of these sites. Therefore, he cannot assume any liability. Instead, the respective provider is always responsible for the content.
> 
> * The linked pages were checked for possible legal violations at the time of linking and illegal content wasn't discernible. A permanent control of the linked pages is unreasonable without concrete evidence of an infringement. However, if the README operator becomes aware of such a violation, he will act immediately. 

### Readme uses
> * [star-solid.svg](https://fontawesome.com/v5.15/icons/star?style=solid "Check it out") & [code-branch-solid.svg](https://fontawesome.com/v5.15/icons/code-branch?style=solid "Check it out") [License: [CC&nbsp;BY&nbsp;4.0](https://fontawesome.com/license/free "Check it out"); Copyright: © Fonticons, Inc.; Changes: made]
> 
> * [Simple Icons](https://simpleicons.org/ "Check it out") [License: [CC0&nbsp;1.0](https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md "Go there")]
> * [Shields.io](https://github.com/badges/shields "Check it out") [License: [CC0&nbsp;1.0](https://github.com/badges/shields/blob/master/LICENSE "Go there")]
