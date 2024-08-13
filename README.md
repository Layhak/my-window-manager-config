<h1>This is the config I use to control my window using key binding and have snap behavior like window for my Mac</h1>
![image](https://github.com/user-attachments/assets/9aa6b66e-8f48-4a57-84b8-47cc544779e4)
<p>You need to use brew to install it first before using this config</p>
Install skhd and start the service:

    brew install koekeishiya/formulae/skhd && skhd --start-service
    
if it's doesn't work:

    skhd --restart-service

<h3>Install Yabai</h3>

    brew install koekeishiya/formulae/yabai && yabai --start-service

if it's doesn't work:

    yabai --start-service


<h1>To make this work you need to create directory:</h1>
- .config/yabai
- .config/skhd
and then copy the config file that have the same name as it parent's.
