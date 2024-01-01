---
icon: polytoria/SpotLight
---

# SpotLight

PointLight is a source of light emitting in a specific direction and angle that can be placed in the world.

{{ inherits("DynamicInstance") }}

## Properties

### Angle:int { property }

Specifies the angle of the spotlight.

### Brightness:int { property }

Specifies how bright/intense the light is.

<div data-search-exclude markdown>
!!! note "Brightness should ideally be between 0-1"
</div>

### Color:Color { property }

Specifies the color of the light.

### Range:int { property }

Specifies how far out the light can reach.

### Shadows:bool { property }

Specifies whether this light emits shadows or not.

<div data-search-exclude markdown>
!!! note "Having many lights with shadows enabled will cause a massive hit in performance. Consider minimzing the amount of lights with shadows to ensure every player is enjoying your game with minimal framerate issues."
</div>
