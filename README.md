# swipe_refresh_layout
a flutter simple swipe refresh layout,container more and load more

# effect
![](https://github.com/Richardpaco-zhang/swipe_refresh_layout/blob/master/effect.gif)

# use
```dart
return new SwipeRefreshLayout(
  onLoad: _handlerRefresh,//Futrue<Null>
  onLoadMore: _handlerRefreshMore,//Futrue<Null>
  child: new ListView(
    children: _notices.map((Notice notice) {
      return new ListTile(
        title: new Text(notice.title),
          subtitle: new Text(notice.content));
      }).toList(),
));
```
