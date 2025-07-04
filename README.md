![banner](Assets/Diami-Banner.png)
# Diami bot [![Discord](https://img.shields.io/badge/El%20Diagrama-blue?style=flat&link=https://discord.com/invite/3x8uMdpeHR)](https://discord.com/invite/3x8uMdpeHR)

![Status](https://img.shields.io/badge/Status-En%20progreso-blue)
![Version](https://img.shields.io/badge/Curren_version-0.5.2-blue)
![discord.js](https://img.shields.io/github/package-json/dependency-version/KevinNovak/Discord-Bot-TypeScript-Template/discord.js)
![License](https://img.shields.io/github/license/Xardax88/Diami-bot)<!-- ![License](https://img.shields.io/badge/licence-MIT-green) -->
![Last Commit](https://img.shields.io/github/last-commit/Xardax88/Diami-bot)
[![Discord Server](https://discordapp.com/api/guilds/774727090188320808/embed.png)](https://discord.com/invite/3x8uMdpeHR)
  
Diami es un bot para Discord v14 creado para El Diagrama, escrito en [TypeScript](https://www.typescriptlang.org/) y [discord.js](https://discord.js.org).</br>
Este Bot es la nueva version del anterior bot conocido como Adonalsium. 


## 🔗 Tecnologías

- ``Node v20.5.0``
- ``Discord.js v14.12.1``
- ``TypeScript v4.7.4``
- ``Mongoose v8.2.4``
- ``Gemini V1.0 (Google Bard)``
- ``Docker``
- ``Fedora Server 39``
- ``Railway``


## 📝 Notas

Esta ves el core completo del bot fue reescrito y adaptado a los nuevos cambios de la api de Discord y las actualizaciones por parte de MongoDB.</br>
Este proyecto comenzó junto con el server de [El Diagrama](https://discord.com/invite/3x8uMdpeHR) y es algo que me entretiene y apasiona.</br>
Asi que solo sera cuestión de seguir
programando y mejorando las funciones de este Bot para Discord.

## 📦 Requerimientos

- Node.js v20 or higher
- Git
- MongoDB

  <br/>

## 🚀 Getting Started

El proyecto utiliza npm para ejecutar

 - Para entorno de producción...
    ~~~sh
    npm install
    npm run start
    ~~~

- Para entorno de producción en Railway...
    ~~~sh
    npm install
    npm run start:railway
    ~~~

- Para entorno de desarrollo...
    ~~~sh
    npm install
    npm run start:dev
    ~~~

> [!NOTE]
> Recuerda crear las variables de entorno:
>
>    ~~~
>    DISCORD_TOKEN=""
>    DISCORD_TOKEN_DEV=""
>    PREFIX=""
>    #
>    CLIENT_ID=""
>    CLIENT_ID_DEV=""
>    #
>    GUILD_ID=""
>    GUILD_ID_DEV=""
>    #
>    MONGO_URL=""
>    MONGO_USER=""
>    MONGO_PASSWORD=""
>    MONGO_DB=""
>    MONGO_DB_DEV=""
>    #
>    GEMINI_API_KEY=""
>    ~~~

## 📦 Requisitos

- Node.js v20 or higher
- Git
- MongoDB

## 📈 Rendimiento

El cambio del core del Diami logro una mejora circunstancial en el consumo de recurso del bot.

![Ado](/Assets/Readme/Captura%20de%20pantalla%202024-04-15%20220741.png)
![Diami](/Assets/Readme/Captura%20de%20pantalla%202024-04-15%20220915.png)


## ✨ TODO

Lista de la implementaciones del bot y su estado

- [x] Comandos Slash
- [ ] Comandos de texto customs
- [x] Menu Contextual
- [x] Logger
- [x] Custom Welcome Message
- [ ] Dashboard
- [x] Animated Avatar
- [ ] Music
- [x] Sistema de Level
    - [x] Experiencia por mensaje
    - [x] Experience por voz
    - [x] Leaderboard
    - [x] Rank
    - [x] Level up
- [ ] Sistema de Economía
    - [x] Economía Básica
        - [x] Balance
        - [x] Extraction
        - [x] Deposito
        - [x] Daily
        - [x] Entregar
    - [ ] Sistema Empleos
    - [ ] Sistema de Tienda
        - [ ] Budges
        - [ ] Items
    - [ ] Sistema de Inventario
    - [ ] Eventos
- [ ] Sistema de Rol
    - [x] Comando de dados
    - [ ] Hojas de personaje
    - [ ] Sistema de Canal Dedicado
- [ ] Juegos
    - [ ] Gachapón
    - [ ] Auto Hero Combat
    - [ ] Tower Defense ``Aun se esta trabajando en el concepto y la aplicación``
    - [ ] Eventos
- [x] Tarot
- [ ] Mascota Virtual
- [x] Implantación de IA ``(powered by Gemini)``

## 🙏 Agradecimientos

- A todos los miembros fundacionales del [El Diagrama](https://discord.com/invite/3x8uMdpeHR)

## 💾 Autor

- [Xardax](https://github.com/Neodoomed/)
