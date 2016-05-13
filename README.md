# Blueprints for Offshore Hook

Implements support for Blueprints for Offshore ORM in Sails

##Install

Install this hook with:

```sh
$ npm install sails-hook-blueprints-offshore --save
```

## Configuration

You should disable original blueprints sails hook.

`.sailsrc`
```
{
  "hooks": {
    "blueprints": false
  }
}
```

## Requirements

This hook require [orm-offshore](https://github.com/Atlantis-Software/sails-hook-orm-offshore) hook.
