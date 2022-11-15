# polybar-custom-module

![image](https://user-images.githubusercontent.com/69158247/201956927-788124fb-6f3a-48e8-8448-bef0c01760ec.png)

### polybar custom script for glances

[module/glances]
type = custom/script
click-left = "alacritty -e glances"
exec = echo " "
format = "  Glances"
format-foreground = ${colors.green}
tail = true
