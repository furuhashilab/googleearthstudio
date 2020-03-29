# Google Earth Studio
Google Earth Studio Know-How

## レンダリング結果を .mp4 ファイルに変換する方法
`% ffmpeg -r 30 -i 接頭辞_%03d.jpeg -vcodec libx264 -pix_fmt yuv420p -r 60 出力動画ファイル名.mp4`

