# accurate-bpm

提供音乐的较精确 BPM（精确到累计误差 1 ms 以内）。

Provides a highly accurate BPM for the music (with a cumulative error < 1 ms).

小数 BPM：

- LIL UGLY MANE - Slugs: 122.0224
- ariiol - 缄色症候: 133.03846

变动 BPM：

- Tomasz Niecik - Szubi Dubi (Radio Edit): 110, 140
- MC赵小六 - 弹舌: 146.68871（由后一段计算而来）, 186.69472
  - 弹舌为原采样 Szubi Dubi 速度的 1.335337 倍，而如果是仅拉伸采样，按十二平均律来升高采样频率需要为 2 ^ (5 / 12) = 1.334839854 倍，按五度相生则需要为 4 / 3 = 1.333333 倍，均有细微差异，尚不清楚机制
  - 若是仅拉伸采样而来，需要在提高 5 个调（500 音分）的基础上，再提高 0.645 个音分
