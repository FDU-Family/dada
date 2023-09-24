# Data Picker 组件

Data Picker 组件用于选择日期。

## Props

| 属性名         | 类型                                          | 默认值      | 描述                                       |
|----------------|-----------------------------------------------|-------------|--------------------------------------------|
| placeholder    | `string`                                      | `''`        | 占位文本，在输入为空时显示。               |
| width          | `string \| number`                           | `600`       | 日期选择器的宽度（以像素或其他 CSS 单位表示）。 |
| shadow         | `boolean`                                     | `false`     | 是否带有阴影。                             |
| border         | `boolean`                                     | `false`     | 是否带有边框。                             |
| size           | `'small' \| 'medium' \| 'large'`             | `'medium'`  | 日期选择器按钮的尺寸。                    |
| type           | `'default' \| 'primary'`                     | `'default'` | 日期选择器按钮的类型。                    |
| start          | `dateRule`                                    | `'2023-01-01'` | 日期选择的起始日期限制。                 |
| end            | `dateRule`                                    | `'2023-12-31'` | 日期选择的结束日期限制。                 |
| fields         | `'year' \| 'month' \| 'day'`                 | `'day'`     | 在日期选择器中显示的字段（'year'、'month'、'day'）。 |
| value          | `string`                                      | -           | 选定的日期值（字符串格式）。               |
| label          | `string`                                      | -           | 日期选择器的标签。                        |

## Events

| 事件名            | 参数类型                        | 描述                           |
|-------------------|---------------------------------|--------------------------------|
| update:value      | `string`                        | 选定的日期值发生变化时触发。     |

## 插槽

组件提供以下插槽：

- `prefix` 插槽：在日期选择器区域的前缀位置插入内容。