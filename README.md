# Flexboite

Code pour montrer comment, en css avec flexbox, on fait une liste dont les élements prennent toute la place du parent, de façon uniforme

![capture d'écran](./capture.png?raw=true)

La propriété importante est :
```css
align-items: stretch;
```

 Elle permet d'étendre les enfants sur toute la place disponible.

- Si les enfants on tous un `flex: 1`, alors ils prendronts la même place.
- Si un des enfants à un `flex: 2`, alors il prendra le double de place.