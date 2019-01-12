# Linux--GNOME-themes
一些比较精美的Linux桌面主题合集，打造一款属于自己的精美Linux系统




## Tools install



## 主题
> 新建一个.themes文件夹  mkdir ~/.themes

- [Flat Remix GNOME theme](https://github.com/daniruiz/flat-remix-gnome)
> Flat Remix GNOME theme is a pretty simple shell theme inspired on material design. It follows a modern design using "flat" colors with high contrasts and sharp borders.

这个合集里面包含了：
 - Flat-Remix-Dark
 - Flat-Remix-Darkest
 - Flat-Remix-Miami-Dark
 - Flat-Remix-Miami

![Flat Remix GNOME theme](https://raw.githubusercontent.com/daniruiz/Flat-Remix-GNOME-theme/master/Images/2.png)


使用的时候，下载这个主题包

```
cp flat-remix-gnome/Flat-Remix*  ~/.themes
gsettings set org.gnome.shell.extensions.user-theme name "Flat-Remix";
或者使用gnome-tweak-tool，Select "Flat Remix" as shell theme

```

## 图标集
> 新建一个.icons文件夹   mkdir ~/.icons

- [la-capitaine-icon-theme MacOS 图标集](https://github.com/keeferrourke/la-capitaine-icon-theme)
>La Capitaine is an icon pack designed to integrate with most desktop environments. The set of icons takes inspiration from the latest iterations of macOS and Google's Material Design through the use of visually pleasing gradients, shadowing, and simple icon geometry.

![la-capitaine-icon-theme](https://github.com/keeferrourke/la-capitaine-icon-theme/blob/master/.product/preview.png)

使用方法

```
cd ~/.icons
git clone https://github.com/keeferrourke/la-capitaine-icon-theme.git
使用gnome-tweak-tool，Select "la-capitaine-icon-theme" as  Appearance/Icons
```




## 拓展插件

- [GNOME Shell Extensions, user themes extension](https://drasite.com/flat-remix-gnome)
>GNOME Shell Extensions is a collection of extensions providing additional and optional functionality to GNOME Shell.

- [A dock for the GNOME Shell 在桌面底端开启一个图标栏](https://github.com/micheleg/dash-to-dock)
- [gnome-shell-simple-dock 跟上面功能类似的一个插件](https://github.com/optimisme/gnome-shell-simple-dock)
>This extension enhances the dash moving it out of the overview and transforming it in a dock for an easier launching of applications and a faster switching between windows and desktops without having to leave the desktop view.

![dash to dock ](https://raw.githubusercontent.com/micheleg/dash-to-dock/master/media/screenshot.jpg)

使用方法

```
git clone https://github.com/micheleg/dash-to-dock.git
make
make install
A Shell reload is required Alt+F2 r Enter and the extension has to be enabled with gnome-tweak-tool or with dconf.
gnome-tweak-tool --> Extensions
```

