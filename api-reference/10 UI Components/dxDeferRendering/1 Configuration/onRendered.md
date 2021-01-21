---
id: dxDeferRendering.Options.onRendered
type: function(e)
default: null
---
---
##### shortDescription
A function that is executed when the content is rendered but not yet displayed.

##### param(e): Object
Information about the event.

##### field(e.component): {WidgetName}
The UI component's instance.

##### field(e.element): dxElement
#include common-ref-elementparam with { element: "UI component" }

##### field(e.model): Object
Model data. Available only if Knockout is used.

---