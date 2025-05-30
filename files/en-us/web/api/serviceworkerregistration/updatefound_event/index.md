---
title: "ServiceWorkerRegistration: updatefound event"
short-title: updatefound
slug: Web/API/ServiceWorkerRegistration/updatefound_event
page-type: web-api-event
browser-compat: api.ServiceWorkerRegistration.updatefound_event
---

{{APIRef("Service Workers API")}}{{SecureContext_Header}} {{AvailableInWorkers}}

The **`updatefound`** event of the
{{domxref("ServiceWorkerRegistration")}} interface is fired any time the {{domxref("ServiceWorkerRegistration.installing")}} property acquires a new service worker.

## Syntax

Use the event name in methods like {{domxref("EventTarget.addEventListener", "addEventListener()")}}, or set an event handler property.

```js-nolint
addEventListener("updatefound", (event) => { })

onupdatefound = (event) => { }
```

## Event type

A generic {{domxref("Event")}}.

## Examples

```js
const registration = await navigator.serviceWorker.getRegistration();
if (registration) {
  registration.addEventListener("updatefound", () => {
    console.log("Service Worker update found!");
  });
}
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- [Using Service Workers](/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
