---
title: Introduce to Linux And Termux (shell cmd) 
author: Dr-Sm@3t
image: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT97qlUP4V-_4iZcRXp5nsIeJvjkh1XGbWxVw&usqp=CAU
date: 2020-11-10 2:23:00 +6:30
categories: [Linux,Termux]
tags: [Termux,Linux,Cmd]
---

## What is linux?

Linux ဆိုတာ ဘာလဲ လို့ မေးလာရင် Linux ဆိုတာ တစ်ကမ္ဘာလုံးကို အခမဲ့ပေးသုံးတဲ Open Source OS တစ်ခုလို့ပဲ ဖြေဖြစ်ပါလိမ့်မယ်

ဒါဆို ထပ်မေးစရာရှိလာလိမ့်မယ်ဗျ Open Source ဆိုတာ ဘာလဲလို့ပေါ Open Source ဆိုတာ လွတ်လပ်စွာ ပြင်ဆင်/ပြောင်းလဲခွင့် Develop လုပ်ခွင့် Customize လုပ်ခွင့် ပေးထားခြင်းကိုဆိုလိုပါတယ် ဥပမာ Open Source Software တစ်ခုမှာ မူရင်း Code ကိုပါ Publish လုပ်ထားပါတယ် ကြိုက်တဲ User က ဖတ်ရှုခွင့်ရှိတယ် မိမိ စိတ်ကြိုက် ပြောင်းလဲသုံးစွဲခွင့်ရှိပါမယ် ပြင်ရေးခွင့်ရှိပါမယ် ဒါမျုးကို Open Source လို့ခေါ်ပါတယ် ဒါဆို Linux ဆိုတာ ဘာလဲ နည်းနည်းတော့သဘောပေါက်လောက်ပါပြီ အခမဲ့ရတယ် Open Source ဖြစ်တယ် ဟုတ်ပြီး ဒါဆို Linux ဘယ်လိုဖြစ်လာသလဲ??? သမိုင်းကြောင်းလေးကို တစ်ချက်ကြည့်ရအောင်။

## History of Linux
*******************
Linux အကြောင်းကိုပြောဖို့ဆိုရင် ဟိုး ကွန်ပျုတာ ခေတ်ဦးကာလကို စပြီးသွားကြည့်ရမှာဖြစ်ပါတယ်

၁၉၇၀ ပြည့်နှစ်မှာ Ken Thompson နဲ့ Dennis Ritchie　တို့နှစ်ယောက်ဟာ Unix ဆိုတဲ Operating System တစ်ခု ရေးသားခဲ့ပါတယ်။ အဲဒီ့ခေတ် အဲ့ဒီ့အခါကတော အလွန်ပြီးပြည့်စုံသော OS တစ်ခုပါ တက္ကသိုလ်တွေအပါအဝင် စီးပွားရေး လုပ်ငန်းတွေမှာပါ အသုံးပြုခဲ့တဲ OS တစ်ခုပါ
နောက်ပိုင်းထွက်တဲ OS တွေဟာ Unix ရဲ့ OS Design ကို အခြေခံပြီး ထွက်ရှိလာတဲ OS တွေလို့တောင်ပြောလို့ရပါတယ်။

၁၉၈၃ မှာတော GNU Project နှင့် GNU ( GNU General Public License ) ရဲ့ ဖခင်ကြီး Richard Stallman ဟာ GNU လို့ခေါ်တဲ Unix-Based OS တစ်ခုကိုတည်ဆောက်ခဲ့ပါတယ် GNU ဆိုတာ GNU's Not Unix ပါတဲ အစတုံးက GNU ကို ဥးတည်ခဲ့တဲ GNU Project ဟာ နောက်ပိုင်းမှာ Open Source Software Projects တွေကိုဦးတည်သွားပါတယ်။

၁၉၈၇ မှာ Andrew S. Tanenbaum က Minix ဆိုတဲ Unix-Based OS တစ်ခုကို ထပ်မံတီထွင်ခဲ့ပါတယ် သို့သော်လည်း ယင်း OS ဟာ 16 Bit Design မျှသာဖြစ်ပြီး Intel 386 ရဲ့ 32 Bit Design　မှာ　အလုပ်မလုပ်တဲပြဿနာတွေ့လာပါရော....။

