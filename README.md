# Nuclear Option zipdb

## The why

I have recently been making extensive use of [Battle Staff Tools](https://spatialillusions.com/unitgenerator/) by our own [Spatial Illusions](https://github.com/spatialillusions). After sitting on it for years, I have finally purchased a year's license for the standalone to make it work on my tablet. This includes a fair few additional features, like the ability to load a [zipdb database](https://battlestafftools.com/documentation/zipdb-format/) of equipment. 

The license comes with a copy of the USA TRADOC WEG in the appropriate format. This is of course very useful for many purposes. I use this tool in a fictional context for help planning mission strategies, mainly with the game [Nuclear Option](https://store.steampowered.com/app/2168680/Nuclear_Option/) by [Shockfront Studios](https://linktr.ee/shockfrontstudios), which features a significant amount of fictional equipment whose details tend to be vital to a good course of action. 

Wouldn't it would be real cool if I could quickly look up the details of any of these in-game systems? Doubly so if I could use it as a source of truth for SIDCs assigned to each in-game equipment, many of which do not have real-world counterparts and require stretching 2525E a bit to fit. For example, the VL-49 Tarantula is a tiltwing, but since there's no tiltwing modifier yet due to no tiltwings existing in real life let alone in service with a military, the TR modifier is used instead to portray the same capabilities.

## The what

1. Rough out a JSON schema that describes what a zipdb should look like based on the WEG zipdb made available with a BST standalone license
2. Hand-craft a proof of concept with only a few entries, hope the inode KV pairs aren't important, and get it to load in BST
3. Create simple tooling to convert a bunch of markdown files to zipdb
4. Export all the in-game NO Encyclopedia entries somehow, hopefully not manual transcription but that is in fact an option.
5. Format those entires in the markdown format you made earlier
6. Hope everything comes together and possibly make a sacrifice to the machine spirits
