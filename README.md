# SimpleScroll


## Usage

```javascript
SimpleScroll.scrollTo('#target');
```

## Options
```javascript
SimpleScroll.scrollTo(target, duration, adjust);
```

* **target**: the target element (can be a string like a div id or a instance of HTMLElement)
* **duration**: the scroll animation duration in ms **default 1000ms (1s)**
* **adjust**: adjust the scroll in pixels (ex: subtraction of the navigation bar height to have a perfect scroll) **default 0**

**Full examples**
```javascript
SimpleScroll.scrollTo('#target', 1200, -100);
```
```javascript
SimpleScroll.scrollTo(document.querySelector('#target'), 1200);
```