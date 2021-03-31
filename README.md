# Chromacord
This repository is currently archived and will not receive any updates. Because of this, the code will be free to take.

- A stupid "theme" that adds a chroma effect to specific elements. Heavily inspired by [Discord RGB Snippet WIP](https://github.com/Fahrenheit/Discord-RGB-Snippet-WIP) by [Fahrenheight#0001](https://github.com/Fahrenheit).

```css
@keyframes chroma {
    0% {color: red;}
    10% {color: orangered;}
    20% {color: orange;}
    30% {color: yellow;}
    40% {color: yellowgreen;}
    50% {color: turquoise;}
    75% {color: blue;}
    90% {color: rgb(147, 4, 248);}
    100% {color: rgb(255, 0, 55);}
}
@keyframes chroma-border {
    0% {border-color: red;}
    10% {border-color: orangered;}
    20% {border-color: orange;}
    30% {border-color: yellow;}
    40% {border-color: yellowgreen;}
    50% {border-color: turquoise;}
    75% {border-color: blue;}
    90% {border-color: rgb(147, 4, 248);}
    100% {border-color: rgb(255, 0, 55);}
}
@keyframes chroma-background-color {
    0% {background-color: red;}
    10% {background-color: orangered;}
    20% {background-color: orange;}
    30% {background-color: yellow;}
    40% {background-color: yellowgreen;}
    50% {background-color: turquoise;}
    75% {background-color: blue;}
    90% {background-color: rgb(147, 4, 248);}
    100% {background-color: rgb(255, 0, 55);}
}
@keyframes chroma-border-left {
    0% {border-left: 4px solid red;}
    10% {border-left: 4px solid orangered;}
    20% {border-left: 4px solid orange;}
    30% {border-left: 4px solid yellow;}
    40% {border-left: 4px solid yellowgreen;}
    50% {border-left: 4px solid turquoise;}
    75% {border-left: 4px solid blue;}
    90% {border-left: 4px solid rgb(147, 4, 248);}
    100% {border-left: 4px solid rgb(255, 0, 55);}
}
@keyframes chroma-transparent {
    0% {background-color: rgba(255, 0, 0, 0.2);}
    10% {background-color: rgba(255, 68, 0, 0.2);}
    20% {background-color: rgba(255, 166, 0, 0.2);}
    30% {background-color: rgba(255, 255, 0, 0.2);}
    40% {background-color: rgba(170, 255, 0, 0.2);}
    50% {background-color: rgba(0, 255, 229, 0.2);}
    75% {background-color: rgba(0, 0, 255, 0.2);}
    90% {background-color: rgba(149, 0, 255, 0.2);}
    100% {background-color:rgba(255, 0, 55, 0.2);} 
}
@keyframes chroma-border-top {
    0% {border-top: thin solid rgb(255, 0, 0);}
    10% {border-top: thin solid rgb(255, 68, 0);}
    20% {border-top: thin solid rgb(255, 166, 0);}
    30% {border-top: thin solid rgb(255, 255, 0);}
    40% {border-top: thin solid rgb(170, 255, 0);}
    50% {border-top: thin solid rgb(0, 255, 229);}
    75% {border-top: thin solid rgb(0, 0, 255);}
    90% {border-top: thin solid rgb(149, 0, 255);}
    100% {border-top: thin solid rgb(255, 0, 55);} 
}
@keyframes chroma-background {
    0% {background: rgb(255, 0, 0);}
    10% {background: rgb(255, 68, 0);}
    20% {background: rgb(255, 166, 0);}
    30% {background: rgb(255, 255, 0);}
    40% {background: rgb(170, 255, 0);}
    50% {background: rgb(0, 255, 229);}
    75% {background: rgb(0, 0, 255);}
    90% {background: rgb(149, 0, 255);}
    100% {background: rgb(255, 0, 55);} 
}

/* Gradient Border - Hoofer#0001 (github.com/HooferDevelops) */
body {
    padding: 2px;
    animation: chroma-background-color 5s ease-in-out infinite;
}

#app-mount {
    width: calc(100% - 4px); /* wow that was easy */
    height: calc(100% - 4px);
}

.icon-22AiRD, .icon-1DeIlz, .button-14-BFJ, .strikethrough-1n4ekb, .headerTag-2pZJzA, .ownerIcon-2NH9FM, .edited-3sfAzf, .activity-2Gy-9S, .header-2V-4Sw, .button-3AYNKb, .childWrapper-anI2G9, .wrapper-2tAnRe, .colorDefault-2K3EoJ, .wordmarkWindows-1v0lYD, .actionIcon-PgcMM2, .colorHeaderPrimary-26Jzh-, .header-2RyJ0Y { /* hashtag icons, user panel buttons + strikethrough, popout username, and other things that I forgot to name xd */
    animation: chroma 5s ease-in-out infinite;
}
.unread-2lAfLh, .item-2hkk8m, .botTagRegular-2HEhHi, .numberBadge-2s8kKX, .mentioned-xhSam7:before { /* unread notifications - channel, role circle */
    animation: chroma-background-color 5s ease-in-out infinite;
}
.embedFull-2tM8-- {
    animation: chroma-border-left 5s ease-in-out infinite;
}
.mentioned-xhSam7 {
    animation: chroma-transparent 5s ease-in-out infinite;
}
.divider-JfaTT5 {
    animation: chroma-border-top 5s ease-in-out infinite;
}
.iconBadge-qZ4Ksk {
    background-color: rgba(255, 255, 255, 0.2);
}
.headerPlaying-j0WQBV {
    opacity: .5;
    animation: chroma-background 5s ease-in-out infinite;
}
.ephemeral-1PsL1r:before {
    animation: chroma-background-color 5s ease-in-out infinite;
}
```

Credits
-------
- [Hoofer#0001](https://github.com/HooferDevelops) - [Gradient Border](https://github.com/HooferDevelops/GradientBorder).
