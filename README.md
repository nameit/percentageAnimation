# percentageAnimation

## 说明
一个简单的用canvas画的可自定义颜色和起止位置的动画百分比

## 配置
| 参数        | 默认值   |  说明  |
| --------   | -----:  | ----:  |
| baseColor     | #e1e1e1 |   底部圆颜色     |
| coverColor        |   #45050   |   动画圆颜色   |
| lineWidth        |    6    |  圆宽  |
| percentage        |    0.8    |  百分比  |
| roundStartDegree        |    0    |  底部圆结束度数  |
| roundEndDegree        |    360    |  底部圆结束度数  |
| coverStartDegree        |    0    |  动画圆开始度数  |
| radius        |    80    |  半径  |
| speed        |    10    |  动画速度  |
| shape        |    round    |  动画圆边角形状  |
| subtitle        |    分    |  辅助文字  |
| numberFont        |    60px Microsoft YaHei    |  数字字体  |
| subFont        |    18px PT Sans    |  辅助字体  |

## 依赖  
jQuery

## 调用
例如：$('.aaa').percentageAnimation({  
  speed: 20  
});