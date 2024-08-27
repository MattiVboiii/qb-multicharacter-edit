# qb-multicharacter
Multi Character Feature for QB-Core Framework :people_holding_hands:

## Preview
(It's translated to Dutch, because I have a Dutch server)
![image](https://cdn.discordapp.com/attachments/1277731701476561027/1277731702541647953/image.png?ex=66cee4a0&is=66cd9320&hm=3ccb3421380fbf9c23e85e25210e6b0d56c90a6b92befa32fd9ac8800866fdaf&)
![image](https://cdn.discordapp.com/attachments/1277731701476561027/1277731703204614215/image.png?ex=66cee4a1&is=66cd9321&hm=465b44d7c3884a4e8648ba6c12a68b4f5650559b41a615112cbae17e76448e0b&)

## Changes/Edits
### 27-08-2024
- Added color changes
- Added borders around names
- Added hover effects for names
- Made the scrollbar smaller
- Fixed width & height

## Future Plans
- Align the headers more horizontally
- Make some font changes?

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>


## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-spawn](https://github.com/qbcore-framework/qb-spawn) - Spawn selector
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) - For giving the player a apartment after creating a character.
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) - For the character creation and saving outfits.
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) - For adjusting the weather while player is creating a character.

## Features
- Ability to create up to 5 characters and delete any character.
- Ability to see character information during selection.

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure qb-multicharacter
ensure qb-spawn
ensure qb-apartments
ensure qb-clothing
ensure qb-weathersync
```
