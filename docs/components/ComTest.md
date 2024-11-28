---
group:
  title: 测试
  order: 1
---

## 测试

```tsx
/**
 * title: 比例尺
 * description: 比例尺显示位置分别为上、右、下、左。
 */

import { sum } from '@/mf';

import React from 'react';

const App: React.FC = () => {
  const result = sum(1, 4);

  return <div>{result}</div>;
};

export default App;
```

## API

| 参数     | 说明                                           | 类型   | 默认值   | 版本 |
| -------- | ---------------------------------------------- | ------ | -------- | ---- |
| style    | 自定义样式                                     | object | {}       |      |
| position | 比例尺位置，可选 `top` `bottom` `left` `right` | string | `bottom` |      |
| spacing  | 1px 对应毫米数                                 | number | 1        |
