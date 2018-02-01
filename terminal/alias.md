# Alias

### Renaming some commands I don't like typing
```
alias fishies="asciiquarium"
alias please="sudo"
alias ws="webstorm"
```

### Shortening some common commands I am too lazy to type everytime
```
alias zs="source ~/.zshrc"
alias config="code ~/.zshrc"
```
Since I change my configuration so much, the zs alias allows me to quickly reload my terminal to see my changes. The config alias allows me to quickly open my main terminal profile for edits.

```
alias cwd="pwd | pbcopy"
```
This alias allows me to quickly copy my current location. I mostly use it when I need to open a second terminal tab and want to be in the same location with out having to do all the cd things to get there.

```
alias ls="clear ; ls -F -G"
```
I set up this alias after relizing that I always type ls ; clear ; ls every time I wanted to look at my files. So I decided to try and make my life easier by changing the default ls command to run clear before loading the files. The -F flag adds symbols to tell me what each type of file is and -G flag adds color.

```
alias sty="stylus -w styles.styl -o styles.css"
alias scs="sass --watch sass/styles.scss:css/styles.css"
```
I get tired of typing these watch commands for my styling in early dev stages before I've gotten around to setting up my gulp/grunt/webpack/whatever. This works for the place I normally have the files.

```
alias nlg="npm list -g --depth=0 2>/dev/null"
alias nll="npm list --depth=0 2>/dev/null"
```
Quick alias set up to show me what npm modules I have installed on a global or local level. Only shows top-level (not all the extra modules installed as dependencies).