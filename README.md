<p align="center">
  <h1 align="center"># wspider (v1.0)</h1>
  <h3 align="center">Probably one of the fastest crawler <i>you've</i> ever seen</h3>


![1](https://img.shields.io/badge/wspider%20version-v1.0-orange) ![w](https://img.shields.io/badge/wuseman-%40Nr1-ff69b4)[![wakatime](https://wakatime.com/badge/user/7c0c8150-9f8e-402d-a34f-2539fea9f88e/project/8e3282b8-ff0d-4680-a385-7b7cc66954bf.svg)](https://wakatime.com/badge/user/7c0c8150-9f8e-402d-a34f-2539fea9f88e/project/8e3282b8-ff0d-4680-a385-7b7cc66954bf) ![wakatime](https://img.shields.io/github/last-commit/wuseman/wspider?color=purple&label=wspider%20last%20commit&logo=wspider) ![1](https://img.shields.io/github/contributors/wuseman/wspider?color=lightgreen&label=wspider%20contributors) ![1](https://img.shields.io/github/languages/code-size/wuseman/wspider?label=wspider%20size) ![2](https://img.shields.io/github/issues-raw/wuseman/wspider?color=red&label=wspider%20issues&logo=wspider&logoColor=red)

</p>




This is a newer version of former [wmirror](https://github.com/wuseman/wmirror) wich now is archived and I will spend alot more time on wspider and it will be ALOT more powerful, wmirror was using single thread with old wget during download and **wspider** is downloading how many files you want. wspider extremely small and fast and I will do my best for add support for authentications asap so you can crawl sites you've logged in to.

wspider is **EXTREMLY** powerful and fast and is using wget2 and In many cases wget2 downloads much faster than wget1.x due to HTTP2, HTTP compression, parallel connections and use of If-Modified-Since HTTP header.

<p align="center">
<b>Be careful and use wspider on your own risk, maybe its 2fast4u!</b><br><br>
<b>Happy crawling! ; )</b>
</p>

| Version            |  Released      | Description                          |
| :----------------- | :------------- | :---------------------------------- | 
| `1.0`              |  2022-07-02    | Clone/Crawl/Mirror/Spidering any website extremely fast with how many threads you want   | 

* Open previews in fullscreen for a proper view

### wspider (250 threads)

![wspider1](https://user-images.githubusercontent.com/26827453/178808318-e8a671b5-698f-4d40-b965-ed0bb6246953.gif)

### wspider (10 threads)

![wspider_10threads](https://user-images.githubusercontent.com/26827453/178815097-e9760ddf-28f6-4313-a6d3-a98ecf4de938.gif)


### wspider (1 threads)

![wspider_1thread](https://user-images.githubusercontent.com/26827453/178814816-d5ba5fc6-4fcc-4bef-8d35-a4123d3a3857.gif)


### GNU/Parallel (old and slow - using ALOT resources for nothing)

Crawler is from here: https://www.gnu.org/software/parallel/man.html

![gnu-parallel2](https://user-images.githubusercontent.com/26827453/178814053-5ecb5e50-988b-4d78-8058-096b7eabc2d1.gif)

### To Be Fixed

- [ ] Add support for darknet
- [ ] Add support for pastebin similiar sites
- [x] Fix so we can crawl all subdomains
- [ ] Add support for some filetypes only 
- [ ] Add support for socks5 proxy servers from the public


### Get Started On Linux/MacOSX

     git clone https://github.com/wuseman/wspider
     cd wspider
     chmod +x wspider.sh
     ./wpider.sh -u <url> -p <path> -t <threads>

### System requirements

- wget2     - Find more info about _wget2_ [here](https://gitlab.com/gnuwget/wget2)

### Changelog

[Versions changelog](CHANGELOG.md).

## Authors: 

* **wuseman <wuseman@nr1.nu\>** 


### License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

### Notice:

_wuseman cannot be held as responsible for users actions regardless of what damage a user can achieve with the information/data wmirror might collect for any user(s). All users that  gathering information or data via wmirror is 100% responsible for their own actions, wmirror has been developed for a legal purpose._
