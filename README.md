<h1 align="center">
<img src="/shimmer.gif?raw=true" alt="Shimmer" /><br />
Shimmer for Android
</h1>


[Shimmer](http://facebook.github.io/shimmer-android) is an Android library that
provides an easy way to add a shimmer effect to any view in your Android app.

It is useful as an unobtrusive loading indicator, and was originally developed for <a href="http://newsroom.fb.com/news/2013/04/introducing-home/">Facebook Home</a>.

Find more examples and usage instructions over at:

[facebook.github.io/shimmer-android](http://facebook.github.io/shimmer-android)

- 一些属性
```kotlin
shimmer_clip_to_children: 是否将闪光效果剪辑给子View，或者不透明地在子View上绘制闪光。
shimmer_colored:          无论您是希望微光仅影响 alpha 还是在子View的顶部绘制颜色。
shimmer_base_color:       如果指定了颜色，则为内容的基色。
shimmer_highlight_color:  如果指定了彩色，则为微光的高光颜色。
shimmer_base_alpha:       如果未指定颜色，则用于渲染基本视图的 alpha透明度。
shimmer_highlight_alpha:  如果未指定颜色，则闪烁突出显示的 alpha。
shimmer_auto_start:       是否在显示视图时自动启动动画。
shimmer_duration:         突出显示从布局的一端移动到另一端所需的时间。
shimmer_repeat_count:     当前动画的重复次数。
shimmer_repeat_delay:     延迟，在此之后当前动画将重复。
shimmer_repeat_mode:      动画到达终点后应该做什么，要么从头重新开始，要么向后倒退。
shimmer_direction:        微光高光的行进方向：从左到右、从上到下、从右到左或从下到上。
shimmer_dropoff:          控制高光淡化边缘的大小。
shimmer_intensity:        控制中心高光的亮度
shimmer_shape:            高光遮罩的形状，可以是线性渐变，也可以是圆形渐变。
shimmer_tilt:             高光倾斜的角度，以度为单位
shimmer_fixed_width:      固定大小的高光遮罩（如果设置）会覆盖相对大小值
shimmer_fixed_height
shimmer_width_ratio:      高光遮罩的大小，相对于它所应用的布局。
shimmer_height_ratio
```

## License

BSD License

For Shimmer-android software

Copyright (c) Meta Platforms, Inc. and affiliates. All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

 * Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

 * Neither the name Meta nor the names of its contributors may be used to
   endorse or promote products derived from this software without specific
   prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
