# discord-theme
my wip theme so far (quickCSS):
```[class*="appAsidePanelWrapper_"],
[class*="notAppAsidePanel_"],
[class*="app_"],
[class*="app__"],
[class*="bg__"][class*="theme-dark"],
[class*="layers__"],
[class*="layer__"],
[class*="container__"],
[class*="base__"],
[class*="bar_"],
[class*="content_"],
[class*="chatContent_"],
[class*="chat_"],
[class*="guilds__"],
[class*="messagesWrapper__"],
[class*="scroller__"],
[class*="scrollerContent__"] {
    background: transparent !important;
    background-color: transparent !important;
    background-image: none !important;
}

#app-mount {
    background-color: transparent !important;
    background-image: url("https://raw.githubusercontent.com/Warp541/discord-theme/main/.wallpaper.jpg") !important;
    background-size: cover !important;
    background-position: center !important;
    background-attachment: fixed !important;
}

[class*="sidebar_"],
[class*="panels_"],
[class*="guilds__"] {
    background-color: hsla(245, 20%, 12%, 0.75) !important;
    backdrop-filter: blur(12px) !important;
    -webkit-backdrop-filter: blur(12px) !important;
}

[class*="chat_"],
[class*="form_"] {
    border-radius: 12px !important;
    overflow: hidden;
}

[class*="channelTextArea"] {
    background-color: hsla(245, 20%, 12%, 0.85) !important;
    backdrop-filter: blur(6px) !important;
    -webkit-backdrop-filter: blur(6px) !important;
    border-radius: 10px !important;
}

:root {
    --brand-500: #7c5cff !important;
    --brand-560: #6b46e0 !important;
}

[class*="layerContainer"] [class*="content_"],
[class*="layerContainer"] [class*="chat_"] {
    background-color: hsla(245, 20%, 12%, 0.9) !important;
    background-image: none !important;
}```
