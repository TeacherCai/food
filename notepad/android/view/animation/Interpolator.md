# Interpolator


 | java类 | xml资源id | 说明 | 
 | ------ | ------ | ------ | 
 | AccelerateDecelerateInterpolator | @android:anim/accelerate_decelerate_interpolator | 其变化开始和结束速率较慢，中间加速 | 
 | AccelerateInterpolator | @android:anim/accelerate_interpolator | 其变化开始速率较慢，后面加速 | 
 | DecelerateInterpolator | @android:anim/decelerate_interpolator | 其变化开始速率较快，后面减速 | 
 | LinearInterpolator | @android:anim/linear_interpolator | 其变化速率恒定 | 
 | AnticipateInterpolator | @android:anim/anticipate_interpolator | 其变化开始向后甩，然后向前
 | AnticipateOvershootInterpolator | @android:anim/anticipate_overshoot_interpolator | 其变化开始向后甩，然后向前甩，过冲到目标值，最后又回到了终值 | 
 | OvershootInterpolator | @android:anim/overshoot_interpolator | 其变化开始向前甩，过冲到目标值，最后又回到了终值 | 
 | BounceInterpolator | @android:anim/bounce_interpolator | 其变化在结束时反弹 | 
 | CycleInterpolator | @android:anim/cycle_interpolator | 循环播放，其速率为正弦曲线 | 
 | TimeInterpolator |   | 一个接口，可以自定义插值器 | 

