<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/835857/14581711/ba623018-0436-11e6-8fce-d2ccd4d379c9.gif">
</p>

Fork from js-cookie

默认不再解码 set 和 get 的 key，如
```js
api.set('last%5Fno', 'test')
```
会保持 `last%5no` 而不转为 `last_no`