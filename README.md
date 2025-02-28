## Run project
Clone:

``` git clone --recursive git@github.com:gustavorayo/video-to-cartoon.git ```

```cd  video-to-cartoon```

Install dependencies

```pip install -r requirements.txt```

```python install.py```

Usage:
```
python vid2cartoon.py --input_video <source_video> --style <style_to_apply> --frames <frames_to_translate> --output <output_video_name>
```
styles supported:
- Van-Gogh
- ghibli
- ryo

Example:
```
python vid2cartoon.py --input_video ./dataset/01.mp4 --style ghibli --frames 91 --output test.mp4
```
## Translation examples

