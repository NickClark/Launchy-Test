Launchy and Growl Test App
=========================

For some reason launchy fails when growl is installed. Without growl, everything
seems to be fine. I have no idea how or why that would interfere.

My original gist can be found [here](http://gist.github.com/956091)

I am using this with rvm and ruby 1.9.2-p180.

To try without growl run (make sure you also run `gem uninstall growl`
first):

    bundle install
    spork cuc
    cucumber features

To break it - just uncomment the growl line from the Gemfile and re-run
the previous commands.

