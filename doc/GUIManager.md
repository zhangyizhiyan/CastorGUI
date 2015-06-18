##new [GUIManager](#)(canvas, css)
Creates a new GUIManager

####Parameters
Name | Type | Description
---|---|---
**canvas** | object | The element canvas
**css** | string | The css GUI for all element
---

##Methods

###getElementById(string) → [GUIElement]()
Returns the element corresponding.

###getCanvasOrigine() → void
Returns the origine canvas (x,y)

###getCanvasWidth(string) → void
Returns the size canvas (width, height)

###fadeIn(element) → void
Set fade in element

###fadeOut(element) → void
Set fade out element

###setVisible(bool) → void
Set this GUI all element to visible or invisible

###isVisible(bool, fade) → void
Returns all element if is visible or no

###dispose() → void
Dispose the GUIManager, and delete all elements.