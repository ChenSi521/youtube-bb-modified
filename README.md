# youtube-bb-modified
<font size=8>I made a little change to this code（https://github.com/mbuckler/youtube-bb）.</font>

Changes:

①If a movie can't be downloaded by youtube-dl, it's 'yt_id' will be stored in './error-youtube_dl-yt_id.txt'.

②If a movie can't be parsed by ffmpeg, it's 'yt_id' will be stored in './error-ffmpeg-yt_id.txt'.

<font size=5>③当下载的过程被中断了，重新启动代码后依然可以接着下载（不会重复下载已经下载过的视频）。</font>

④下载过的视频的'yt_id'被记录在right-yt_id.txt文件夹中。

⑤还可以手动把已经下载过的视频的'yt_id'写入right-yt_id.txt文件中，然后就不会重复下载这些视频了。


Usage：

You only need replace it's 'youtube_bb.py'(https://github.com/mbuckler/youtube-bb/youtube_bb.py) by 'youtube_bb.py' of this repository.

The use-method of original code isn't changed anyway.


