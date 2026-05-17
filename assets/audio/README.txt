《这个神坛不太灵》音频放置说明

路径:
  assets/audio/

当前代码读取的文件名:
  BOY.mp3      求上岸神 BGM,进入上岸神页面后循环播放
  GIRL.mp3     不掉头发神 BGM,进入头发神页面后循环播放
  HJM.mp3      出签瞬间播放,会暂停 BOY/GIRL
  gather.mp3   抽签聚力音效,首次抽签弹幕向内汇聚时播放
  reveal.mp3   签图第一次出现的短音效,与 HJM.mp3 同一时刻播放

格式:
  推荐 mp3。若使用 wav/ogg,需要同步改 demo HTML 里的 audio src。

注意:
  视频本身已经带 BGM,不再需要 video1.mp3/video2.mp3/video3.mp3。
  浏览器通常要求用户先点一次页面后才能播放声音,所以声音会在首次点击后启动。
