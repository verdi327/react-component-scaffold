# Why

Tired of writing so much boilerplate code when you go to create a new React component?

Use `react-component-scaffold` to speed up your development time!

# Usage

react-component-scaffold is a simple command line tool which can be added to your npm scripts.

The command takes 1 required arg and 2 optional args.

`node generate componentName /path/to/subfolder -f`

Where
* componentName is required
* path/to/subfolder is optional nested component within your /src dir
* -f is a flag as to whether you want a stateful or stateless component, it defaults to stateful

# Examples

`node generate FooBar` 

Create a class component FooBar inside of /src folder

`node generate FooBar /Components`

Creates a class component FooBar inside of /src/Components

`node generate FooBar -f`

Create a stateless component FooBar inside of /src
