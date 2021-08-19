# Discord Shitpost

Un modulo de discord que pone videos/imagenes de shitpost

# Para instalar:

```npm install discord-shitpost```

# Uso

``
const Shitpost = require("discord-shitpost"); //Instalar paquete requerido
console.log(Shitpost.imgShitpost()) //retorna imagenes de shitpost
``

# Ejemplo Discord

``js
const Shitpost = require('discord-shitpost');
const Discord = require('discord.js');
const client = new Discord.Client();

client.on('ready', () => {
    console.log('A sus ordenes memero!')
});

client.on('message', (message) => {
    if (message.content == 'shitpost') {
        message.channel.send(Shitpost.imgShitpost())
    }
});

client.login('token');
``

# Metodos 
`Shitpost.imgShitpost` Retorna una imagen de un meme/shitpost

`Shitpost.vidShitpost` Retorna un video de un meme o shitpost

`Shitpost.allShitpost` Retorna un meme random puede ser de imagen o de video
[**Discord server**](https://discord.gg/sRuTH454aB)
