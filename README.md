# an accessible tumblr theme

hi! this is a tumblr theme i made. graphic design is not my passion, but it does have the following features:

- screenreader accessible
- screenreaders can scroll through posts by using headings!!
- keyboard accessible
- can zoom to however big you like
- has a blocklist function to hide posts via the list of tags in the sidebar. you do have to hit the block button every time you move to a different page though, couldn’t find a good way to implement it over multiple pages..
- image alt text shows up when you hover over the image, if it exists

you can go to [whale-blanket dot tumblr dot com](https://whale-blanket.tumblr.com) for a demo.

i don't use tumblr anymore, and also i wrote most of this code years ago when i didn't actually understand how javascript works, so things might be broken. if something comes up, [open an issue in this repo](https://github.com/stillnotstars/tungle/issues/new), ping me on mastodon [@daffodilian@weirder.earth](https://weirder.earth/@daffodilian), or send an ask to my tumblr: [@stillnotstars](https://stillnotstars.tumblr.com).

shoutouts to [1linelayouts](https://1linelayouts.glitch.me/) for being a cool css resource for a bunch of fancy stuff with `display: grid/flex`.

## how to install
copy the text in [this file](https://raw.githubusercontent.com/stillnotstars/tungle/main/theme.html).

open the tumblr customizer. at the top of the sidebar, under your current theme name, should be the text "edit html." click that, delete everything currently there, and paste the plain text from the previously linked file. click "update preview," "save," and tweak settings as needed.

unfortunately you have to manually repeat this step every time i update the code here.

## possible improvements?

- [ ] make embedded youtube videos, photosets, etc display properly
- [ ] more robust blacklisting? don't count on this ever happening, though, i don't know any ways of doing this. if you do, feel free to open an issue or pr
