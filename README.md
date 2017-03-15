# App主界面Tab实现方法：ViewPager+FragmentPagerAdapter实现Tab (界面可以滑动)

```java
/**
 * App主界面Tab实现方法：ViewPager+FragmentPagerAdapter实现Tab (界面可以滑动)
 *
 * 推荐使用此方法
 *
 * 注意：这里使用v4包
 */
```

```java
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical" >

    <include layout="@layout/top" />

    <android.support.v4.view.ViewPager
        android:id="@+id/id_viewpager"
        android:layout_width="fill_parent"
        android:layout_height="0dp"
        android:layout_weight="1" />

    <include layout="@layout/bottom" />

</LinearLayout>
```

![](https://github.com/ykmeory/APP_MainInterface_Tab03/blob/master/img.jpg "screenshot")
