---

layout: bright

style: |

    #Cover h2 {
        width: 40%;
        margin:20px 0 0;
        color:#000;
        text-align:center;
        font-size:70px;
        }
    #Cover p {
        width: 40%;
        margin:10px 0 0;
        text-align:center;
        color:#000;
        font-style:italic;
        font-size:20px;
        }
    .note {
        font-size: 80%;
        color: rgba(102, 102, 102, 0.55)
        }
    iframe {
        position: absolute;
        right: 0;
        bottom: 0;
        }
    .top-right img {
        position: absolute;
        right: 0;
        top: 0;
    }
    .right img {
        position: absolute;
        right: 0;
        bottom: 0;
        }
    .full-width img {
        position: absolute;
        left: 0;
        bottom: 0;
        }
---

# Fast, Free, and Secure Websites {#Cover}

Starring [Jekyll](http://jekyllrb.com/)

![robot](pictures/robot.jpg)
<!-- photo: By D J Shin (Own work) [CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0) or GFDL (http://www.gnu.org/copyleft/fdl.html)], via Wikimedia Commons -->


## Static Site Generators

1. Supports Any Workflow: [StaticGen](https://www.staticgen.com/), [StaticSiteGenerators](https://staticsitegenerators.net/)
1. …HTML, CSS, and JavaScript (see [staticapps](http://www.staticapps.org/))
1. …Secure
1. …Performant
1. …Somewhere between cheap and **FREE**

{:.right .next}
![](http://i.giphy.com/ZYi2Lc03nrryw.gif)


## Serverless/Static Web Apps

But there is a server...<br/>
<span class="next">and the app changes.</span>

{:.next}
![](http://i.giphy.com/Rno6YVT6CzLLq.gif)



## What We Mean

Web applications that don't alter their assets per client (browser). <br/> 
[static web servers](https://en.wikipedia.org/wiki/Static_web_page): 
[Amazon S3](https://aws.amazon.com/s3/), [Github Pages](https://pages.github.com/), 
[DivShot](https://divshot.com/blog/web-development/advanced-jekyll-features/)

{:.full-width}
![servers](pictures/servers.jpg)


## Rise of the Web API

1. [Web APIs](https://en.wikipedia.org/wiki/Web_API) remove technical barriers.
1. …Reduce costs.
1. …Speed development.
1. …[Thousands](http://www.programmableweb.com/apis/directory) of options.

<blockquote class="imgur-embed-pub" lang="en" data-id="azyruE3" data-context="false">
<a href="//imgur.com/azyruE3">View post on imgur.com</a>
</blockquote>
<script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

## Security

1. No database. No problem.
1. …Client security can still be an issue, know your API provider.
1. …Limited to open/public APIs or [tokens](http://www.staticapps.org/articles/authentication-and-authorization)
1. …**Don't share your API key**

{:.right}
![](http://i.giphy.com/MvzUask3j3DvG.gif)


## Performance

1. Things you can control
    - Local code quality
    - Local assets (but you should probably use a [CDN](https://en.wikipedia.org/wiki/Content_delivery_network))
1. …Things you can't always control
    - Web host speed, availability
    - API speed, availability, rate limits
    - CDNs and 3rd-party speed, availability
    
{:.right}    
![](http://i.giphy.com/g80F2NcV1b13G.gif)    


## Why Jekyll

{:.top-right}
![](pictures/jekyll.png)

1. It's open source and **FREE**.
1. …Themes! [here](http://jekyllthemes.org/),
[here](https://github.com/imathis/octopress/wiki/3rd-Party-Octopress-Themes),
or [here](https://mademistakes.com/work/jekyll-themes/)
1. …Github makes it better:
    - …Compiled and hosted, **FREE** (for public repos).
    - …Supports several [plugins](https://pages.github.com/versions/)
    - …Supports custom domains, **FREE**.
    - …Unlimited history/backups.
    - …Work online or offline.

{:.right}
![](http://i.giphy.com/ADgfsbHcS62Jy.gif)


## Jekyll Workflow

1. Fork/clone/fetch it.
1. …Edit it (Github, [Prose.io](http://prose.io/), text editor, IDE).
1. …Commit and push it to `gh-pages` branch.
1. …Profit $$$.

{:.right}
![](http://i.giphy.com/sM4ALgO3D7F8k.gif)

## Jekyll Local Workflow

1. Clone/fetch it.
1. …Check for submodules:
![submodules](pictures/submodule.png)
    - `git submodule init`
    - `git submodule update`
1. …`bundle install` (assumes [Ruby](https://www.ruby-lang.org/en/documentation/installation/), [bundler](http://bundler.io/))
1. …`jekyll serve`


## Examples

1. [This presentation](https://github.com/AutoSponge/jekyller)
1. [List on Github Pages](https://github.com/showcases/github-pages-examples)
1. [Poole](https://github.com/poole/poole)
1. Cutting edge workflow [with Gulp and SASS](https://github.com/sondr3/generator-jekyllized/tree/beta)
1. [hpstr theme](https://mmistakes.github.io/hpstr-jekyll-theme/)
1. [incorporated theme](https://github.com/kippt/jekyll-incorporated)


## Resources

1. [Treehouse Blog](http://blog.teamtreehouse.com/using-github-pages-to-host-your-website)
1. [Read Write Web](http://readwrite.com/2013/11/27/github-pages-explained)
1. [Github Pages](https://pages.github.com/)
1. [Jekyll](http://jekyllrb.com/docs/github-pages/)
1. [Jekyll Bootstrap](http://jekyllbootstrap.com/)
1. [Octopress](http://octopress.org/docs/deploying/github/)
