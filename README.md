Author: William Davis

#### Project: Loopy

#### Date: 4-28-20

#### -- LOOPY SETUP--

Hello! I&#39;m glad that you have made it here, I must admit I rarely ever look a the README file even if the letters are in all-caps. However, it is likely you will find this information very helpful in understanding my horrendous file-management.

1. THIS IS A BETA
  1. At the moment, you are likely here as a result of being connected to me through Bates College or my immediate friend group. This is the product of 2 days with no sleep and keeping track of time with beers and cups of coffee.
  2. I will be releasing an update soon fixing some bugs with the voice-recorder, the &quot;2x Loop&quot; button, and improved functionality with the pitch and reverb sliders.
  3. My most important plan for the future is to collect different sounds-banks and have a list of which type of instrument you want the use the synth on.
2. GETTING STARTED
  1. To download the Pure Data platform, follow this link: [https://puredata.info/downloads/pure-data](https://puredata.info/downloads/pure-data)
    1. If you have a Mac, click on the Apple logo highest on the list. This should automatically download the _ **pd-0.50-2.mac.tar.gz** _file on your computer. Double-click it and the app should be automatically installed in your downloads.
    2. Move this to your applications folder.
  2. You are seeing this because you have likely unzipped the file I sent to you. In the Loopy folder, there should be a file called _ **Loopy-02** __ **.pd** _. Open this file and you should see the interface. I am actively working on cleaning up the folder so it&#39;s easier to manage.

1. OPERATING MANUAL

    1. — HEADPHONES ARE ESSENTIAL—
    2. You can set this up by going to the _ **Pd** _button at the top of your screen, going to preferences, audio, and then choosing your input and output devices.

  1. The drum kit is numbers 1-10 on the keyboard (WARNING: It is pretty loud so keep the volume very low)
  2. The piano is set like most MIDI keyboard setups (G=G,H=A,J=B,K=D… etc — it&#39;s pretty intuitive and the buttons help).
  3. If you have a Mac, your computer might want to quickly push some of the piano sample waves to the cloud. If the keys aren&#39;t producing sound, the .wav files are either in the cloud or not in the correct location.
  4. The piano and bass operate on partly the same keys, so when you want a piano, turn the bass down, if you want bass, turn the piano down. You can choose to have a little bit on top of the other, it&#39;s fun to experiment with.
  5. The loopers work pretty much like loopers but the pitch and reverb are there mostly for aesthetics, I&#39;ll get them functional soon.
  6. The voice looper was giving me problems right at the end so I&#39;m going to have to investigate that further. Sometimes it works, sometimes it doesn&#39;t.

--- DESCRIPTION---

A few weeks ago, I discovered this amazing artist by the name of Marc Rebillet. He has gotten quite the following on youtube for his energetic live-streams where he uses a looper and creates songs based on suggestions from the viewers. I was inspired by the concept but was upset to find that the looper he was using was well over $1000 dollars so I decided that I would happily watch from the sidelines. I was then reminded of the live-looper example that Professor Asha Tamirisa gave us and I went to work, and worked, kept working, thought I was going to be able to use my keyboard at home and use it as a midi controller in PureData, couldn&#39;t order the converter in time, bounced over 50 short audio samples from GarageBand, and key-bound my keyboard to different sounds. Although I initially was using my professor&#39;s looper she provided, I found the sound quality was lost somewhere in the abstraction. I ended up writing my own looper abstraction which reads and writes to a sound file and then uses a timer to trigger them to play repetitively. Not only did this use significantly less code, but the sound quality was also improved. On the patch, I have 2 keyboards, one for a piano with 2 full octaves, and another one for an electric bass with 1. Next to the bass, I have a pad that has been key-bound to a drum kit from GarageBand. I also have coded in some other functional objects like pitch and reverb (although they really just make the sound quality bad), and a sync button which aligns the recordings up so everything falls on the same beat (VERY IMPORTANT). If the first loop is too short, I have a &quot;2x&quot; button which will record another layer for 2 loops. As far as the words that go along with it, this was truly improvised right before 4:00 AM and later written down. Overall, I am very proud of this project and really put in a lot of time and frustration to pull it together and I&#39;m going to download some more sounds that I can experiment with.

The final song is called Ambience.
