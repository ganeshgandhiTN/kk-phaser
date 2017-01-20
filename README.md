# kk-phaser
phaser custom build for stock-games

Forked from https://github.com/photonstorm/phaser v2.

Instructions for generating custom builds: http://phaser.io/tutorials/creating-custom-phaser-builds

Currently excluded modules: 'gamepad,keyboard,bitmapdata,rendertexture,bitmaptext,retrofont,net,sound,debug,arcade,ninja,p2,tilemaps,particles,creature,video,rope,tilesprite,weapon'

Remember to add --split flag when building as PIXI and Phaser need to come in separate packages. Example build command:

grunt custom --split true --filename phaser --exclude gamepad,keyboard,bitmapdata,rendertexture,bitmaptext,retrofont,net,sound,debug,arcade,ninja,p2,tilemaps,particles,creature,video,rope,tilesprite,weapon