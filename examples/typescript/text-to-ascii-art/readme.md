# text-to-ascii-art

> Converts text to ascii art.

This project provides a hosted, SaaS version of [figlet.js](https://github.com/patorjk/figlet.js) by [patorjk](https://github.com/patorjk).

Note that the majority of the revenue from this hosted API goes back to the open source maintainers behind the original [figlet.js](https://github.com/patorjk/figlet.js) project.

<a href="https://transitive-bullshit_text-to-ascii-art_50c6fcc1.saasify.sh">
  <img
    src="https://badges.saasify.sh"
    height="40"
    alt="Use Hosted API"
  />
</a>

## Examples

Below are some of my favorite fonts. See [fonts.ts](./fonts.ts) for the full list of fonts.

#### Ghost

[/?text=Boo!&font=Ghost](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Boo!&font=Ghost)

```
.-. .-')                            ,---.
\  ( OO )                           |   |
 ;-----.\  .-'),-----.  .-'),-----. |   |
 | .-.  | ( OO'  .-.  '( OO'  .-.  '|   |
 | '-' /_)/   |  | |  |/   |  | |  ||   |
 | .-. `. \_) |  |\|  |\_) |  |\|  ||  .'
 | |  \  |  \ |  | |  |  \ |  | |  |`--'
 | '--'  /   `'  '-'  '   `'  '-'  '.--.
 `------'      `-----'      `-----' '--'
```

#### Big Money-ne

[/?text=Saasify&font=Big%20Money-ne](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Big%20Money-ne)

```
  /$$$$$$                                /$$  /$$$$$$
 /$$__  $$                              |__/ /$$__  $$
| $$  \__/  /$$$$$$   /$$$$$$   /$$$$$$$ /$$| $$  \__//$$   /$$
|  $$$$$$  |____  $$ |____  $$ /$$_____/| $$| $$$$   | $$  | $$
 \____  $$  /$$$$$$$  /$$$$$$$|  $$$$$$ | $$| $$_/   | $$  | $$
 /$$  \ $$ /$$__  $$ /$$__  $$ \____  $$| $$| $$     | $$  | $$
|  $$$$$$/|  $$$$$$$|  $$$$$$$ /$$$$$$$/| $$| $$     |  $$$$$$$
 \______/  \_______/ \_______/|_______/ |__/|__/      \____  $$
                                                      /$$  | $$
                                                     |  $$$$$$/
                                                      \______/
```

#### ANSI Shadow

[/?text=Saasify&font=ANSI%20Shadow](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=ANSI%20Shadow)

```
███████╗ █████╗  █████╗ ███████╗██╗███████╗██╗   ██╗
██╔════╝██╔══██╗██╔══██╗██╔════╝██║██╔════╝╚██╗ ██╔╝
███████╗███████║███████║███████╗██║█████╗   ╚████╔╝
╚════██║██╔══██║██╔══██║╚════██║██║██╔══╝    ╚██╔╝
███████║██║  ██║██║  ██║███████║██║██║        ██║
╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝╚═╝        ╚═╝
```

#### Bloody

[/?text=Saasify&font=Bloody](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Bloody)

```
  ██████  ▄▄▄      ▄▄▄        ██████  ██▓  █████▒▓██   ██▓
▒██    ▒ ▒████▄   ▒████▄    ▒██    ▒ ▓██▒▓██   ▒  ▒██  ██▒
░ ▓██▄   ▒██  ▀█▄ ▒██  ▀█▄  ░ ▓██▄   ▒██▒▒████ ░   ▒██ ██░
  ▒   ██▒░██▄▄▄▄██░██▄▄▄▄██   ▒   ██▒░██░░▓█▒  ░   ░ ▐██▓░
▒██████▒▒ ▓█   ▓██▒▓█   ▓██▒▒██████▒▒░██░░▒█░      ░ ██▒▓░
▒ ▒▓▒ ▒ ░ ▒▒   ▓▒█░▒▒   ▓▒█░▒ ▒▓▒ ▒ ░░▓   ▒ ░       ██▒▒▒
░ ░▒  ░ ░  ▒   ▒▒ ░ ▒   ▒▒ ░░ ░▒  ░ ░ ▒ ░ ░       ▓██ ░▒░
░  ░  ░    ░   ▒    ░   ▒   ░  ░  ░   ▒ ░ ░ ░     ▒ ▒ ░░
      ░        ░  ░     ░  ░      ░   ░           ░ ░
                                                  ░ ░
```

