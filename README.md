# About
* What is this repo?
> This is a slightly modified fork which includes some extra features & memes added to my liking.
* How's this different from the main repo?
> * Since the `list` module in the main repo doesn't have recursive search support, I integrated **SearchX-bot**'s search module into this. You can now search for files/folders in more than one drive.  
> **Note**: I did **not** integrate the main repo's **Shortener** feature to the search module, since I personally don't like shortened links in my search results.  

>* Apart from the search module, I also integrated my RSS feed parser module, **rss-chan**. You'll never be late to your mirroring schedules now. You can read more about it [here](https://github.com/hyPnOtICDo0g/rss-chan).

* What're those extra features?
> * I've made some improvements to the search module, such as:  
>   * Search filter to display (only) folders/files. It can be used by appending `-f` at the end of a search query.  
>   * Time taken to fetch the results
>   * Number of results found
>  * Added support to the `/mirror` command to automatically fetch & download an URL when replied to a certain message. Magnet, Torrent, Mega & Direct links are supported.

> Format:
```
/find file_name -f
```
>Example:
```
/find Screenshot -f
```
>The above example displays all the file(s) with the name **Screenshot**. Folders have been set as the default filter, meaning without the `-f` flag only the folder names matching the search query are displayed in search results.

# How to deploy?

* Fork, clone & navigate to your repository's directory.
* Open `drive_folder` using your desired text editor & add the drive names & drive IDs separated by a space to the cloned folder.
* If your drive name includes a **space**, replace it with an **underscore** as shown in the format below.

Format:

```
drive_name drive_id
```

Example:

```
sample_drive 0ASbFU2s497sDUk1PVA
```
* Visit the repo(s) below for further instructions.

# Credits

Projects used in the making:

* [rss-chan](https://github.com/hyPnOtICDo0g/rss-chan)
* [slam-mirrorbot](https://github.com/Slam-Team/slam-mirrorbot)
* [SearchX-bot](https://github.com/SVR666/SearchX-bot)

BTW, here's a cute picture of [Hishiro](https://i.imgur.com/QPkgVg6.png).
