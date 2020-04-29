pixel-sprite-generator
======================

JavaScript implementation of a procedural pixel sprite generator similar to the old days of video game sprites. The sprites are algorithmically generated by combinatorial methods. 

## Live Example
[http://plnkr.co/edit/Dji8rljS0yDL16Ao8Iq6?p=preview](http://plnkr.co/edit/Dji8rljS0yDL16Ao8Iq6?p=preview)

<a href="http://plnkr.co/edit/Dji8rljS0yDL16Ao8Iq6?p=preview"><img src="https://github.com/zfedoran/pixel-sprite-generator/raw/master/doc/screenshot.png"></a>

## Installation

#### Using Bower
If you have [bower](http://bower.io/) installed, you can add the pixel-sprite-generator to your project using the following command.

```
bower install pixel-sprite-generator
```

#### Using NPM
If you have [npm](https://www.npmjs.org/) installed, you can add the pixel-sprite-generator to your project using the following command.

```
npm install pixel-sprite-generator
```

## Ports/Other Languages
- Dart [pixel-sprite-generator](https://github.com/tobbel/pixel-sprite-generator) port by [tobbel](https://github.com/tobbel)
- Haxe [pixel-sprite-generator](https://github.com/Zielak/pixel-sprite-generator) port by [Zielak](https://github.com/Zielak)
- C# [pixel-sprite-generator](https://github.com/BenMcLean/Pixel-Sprite-Generator-CSharp) port by [BenMcLean](https://github.com/BenMcLean)
- libGDX [pixel-sprite-generator](https://github.com/BenMcLean/pixel-sprite-generator-libgdx) port by [BenMcLean](https://github.com/BenMcLean)
- Unity3d [pixel-sprite-generator](https://github.com/Shogan/PixelSpriteGenerator-Unity) port by [Shogan](https://github.com/Shogan)
- Node.js [pixel-sprite-generator](https://github.com/blipn/pixel-sprite-generator-nodejs) port by [blipn](https://github.com/blipn)
- Node.js/Browser [pixel-sprite-generator](https://github.com/seiyria/mixel) port by [seiyria](https://github.com/seiyria)
- Rust [sprite-gen](https://github.com/tversteeg/sprite-gen) port (with editor) by [tversteeg](https://github.com/tversteeg)
- OCaml [px_sprite_gen](https://github.com/fccm/px_sprite_gen) port by [Florent Monnier](https://github.com/fccm)
- Python [Sprite-Generator](https://github.com/MaartenGr/Sprite-Generator) port by [MaartenGr](https://github.com/MaartenGr)


## Algorithm

The sprites are generated by using a two dimensional mask. The values in the mask are then randomized and mirrored. The resulting template is rendered to a canvas element.

<a href="http://web.archive.org/web/20080228054410/http://www.davebollinger.com/works/pixelspaceships/"><img src="https://github.com/zfedoran/pixel-sprite-generator/raw/master/doc/algorithm-1.png"></a>

The algorithm is explained in more detail on [Dave Bollinger's](http://web.archive.org/web/20080228054410/http://www.davebollinger.com/works/pixelspaceships/) website.

<a href="http://web.archive.org/web/20080228054410/http://www.davebollinger.com/works/pixelspaceships/"><img src="https://github.com/zfedoran/pixel-sprite-generator/raw/master/doc/algorithm-0.png"></a>
