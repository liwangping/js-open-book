perspective: 1000px;得到三维定位的元素一些透视在z = 0平面和用户之间的距离。

居中操作
transform:平移
margin：移动自身宽高一半

transform: rotate(60deg);需要考虑兼容性

 text-indent: 2em; 首行缩进

 querySelectorAll结果以数组显示

 clamp = function(val,min,max){
                        return Math.max(min,Mathd.min(val,max));
                    }
//去一个在最大值和最小值之间的中间值

 var angle = clamp((centerPoint - evt.pageX + pageSize)/pageSize * -90,-180,0)
 记住角度
  shaow.style[prefixes[i] + 'Transform'] = 'translateZ(1px) skewX('+ (angle / 8) + 'deg)';
  skewX