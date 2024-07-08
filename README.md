# cs2-advertisement
A plugin for cs2 that allows you to show ads in chat/center/panel

<br>
<p align="center">
<a href="https://www.buymeacoffee.com/thesamefabius"><img src="https://img.buymeacoffee.com/button-api/?text=Support my work&emoji=🐱&slug=thesamefabius&button_colour=febee6&font_colour=000000&font_family=Inter&outline_colour=000000&coffee_colour=FFDD00" /></a>
</p>


# Installation
1. Install [CounterStrike Sharp](https://github.com/roflmuffin/CounterStrikeSharp) and [Metamod:Source](https://www.sourcemm.net/downloads.php/?branch=master)
3. Download [Advertisement](https://github.com/partiusfabaa/cs2-advertisement/releases/tag/v1.0.5)
4. Unzip the archive and upload it to the game server

# Config
The config is created automatically in the same place where the dll is located
```
{
  "PrintToCenterHtml": false,
  "WelcomeMessage": {
    "MessageType": 0,
    "Message": "Welcome, {RED}{PLAYERNAME}",
    "DisplayDelay": 5
  },
  "Ads": [
    {
      "Interval": 35,
      "Messages": [
        {
          "Chat": "IP: {RED}{IP}:{PORT}",// Chat advertising
          "Center": "Server name: {SERVERNAME}" 		// Advertising in the center
        },
        {
          "Chat": "{current_time}"
        },
        {
          "Chat": "{map_name}"
        },
		{
          "Chat": "{LIGHTBLUE}HOSTING {DEFAULT}★ ASTRAL ★ {LIGHTPURPLE}|{DEFAULT} Entre em nosso Discord e fique por dentro de todas as novidades!{LIME} https://discord.gg/sxq69nuQ7T"
        }
      ]
    },
	
	
    {
      "Interval": 40,
      "Messages": [
        {
          "Chat": "{BLUE}HOSTING {DEFAULT}★ ASTRAL ★ {LIGHTPURPLE}|{DEFAULT} Comandos Basicos {LIME}!top{DEFAULT}, {LIME}!rank{DEFAULT}, Skin Players, {LIME}!MD{DEFAULT}, Skin Wepom {LIME}!ws"
        },
        {
          "Chat": "{BLUE}HOSTING {DEFAULT}★ ASTRAL ★ {LIGHTPURPLE}SERVER!",
		"Center": "Bem Vindo ao Servidor do ♪♪ ★ ASTRAL ★♪♪"
        }
      ]
    }
  ],
  "Panel": null,
  "DefaultLang": "US",
  "LanguageMessages": {
    "map_name": {
      "RU": "\u0422\u0435\u043A\u0443\u0449\u0430\u044F \u043A\u0430\u0440\u0442\u0430: {MAP}",
      "US": "Mapa Atual: {MAP}",
      "CN": "{GRAY}\u5F53\u524D\u5730\u56FE: {RED}{MAP}"
    },
    "current_time": {
      "RU": "{GRAY}\u0422\u0435\u043A\u0443\u0449\u0435\u0435 \u0432\u0440\u0435\u043C\u044F: {RED}{TIME}",
      "US": "Hora Atual: {RED}{TIME}",
      "CN": "{GRAY}\u5F53\u524D\u65F6\u95F4: {RED}{TIME}"
    }
  },
  "MapsName": {
    "de_mirage": "Mirage",
    "de_dust": "Dust II"
  }
}{
  "PrintToCenterHtml": false,
  "WelcomeMessage": {
    "MessageType": 0,
    "Message": "Welcome, {RED}{PLAYERNAME}",
    "DisplayDelay": 5
  },
  "Ads": [
    {
      "Interval": 35,
      "Messages": [
        {
          "Chat": "IP: {RED}{IP}:{PORT}",// Chat advertising
          "Center": "Server name: {SERVERNAME}" 		// Advertising in the center
        },
        {
          "Chat": "{current_time}"
        },
        {
          "Chat": "{map_name}"
        },
		{
          "Chat": "{LIGHTBLUE}HOSTING {DEFAULT}★ ASTRAL ★ {LIGHTPURPLE}|{DEFAULT} Entre em nosso Discord e fique por dentro de todas as novidades!{LIME} https://discord.gg/sxq69nuQ7T"
        }
      ]
    },
	
	
    {
      "Interval": 40,
      "Messages": [
        {
          "Chat": "{BLUE}HOSTING {DEFAULT}★ ASTRAL ★ {LIGHTPURPLE}|{DEFAULT} Comandos Basicos {LIME}!top{DEFAULT}, {LIME}!rank{DEFAULT}, Skin Players, {LIME}!MD{DEFAULT}, Skin Wepom {LIME}!ws"
        },
        {
          "Chat": "{BLUE}HOSTING {DEFAULT}★ ASTRAL ★ {LIGHTPURPLE}SERVER!",
		"Center": "Bem Vindo ao Servidor do ♪♪ ★ ASTRAL ★♪♪"
        }
      ]
    }
  ],
  "Panel": null,
  "DefaultLang": "US",
  "LanguageMessages": {
    "map_name": {
      "RU": "\u0422\u0435\u043A\u0443\u0449\u0430\u044F \u043A\u0430\u0440\u0442\u0430: {MAP}",
      "US": "Mapa Atual: {MAP}",
      "CN": "{GRAY}\u5F53\u524D\u5730\u56FE: {RED}{MAP}"
    },
    "current_time": {
      "RU": "{GRAY}\u0422\u0435\u043A\u0443\u0449\u0435\u0435 \u0432\u0440\u0435\u043C\u044F: {RED}{TIME}",
      "US": "Hora Atual: {RED}{TIME}",
      "CN": "{GRAY}\u5F53\u524D\u65F6\u95F4: {RED}{TIME}"
    }
  },
  "MapsName": {
    "de_mirage": "Mirage",
    "de_dust": "Dust II"
  }
}

CHAT COLORS: {DEFAULT}, {RED}, {LIGHTPURPLE}, {GREEN}, {LIME}, {LIGHTGREEN}, {LIGHTRED}, {GRAY}, {LIGHTOLIVE}, {OLIVE}, {LIGHTBLUE}, {BLUE}, {PURPLE}, {GRAYBLUE}
	
PANEL COLORS: <font color='HEXCOLOR'>TEXT</font>
	
TAGS:
	{MAP} 	- current map
	{TIME} 	- server time
	{DATE} 	- current date
	{SERVERNAME} - server name
	{IP} - server ip
	{PORT} - server port
	{PLAYERS} - number of players on the server
	{MAXPLAYERS} - how many slots are available on the server
	\n		- new line
```

# Images
CHAT:
![image](https://github.com/partiusfabaa/cs2-advertisement/assets/96542489/c6b008b4-9b66-4d8a-9cd8-c40505d0f1c3)

CENTER:
![image](https://github.com/partiusfabaa/cs2-advertisement/assets/96542489/5f56cb66-6aac-423a-b7d0-efa066e37da4)

PANEL:
![image](https://github.com/partiusfabaa/cs2-advertisement/assets/96542489/cd1e788f-9e8e-4276-a90c-e08d8adb21f5)

# Commands
`css_advert_reload` - reloads the configuration. The `@css/root` flag is required for use.
