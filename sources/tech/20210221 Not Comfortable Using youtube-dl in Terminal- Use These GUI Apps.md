[#]: collector: (lujun9972)
[#]: translator: (hongsofwing)
[#]: reviewer: ( )
[#]: publisher: ( )
[#]: url: ( )
[#]: subject: (Not Comfortable Using youtube-dl in Terminal? Use These GUI Apps)
[#]: via: (https://itsfoss.com/youtube-dl-gui-apps/)
[#]: author: (Ankush Das https://itsfoss.com/author/ankush/)

在终端中使用youtube-dl不舒服？试一下这些GUI应用
=========================================

如果你一直关注我们，你可能知道这个问题已经解决[youtube-dl project was taken down temporarily by GitHub][1]
考虑到它已经恢复和可以完全访问，可以肯定地说这不是一个非法的工具。
它是一个非常实用的命令行工具，让你能从YouTube下载视频与其他一些网站[download videos from YouTube][2]，虽然使用youtube-dl并不是很复杂，[Using youtube-dl][3]但是我能理解这并不是每一个人喜欢的方式。
好在有一些工具为youtube-dl提供了前端GUI界面

### 使用youtube dl GUI应用程序的前提条件


在你尝试下面提到的选项之前，你应该在你的系统上安装好youtube-dl确保能够下载/选择不同的格式下载
你可以依照我们的步骤设置并且探索更多的信息
安装youtube-dl[youtube-dl][6]，你可以在你的Linux命令终端里输入以下命令：


```
sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
```

首先你需要下载最新版本，你只需要输入以下命令：

```
sudo chmod a+rx /usr/local/bin/youtube-dl
```

你也可以根据[official setup instructions][7]如果你需要其他的方法来安装它
### Youtube-dl GUI 应用程序

Linux上的大多数下载管理器还允许您从YouTube和其他网站下载视频。然而，youtube的dlgui应用程序可能有额外的选项，比如只提取音频或者下载特定分辨率和视频格式的视频。

请注意，下面的列表没有特定的排名顺序。你可以选择适合你要求的。
#### 1\. AllTube下载

![][8]

**关键特征:**

  * Web GUI
  * 开源
  * 自主选项


AllTube是一个开源的web GUI，你可以通过访问<https://alltubedownload.net/>了解。
如果你选择了这个功能，就无需在系统上安装youtube-dl或ffmpeg。它能提供简单的用户界面，你只需要粘贴视频的网站链接，然后选择你喜欢的文件格式下载。你也可以选择在服务器上部署它。
请注意该工具无法提取视频的MP3文件，它只适用于视频。你可以通过它们的网站[GitHub page][9]获取更多资讯。

[AllTube Download Web GUI][10]

#### 2\. youtube-dl GUI界面

![][11]

**关键特征:**

  * 跨平台
  * 显示估计的下载大小
  * 提供音频和视频下载选项



一个有用的跨平台GUI应用程序，使用electron和node.js制作。你可以轻松地下载音频和视频以及选择各种可用文件格式。
你还可以下载部分频道或播放列表，如果你想。估计的下载大小肯定很方便，特别是如果你下载高质量的视频文件。
就像提到的，它适用于Windows和macOS，而且，你将获得适用于Linux系统的应用程序[GitHub releases][12]。
[Youtube-dl GUI][13]

#### 3\. Videomass

![][14]

**关键特征:**

  * 跨平台
  * 转换音频/视频格式  
  * 支持多个URL
  * 适用于想使用FFmpeg的用户

如果你想从YouTube下载视频或音频，并将它们转换成你喜欢的格式，Videomass是一个不错的选择。为了实现这一点，你的系统需要同时拥有youtube-dl与ffmpeg。你可以轻松添加多个URL进行下载，还可以根据需要设置输出目录。

![][15]

你还可以通过高级设置来禁止youtube-dl，或者更改一些文件选项，还有一些更方便的选项。
它为Ubuntu用户提供PPA，为其他Linux发行版提供AppImage文件。[GitHu][16][b][16] [page][16]获取更多资讯。

[Videomass][17]

####附加说明：Haruna视频播放器

![][18]

**关键特征:**

  *播放/在线播放 Youtube视频


Haruna video播放器最初是 [MPV][19]。即使你无法使用它下载YouTube视频，你也可以通过YouTube dl观看/在线YouTube视频。
你可以在我们的文章[original article][20]了解更多视频播放器。

### 包装

尽管你能通过GitHub和其他平台找到youtube-dl的不同GUI界面，它们大多数显示出来的是不好，或者是出现多个错误，没有更多的开发者维护。

[Tartube][21]是这样一个选项，你可以尝试，但它可能无法按预期工作。我用过Pop!_OS操作系统和Ubuntu MATE 20.04系统（新安装）。每次我尝试下载一些东西时，它都会失败，无论我做什么（即使系统中安装了youtube-dl和ffmpeg）。

因此，我个人最喜欢的似乎是web GUI（[AllTube Download][9]），它不依赖于系统上安装的任何东西，也可以自托管。
在评论中告诉我什么最适合你，如果我错过了你最喜欢的选择。

--------------------------------------------------------------------------------

via: https://itsfoss.com/youtube-dl-gui-apps/

作者：[Ankush Das][a]
选题：[lujun9972][b]
译者：[hongsofwing](https://github.com/hongsofwing)
校对：[hongsofwing](https://github.com/hongsofwing)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://itsfoss.com/author/ankush/
[b]: https://github.com/lujun9972
[1]: https://itsfoss.com/youtube-dl-github-takedown/
[2]: https://itsfoss.com/download-youtube-videos-ubuntu/
[3]: https://itsfoss.com/download-youtube-linux/
[4]: https://ffmpeg.org/
[5]: https://itsfoss.com/ffmpeg/#install
[6]: https://youtube-dl.org/
[7]: https://ytdl-org.github.io/youtube-dl/download.html
[8]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2021/02/alltube-download.jpg?resize=772%2C593&ssl=1
[9]: https://github.com/Rudloff/alltube
[10]: https://alltubedownload.net/
[11]: https://i2.wp.com/itsfoss.com/wp-content/uploads/2021/02/youtube-dl-gui.jpg?resize=800%2C548&ssl=1
[12]: https://github.com/jely2002/youtube-dl-gui/releases/tag/v1.8.7
[13]: https://github.com/jely2002/youtube-dl-gui
[14]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2021/02/videomass.jpg?resize=800%2C537&ssl=1
[15]: https://i0.wp.com/itsfoss.com/wp-content/uploads/2021/02/videomass-1.jpg?resize=800%2C542&ssl=1
[16]: https://github.com/jeanslack/Videomass
[17]: https://jeanslack.github.io/Videomass/
[18]: https://i1.wp.com/itsfoss.com/wp-content/uploads/2021/01/haruna-video-player-dark.jpg?resize=800%2C512&ssl=1
[19]: https://mpv.io/
[20]: https://itsfoss.com/haruna-video-player/
[21]: https://github.com/axcore/tartube
