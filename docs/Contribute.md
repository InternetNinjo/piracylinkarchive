


# Contributing Guide

![Contribute Banner](https://small.fileditchstuff.me/s18/aedMqAnpFqqczfvgFoT.png)

### How to Contribute

To ensure quality and consistency, please follow these guidelines closely when submitting your links or updates to the repository.

### Contribution Guidelines

- Only submit links from trusted sources, especially those listed on [fmhy](https://fmhy.net).
- **No NSFW content** is allowed.
- Ensure all submissions are properly formatted.
- Do **not** use link shorteners under any circumstances.
- Always provide the original source of the link.

##### Special note on Empress releases:

> Empress cracks fall into a grey area, and their safety cannot be guaranteed. If another group has already cracked the software, **avoid using** Empress releases.

---

### Step 1: Collecting Links

Start by selecting links from [fmhy](https://fmhy.lol). Be sure to navigate past any captchas and reach the final destination. If multiple file hosts are available, list all of them using a service like [Pastebin](https://pastebin.com).

### Step 2: Cloning the Repository

Clone the repository to your local machine using Git, and open the project in a text editor such as Visual Studio Code (VSCode). The repository link is:

[https://github.com/Piracy-Link-Archive/piracylinkarchive/](https://github.com/Piracy-Link-Archive/piracylinkarchive/)

### Step 3: Formatting Your Submission

Once the markdown file is open in your editor, add your links as a new dropdown menu using the following template:

```
---

## The title of your media
<details>
<summary>NAME</summary>
<pre><a href="THE LINK" target="_blank">Source + Type + Group</a></pre>
</details>
```

- Replace `NAME` with the title of the software/game.
- Replace `THE LINK` with the actual download URL.
- Specify the source (e.g., FitGirl), type (e.g., Repack), and group (e.g., Rune) for proper identification.
- Additional metadata can be added if needed.

##### Adding more links to a dropdown:

To add additional links under the same title, follow this format:

```
<pre><a href="THE LINK" target="_blank">Source + Type + Group</a></pre>
```

For example, if there are two links for a title, it should look like this:

```
## The title of your media
<details>
<summary>NAME</summary>
<pre><a href="THE LINK" target="_blank">Source + Type + Group</a></pre>
<pre><a href="ANOTHER LINK" target="_blank">Source + Type + Group</a></pre>
</details>
```

If the title already exists in the repository, simply add your new links in the same format as shown.

### Step 4: Submitting Your Changes

Once you've made your changes, commit them and push the updates to your branch. Create a pull request on Gitea. After your submission is reviewed and approved, it will be merged into the main repository.

---

### Guidelines for Magnet/Torrent Users

- **Do not use The Pirate Bay**.
- Only use trusted uploaders for game content, such as verified members from cs.rin.ru, Anadius, DODI, FitGirl, JohnCena141 (Linux), KaOsKrew, s7on3r, and TinyRepacks.

When submitting torrent links, always include:
1. A magnet link.
2. A torrent file hosted on a reputable service like [Fileditch](https://fileditch.com). Avoid using cashlink services, malware-infected hosts, or similar unsafe platforms.

