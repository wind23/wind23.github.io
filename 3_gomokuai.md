---
layout: page
title: SlowRenju, a Gomoku AI
label: SlowRenju
permalink: /gomokuai.html
---

SlowRenju
=========

I have been developing *SlowRenju*, a gomoku AI engine since Jan 2012, which
is based on iteratively deepening alpha-beta pruning algorithm with a transposition
table. SlowRenju has been participating in the Gomoku AI programming tournament 
Gomocup since 2013, which is one of the more famous computer gomoku tournament now.

*Gomoku*, also known as *Five In a Row* or *五子棋*, is a game playing on a 15×15 (or maybe larger) board.
Two persons put their own stones on the crossing of the board alternatively, and the game
ends with a player winning by creating a line of five stones horizontally, vertically or diagonally,
or with a draw by the board filled up with stones. There are also some variants of gomoku,
among which the most famous one is *renju*, in which the black player (the player who moves first)
loses by creating a double-three, a double-four or an over-line.

SlowRenju can support freestyle gomoku rule, standard gomoku rule and renju rule.

SlowRenju has been open-source on Github since May 2019. It is distributed under the GNU General Public License v3.0.

<https://github.com/wind23/SlowRenju>

Download
========


1. SlowRenju v1.0.11 for Android (with engine SlowRenju 2016). Install it from [Google Play](https://play.google.com/store/apps/details?id=com.wind23.slowrenju) or the [APK file]({{ "/download/SlowRenju_Mobile_1_0_11.apk" | prepend: site.baseurl }}).
2. SlowRenju v5.1.4 engine (the version for Gomocup 2020). [Get it.](https://github.com/Gomocup/GomocupDownload/raw/master/2020/SLOWRENJU20.zip)
3. SlowRenju v5.1.3 engine (the version for Gomocup 2019). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU19.zip)
4. SlowRenju v5.1.2 engine (the version for Gomocup 2018). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU17.zip)
5. SlowRenju v5.1.1 engine (the version for Gomocup 2017). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU17.zip)
6. SlowRenju v5.0.11 engine (the version for Gomocup 2016). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU16.zip)
7. SlowRenju v4.1 engine (the version for Gomocup 2015). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU15.zip)
8. SlowRenju v4.0 engine (the version for Gomocup 2014). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU14.zip)
9. SlowRenju v3.2 with Win32 GUI (out of date and deprecated). [Get it.]({{ "/download/SlowRenju_v3.21.rar" | prepend: site.baseurl }})
10. SlowRenju v3.1 engine (the version for Gomocup 2013). [Get it.](https://gomocup.org/static/download-ai/SLOWRENJU13.zip)

In Gomocup
==========

Results of SlowRenju in Gomocup:

- In Gomocup 2020, SlowRenju v5.1.4 got the 10th in the freestyle group,
8th in the fastgame group, the 9th in the standard group, the 4th in
the renju group, and the 4th in the experimental Swap-2 group.
See [results](https://gomocup.org/results/gomocup-result-2019/).
- In Gomocup 2019, SlowRenju v5.1.3 got the 8th in the freestyle group,
10th in the fastgame group, the 6th in the standard group and the 5th in
the renju group.
See [results](https://gomocup.org/results/gomocup-result-2019/).
- In Gomocup 2018, SlowRenju v5.1.2 got the 7th in the freestyle group,
8th in the fastgame group, the 4th in the standard group and the 4th in
the renju group.
See [results](https://gomocup.org/results/gomocup-result-2018/).
- In Gomocup 2017, SlowRenju v5.1.1 got the 4th in the freestyle group,
4th in the fastgame group, the 3rd in the standard group and the 3rd in
the renju group.
See [results](https://gomocup.org/results/gomocup-result-2017/).
- In Gomocup 2016, SlowRenju v5.0.11 got the 3rd in the freestyle group,
3th in the fastgame group, the 4th in the standard group and the 3rd in
the renju group.
See [results](https://gomocup.org/results/gomocup-result-2016/).
- In Gomocup 2015, SlowRenju v4.1 got the 10th in the freestyle group,
10th in the fastgame group and 7th in the standard group.
See [results](https://gomocup.org/results/gomocup-result-2015/).
- In Gomocup 2014, SlowRenju v4.0 got the 10th in the freestyle group,
9th in the fastgame group and 5th in the standard group.
See [results](https://gomocup.org/results/gomocup-result-2014/).
- In Gomocup 2013, SlowRenju v3.2 got the 10th in the freestyle group,
9th in the fastgame group and 6th in the standard group.
See [results](https://gomocup.org/results/gomocup-result-2013/).

The Elo rating of SlowRenju in the [Gomocup Elo Rating List](https://gomocup.org/elo-ratings/):

- Freestyle rule: 1893, the 9th place.
- Fast game: 1832, the 11th place.
- Standard rule: 1913, the 6th place.
- Renju rule: 2302, the 5th place.

I have been organizing Gomocup with Kai Sun since 2016.

Acknowledgement
===============

Thanks to the friends who have been helping me with the project constantly: Kai Sun, Tao Tao and Rong Xiao.

Links
=====

1. [Gomocup](https://gomocup.org). The website for a computer gomoku tournament, previously held by Tomas Kubes
and currently by Kai Sun and Tianyi Hao.
2. [Yixin](https://www.aiexp.info/pages/yixin.html). The strongest gomoku/renju AI in the world, developed by 
[Kai Sun](https://www.kaisun.org/).
3. [Piskvork](https://sourceforge.net/projects/piskvork/files/piskvork.zip/download), an open-source gomoku GUI supporting the Gomocup
protocol, developed by [Petr Lastovicka](http://petr.lastovicka.sweb.cz/).
Together with Pela, the strongest open-source gomoku engine.