Unix ဟာ　ကျောင်းသားတွေနဲ့ ကွန်ပျုတာပညာရှင်တွေအတွက်　သာ　အဆင်ပြေပြီး　Appe ရဲ့　Macကလည်းစျေးကြီးနေတဲ့ အတွက်　သာမန်User များအသုံးပြုရန် OS တစ်ခုလိုအပ် လာပါတယ်　ဒါကို Linux ရဲ့　ဖခင်ကြီး　Linus Torvalds　ကစတင်သတိပြုခဲ့မိပြီး ၁၉၉၁ မှာ　Linux Kernal ဖြစ်လာမယ့်　OS　Project တစ်ခုကို　စတင်ခဲ့ပါတယ်　Linux ဆိုတာ　သူ့နာမည် Linus နဲ့　Minix ကိုပေါင်းပြီး ပေးထားတာဖြစ်ပါတယ်။ အစက　Linux Torvalds ဟာ　Freax လို့　နာမည်ပေးချင်တာဗျ　Free & Freak ဆိုတာကို　ယူပြီး unix နဲ့ပေါင်းချင်တာပေါ့　နောက်ကျမှ　Linux　လို့ပဲ နာမည်ပေးလိုက်တော့တာ　Linux Torvalds ကတော　Linux ကို　သူအပျော်သဘောမျိုးနဲ့ပဲ　ရေးခဲ့တာပါတဲ　အပျင်းပြေပေါ့။ သူရေးပြီးတော　Minix ကိုရေးတဲ Andrew S. Tanenbaum　ကိုသွားပြပါသတဲ့။　ဟို　Minix ရေးတဲ့လူက　ပါမောက္ခ　သူက　ကွန်ပျုတာ တက္ကသိုလ်ကျောင်းသား　ဘာပြောကောင်းမလဲ　ဟိုပါမောက္ခကကောလွှတ်လိုက်တာပေါ့။

　Linux က ဘာေ..ာက်သုံးကျလို့လဲတဲ။ Linux Torvalds ဟာ　Kernal ပြီးတာနဲ့　Usenet မှာ　တင်ပေးလိုက်ပါရော Usenet ဆိုတာ　လွယ်လွယ်ပြောရရင်　ဟိုတုံးက　အင်တာနက်ပေါ့ဗျာခေတ်ဟောင်း　Internet
သူတင်ပေးလိုက်ပုံကိုလည်းကြည့်ဦး Linux ဟာ　GNU လို　Pro မဟုတ်ပဲ　အပျော်သဘောရေးထားတဲဝါသနာအရ တည်ဆောက်ထားတဲ့ OS တစ်ခုသက်သက်ပါပဲတဲ　Minix က　Code တွေလုံးဝမပါပါဘူးတဲ့　Free ပေးမယ်　Open Source တဲ အစပိုင်းမှာတော　Linux ဟာ　GPL License အောက်မှာ　မနေပါဘူး　စီးပွားရေးလုပ်ငန်းတွေအတွက် သတ်မှတ်ထားတဲ　စည်းမျဉ်းတွေပါတဲ့　License သီးသန့်တစ်ခုနဲ့　အလုပ်လုပ်ပါတယ်　နောက်ပိုင်းမှ　GNU GPL ထဲကိုရောက်သွားတာပါ　ဒီလိုနဲ့　Linux ကို　ဟိုတစ်ယောက်ကသုံး　ဒီတစ်ယောက်သုံးနဲ့ ဟိုတစ်ယောက်ပြင်ဒီတစ်ယောက်ပြင်　နဲ့　ပိုမိုကောင်းမွန်ပြည့်စုံသော　OS တစ်ခုသို့ရောက်ရှိလာပါတယ်။ 
နောက်ပိုင်း GUI တွေပါထည့်သွင်း　Customize လုပ်ရင်းနဲ့ Linux မူကွဲ Linux Distributions တွေအများကြီး ပေါ်ထွက်လာပါတယ် ( GUI ဆိုတာ Graphical User Interface ပါ ) အဲဒီလို Linux Distributions တွေ ဘယ်လောက်ထိများလိုက်လိုဆိုရင် ရာချီပြီးရှိတာကို http://distrowatch.com/
မှာသွားကြည့်နိုင်ပါတယ်။ တချို့ကတော အခမဲ့ပေးတယ် တချို့ကျလည်းသူတို့ပြင်ထားတာကို ရောင်းစားတယ်။
ရောင်းစားခွင့်လည်းပေးထားပါတယ် GPL အရ ကိုယ့်စိတ်ကြိုက်ပြင်ပြီးရင် ပြင်ထားတဲ့ဟာကို Developer အလကားပေးချင်တဲ့လူကိုပေး တကယ်လို့ Developer က အမြင်ကပ်တဲ့ကောင်ဆို ပိုက်ဆံနဲ့ရောင်းစားလို့လည်း ဘာမှမပြောပါ။ The Best Linux Distributions ဆိုပြီး ရှာကြည့်ပြီး ကိုယ့်အတွက်အဆင်ပြေမဲ့ Distriburitons ကိုလည်း စိတ်ကြိုက်ရွေးချယ် အသုံးပြုလို့ရပါတယ်။

https://www.techradar.com/news/best-linux-distro

အပေါ်က လင့်ခ်မှာလည်း The Best Linux Distro တွေကိုအောက်ပါအတိုင်း အစဉ်လိုက်ဖော်ပြပေးထားပါတယ်..

1. Elementary OS
2. Linux Mint
3. Arch Linux
4. Ubuntu
5. Tails
6. CentOS 7
7. Ubuntu Studio
8. openSUSE

## Front Matter

