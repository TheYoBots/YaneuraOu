![Make CI (MSYS2 for Windows)](https://github.com/yaneurao/YaneuraOu/workflows/Make%20CI%20(MSYS2%20for%20Windows)/badge.svg?event=push)
![Make CI (DeepLearning for Windows)](https://github.com/yaneurao/YaneuraOu/workflows/Make%20CI%20(DeepLearning%20for%20Windows)/badge.svg?event=push)
![Make CI (MinGW for Windows)](https://github.com/yaneurao/YaneuraOu/workflows/Make%20CI%20(MinGW%20for%20Windows)/badge.svg?event=push)
![Make CI (for Ubuntu Linux)](https://github.com/yaneurao/YaneuraOu/workflows/Make%20CI%20(for%20Ubuntu%20Linux)/badge.svg?event=push)
![Make CI (DeepLearning for Ubuntu Linux)](https://github.com/yaneurao/YaneuraOu/workflows/Make%20CI%20(DeepLearning%20for%20Ubuntu%20Linux)/badge.svg?event=push)
![NDK CI (for Android)](https://github.com/yaneurao/YaneuraOu/workflows/NDK%20CI%20(for%20Android)/badge.svg?event=push)

# About this project

YaneuraOu is the World's Strongest Shogi engine(AI player), WCSC29 1st winner, educational and USI compliant engine.

# Notice

2019/05/05 We participated in WCSC29 (World Computer Shogi Championship / 2019) as "YaneuraOu with Otafuku Lab 2019" and won the championship. (WCSC first participation, victory) For the next year, I will call myself the strongest in the world. (｀･ω･´)ｂ
- [WCSC29 YaneuraOu won the championship!](http://yaneuraou.yaneu.com/2019/05/06/wcsc29%E3%80%81%E3%82%84%E3%81%AD%E3%81%86%E3%82%89%E7%8E%8B%E5%84%AA%E5%8B%9D%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F%EF%BC%81/)

# YaneuraOu Engine Tournament Results

- 2017 World Computer Shogi Championship (WCSC27) "elmo" championship
- 2017 5th Shogi Den-O Tournament (SDT5) "Heisei Shogi Battle Pompoko" Winner
- 2018 World Computer Shogi Championship (WCSC28) "Hefeweizen" Winner
- Winner of the 2019 World Computer Shogi Championship (WCSC29) "YaneuraOu with Otafuku Lab 2019".
  - All the top eight teams in the final have adopted YaneuraOu's thinking engine.

# About how to use YaneuraOu

  - Setup procedure: [YaneuraOu setup question thread](http://yaneuraou.yaneu.com/2017/05/04/%E3%82%84%E3%81%AD%E3%81%86%E3%82%89%E7%8E%8B-%E3%82%BB%E3%83%83%E3%83%88%E3%82%A2%E3%83%83%E3%83%97%E8%B3%AA%E5%95%8F%E3%82%B9%E3%83%AC%E3%83%83%E3%83%89/)
  - Description of engine options: [docs/USIextensioncommand.txt](docs/USI%E6%8B%A1%E5%BC%B5%E3%82%B3%E3%83%9E%E3%83%B3%E3%83%89.txt)
  - Technical documents such as evaluation function learning commands, book generation commands, build methods, etc.: [docs/Explanation.txt](/docs/%E8%A7%A3%E8%AA%AC.txt)

# Currently ongoing subprojects

## YaneuraOu Engine (YaneuraOu with Otafuku Lab 2019)

We will continue to improve this engine section in 2019.

## YaneuraOu Tsume Shogi solver

Under development by tanuki: A solver that can solve the length of Tsume Shogi.

# Past subprojects

Click here for past sub-projects such as YaneuraOu nano, mini, classic, Ote Shogi, Toru Ichite Shogi, Cooperative Solver, and Continuous Self-Competition Framework.

- [Past subprojects](/docs/README2017.md)

# YaneuraOu evaluation function file

- YaneuraOu 2018 KPPT type --Apery (WCSC26), Apery (SDT4) = "Floating Se" evaluation function binary can be used as it is.
- YaneuraOu 2018 KPP_KKPT type --You can use the one in the evaluation function for KPP_KKPT type build of the [past subproject](/docs/README2017.md).
- YaneuraOu 2018 NNUE type --tanuki- (SDT5, WCSC28, WCSC29), NNUEkai and other evaluation functions can be used.

# YaneuraOu News

It is a list of headlines of related articles written on the official blog of YaneuraOu. You can also find explanations of each engine option, download a book file, and how to generate a book.

  - [YaneuraOu News Table of Contents List](docs/news.md)

# For developers participating in the WCSC (World Computer Shogi Championship)

If you participate using YaneuraOu as a library, you can use all the files on GitHub of YaneuraOu and all the files directly linked from this top page.

# License

Many parts of the source code of the YaneuraOu project use Stockfish as it is, and some parts refer to Apery/Silent Majority, so the YaneuraOu project follows the license (GPLv3) of those projects. Will do.

The "Rezero Evaluation Function File" is the original of the YaneuraOu Project, but we do not claim any rights, so please feel free to use it.
