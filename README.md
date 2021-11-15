

### VideoTest
Use simple MVVM without DI and Coroutine.
Also in this case via timelimit don't use usecase/interactor.
But use the repository directly in ViewModel.
Use ViewPager2 for displaying video.
In the beginning, try to use one player instance with multiple MediaItem(playlist)
and seek to specific MediaItem but it needs more time.
So in the end-use unique player for every ViewHolder.

P.S: Spend 3 and half hours on this project. Unfortunately, can't make it within 2-3 hours. The biggest issue was the SSL certificate error.
# VideoTest
