# 最小值 & 最大值
你可以设定最小值和最大值。
```html
<n-input-number
  v-model="value"
  placeholder="最小值"
  :min="-3"
  :max="5"
/>
<n-input-number
  v-model="value"
  placeholder="最大值"
  :min="-5"
  :max="3"
/>
```
```js
export default {
  data () {
    return {
      value: null
    }
  }
}
```
```css
.n-input-number {
  margin: 0 8px 12px 0
}
```