#### Alligator

[/?text=Saasify&font=Alligator](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Alligator)

```
      ::::::::      :::         :::      :::::::: ::::::::::: :::::::::: :::   :::
    :+:    :+:   :+: :+:     :+: :+:   :+:    :+:    :+:     :+:        :+:   :+:
   +:+         +:+   +:+   +:+   +:+  +:+           +:+     +:+         +:+ +:+
  +#++:++#++ +#++:++#++: +#++:++#++: +#++:++#++    +#+     :#::+::#     +#++:
        +#+ +#+     +#+ +#+     +#+        +#+    +#+     +#+           +#+
#+#    #+# #+#     #+# #+#     #+# #+#    #+#    #+#     #+#           #+#
########  ###     ### ###     ###  ######## ########### ###           ###
```

#### Alligator2

[/?text=Saasify&font=Alligator2](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Alligator2)

```
 ::::::::      :::         :::      :::::::: ::::::::::: :::::::::: :::   :::
:+:    :+:   :+: :+:     :+: :+:   :+:    :+:    :+:     :+:        :+:   :+:
+:+         +:+   +:+   +:+   +:+  +:+           +:+     +:+         +:+ +:+
+#++:++#++ +#++:++#++: +#++:++#++: +#++:++#++    +#+     :#::+::#     +#++:
       +#+ +#+     +#+ +#+     +#+        +#+    +#+     +#+           +#+
#+#    #+# #+#     #+# #+#     #+# #+#    #+#    #+#     #+#           #+#
 ########  ###     ### ###     ###  ######## ########### ###           ###
```

#### Banner3-D

[/?text=Saasify&font=Banner3-D](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Banner3-D)

```
:'######:::::'###:::::::'###:::::'######::'####:'########:'##:::'##:
'##... ##:::'## ##:::::'## ##:::'##... ##:. ##:: ##.....::. ##:'##::
 ##:::..:::'##:. ##:::'##:. ##:: ##:::..::: ##:: ##::::::::. ####:::
. ######::'##:::. ##:'##:::. ##:. ######::: ##:: ######:::::. ##::::
:..... ##: #########: #########::..... ##:: ##:: ##...::::::: ##::::
'##::: ##: ##.... ##: ##.... ##:'##::: ##:: ##:: ##:::::::::: ##::::
. ######:: ##:::: ##: ##:::: ##:. ######::'####: ##:::::::::: ##::::
:......:::..:::::..::..:::::..:::......:::....::..:::::::::::..:::::
```

#### Georgia11

[/?text=Saasify&font=Georgia11](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Georgia11)

```
                                      ,,      ,...
 .M"""bgd                             db    .d' ""
,MI    "Y                                   dM`
`MMb.      ,6"Yb.   ,6"Yb.  ,pP"Ybd `7MM   mMMmm`7M'   `MF'
  `YMMNq. 8)   MM  8)   MM  8I   `"   MM    MM    VA   ,V
.     `MM  ,pm9MM   ,pm9MM  `YMMMa.   MM    MM     VA ,V
Mb     dM 8M   MM  8M   MM  L.   I8   MM    MM      VVV
P"Ybmmd"  `Moo9^Yo.`Moo9^Yo.M9mmmP' .JMML..JMML.    ,V
                                                   ,V
                                                OOb"
```

#### Roman

[/?text=Saasify&font=Roman](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Roman)

```
 .oooooo..o                               o8o   .o88o.
d8P'    `Y8                               `"'   888 `"
Y88bo.       .oooo.    .oooo.    .oooo.o oooo  o888oo  oooo    ooo
 `"Y8888o.  `P  )88b  `P  )88b  d88(  "8 `888   888     `88.  .8'
     `"Y88b  .oP"888   .oP"888  `"Y88b.   888   888      `88..8'
