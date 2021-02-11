# React-Swipeable-Cards

![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)

React-swipeable-cards is a flexible react component that lets you build custom interactive cards that can be swipeable.

## Differences between the orignal package

This fork is the same as the original but a swipeSensitivity prop has been added. If not provided the value will be 300. (Decided to do this because the default value was not very mobile friendly)

Original Package: https://github.com/ravelinx22/react-swipeable-cards

## Tips

The moment you want to use this repo as is, or change something else, to be able to import it in your project you gotta build it first. You cannot just *yarn add git+https://github.com/xhuliodo/react-swipeable-cards.git#master* . So first make sure the node version you are using for the build is 8 (for me -v 8.17.0 worked fine) then simply run *yarn run build*. Afterward upload the /es and /lib files in another repo or simple reference it while importing it differently (would suggest the first to keep the package size as small as possible).

My build repo of the latest code: https://github.com/xhuliodo/react-movie-cards-build

## License

MIT ©
