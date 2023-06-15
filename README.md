# Bevey Engine Snippets

VSCode extension with helpful code snippets for Bevy Engine.

Compared to simple abbreviations, I prefer this kind of snippet prefix that can be seen at a glance, maybe you find a problem with a snippet, you can raise the issue in the GitHub repository, and the problem will be solved quickly. If you are missing your usual snippet, feel free to ask for it!

Available on:

- [**Bevy Engine**](https://bevyengine.org/)
- [**VSCode Marketplace**](https://marketplace.visualstudio.com/items?itemName=rendaoer.bevyengine-snippets)

## Snippets

### Inits

| Snippet            | Description                                                                                |
| ------------------ | ------------------------------------------------------------------------------------------ |
| `use bevy prelude` | Imports the Bevy Engine's prelude.                                                         |
| `app init`         | Initializes a Bevy application with default plugins and runs it.                           |
| `app2 init`        | Initializes a Bevy application for 2D rendering with default plugins and a startup system. |
| `app3 init`        | Initializes a Bevy application for 3D rendering with default plugins and a startup system. |
| `plugin init`      | Provides a template for initializing a Bevy plugin.                                        |
| `add system`       | Provides a template for adding a system to Bevy.                                           |

### Components

| Snippet            | Description                                                                                    |
| ------------------ | ---------------------------------------------------------------------------------------------- |
| `component struct` | Generates a component struct with the `#[derive(Component)]` attribute.                        |
| `component enum`   | Generates a component enum with the `#[derive(Component)]` attribute.                          |
| `state enum`       | Generates a state enum with various attributes such as `#[derive(States)]`, `#[default]`, etc. |

### Spawns

| Snippet              | Description                                                                                                                                                           |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `spawn node`         | Spawns a node entity with the `NodeBundle` component and sets its style and background color.                                                                         |
| `spawn node flex`    | Spawns a node entity with the `NodeBundle` component, sets its style to flex layout, and sets its size and background color.                                          |
| `spawn button`       | Spawns a button entity with the `ButtonBundle` component, sets its style, and sets its size, layout, and background color.                                            |
| `spawn button image` | Spawns a button entity with an image using the `ButtonBundle` component, sets the image's texture, style, size, layout, and background color.                         |
| `spawn text section` | Spawns a text entity with a specific section using the `TextBundle::from_section` method, sets the section, text style properties such as font, font size, and color. |
| `spawn sprite`       | Spawns a sprite entity using the `SpriteBundle` component, sets the sprite's texture and transform properties such as translation.                                    |

### Params

| Snippet             | Description                                                                                                              |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `mut commands`      | Declares a mutable `Commands` resource.                                                                                  |
| `res`               | Declares a resource of type `Res<T>`, where `T` is the specified type.                                                   |
| `res asset`         | Declares a resource of type `Res<AssetServer>`.                                                                          |
| `res texture atlas` | Declares a mutable resource of type `ResMut<Assets<TextureAtlas>>`.                                                      |
| `res state`         | Declares a resource of type `Res<State<T>>`, where `T` is the specified type.                                            |
| `res nextstate`     | Declares a mutable resource of type `ResMut<NextState<T>>`, where `T` is the specified type.                             |
| `res keycode`       | Declares a resource of type `Res<Input<KeyCode>>` and assigns it to the variable `kb`.                                   |
| `query`             | Declares a query for components of type `T` and `U`, where `T` is the specified type and `U` is the specified component. |
| `query only`        | Declares a query for components of type `T` only, where `T` is the specified type.                                       |

### Events

| Snippet        | Description                                                                                                                                         |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| `event reader` | Declares a mutable `EventReader<T>` where `T` is the specified event type.                                                                          |
| `event wirte`  | Declares a mutable `EventWriter<T>` where `T` is the specified event type.                                                                          |
| `event handle` | Iterates over the specified iterator `1` and assigns each element to the variable `0`. The code block within the loop is executed for each element. |

### Others

| Snippet       | Description                                                                                                                                                                                                                             |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `run instate` | Wraps the system or command in a `run_if` function with the condition `in_state(${0})`, where `${0}` is the specified state. This ensures that the system or command is only executed if the current state matches the specified state. |
