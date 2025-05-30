---
title: SVGGraphicsElement
slug: Web/API/SVGGraphicsElement
page-type: web-api-interface
browser-compat: api.SVGGraphicsElement
---

{{APIRef("SVG")}}

The **`SVGGraphicsElement`** interface represents SVG elements whose primary purpose is to directly render graphics into a group.

{{InheritanceDiagram}}

## Instance properties

_This interface also inherits properties from its parent, {{domxref("SVGElement")}}._

- {{domxref("SVGGraphicsElement.requiredExtensions")}} {{ReadOnlyInline}}
  - : An {{domxref("SVGStringList")}} reflecting the {{SVGAttr("requiredExtensions")}} attribute of the given element.
- {{domxref("SVGGraphicsElement.systemLanguage")}} {{ReadOnlyInline}}
  - : An {{domxref("SVGStringList")}} reflecting the {{SVGAttr("systemLanguage")}} attribute of the given element.
- {{domxref("SVGGraphicsElement.transform")}} {{ReadOnlyInline}}
  - : An {{domxref("SVGAnimatedTransformList")}} reflecting the computed value of the {{cssxref("transform")}} property and its corresponding {{SVGAttr("transform")}} attribute of the given element.

## Instance methods

_This interface also inherits methods from its parent, {{domxref("SVGElement")}}._

- {{domxref("SVGGraphicsElement.getBBox()")}}
  - : Returns a {{domxref("DOMRect")}} representing the computed bounding box of the current element.
- {{domxref("SVGGraphicsElement.getCTM()")}}
  - : Returns a {{domxref("DOMMatrix")}} representing the matrix that transforms the current element's coordinate system to its SVG viewport's coordinate system.
- {{domxref("SVGGraphicsElement.getScreenCTM()")}}
  - : Returns a {{domxref("DOMMatrix")}} representing the matrix that transforms the current element's coordinate system to the coordinate system of the SVG viewport for the SVG document fragment.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