Basically, you need to fill the [Front Matter](https://jekyllrb.com/docs/front-matter/) as below at the top of the post:

```yaml
---
title: TITLE
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     # TAG names should always be lowercase
---
```

> **Note**: The posts' ***layout*** has been set to `post` by default, so there is no need to add the variable ***layout*** in Front Matter block.

### Timezone of date

In order to accurately record the release date of a post, you should not only setup the `timezone` of `_config.yml` but also provide the the post's timezone in field `date` of its Front Matter block. Format: `+/-TTTT`, e.g. `+0800`.

### Categories and Tags

The `categories` of each post is designed to contain up to two elements, and the number of elements in `tags` can be zero to infinity.

The list of posts belonging to the same *category*/*tag* is recorded on a separate page. At the same time, the number of these *category*/*tag* type pages is equal to the number of `categories` / `tags` elements for all posts, which means that the two number must be exactly the same.

For instance, let's say there is a post with front matter:

```yaml
categories: [Animal, Insect]
tags: bee
```

Then we should have two *category* type pages placed in folder `categories` of root and one *tag* type page placed in folder `tags`  of root:

```sh
.
├── categories
│   ├── animal.html         # a category type page
│   └── insect.html
├── tags
│   └── bee.html            # a tag type page
...
```
    
and the content of a *category* type page is

```yaml
---
layout: category
title: CATEGORY_NAME        # e.g. Insect
category: CATEGORY_NAME     # e.g. Insect
---
```

the content of a *tag* type page is

```yaml
---
layout: tag
title: TAG_NAME             # e.g. bee
tag: TAG_NAME               # e.g. bee
---
```

With the increasing number of posts, the number of categories and tags will increase several times!  If we still manually create these *category*/*tag* type files, it will obviously be a super time-consuming job, and it is very likely to miss some of them, i.e., when you click on the missing `category` or `tag` link from a post or somewhere, the browser will complain to you "404 Not Found". The good news is we got a lovely script tool `_scripts/sh/create_pages.sh` to finish the boring tasks. Basically we will use it through `run.sh`, `build.sh` or `deploy.sh` that placed in `tools/` instead of running it separately. Check out its use case [here]({{ "/posts/getting-started/#deployment" | relative_url }}).

## Last modified date

The last modified date of a post is obtained according to the post's latest git commit date, and the modified date of all posts are designed to be stored in the file `_data/updates.yml`. Then contents of that file may be as follows:

```yaml
-
  filename: getting-started             # the post filename without date and extension
  lastmod: 2020-04-13 00:38:56 +0800    # the post last modified date
-
  ... 
```

You can choose to create this file manually, But the better approach is to let it be automatically generated by a script tool, and `_scripts/sh/dump_lastmod.sh` was born for this! Similar to the other script (`create_pages.sh`) mentioned above, it is also be called from the other superior tools, so it doesn't have to be used separately.

When some posts have been modified since their published date and also the file `_data/updates.yml` was created correctly, a list with the label **Recent Updates** will be displayed in the right panel of the desktop view, which records the five most recently modified posts.

## Table of Contents

By default, the **T**able **o**f **C**ontents (TOC) is displayed on the right panel of the post. If you want to turn it off globally, go to `_config.yml` and set the value of variable `toc` to `false`. If you want to turn off TOC for specific post, add the following to post's [Front Matter](https://jekyllrb.com/docs/front-matter/):

```yaml
---
toc: false
---
```


## Comments

Similar to TOC, the [Disqus](https://disqus.com/) comments is loaded by default in each post, and the global switch is defined by variable `comments` in file `_config.yml` . If you want to close the comment for specific post, add the following to the **Front Matter** of the post:

```yaml
---
comments: false
---
```


## Mathematics

For website performance reasons, the mathematical feature won't be loaded by default. But it can be enabled by:

```yaml
---
math: true
---
```

## Preview Image

If you want to add an image to the top of the post contents, specify the url for the image by:

```yaml
---
image: /path/to/image-file
---
```

## Pinned Posts

You can pin one or more posts to the top of the home page, and the fixed posts are sorted in reverse order according to their release date. Enable by:

```yaml
---
pin: true
---
```

## Code Block

Markdown symbols <code class="highlighter-rouge">```</code> can easily create a code block as following examples.

```
This is a common code snippet, without syntax highlight and line number.
```

## Specific Language

Using <code class="highlighter-rouge">```language</code> you will get code snippets with line numbers and syntax highlight.

> **Note**: The Jekyll style `{% raw %}{%{% endraw %} highlight LANGUAGE {% raw %}%}{% endraw %}` or `{% raw %}{%{% endraw %} highlight LANGUAGE linenos {% raw %}%}{% endraw %}` are not allowed to be used in this theme !

```yaml
# Yaml code snippet
items:
    - part_no:   A4786
      descrip:   Water Bucket (Filled)
      price:     1.47
      quantity:  4
```

### Liquid Codes

If you want to display the **Liquid** snippet, surround the liquid code with `{% raw %}{%{% endraw %} raw {%raw%}%}{%endraw%}` and `{% raw %}{%{% endraw %} endraw {%raw%}%}{%endraw%}` .

{% raw %}
```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```
{% endraw %}

## Learn More

For more knowledge about Jekyll posts, visit the [Jekyll Docs: Posts](https://jekyllrb.com/docs/posts/).
