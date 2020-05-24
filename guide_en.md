# Recommendations

**Immersion** is the best way to learn any language. You want to get to doing that as soon as possible. For this, you will need to attack the writing and the basics of grammar first, and following that, every aspect of the language proficiency can be improved while using the learning materials at the same time. Here's the optimal sequence to begin with.

-  learn the syllabic alphabets which are necessary for everything else;
-  get used to reading (recognising) the hieroglyphic writing system of *kanji* (&quot;Chinese characters&quot; — but in fact, there are plenty of kanji that only exist in Japanese);
-  skim over a grammar guide (a Japanese self-study book or grammar reference) once quickly, and don't try to really memorise everything you see, Japanese morphology is simple enough;
-  wield the good dictionaries and get to a full-time daily immersion;
-  whenever you've accumulated a number of insurmountable grammar issues, read the grammar guide about it;
-  in about half-year after you started, read the grammar guide paying full attention this time.

### Syllabic Alphabets

Japanese has two "alphabets" called **hiragana** and **katakana** (they call the both &quot;kana&quot; for short). There are many essentially similar resources that can help you memorise it, using interactive sites, apps, or you can simply memorise it the old-school way if everything else fails.

Here are [the sites](https://github.com/daigakulounge/ochinchingadaiskinandayo/blob/master/links_en.md#kana) for memorising and practicing kana.

---

#### Advice from Ras

[These](http://youtu.be/6p9Il_j0zjc) two [videos](http://youtu.be/s6DKRgtVLGA) use mnemonic pictures, I just drew them and compared them with how kana's written, and definitely don't forget to repeat after the Japanese guide aloud. I spent 4 days 30 minutes each to remember it all.

---
And moving on to...

### The Grammar

Just start with Tae Kim's Grammar Guide, don't overthink things that seem to fly over your head — the main idea is to finish reading it as soon as you can.

If you're self-studying, we recommend against using textbooks like *Minna no nihongo, Genki,* etc. because they imply your interaction with a teacher, asking questions, getting little tips and tricks, which you won't get from it on your own and your study will stutter; we saw very few people who managed to learn from those books and then speak actual Japanese.

One great grammar reference can be found at [itazuraneko](https://itazuraneko.neocities.org/grammar/taekim.html), helpful even for the advanced learner and practitioner.

---

### Kanji

You need to develop a habit, the synaptic chains in your brain, that will help you quickly tell apart the kanji's elements and keep the harder ones wieldy by using mnemonics. So here's how to easily goad your mind into wrapping around them.

RTK: [Remembering the Kanji](https://nihongoshark.com/learn-kanji/). A structured kanji and mnemonic reference. Usually practiced together with Anki and [kohii](https://kanji.koohii.com/) (this site offers the fellow learners' mnemonic options for kanji). (While the site is being updated, you can just use the [original books](https://cloud.mail.ru/public/3nFy/3FHGcFdjN).)

For the Russian-speaking community, we largely recommend ПБП — [Путь Бесхвостой Птички. Иероглифика методом Шерлока Холмса](https://vk.com/doc238918187_437163879?hash=f0732cea2d089a1b2e&amp;dl=141380ff882f64c0c6).

---

### Visual Novels (VN)

Visual novels are books that come as games. They are the most comprehensive option for immersion, as they include many aspects of learning the language at once — including the written text, its professional voicing for the dialogues, as well as non-voiced text (to practice speaking aloud while in the flow) including the protagonist's lines and the author's narrative. Besides, the characters have sprites helping you learn how the phrases correspond with the mood of the speaker. You can skip picking separate immersion outlets this way.

#### The OS's Japanese Locale

In order to run most Japanese VNs the operating system must be "Japanese" to begin with. Sometimes this is due to the intentional checks (so you're only allowed to run the game while in Japan (no we aren't certain why that's a thing)), but more often than not it's simply about the non-Unicode charset of the OS, something Japan has somehow only recently started fighting for real.

In most cases the VN will be built for Windows OS, and you will stumble upon this issue either in Windows or in Linux `wine`.

**Windows 10**: Press **Ctrl**+**Esc** либо [**Win**], input “cp” and go to Control Panel.  
Open _Region,_ and the tab _Administrative._ 
Click _Change system locale..._ and make it look as below:   
![screenshot](https://raw.githubusercontent.com/daigakulounge/ochinchingadaiskinandayo/master/misc/image5.png)    

Reboot after applying the changes, and the base font of many standard controls will change considerably, including showing “¥” instead of “\”. Non-Unicode apps (like certain Russian apps or maybe Chinese or some European languages) might stop showing the non-English (non-ASCII) characters correctly, or sometimes stop working altogether; due to this (and for other matters of convenience), we recommend playing VNs in a separate virtual machine (VM), although yours truly has been experiencing a rather miniscule amount of Russian/Cyrillics related issues as of y2020.

If you then run your VN and the system keeps complaining that you're not in Japan, you might need to take several less trivial steps which might include modifications of the VN's executable files. Either refer to https://t.me/vn_club for help, use Google or your own reverse engineering skills, or just pick a different less anal VN.

### Where to Get These

Pick one at [vndb.org](http://vndb.org) (we're trying to keep a [list of known good writers](https://t.me/vn_club/2608) updated). Look for the game in Steam (unless the Steam version has the Japanese cut out, then go to dlsite or the likes), buy it and play it. If that way isn't working out for some reason, you go pirate the thing (for some VNs there's just no other way).

### Dictionary

There are many options among the books, sites, or apps you can use, but we'll mention two apps here: the stand-alone app [qolibri](https://github.com/ludios/qolibri/releases) and [Yomichan](https://foosoft.net/projects/yomichan/) the browser addon. First you're going to need to import the [dictionaries in a specific format](https://www.mediafire.com/file/o3b6jt999dtd9vc/Yomichan_Dictionaries.zip/file). The starter pack of offline dictionaries is _JMdict (English/Russian), Anime &amp; Jdrama Freq, and Daijirin._

Don't forget to tweak the options as shown on the screenshots below. This lets you look up words from within yomichan's popups even (and you'll need this when you'll read the Japanese-only explanatory dictionaries).    

![yomichan recursive lookup](https://github.com/daigakulounge/ochinchingadaiskinandayo/blob/master/misc/image2.png?raw=true)    
Don't forget about the search page in Yomichan (**Alt**+**Insert**):    

![yomichan search page](https://github.com/daigakulounge/ochinchingadaiskinandayo/blob/master/misc/image4.png?raw=true)    


### Text Hooker (optional)

*Text Hooker* is a convenience app for Windows that makes reading VN for study easier. It hooks itself up into the VN of choice and intercepts screen text output functions extracting text from that and showing it as plain copyable text in a separate window, allowing for easy copypasting to a dictionary.

There are quite a few of these around, but again, we'll pick two: *Easy Text Hooker* and [*Textractor*](https://github.com/Artikash/Textractor/releases). In *Easy Text Hooker,* make sure you've enabled automatic copying to clipboard. In *Textractor,* disable the machine translation addons first. You don't need those to learn Japanese, they are not your friends.

When you've set it up, run it, point it at the VN you're hooking up to, and click through the in-game text a few times to see if it works. If it doesn't seem to, try looking up the *H-code* like this: (in Google) `<Japanese VN title> H-Code`. If you aren't successful, try asking [_in the Telegram chat_](https://t.me/vn_club).

We'd also like to warn you that many games from Nitro+ (or more specifically VNs running on Mages engine) will be invisible to Text Hooker. That means you won't be likely to use text hookers to read Steins;Gate, Chaos;Child, Robotics;Notes, and such.

Another reason your text hooker might simply not catch the text anyway is when the H-code it uses is meant for the different game version.

---

### Remembering Words and Kanji

#### Anki

[Anki](https://apps.ankiweb.net/) is an app that uses the scientifically proven Spaced Repetition Algorithm to help memorise words. An e-card deck that supports sound, video, and images.

---

### How to Use MS IME Efficiently

Inputting Japanese text is a small form of art in its own right, and is another thing you have to remember how to use.

Activate the assistive Japanese input by pressing **Alt**+[**~\`**]. You can now access the many keystrokes that simplify text input.

Intuitively enough, in the main mode, you start typing in Japanese words in Latin transliteration (US keyboard layout); when you've entered a chunk of text (it could be a word, a clause, a phrase, you'll get it as you go) you begin changing it up from the basic hiragana input. [**X**] or [**L**] allow you to input small kana: **a** for あ, **la** for ぁ and so on; inputting っ as in ずっと is easier by duplicating the following consonant: &quot;zutto&quot;. Japanese quotation marks 「」 are at the  **[** and **]** keys, while various parentheses are located at [**(9**] and [**)0**].

Next, either press **space** to open the _list of candidates,_ or press a conversion shortcut (whose main use is inputting the more rare katakana words).

**Conversion Shortcuts:** Suppose we've typed in 「 **あばたー** 」(abata-). Press **F7** to turn that into 「アバター」. **F6** to turn it back to 「あばたー」. **F8** → 「ｱﾊﾞﾀｰ」. **F9** → 「ａｂａｔａ－」. **F10** → 「abata-」. Pressing the same key several times  will select progressively less characters out of what you wrote to convert it.

Press **Enter** to apply changes. In case of the candidate list, you can press the number key corresponding to the candidate you wanted.

Certain words will take you to an unexpectedly large candidate list. **こめ** for ※. [**/?**] inputs the middle dot 中黒, yen sign, or ellipsis. **きごう** includes special characters from the traditional Japanese charset such as math symbols, Cyrillics, or Greek alphabet. **かおもじ** gives a list of emoticons (which you can expand by importing a MS入力顔文字辞書 (google it)).

**Ctrl** + **F10** summons the IME popup menu:   
![calling menu](https://github.com/daigakulounge/ochinchingadaiskinandayo/blob/master/misc/image3.png?raw=true)   

In IME Pad, you can simply draw kanji with a mouse if the source won't let you to just copy from it, or pick the right one based on the number of strokes or its radical.

---

### FAQ

Q. I can't find the meaning of [expression] in my dictionary (or find the difference between the synonyms), what now?  
A. Try a different dictionary; otherwise, google for <expression> + `意味`／`使い分け`.

Q. Can I just use one kana? Say, hiragana?  
A. No, you can't Both kanas are used equally often and are seen everywhere.

Q. What's the minimal number of counters that you need to know?
A. つ、人、匹、羽、個、台、杯 should suffice for starters.

Q. You know, I have a textbook, obviously meant for working with a teacher, and I'm sure that it's the best and your guide's incorrect!  
A. This guide is intended for _self_ study in the shortest time.

Q. But I hate VNs!  
A. You could study by separately immersing into books, audio, news, anime, manga — it's just more hassle and your "diet" might not be as balanced. Also, we can't stop you.

Q. Where can I practice talking in Japanese?  
A. Many places, like in [our dedicated Telegram chat](https://t.me/nihongo_practice). Please read the chat description and rules before you post _anything_ in there.

Q. How much time should I dedicate per day? What if I take an N days long break?  
A. Immersion implies giving the language as much time as you can. If you have to juggle work, commute, family, etc., you're definitely gonna be short on time for immersion. If you must learn it no matter what, you'll have to limit yourself to repeating  phrases that someone else made book examples with.  
You can take a break, but it's better to try giving it about 15 minutes a day anyway. If you seriously can't do that, you'll start forgetting the words, especially during the initial stages.

Q. When did this guide last update?
A. The latest update happened on 2020-03-24.
