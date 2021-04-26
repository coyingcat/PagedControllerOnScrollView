# PagedControllerOnScrollView



### [blog juejin: iOS 嵌套滚动界面实现思路： UIScrollView 上面放 UIPageViewController](https://juejin.cn/post/6955305943668097032)

based on bawn/Aquaman



UIScrollView 能否横着滚动 / 竖着滚动

取决于其 content size.



* 其 content size's width > frame size width, 可以横着滚



* 其 content size's height > frame size height, 可以竖着滚