oo     .d8P d8(  888  d8(  888  o.  )88b  888   888       `888'
8""88888P'  `Y888""8o `Y888""8o 8""888P' o888o o888o       .8'
                                                       .o..P'
                                                       `Y8P'
```

#### Poison

[/?text=Saasify&font=Poison](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Poison)

```
 @@@@@@    @@@@@@    @@@@@@    @@@@@@   @@@  @@@@@@@@  @@@ @@@
@@@@@@@   @@@@@@@@  @@@@@@@@  @@@@@@@   @@@  @@@@@@@@  @@@ @@@
!@@       @@!  @@@  @@!  @@@  !@@       @@!  @@!       @@! !@@
!@!       !@!  @!@  !@!  @!@  !@!       !@!  !@!       !@! @!!
!!@@!!    @!@!@!@!  @!@!@!@!  !!@@!!    !!@  @!!!:!     !@!@!
 !!@!!!   !!!@!!!!  !!!@!!!!   !!@!!!   !!!  !!!!!:      @!!!
     !:!  !!:  !!!  !!:  !!!       !:!  !!:  !!:         !!:
    !:!   :!:  !:!  :!:  !:!      !:!   :!:  :!:         :!:
:::: ::   ::   :::  ::   :::  :::: ::    ::   ::          ::
:: : :     :   : :   :   : :  :: : :    :     :           :
```

#### Small Poison

[/?text=Saasify&font=Small%20Poison](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Small%20Poison)

```
 @@@@@@  @@@@@@   @@@@@@   @@@@@@ @@@ @@@@@@@@ @@@ @@@
!@@     @@!  @@@ @@!  @@@ !@@     @@! @@!      @@! !@@
 !@@!!  @!@!@!@! @!@!@!@!  !@@!!  !!@ @!!!:!    !@!@!
    !:! !!:  !!! !!:  !!!     !:! !!: !!:        !!:
::.: :   :   : :  :   : : ::.: :  :    :         .:
```

#### Doh

[/?text=Saasify&font=Doh](https://api.saasify.sh/1/call/transitive-bullshit/text-to-ascii-art@50c6fcc1/?text=Saasify&font=Doh)

```
   SSSSSSSSSSSSSSS                                                      iiii     ffffffffffffffff
 SS:::::::::::::::S                                                    i::::i   f::::::::::::::::f
S:::::SSSSSS::::::S                                                     iiii   f::::::::::::::::::f
S:::::S     SSSSSSS                                                            f::::::fffffff:::::f
S:::::S              aaaaaaaaaaaaa    aaaaaaaaaaaaa      ssssssssss   iiiiiii  f:::::f       ffffffyyyyyyy           yyyyyyy
S:::::S              a::::::::::::a   a::::::::::::a   ss::::::::::s  i:::::i  f:::::f              y:::::y         y:::::y
 S::::SSSS           aaaaaaaaa:::::a  aaaaaaaaa:::::ass:::::::::::::s  i::::i f:::::::ffffff         y:::::y       y:::::y
  SS::::::SSSSS               a::::a           a::::as::::::ssss:::::s i::::i f::::::::::::f          y:::::y     y:::::y
    SSS::::::::SS      aaaaaaa:::::a    aaaaaaa:::::a s:::::s  ssssss  i::::i f::::::::::::f           y:::::y   y:::::y
       SSSSSS::::S   aa::::::::::::a  aa::::::::::::a   s::::::s       i::::i f:::::::ffffff            y:::::y y:::::y
            S:::::S a::::aaaa::::::a a::::aaaa::::::a      s::::::s    i::::i  f:::::f                   y:::::y:::::y
            S:::::Sa::::a    a:::::aa::::a    a:::::assssss   s:::::s  i::::i  f:::::f                    y:::::::::y
SSSSSSS     S:::::Sa::::a    a:::::aa::::a    a:::::as:::::ssss::::::si::::::if:::::::f                    y:::::::y
S::::::SSSSSS:::::Sa:::::aaaa::::::aa:::::aaaa::::::as::::::::::::::s i::::::if:::::::f                     y:::::y
S:::::::::::::::SS  a::::::::::aa:::aa::::::::::aa:::as:::::::::::ss  i::::::if:::::::f                    y:::::y
 SSSSSSSSSSSSSSS     aaaaaaaaaa  aaaa aaaaaaaaaa  aaaa sssssssssss    iiiiiiiifffffffff                   y:::::y
                                                                                                         y:::::y
                                                                                                        y:::::y
                                                                                                       y:::::y
                                                                                                      y:::::y
                                                                                                     yyyyyyy
```

## License

This SaaS project was bootstrapped with [Saasify](https://saasify.sh).

MIT © [Saasify](https://saasify.sh)
