ObsidianBlade - A semantic coloring theme for IntelliJ IDEA
----------------------------------------------------------

### Scala

![ObsidianBlade - Obsidian based color scheme](https://raw.githubusercontent.com/staslev/ObsidianBlade/master/screenshots/ObsidianBlade-with-Scala-1.png "ObsidianBlade for Scala")

### Java (a slightly outdated screenshot)

![ObsidianBlade - Obsidian based color scheme](https://raw.githubusercontent.com/staslev/ObsidianBlade/master/screenshots/ObsidianBlade-with-Java-1.png "ObsidianBlade for Java")

**ObsidianBlade** is a spin off of the classic [Obsidian](http://ideacolorthemes.org/themes/2/), the source of which I actually wanted to fork, but couldn't quite find the repo. Anyhow, thanks Morinar!

ObsidianBlade targets mainly `Java` and `Scala` (and some `Bash`) and introduces a fine-grained semantic color coding that allows one to easily tell apart semantic constructs in a glimpse of an eye. Class memebers, method parameters, local variables all have their own color, making code both pretty and easy to read.

IntelliJ version compatability:
=======================
* For IntelliJ 16.x, 17.x use the `master` branch
* For IntelliJ 13.x, 14.x, 15.x use the `v1.0` tag

Importing ObsidianBlade
=======================

1.  Download the latest [settings.jar](https://github.com/staslev/ObsidianBlade/raw/master/settings.jar).
2.  From IntelliJ, go to `File` then `Import Settings` and specify the `settings.jar` file you've downloaded in the previous step.
3. Make sure to set IntelliJ's theme to `Darcula` :
	1. Go to `IntelliJ IDEA` menu (top menu bar)
	2. Click on `Preferences`, then `Appearance & Behavior`, then  `Appearance`
	3. Set the `Scheme` to `Darcula`
4.  Finally, set the color scheme to `ObsidianBlade`:
	1. Go to `IntelliJ IDEA` menu (top menu bar)
	2. Click on `Preferences`, then `Editor`, then the `Color Scheme` and set `ObsidianBlade` as the color scheme

###### (Optional) Installing the "Source Code Pro" font:
1.  Download the [Source Code Pro](http://downloads.sourceforge.net/project/sourcecodepro.adobe/SourceCodePro_FontsOnly-1.017.zip) font to complement ObsidianBlade (and your IntelliJ in general).
2. Go to `IntelliJ IDEA` menu (top menu bar), click on `Preferences`, then `Editor`, then `Font` and set the font to `Source Code Pro`

Building ObsidianBlade:
=======================

4.  Download and extract the latest sources ([ObsidianBlade-master.zip](https://github.com/staslev/ObsidianBlade/archive/master.zip)).
5.  Execute `buildSettings.sh` to generate a `settings.jar` file.
6.  Perform the steps described in [Importing ObsidianBlade](https://github.com/staslev/ObsidianBlade#importing-obsidianblade) **starting from step 2**.
