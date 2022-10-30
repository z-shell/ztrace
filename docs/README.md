<!-- markdownlint-disable MD041 -->
<div align="center"><table style="width:100%;height:auto">
 <tr align="justify" margin-left="auto" margin-right="auto"><td align="center">
  <h1>
  <a href="https://github.com/z-shell/zi">
    <img src="https://github.com/z-shell/zi/raw/main/docs/images/logo.png" alt="Logo" width="80" height="80" />
  </a>
  ❮ Zi ❯ Plugin - Ztrace
  </h1>
<h3>
  <a href="https://github.com/orgs/z-shell/discussions/">《❔》Ask a Question </a>
  <a href="https://wiki.zshell.dev/search/">《💡》Search Wiki </a>
  <a href="https://github.com/z-shell/community/issues/new?assignees=&labels=%F0%9F%91%A5+member&template=membership.yml&title=team%3A+">《💜》Join </a>
  <a href="https://translate.zshell.dev">《🌐》Localize </a>
</h3>
</td></tr>
<tr><td align="center">
  <a title="Crowdin" target="_self" href="https://translate.zshell.dev">
    <img align="center" src="https://badges.crowdin.net/e/f108c12713ee8526ac878d5671ad6e29/localized.svg" />
  </a>
  <a title="License GPL-3.0" target="_self" href="https://www.gnu.org/licenses/gpl-3.0/">
    <img align="center" src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" alt="Project License" />
  </a>
  <a title="VIM" target="_self" href="https://github.com/z-shell/zi-vim-syntax/">
    <img align="center" src="https://img.shields.io/badge/--019733?logo=vim" alt="VIM" />
  </a>
  <a title="ZI-Src" target="_self" href="https://open.vscode.dev/z-shell/ztrace/">
    <img
      align="center"
      src="https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff"
      alt="Visual Studio Code"
    />
  </a><br />
  <p><a href="https://asciinema.org/a/45530" target="_blank"><img src="https://asciinema.org/a/45530.svg" /></a></p>
</td></tr><tr><td align="left"><br />

`Ztrace` plugin allows to catch output of commands in background.
By issuing:

```zsh
ztstart 3
```

We inform `Ztrace` to catch output of `3` commands. Click image above to watch the asciicast.

## Installation

### [ZI](https://github.com/z-shell/zi)

Add `zi load z-shell/ztrace` to your `.zshrc` file. zi will handle
cloning the plugin for you automatically the next time you start zsh.

### [Antigen](https://github.com/zsh-users/antigen)

Adding `antigen bundle z-shell/ztrace` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start zsh. You can also add the plugin to a running zsh with `antigen bundle z-shell/ztrace` for testing before adding it to your `.zshrc`.

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone git@github.com:z-shell/ztrace.git`
3. Add zsnapshot to your plugin list

### [Zgenom](https://github.com/jandamm/zgenom)

Add `zgenom load z-shell/ztrace` to your .zshrc file in the same function you're doing your other `zgen load` calls in.

## More information

Below are keyboard shortcuts used by `ztrace` command:

- `Ctrl-T` - start Zsh Command Architect (Zshell binding)
- `Ctrl-E` - switch between Ztrace and History views
- `Enter` - delete selected segment (when in command window) or add selected segment (when in history window)
- `[` or `]` - move active segment (when in command window)
- `Shift-left` or `Shift-right` - move active segment (when in command window)
- `Tab` - switch between the two available windows
- `g, G` - beginning and end of the list
- `/` - start incremental search
- `Esc` - exit incremental search, clearing filter
- `<`,`>`, `{`,`}` - horizontal scroll
- `Ctrl-L` - redraw of whole display
- `Ctrl-O`, `o` - enter uniq mode (no duplicate lines)
- `Ctrl-W` (in incremental search) - delete whole word
- `Ctrl-K` (in incremental search) - delete whole line
- `Ctrl-D`, `Ctrl-U` - half page up or down
- `Ctrl-P`, `Ctrl-N` - previous and next (also done with vim's j,k)

</td></tr><tr><td align="center"><h2 align="left">Credits</h2>
 <a href="https://trunk.io" rel="nofollow">
  <img style="width:140;height:40px" src="https://storage.googleapis.com/digital-space/img/brand/trunk/trunk-white.svg" alt="Trunk" />
 </a>
 <a href="https://crowdin.com/?utm_source=badge&utm_medium=referral&utm_campaign=badge-add-on" rel="nofollow">
  <img style="width:140;height:40px" src="https://space.ss-o.workers.dev/img/brand/crowdin/localization-at-dark-rounded@2x.png" srcset="https://badges.crowdin.net/badge/light/crowdin-on-dark.png 1x,https://badges.crowdin.net/badge/light/crowdin-on-dark@2x.png 2x"alt="Crowdin | Agile localization for tech companies" />
 </a>
 <a href="https://www.digitalocean.com/?refcode=090bdb63f800&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge" rel="nofollow">
  <img style="width:140;height:40px" src="https://web-platforms.sfo2.digitaloceanspaces.com/WWW/Badge%203.svg" alt="DigitalOcean Referral Badge" />
 </a>
 <a href="https://cloudflare.com" rel="nofollow">
  <img style="width:140;height:40px" src="https://storage.googleapis.com/digital-space/img/brand/cloudflare/cf-logo-v-rgb.png" alt="Cloudflare" />
 </a>
 </td></tr></table></div>
