## PhpStorm Live Templates

These project contains my PhpStorm live templates. Live Templates is a great feature of any IDE, but in PhpStorm there are no live templates preconfigured for php, so I defined mine.

To use them just copy the xml file in your templates folder (see [this article][2] to find out where it's located). For example on Mac OS X you can open Terminal.app and type

    curl -o ~/Library/Preferences/WebIDE10/templates/PHP.xml \
    https://raw.github.com/fabn/phpstorm-live-templates/master/PHP.xml

**WARNING: this will override any existing template in the PHP group if you have any of them defined**

After that you have to restart the IDE to make changes effective, and you'll have a lot of templates defined. If you don't have any template defined in your templates folder, you can easily replace it with a clone of this repository to receive updates with

    rmdir ~/Library/Preferences/WebIDE10/templates/ && \
    git clone git://github.com/fabn/phpstorm-live-templates.git ~/Library/Preferences/WebIDE10/templates

Read more on this feature [here][1] and [here][3]

[1]: http://blogs.jetbrains.com/webide/2010/03/zen-coding-support-in-webstormphpstorm
[2]: http://www.jetbrains.com/phpstorm/webhelp/live-templates-2.html
[3]: http://www.jetbrains.com/phpstorm/webhelp/creating-and-editing-template-variables.html
