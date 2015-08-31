flex: 1 is the equivalent of height: 100%

alignItems: 'stretch' which is the default and width: 100%.

flexDirection: 'row', the axis is inverted for the two above

```
<View>
  <View style={{flex: 1}} />
  <View style={{flex: 2}} />
</View>
```

The first view is going to take up 1/(1+2) and the second is going to take up 2/(1+2) of the parent

What about... 80% width, centered.

```
<View>
    <View style={{flex: .1}} />
    <View style={{flex: .8}} />
    <View style={{flex: .1}} />
</View>
```
