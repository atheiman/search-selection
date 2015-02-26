```javascript
window.addEventListener('contextmenu', function(ev) {
    ev.preventDefault();
    alert('success!');
    return false;
}, false);
```

```javascript
window.addEventListener('click', function(ev) {
    var x = ev.clientX, y = ev.clientY,
    elementMouseIsOver = document.elementFromPoint(x, y);
    elementMouseIsOver.style.backgroundColor = '#222';
    elementMouseIsOver.style.color = '#ddd';
    alert('element: ' + elementMouseIsOver + '\nx: ' + x + '\ny: ' + y);
});
```
