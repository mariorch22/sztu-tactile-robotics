# Lab 4 slides · 一枚传感器，两个世界

[中文幻灯片](index.html) · [English slides](index.en.html) · [Lab 4](../README.md)

## 使用方法

下载后用 Chrome、Edge 或 Firefox 打开 HTML。图形、数据、回放动画与讲稿均已内嵌，
离线即可演示；外部参考资料链接需要联网。中英文 HTML 放在同一目录即可切换语言。

| 操作 | 快捷键 |
| --- | --- |
| 展开下一步 / 下一页 | →、空格、PageDown |
| 上一步 / 上一页 | ←、PageUp |
| 第一页 / 最后一页 | Home / End |
| 目录 / 当前页讲稿 | O / N |
| 全屏 | F |
| 关闭目录、讲稿或帮助 | Esc |

手机或触摸屏支持左右滑动。按 N 显示的讲稿会出现在当前投影画面上。

中文为 17 页、约 20 分钟的课堂导入；英文扩展版为 26 页、约 30 分钟，
包含 MLP、梯度下降、encoder/decoder、latent space 和跨模态转换。
英文第 10 页可调整神经元输入，第 15 页可调整曲线，第 21 页可切换训练与推理。

需要静态 PDF 时，使用浏览器打印的“保存为 PDF”，打开背景图形并关闭页眉页脚。
打印样式会展开全部页面与图示；交互演示使用 HTML。

## English

Open either HTML file in a browser. Each deck includes its graphics, replay animation,
data, navigation and speaker notes. Use arrow keys or Space to advance, O for the
overview, N for notes on the same display, and F for fullscreen. Keep both HTML files
together for language switching. For a shorter English introduction, skip slides
4, 10, 15, 19 and 22.

Browser printing expands every slide and reveal. Enable background graphics and
disable headers and footers when saving a PDF.

## Data and model context

The slides focus on sensor ID3 at the index fingertip. The opening animation shows
simulation renderings with measured readings on the left and synthetic readings on
the right. Slide 3 uses the supplied PAXINI left-hand meshes in a neutral zero-joint
pose to locate ID3; it is a model illustration, not a hardware photograph.

The data contains five measured records (365 tactile packets) and 300 synthetic
sequences (21,900 paired time steps). Toy neuron and curve controls are conceptual
illustrations. Fitting animations interpolate to the final prediction rather than
showing individual training epochs. Reference errors describe these held-out records;
they do not establish generalization to arbitrary materials or hand poses.

See the [reference results](../datasets/README.md), [metrics](../reference_metrics.json),
and [data and model provenance](../replay_assets/README.md).
