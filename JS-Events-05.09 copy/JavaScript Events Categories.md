## JS Events კატეგორიების მიხედვით

### Mouse Events

მაუსის მოქმედებებთან დაკავშირებული ივენთები (დაჭერა, გადაადგილება, ჰოვერი). `click`, `dblclick`, `mousedown`, `mouseup`, `mousemove`, `mouseenter`, `mouseleave`, `mouseover`, `mouseout`, `contextmenu`, `auxclick`, `wheel`

### Keyboard Events

კლავიატურაზე ღილაკების დაჭერასთან დაკავშირებული ივენთები. `keydown`, `keyup`, `keypress` (deprecated)

### Form Events

ფორმებთან და input ველებთან დაკავშირებული ივენთები (გაგზავნა, მნიშვნელობის ცვლილება). `submit`, `reset`, `change`, `input`, `invalid`, `select`, `formdata`

### Focus Events

ელემენტზე ფოკუსის მიღება/დაკარგვასთან დაკავშირებული ივენთები. `focus`, `blur`, `focusin`, `focusout`

### Clipboard Events

კოპირება/ამოჭრა/ჩასმის მოქმედებებთან დაკავშირებული ივენთები. `copy`, `cut`, `paste`

### Drag & Drop Events

ელემენტების გადათრევასა და დაგდებასთან დაკავშირებული ივენთები. `dragstart`, `drag`, `dragenter`, `dragover`, `dragleave`, `drop`, `dragend`

### Touch Events

სენსორულ ეკრანზე თითით შეხებასთან დაკავშირებული ივენთები. `touchstart`, `touchmove`, `touchend`, `touchcancel`

### Pointer Events

უნიფიცირებული ივენთები, რომლებიც აერთიანებს მაუსის, თითისა და pen ინფუთს. `pointerdown`, `pointerup`, `pointermove`, `pointerover`, `pointerout`, `pointerenter`, `pointerleave`, `pointercancel`, `gotpointercapture`, `lostpointercapture`

### Media Events (audio/video)

ვიდეო/აუდიო ელემენტების state-ცვლილებებთან დაკავშირებული ივენთები. `play`, `pause`, `ended`, `timeupdate`, `volumechange`, `seeking`, `seeked`, `waiting`, `canplay`, `canplaythrough`, `loadstart`, `loadeddata`, `loadedmetadata`, `stalled`, `suspend`, `ratechange`, `durationchange`, `emptied`, `progress`

### Window/Document Events

გვერდის/ბრაუზერის ფანჯრის state-თან დაკავშირებული გლობალური ივენთები. `load`, `unload`, `beforeunload`, `DOMContentLoaded`, `resize`, `scroll`, `hashchange`, `popstate`, `pagehide`, `pageshow`, `online`, `offline`, `visibilitychange`, `beforeprint`, `afterprint`

### Progress/Network Events (XHR, Fetch-related)

ქსელური მოთხოვნების პროგრესთან და დასრულებასთან დაკავშირებული ივენთები. `loadstart`, `progress`, `load`, `loadend`, `error`, `abort`, `timeout`

### Animation & Transition Events

CSS ანიმაციებისა და ტრანზიციების დაწყება/დასრულებასთან დაკავშირებული ივენთები. `animationstart`, `animationend`, `animationiteration`, `animationcancel`, `transitionstart`, `transitionend`, `transitionrun`, `transitioncancel`

### Storage Events

`localStorage`/`sessionStorage`-ის ცვლილებებთან დაკავშირებული ივენთი. `storage`

### Selection Events

ტექსტის მონიშვნასთან დაკავშირებული ივენთები. `selectstart`, `selectionchange`

### Sensor/Device Events

მოწყობილობის სენსორებთან (ორიენტაცია, მოძრაობა) დაკავშირებული ივენთები. `deviceorientation`, `devicemotion`, `orientationchange`

### Fullscreen Events

სრულეკრანიან რეჟიმში გადასვლასთან დაკავშირებული ივენთები. `fullscreenchange`, `fullscreenerror`

### Gamepad Events

გეიმფედის დაკავშირება/გათიშვასთან დაკავშირებული ივენთები. `gamepadconnected`, `gamepaddisconnected`

### WebSocket Events

WebSocket კავშირის სტატუსთან დაკავშირებული ივენთები. `open`, `message`, `close`, `error`

### Service Worker / PWA Events

Service Worker-ის lifecycle-თან და PWA ფუნქციონალთან დაკავშირებული ივენთები. `install`, `activate`, `fetch`, `message`, `push`, `sync`, `beforeinstallprompt`, `appinstalled`

### Error/Security Events

შეცდომებთან და უსაფრთხოების დარღვევებთან დაკავშირებული ივენთები. `error`, `securitypolicyviolation`, `rejectionhandled`, `unhandledrejection`

### Custom Events

დეველოპერის მიერ განსაზღვრული, `dispatchEvent`-ის მეშვეობით გამოძახებული ივენთები. `CustomEvent`