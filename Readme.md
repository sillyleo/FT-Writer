# FT Writer 1.1

FT Writer is a [FoldingText](http://www.foldingtext.com) theme based on [iA Writer](http://www.iawriter.com), featuring:

- **Focus Mode** `new in 1.1`
- 2 fonts option: **Cousine** or **Nitti** .
- Fine-tuned line height for both fonts
- Looks like iA Writer (duh)
- Subtle CSS animation
- Fixed line-height for Asian languages. (No more jumping text)

FoldingText is a clever text productivity app, and iA Writer is the most beautiful one. I made a theme that makes FoldingText look like iA Writer

## Focus Mode

Now you can shrink the window to focus on to-dos!

<video width="100%" controls="controls">
  <source src="http://d.pr/v/5IXX+" type="video/mp4">
</video>

[Watch Video](http://d.pr/v/5IXX)

## Cousine

![Cousine Mode](http://d.pr/i/czU5+)

FT Writer uses the **Cousine** as default. It's [available from Google](). 

## Nitti

![Nitti Mode](http://d.pr/i/buUo+)

Nitti is a commercial font which can be [purchased here](http://www.boldmonday.com/en/nitti) (Buy Nitti Light). If you have **Nitti** installed you can enable **Nitti-mode**.

## Install

1. Open your Terminal.app in Applications > Utilities.
2. Paste the following command and press enter:
	`git clone git://github.com/sillyleo/FT-Writer.git ~/Library/Containers/com.foldingtext.FoldingText/Data/Library/Application\ Support/FoldingText/Themes/User.fttheme`
3. Restart FoldingText

## Update

1. Open your Terminal.app in Applications > Utilities.
2. Paste the following command and press enter:
	`cd ~/Library/Containers/com.foldingtext.FoldingText/Data/Library/Application\ Support/FoldingText/Themes/User.fttheme`
3. And then `git pull`
4. Restart FoldingText

**Note**: After updating, your Nitti will be overridden, you'll need to rename your CSS again.

## Uninstall

1. In Finder, press `command + shift + g`, paste the following path and press enter:
	`~/Library/Containers/com.foldingtext.FoldingText/Data/Library/Application Support/FoldingText/Themes/`
2. Remove the `User.fttheme` folder.

## Enable Nitti Mode

1. Purchase Nitti
2. In Finder, press `command + shift + g`, paste the following path and press enter:
	`~/Library/Containers/com.foldingtext.FoldingText/Data/Library/Application Support/FoldingText/Themes/`
3. Rename `style.css` into something like `style-cousine.css` and rename `style-nitti.css` into `style.css`
4. Restart FoldingText

## Contact

If you have any questions please mention me on Twitter: [@sillyleo](http://twitter.com/sillyleo)

## Special Thanks

Thanks to [@evenwu](http://twitter.com/evenwu) for some tips on Github and CSS.