1. I spent a couple of hours doing the test.Should I have more time, following would be added:
Theming/Styling
Paging support on movie list page
Swipe and refresh on movie list page
Add persistent functionalities using Room
Add dependency injection using Dagger 2
Add some anmiations, for example touch effect/activity transition

2. Normally performance issues can be reflected by android studio profilers. I had experience fixing memory leaks such as frequent obejct allocation and unreleased objects. Leakcanary is a good tool to help with this. In addition, overuse of threading can exhaust CPU. I used to optimize CPU usage by using thread pool and tuning thread numbers and priorities.

3. From Android M runtime permission is enabled. The dangerous permission should be requested at runtime and ideally right before the corresponding functionality is used.
