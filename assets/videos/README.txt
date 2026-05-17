《这个神坛不太灵》信息流视频放置说明

路径:
  assets/videos/

当前代码读取的文件名:
  video1.mp4  求上岸神前置视频,用户刷到后下一屏召唤求上岸神
  video2.mp4  不掉头发神前置视频,用户刷到后下一屏召唤不掉头发神
  video3.mp4  通用收尾视频,抽签/分享后点继续刷会来到这里

建议规格:
  竖屏 9:16,推荐 720x1280 或 1080x1920。
  建议 5-15 秒,可以自带 BGM。HTML 会先 muted autoplay 保证视频可自动播放,
  用户首次点击后会放开当前视频声音；进入神页/出签页会暂停视频声音。

未来扩展:
  如果每个场景要有独立的页后视频,建议命名为:
    anside_after.mp4
    toufa_after.mp4
  如果每个场景要有多条前置视频,建议命名为:
    anside_before_01.mp4 / anside_before_02.mp4
    toufa_before_01.mp4 / toufa_before_02.mp4
  扩展后需要在 demo HTML 中新增对应 section 或改 src 映射。
