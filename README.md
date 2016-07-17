# react-native-swiper-split

![logo](http://www.moonsite.co.il/images/logo3.png)

The best Swiper component for React Native.
#### With Extras
-----

### Basic Usage

- Install `react-native` first

```bash
$ npm i react-native-swiper-split --save
```

- get more options info from
## [react-native-swiper](https://github.com/leecade/react-native-swiper)


### New Properties

| Prop  | Default  | Type | Description |
| :------------ |:---------------:| :---------------:| :-----|
| decreasePage | false | `bool` | decrease pixels from child swiper. |
| pageSplit | 1 | number | how many splits you will see on same page. |


```jsx
var swiper = React.createClass({
  _onMomentumScrollEnd: function (e, state, context) {
    console.log(state, context.state)
  },
  render: function() {
    return (
      <Swiper style={styles.wrapper}
      decreasePage={20}
      pageSplit={2}>
     ...
      </Swiper>
    )
  }
})
```

## Contribution

- [@Amos](mailto:ami@moonsite.co.il) The main author.
- [@Ziv](mailto:ziv@moonsite.co.il) The secondary contributor.

## Questions

Feel free to [contact me](mailto:ami@moonsite.co.il) or [create an issue](https://github.com/amos80m/react-native-swiper-split/)

> Inspired by [leecade/react-native-swiper](https://github.com/leecade/react-native-swiper).
