# Scenes and nodes

---

## Nodes

Nodes are the fundamental building blocks for creating a game. A node can perform a variaty of specialized functions. Any given node has the following attributes:

* It has a name.
* It has editable properties.
* It can receive a callback to process every frame.
* It can be extended (to hace more functions).
* It can be added to anoter node as a child.

The las one implies that we can have **trees** of nodes.

## Scene

A scene is a group of nodes organized hierarchically. A scene:\

* Always have a root node.
* Can be saved to disk and loaded back.
* Can be _instanced_.

Running a game is running a scene. A project can contain several scenes. Una must be the main scene. The Godot editor is a scene editor.

