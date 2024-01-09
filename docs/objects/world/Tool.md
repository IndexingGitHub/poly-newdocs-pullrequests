---
title: Tool
description: Tools are objects that can be held by players.

icon: polytoria/Tool
weight: 7
---

# Tool

:polytoria-Tool: Tools are objects that can be held by players.

{{ inherits("Instance") }}

## Events

### Activated { event }

Fires when the user clicks while holding the tool.

### Deactivated { event }

Gets fired when the user lets go of the mouse button while holding the tool.

### Equipped { event }

Fired when the tool is equipped.

### Unequipped { event }

Fired when the tool is unequipped.

**Example**

```lua
tool.Activated:Connect(function()
    print("Tool has been activated!")
end)
```

## Methods

### Play(animationName;string) { method }

Plays an animation on the tool or the player that is currently holding the tool.

<div data-search-exclude markdown>
!!! tip "You can use the following emotes on these tools: `slash`, `eat`, and `drink`."
</div>

## Properties

### Droppable:bool { property }

Determines whether the tool can be dropped by the player or not.
