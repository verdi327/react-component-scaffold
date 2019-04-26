# Usage
`node generate componentName /subfolder -f`

Where
componentName is required
Subfolder is optional and will nest under your /src folder
-f is a flag as to whether you want a stateful or stateless component

# Examples
`node generate FooBar` 
Create a class component FooBar inside of /src folder

`node generate FooBar /Components`
Creates a class component FooBar inside of /src/Components

`node generate FooBar -f`
Create a stateless component FooBar inside of /src
