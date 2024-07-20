# ZestyTheme <!-- omit in toc -->

A fork with some tweaks and personal customizations.

A minimal and elegant theme for Jellyfin based/inspired by [Ultrachromic](https://github.com/CTalvio/Ultrachromic), [Glassmorphism](https://github.com/alexyle/jellyfin-theme), [Scyfin](https://github.com/loof2736/scyfin) & [JellyTheme](https://github.com/alexyle/jellyfin-theme).

Compatible with 10.9.x!

Notes:

 You must enable Backdrops on *every* device you plan to use this on. For this I use [JellyTweaks](https://github.com/gaam24/JellyTweaks), to force it on every device (use under your own discretion).

 Theme is still **WIP**, and may look broken in some areas.

## Table of content <!-- omit in toc -->

- [Screenshots](#screenshots)
- [Installing](#installing)
- [Color Scheme](#color-scheme)
- [Tweaks](#tweaks)
  - [General](#general)
    - [Hide end time in player](#hide-end-time-in-player)
    - [Hide buttons in player](#hide-buttons-in-player)
    - [Hide playbar markers](#hide-playbar-markers)
    - [Hide replay button](#hide-replay-button)
  - [Desktop](#desktop)
    - [Hide external links (IMDb, TheMovieDb, trakt, etc.)](#hide-external-links-imdb-themoviedb-trakt-etc)
    - [Hide original title](#hide-original-title)
    - [Hide track selection](#hide-track-selection)
    - [Make posters bigger](#make-posters-bigger)
  - [Mobile](#mobile)
    - [Add media info to episodes](#add-media-info-to-episodes)
    - [Hide external links (IMDb, TheMovieDb, trakt, etc.)](#hide-external-links-imdb-themoviedb-trakt-etc-1)
    - [Hide original title](#hide-original-title-1)
    - [Hide SyncPlay button](#hide-syncplay-button)
    - [Hide track selection](#hide-track-selection-1)

---

## Screenshots

<img src="./images/home.jpg" alt="home" width="100%"/>
<img src="./images/Akira.png" alt="movies" width="100%"/>
<img src="./images/TheSimpsons.png" alt="tv-shows" width="100%"/>
<img src="./images/player.png" alt="player" width="100%"/>
<img src="./images/login.jpg" alt="login" width="100%"/>
Mobile:
<img src="./images/phone.jpg" alt="phone" width="100%"/>

---

## Installing

To add the theme to Jellyfin, copy the following line to Dashboard > General > Custom CSS:

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/theme.css');`

---

## Color Scheme

The default color scheme is the following:

<img src="./images/colorschemes/electric-cyan.png" alt="default" width="30%"/>

**If** you'd like to change the default colors to one of the presets below (optional):

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/blue.css');`

<img src="./images/colorschemes/blue.png" alt="blue" width="30%"/>

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/coral.css');`

<img src="./images/colorschemes/coral.png" alt="coral" width="30%"/>

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/gray.css');`

<img src="./images/colorschemes/gray.png" alt="gray" width="30%"/>

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/green.css');`

<img src="./images/colorschemes/green.png" alt="green" width="30%"/>

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/purple.css');`

<img src="./images/colorschemes/purple.png" alt="purple" width="30%"/>

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/red.css');`

<img src="./images/colorschemes/red.png" alt="red" width="30%"/>

`@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/colorschemes/yellow.css');`

<img src="./images/colorschemes/yellow.png" alt="yellow" width="30%"/>

Then enable Backdrops in Jellyfin (Settings > Display > Backdrops) if you haven't already.¹ 

For more info on custom colors [click here](./colorschemes/COLORS.md)

---

## Tweaks

There are a few of tweaks you can add, any of the following are optional:

### General

#### Hide end time in player

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/hideEndTimePlayer.css');
```

| Original  | Modified |
| ------------- | ------------- |
| <img src="./images/tweaks/hideEndTimePlayer/Original.png" alt="Original" width="100%"/>  | <img src="./images/tweaks/hideEndTimePlayer/Modified.png" alt="Modified" width="100%"/>  |

#### Hide buttons in player

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/hideExtraPlayerButtons.css');
```

<img src="./images/tweaks/hideExtraPlayerButtons/Original.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideExtraPlayerButtons/Modified.png" alt="Modified" width="48%"/>

#### Hide playbar markers

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/hidePlaybarMarkers.css');
```

<img src="./images/tweaks/hidePlaybarMarkers/Original.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hidePlaybarMarkers/Modified.png" alt="Modified" width="48%"/>

#### Hide replay button

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/hideReplayButton.css');
```

<img src="./images/tweaks/hideReplayButton/Original.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideReplayButton/Modified.png" alt="Modified" width="48%"/>

---

### Desktop

#### Hide external links (IMDb, TheMovieDb, trakt, etc.)

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/desktop/hideExternalLinks.css');
```

<img src="./images/tweaks/hideExternalLinks/OriginalDesktop.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideExternalLinks/ModifiedDesktop.png" alt="Modified" width="48%"/>

#### Hide original title

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/desktop/hideOriginalTitle.css');
```

<img src="./images/tweaks/hideOriginalTitle/OriginalDesktop.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideOriginalTitle/ModifiedDesktop.png" alt="Modified" width="48%"/>

#### Hide track selection

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/desktop/hideTrackSelection.css');
```

<img src="./images/tweaks/hideTrackSelection/OriginalDesktop.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideTrackSelection/ModifiedDesktop.png" alt="Modified" width="48%"/>

#### Make posters bigger

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/desktop/makePostersBigger.css');
```

---

### Mobile

#### Add media info to episodes

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/mobile/addMediaInfoMobile.css');
```

<center>
<img src="./images/tweaks/addMediaInfoMobile/Original.png" alt="Original" width="48%"/>
<img src="./images/tweaks/addMediaInfoMobile/Modified.png" alt="Modified" width="48%"/>
</center>

#### Hide external links (IMDb, TheMovieDb, trakt, etc.)

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/mobile/hideExternalLinks.css');
```

<center>
<img src="./images/tweaks/hideExternalLinks/OriginalMobile.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideExternalLinks/ModifiedMobile.png" alt="Modified" width="48%"/>
</center>

#### Hide original title

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/mobile/hideOriginalTitle.css');
```

<center>
<img src="./images/tweaks/hideOriginalTitle/OriginalMobile.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideOriginalTitle/ModifiedMobile.png" alt="Modified" width="48%"/>
</center>

#### Hide SyncPlay button

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/mobile/hideSyncMobile.css');
```

<center>
<img src="./images/tweaks/hideSyncMobile/Original.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideSyncMobile/Modified.png" alt="Modified" width="48%"/>
</center>

#### Hide track selection

```css
@import url('https://cdn.jsdelivr.net/gh/J0nan/ZestyTheme@main/tweaks/mobile/hideTrackSelection.css');
```

<center>
<img src="./images/tweaks/hideTrackSelection/OriginalMobile.png" alt="Original" width="48%"/>
<img src="./images/tweaks/hideTrackSelection/ModifiedMobile.png" alt="Modified" width="48%"/>
</center>

---

**Things I'd like to do, if I can figure out how to (HELP WANTED):** 

 Turn seasons into a carousel to prevent this behavior:
 
<img src="./images/caroussel.jpg" alt="season-caroussel" width="65%"/>

 Make it so there is no "overflowing" entries in Genres after I increased Poster size

<img src="./images/genres.jpg" alt="genres" width="65%"/>
