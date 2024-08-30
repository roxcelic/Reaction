# Hey,
If youve been keeping up with this project youll know it was originally in my `general python` repo<br>
after doing a ton of improvments to this i decided it deserved its own repository, it currectly creates its own files in `~/Documents/funny/` it will make a config file is one already doesnt exist, you can edit the `display.IMAGE_URLS` as the static images that display for longer and you can edit `reaction.REACTION_URLS` for the gifs or images that appear occasionally.<br>
windows my call the software malwear, personally ive had it call it a sever fishing scam so you can download the `index.py` and `favicon.ico` file and run the following command to build it yourself:

```bat
python -m PyInstaller --onefile --noconsole --icon="favicon.ico" --distpath ..\dist --workpath ..\build index.py
```

or download it from [files.roxcelic.love/funny/funny.exe](https://files.roxcelic.love/funny/funny.exe)
there will be the most recent release in the github repo too