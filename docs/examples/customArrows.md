## Custom arrows
You can set custom arrows, using arrowLeft and arrowRight props. You can handle arrow click event by yourself, or you can tell Carousel to do that for you (using addArrowClickHandler prop).
```jsx render
// import Icon from 'react-fa';
<Carousel
    arrowLeft={<Icon name="angle-double-left" />}
    arrowRight={<Icon name="angle-double-right" />}
    addArrowClickHandler
>
  <img src={imageOne} />
  <img src={imageTwo} />
  <img src={imageThree} />
</Carousel>
```
