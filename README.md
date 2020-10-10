# open-genshin

Map of the voice packages of the Chinese cross-platform game, Genshin.

## What's this?

This is the configuration file that represents the relations between the voice files (wav) and their respective contents.

## What's the format of the configuration file?

The file is a Microsoft csv file that maps the voice files to their respective content. To list a few:

```csv
External11 00045.wav,我会提炼出甜甜花的花蜜做成糖块，脑袋转不动的时候吃一块就又可以集中精神了。做研究糖分的补充是很重要的。
External11 00047.wav,看来是有一些不该追问的过往呢。
External11 00054.wav,比如去蒙德购物，或者一起再去看看7天神像。
```

The string left to the comma is the name of the file, while the string to the right is its respective content.

## What could be this used for?

Some machine learning software require such a configuration map in order to do recognition, generation or synthesis work.

## Contribute!

**2020.10.10 update:**

1. I have used up my free iFlyTek quota. A large portion of the entire voice repository has been completed, but there are quite a few remaining content. Anyone who used his/her own appID and appSecret, please remove your credentials before committing.
2. I have given up playing the game in just one day because I have discovered a bug inside it that prevents me from continuing my mainthread plot. Details: (zh_CN) <https://t.bilibili.com/444157265461365521>.
3. I LOVE PAIMON while Mihoyo disappoints me.

Because I haven't played the game and of course don't know much about it, I tried the iFlyTek's Neural Network Service to automatically recognize the voice contents, and of course there are super many mistakes.

To add to this file:

1. Clone this repository.
2. Use the given Python script to automatically add content. This script utilizes iFlyTek open platform (This is a modded version of mine from the provided SDK by iFlyTek). Fill your appID as well as your App Secret into the script.
3. When using the script, pay attention to the status. Avoid duplicating items in it!
4. To manually correct the file's content, edit the file via Microsoft Excel. It is very friendly!

To access the audio:

Go to <https://wwa.lanzous.com/b083vered> (Password: 6hxk)

Now the shared content is not complete yet because I have been busy transcripting the remaining audio content. There are totally **31** "External" packages in total and currently transcription of 2 of them have been completed.

I used [this](https://www.bilibili.com/read/cv7735377/) method to extract the audio files.
