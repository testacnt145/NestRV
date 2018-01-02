# NestRV

## Material Design

1) [Which Color is where?](https://stackoverflow.com/questions/22192291/how-to-change-the-status-bar-color-in-android)
2) [Colors] (https://material.io/guidelines/style/color.html#color-color-system)
3) [Status bar] (https://material.io/guidelines/layout/structure.html#structure-system-bars)

## Guidelines
1) https://guides.codepath.com/android/Using-the-RecyclerView
2) https://guides.codepath.com/android/Handling-Scrolls-with-CoordinatorLayout
3) https://guides.codepath.com/android/Heterogenous-Layouts-inside-RecyclerView

## Tutorials
#### 1- [CardView](https://www.androidhive.info/2016/05/android-working-with-card-view-and-recycler-view/)
1) Overflow button in cards

#### 2- [RecyclerViewSnap](https://rubensousa.github.io/2016/08/recyclerviewsnap)
1) [Youtube](https://www.youtube.com/watch?v=aWb-PizXU8I)
2) Animation - Ripple Effect

#### 3- [RVMultipleViewItems](https://www.journaldev.com/12372/android-recyclerview-example)
1) 4 types of items, can take help from it

#### 4- [Heterogeneous](https://github.com/delaroy/Heterogeneous)
1) [Youtube](https://www.youtube.com/watch?v=03OWg7TamOo)
2) Clean code - multiple recycler view


#### 5- [PlayStore like View](http://android-pratap.blogspot.in/2015/12/horizontal-recyclerview-in-vertical.html)
1) [Youtube](https://www.youtube.com/watch?v=YAgHynYKmQM)

## Issues
1) [setNestedScrollingEnabled(false)](https://stackoverflow.com/questions/34791752/nested-recyclerview-with-coordinatorlayout)
2) [setRecycledViewPool(RecycledViewPool)](https://medium.com/@mgn524/optimizing-nested-recyclerview-a9b7830a4ba7)


## Databinding
### Why not Databinding?
1) DB is for static data
2) Recycler view multiple items
3) Adding dynamic imageviews in Linear Layout is problem (Solution: use recycler view there)
4) Switch in latest deals
5) animations

### Usecase
We can use it just to bind and avoid findviewbyid
   But it will cause issues (xml -> premium_brand_image) (api -> image)

## Reddit
1) [Is a RecyclerView of RecyclerViews a good idea?](https://www.reddit.com/r/androiddev/comments/7jxlkb/is_a_recyclerview_of_recyclerviews_a_good_idea/)
2) [What is the best way to design layout like Google Play App](https://www.reddit.com/r/androiddev/comments/7588bw/what_is_the_best_way_to_design_layout_like_google/)

## MVP
### Activity
1) Do not define variable
2) Do not define static variable
3) use OnClickBtnA()
4) activity should not call any activity method, presenter should call method

## Dynamic UI
1) Where to place assets?

https://stackoverflow.com/questions/28613118/how-to-make-my-app-look-the-same-in-all-devices
https://developer.android.com/guide/practices/screens_support.html#DeclaringTabletLayouts

````
res/layout/main_activity.xml # For handsets (smaller than 600dp available width)
res/layout-sw600dp/main_activity.xml # For 7” tablets (600dp wide and bigger) 
res/layout-sw720dp/main_activity.xml # For 10” tablets (720dp wide and bigger)
````

https://www.reddit.com/r/androiddev/comments/2zu8za/is_using_dp_for_widthheight_instead_of_wrap/

#### For Designer
https://www.reddit.com/r/graphic_design/comments/1ulhbp/trying_to_wrap_my_brain_around_android_design/


Convert pixel to dp
http://labs.rampinteractive.co.uk/android_dp_px_calculator/

Visual designer question
https://stackoverflow.com/questions/13404377/how-do-i-convert-pt-to-sp

Zain devices dimentions
https://material.io/devices/


## UI Assets
[Main](https://material.io/guidelines/layout/metrics-keylines.html#metrics-keylines-keylines-spacing)
1) [Image Scale Type](https://robots.thoughtbot.com/android-imageview-scaletype-a-visual-guide)
2) **Toolbar Icon** [Location](https://material.io/icons) | [Size](https://www.creativefreedom.co.uk/icon-designers-blog/android-4-1-icon-size-guide-made-simple/)
3) **Navigation View Icon**
4) 
