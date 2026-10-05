# MuseScore Repeat Dynamics

让 MuseScore 在反复段落中，第一次播放用 mf、第二次用 f。

这是官方十多年来一直未实现的功能请求。

## 应用方法

```bash
git clone --recursive https://github.com/musescore/MuseScore.git
cd MuseScore
git apply 0001-Add-repeat-aware-playback-dynamics-playbackCount-sup.patch
