视频自动下载合并脚本


分两部分

下载m3u8
https://cloud.tencent.com/developer/article/1585735
https://segmentfault.com/a/1190000025182822

ffmpeg合并成mp4
https://www.npmjs.com/package/@ffmpeg/ffmpeg
<script src="https://unpkg.com/@ffmpeg/ffmpeg@0.10.0/dist/ffmpeg.min.js"></script>
const ffmpeg = createFFmpeg({
  corePath: 'https://unpkg.com/@ffmpeg/core@0.10.0/dist/ffmpeg-core.js',
});
var jq = document.createElement('script');
jq.src = "https://cdn.staticfile.org/jquery/3.4.1/jquery.min.js";
document.getElementsByTagName('head')[0].appendChild(jq);
远程引用成功后需要提示