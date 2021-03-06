Spacebase DF-9 v2 - Space station building game

This is a community maintained fork of DoubleFine's original game, which
was open sourced May 12, 2015 under the Common Public Attribution
License (CPAL-1.0: http://opensource.org/licenses/cpal_1.0).  (See
Licensing History below for more discussion).


Installation
============

Linux: 

  $ ./linux_install.sh

This will copy the modified game files on top of your Steam installation
of the game (after backing it up of course!)  This assumes you let Steam
install to its default location (i.e. under ~/.steam/).  If you need to
override the Steam path, this can be done with the STEAM_COMMON env
variable:

  $ STEAM_COMMON="~/Foo/steam/steamapps/common/" ./linux_install.sh

To restore the original game, just run:

  $ ./linux_install.sh restore

Or else just direct Steam to re-install Spacebase DF-9.  Note that save
files won't necessarily be backwards compatible!


Bugs
====
If you need to report a bug, please send us an email at spacebasehub at
gmail dot com, including a description of what you were doing, your log
file and a screenshot of the bug - whatever you think would best help us
understand the problem.

You can find your game log at:

  Windows
  <drive>:\Program Files (x86)\steam\steamapps\common\SpacebaseDF9\moai_log_space.txt 

  Linux
  ~/.steam/steam/steamapps/common/SpacebaseDF9/moai_log_Space.txt

If you can, also attach the save game located at:

  Windows
  <drive>:\Users\<your user name>\Documents\SpacebaseDF9\saves\ 

  Linux
  ~/.local/share/doublefine/spacebasedf9/Saves/


Debugging
=========
To test events more quickly you can toggle the dev debug stuff so you
can generate a new list of events and activate them at your
will. There’s a good amount of info on debugging on the wiki.

  http://spacebasedf9.gamepedia.com/Source_Documentation

See DebugMenu.lua for how to implement new debugging operations.


Contributing
============
Derelict Games is at heart a collaborative open source project, and
as such welcomes community contributions.  You're welcome to send
new art, one-off patches, content suggestions, and good ideas via the
usual bug reporting instructions outlined above.

Those wishing to do more substantial code contributions may wish to look
at our repository on gitlab.  Send us a pull request if you have
something cool to include.

If you'd like to participate more deeply and directly, that's great!
We've got a "2 contributions" rule as an entry requirement, so get a
couple patches accepted, or thumbs up from the art crew on a couple
pieces of art or sound or whatnot.  Then, just ask one of the current
team and we'll get you hooked in!

What skills do you need?  Most of the code is written in Lua, and as
it's a big established codebase it overall requires Patience and
Persistence.  Artwork requires 3D modeling skills and a good eye for
design, texturing is a plus; exports need to be in OBJ.  Content
production requires a sense of humor and experience with standard Sci Fi
tropes.  Translation work requires being able to write coherently in
more than one language.  Packaging and porting requires depth of
knowledge in how your operating system works.  Even more critical are
skills like, "Good teammanship," and "Having time to commit."


Code Style
==========
The code uses 'hungarian notation'.  For an explanation, see

  http://blogs.msdn.com/b/ericlippert/archive/2003/09/12/52989.aspx

We believe the meaning is:  n is Number, b is Boolean, t is Table, r is
Reference, e is Enum.
check email


== Licensing History ==

Path v1.07 Unofficial - Sep 27, 2015
    The official Unofficial Patch of v1.07 was released. A few bugs were recorded in emails, in forums and between us in the Slack system.
    Cxsquared has given us access to his server setup to be ready for a new website that has emails, forums and other various things.
    Patch v1.07.01 will be released Oct 6 or 7, 2015.

Resoration Code - Sep 20, 2015
    We have a Slack messaging system room. Similar to IRC, sbrs.slack.com under the #Dev room 
    to come and chat with us about what we're all doing.

MOTD - May 12, 2015
    Open source license available at: http://opensource.org/licenses/cpal_1.0

    -- https://web.archive.org/web/20150512113236/http://blog.spacebasedf9.com/motd/motd.txt

JP - Sept 17, 2014
    We’re also pleased to announce we’ll be releasing the game’s full
    Lua source code a short time after 1.0, which will allow the
    community to create potentially far-ranging mods that add content,
    new features, and change some fundamental game behaviors.

    -- http://store.steampowered.com/news/externalpost/steam_community_announcements/521612880954244703

JP - Oct 27, 2014
    The game’s Lua source code is now available in the game’s install
    directory on all platforms. Usually this will be in your Steam
    directory, under SteamApps\common\SpacebaseDF9\Data\Scripts. If you
    own the game you can modify these files and distribute your
    modifications to other users as you like. A large portion of
    Spacebase is written in Lua, so there are relatively few limits on
    what you can do with this.

    -- http://steamcommunity.com/games/246090/announcements/detail/216497448170557993
