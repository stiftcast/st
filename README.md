# st
My custom build of [st](https://st.suckless.org/), with inspiration taken from Luke Smith's [fork](https://github.com/LukeSmithxyz/st), but based on st 0.8.4.

## Features
### Keybindings & Shortcuts
- `<M-u> and <M-d>` - act as PgUp/PgDn
- `<M-c> and <M-v>` - act as copy and paste
- `<M-w and M-m>` - act as increase and decrease transparency respectively

'M' in the above refers to the modkey, which is set in `config.h`, this build has it set to be the Alt key.

Right clicking a selection of text will execute a program or script defined in `config.h` (plumb_cmd variable)
### Patches
The following patches have been applied:
-  [alpha](https://st.suckless.org/patches/alpha/st-alpha-0.8.2.diff)
-  [anygeometry](https://st.suckless.org/patches/anygeometry/st-anygeometry-0.8.1.diff)
-  [anysize](https://st.suckless.org/patches/anysize/st-anysize-20201003-407a3d0.diff)
-  [blinking cursor](https://st.suckless.org/patches/blinking_cursor/st-blinking_cursor-20200531-a2a7044.diff)
-  [boxdraw](https://st.suckless.org/patches/boxdraw/st-boxdraw_v2-0.8.3.diff)
-  [changealpha](https://github.com/LukeSmithxyz/st/commit/73a6020865607018f6442317e7f94fb5d54a7016)
-  [clipboard](https://st.suckless.org/patches/clipboard/st-clipboard-20180309-c5ba9c0.diff)
-  [desktopentry](https://st.suckless.org/patches/desktopentry/st-desktopentry-0.8.2.diff)
-  [externalpipe](https://st.suckless.org/patches/externalpipe/st-externalpipe-0.8.4.diff) + [externalpipe-signal](https://st.suckless.org/patches/externalpipe-signal/st-externalpipe-signal-0.8.2.diff)
-  [font2](https://st.suckless.org/patches/font2/st-font2-20190416-ba72400.diff)
-  [right click to plumb](https://st.suckless.org/patches/right_click_to_plumb/simple_plumb.diff)
-  [visualbell2-basic](https://st.suckless.org/patches/visualbell2/st-visualbell2-basic-2020-05-13-045a0fa.diff) + [visualbell2-enhanced](https://st.suckless.org/patches/visualbell2/st-visualbell2-enhanced-2020-05-13-045a0fa.diff)
-  [scrollback](https://st.suckless.org/patches/scrollback/st-scrollback-20200419-72e3f6c.diff) + [scrollback-mouse](https://st.suckless.org/patches/scrollback/st-scrollback-mouse-20191024-a2c479c.diff) + [scrollback-mouse-altscreen](https://st.suckless.org/patches/scrollback/st-scrollback-mouse-altscreen-20200416-5703aa0.diff)
-  [vertcenter](https://st.suckless.org/patches/vertcenter/st-vertcenter-20180320-6ac8c8a.diff)
-  [w3m](https://st.suckless.org/patches/w3m/st-w3m-0.8.3.diff)
-  [workingdir](https://st.suckless.org/patches/workingdir/st-workingdir-20200317-51e19ea.diff)
-  [xresources](https://st.suckless.org/patches/xresources/st-xresources-20200604-9ba7ecf.diff)
