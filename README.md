# Nodelo ⚙

A play on words from Nodelo's cousin, [Modelo](https://github.com/tundradawn/modelo) by @tundradawn.
Intended as a general purpose low-level template to get ES6 running quick and easy.
If you don't need all the bells and whistles, this template might be for you. 

# Contents
#### `babel.rc`
- Targets: `node: 'current'`.

**Plugins:**
- [@babel/plugin-transform-classes](https://babeljs.io/docs/en/babel-plugin-transform-classes)
 - default: `loose:false`
- [@babel/plugin-proposal-class-properties](https://babeljs.io/docs/en/babel-plugin-proposal-class-properties)
 - _default_: `loose:false`
- [@babel/plugin-transform-runtime](https://babeljs.io/docs/en/babel-plugin-transform-runtime)
 - _default_: `corejs: 3`, `regenerator: true`

### Everything from [Modelo](https://github.com/tundradawn/modelo):

##### `.gitignore`
- ignores node elements, common UNIX elements such as `.DS_Store` and more.

##### `.editorconfig`
- ensure spacing and other fine factors of the coding life are consistant acrosses not only IDE's but also OS enviroments.

##### `.eslintrc.js`
- Contains common eslint rules with a small selection of simple ignores to aid in fast building of repos.
- Uses the Airbnb ruleset thanks to the suggestion from @jadnco

##### `.gitattributes`
- Forces all binary and text files to follow consistant line ending rules, as some team members work with Windows and others Mac.

# Base Licence `AGPL-3.0-or-later`
Why did i choose this licence? For this specific line right here:
> When a modified version is used to provide a service over a network, the complete source code of the modified version must be made available.

_Found on [choosealicence.com](https://choosealicense.com/licenses/);_

This seems to be a good all around licence to ensure all parties are getting the same access to Opensource Software software..
