# File Converter

## Description
**File Converter** is a very simple tool which allows you to convert and compress one or several file(s) using the context menu of windows explorer.

You can download it here: [www.file-converter.org](http://file-converter.org/?from=readme.md).

## Supported file formats

Category 	| Supported output formats	| Compatible input formats
------------|---------------------------|--------------------------------------------------------------------------------------------
 Audio		| aac, flac, mp3, ogg, wav	| 3gp, aiff, ape, avi, bik, cda, flac, flv, m4a, mkv, mov, mp3, mp4, ogg, wav, wma, webm, wmv
 Video		| avi, mkv					| 3gp, avi, bik, flv, mkv, mov, webm, wmv
 Image		| ico, jpg, png,			| bmp, ico, jpg, jpeg, png, tiff

*Note: If your source file is a video, the conversion to an audio format will extract the audio part of the video.*

*Note 2: The mkv output file format encodes video using H.264 encoder for video and AAC encoder for audio.*

*Note 3: The avi output file format encodes video using Xvid encoder for video and Mp3 encoder for audio.*

## Thanks

File converter uses the following middlewares:

**ffmpeg** as file conversion software.
Thanks to ffmpeg devs for this awesome open source file conversion tool. [Web site link](https://www.ffmpeg.org/)

**SharpShell** to easily create windows context menu extensions.
Thanks to Dave Kerr for his work on SharpShell. [CodePlex link](https://sharpshell.codeplex.com/)

**Ripper** and **yeti.mmedia** for CD Audio extraction.
Thanks to Idael Cardoso for his work on CD Audio ripper. [Code project link](http://www.codeproject.com/Articles/5458/C-Sharp-Ripper)

**Markdown.XAML** for markdown rendering in the wpf application.
Thanks to Bevan Arps for his work on Markdown.XAML. [GitHub link](https://github.com/theunrepentantgeek/Markdown.XAML)

## License

File Converter is licensed under the GPL version 3 License.
For more information check the LICENSE.md file in your installation folder or the [gnu website](http://www.gnu.org/licenses/gpl.html).
