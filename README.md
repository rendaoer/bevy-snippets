# Bevey Engine Snippets

VSCode extension with helpful code snippets for Bevy Engine.

Compared to simple abbreviations, I prefer this kind of snippet prefix that can be seen at a glance, maybe you find a problem with a snippet, you can raise the issue in the GitHub repository, and the problem will be solved quickly. If you are missing your usual snippet, feel free to ask for it!

Available on:

- [**Bevy Engine**](https://bevyengine.org/)
- [**VSCode Marketplace**](https://marketplace.visualstudio.com/items?itemName=rendaoer.bevyengine-snippets)

## Snippets

| Snippet             | Description                                                       |
| ------------------- | ----------------------------------------------------------------- |
| `use bevy prelude`  | Quick import of Bevy Engine's prelude                             |
| `app init`          | Initialize a basic Bevy application                               |
| `app2 init`         | Initialize a Bevy application with 2D setup                       |
| `app3 init`         | Initialize a Bevy application with 3D setup                       |
| `component struct`  | Create a component struct                                         |
| `component enum`    | Create a component enum                                           |
| `state enum`        | Create a state enum                                               |
| `plugin init`       | Initialize a Bevy plugin                                          |
| `mut commands`      | Mutable `Commands` variable declaration                           |
| `res asset`         | `AssetServer` resource declaration                                |
| `res texture atlas` | Mutable `Assets<TextureAtlas>` resource declaration               |
| `res state`         | `State` resource declaration                                      |
| `res nextstate`     | Mutable `NextState` resource declaration                          |
| `query`             | `Query` declaration with component types                          |
| `query only`        | Code snippet for querying read-only components.                   |
| `run instate`       | Code snippet for running a system only in a specific state.       |
| `event reader`      | Code snippet for creating an event reader.                        |
| `event wirte`       | Code snippet for creating an event writer.                        |
| `event handle`      | Code snippet for handling events.                                 |
| `add system`        | Code snippet for adding a system.                                 |
| `add system insert` | Code snippet for adding a system and inserting it into an entity. |
