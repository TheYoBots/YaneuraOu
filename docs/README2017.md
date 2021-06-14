# Assortment of thinking engines from past subprojects

- [Click here](https://github.com/yaneurao/YaneuraOu/releases/tag/v4.73_engine2016) to download the thinking engine of past subprojects.

# Past subprojects

## YaneuraOu 2017 GOKU: Participated in SDT5 as "Goku YaneuraOu".

I participated in the 5th Shogi Den-O Tournament in November 2017. (Strength of the search part, not much different from the previous version) When using an evaluation function such as Apery (SDT5), it seems that it is about R4200 with Xeon 24 core.

## YaneuraOu 2017 Early

Completed May 5, 2017. Elmo using this thinking engine won the WCSC27. At the 2017 Shogi Den-O Tournament, the Heisei Shogi Battle Pompoko using this thinking engine won the championship. Using the evaluation functions of elmo (WCSC27) and Soten Illusion Knights of Tanuki (WCSC27 participation), it seems that it is about R4000 with Xeon 24 core.

- [Click here](https://github.com/yaneurao/YaneuraOu/releases/) to download the main body of the thinking engine

## YaneuraOu 2016 Late

The 4th Shogi Den-O Tournament participation version. "Shin Yaneura King"

Using the NDF learning method, we adjusted various parameters using Hyperopt etc., and the strength exceeded the skill (2015). 
(About R3650) → The 4th Shogi Den-O Tournament has finished successfully. King Yaneura won the 3rd place. Thank you to everyone who supported us.

## YaneuraOu 2016 Mid

YaneuraOu Thinking Engine 2016 Mid Edition. It automates the adjustment of various hyperparameters using Hyperopt etc. and automatically adjusts. Strengthened for long time. The evaluation function binary of Apery (WCSC26) can be read. (About R3450)

## YaneuraOu classic-tce

YaneuraOu classic-tce is the source code of YaneuraOu classic with time control (countdown, corresponding to Fisher rules) and ponder functions added. (About R3250)

## YaneuraOu classic

YaneuraOu classic aims to be as strong as Apery (WCSC 2015) by improving the source code of YaneuraOu mini. We also added a jishogi declaration function. (About R3000)

## YaneuraOu mini

YaneuraOu mini is a parallel version of YaneuraOu nano plus, which looks like shogi software. Written in stronger, educational and shorter code than Bonanza6. About 3000 lines in total, about 500 lines in the search section. (About R2700)

## Yaneurao nano plus

YaneuraOu nano plus is a very simple and reasonably strong thinking engine with about 300 lines in the search section and improved ordering. (About R2500)

## YaneuraOu nano

YaneuraOu nano is a basic program of Shogi AI written in about 1500 lines. The search section is about 150 lines, and it is a very simple code, and no pruning other than αβ is done. (About R2000)

## YaneuraOu cooperation solver

Cooperation-packed solver that can solve "Jugemu 3" (49909 hands) →　[Explanation page](http://yaneuraou.yaneu.com/2016/01/02/%E5%8D%94%E5%8A%9B%E8%A9%B0%E3%82%81solver%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%99/)

## YaneuraOu Check Shogi Edition

Shogi with an irregular rule that you win if you check. It has become the strongest checkered shogi in the world. (R4250)

## YaneuraOu Take Ichigo Shogi Edition

Shogi with an irregular rule that if you have a legal move, you must take it.

## Continuous automatic game framework

You can automate continuous automatic games. A python version of the script is also available. From now on, we will focus on the python version.

# Past evaluation function file

For YaneuraOu Ote Shogi Edition

- [Evaluation function file for check shogi V1 commentary article](https://drive.google.com/file/d/0Bzbi5rbfN85NOEF6QWFienZrSDg/) [解説記事](http://yaneuraou.yaneu.com/2016/11/21/%E7%8E%8B%E6%89%8B%E5%B0%86%E6%A3%8B%E5%B0%82%E7%94%A8%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%ABv1%E3%81%8C%E5%87%BA%E6%9D%A5%E3%81%BE%E3%81%97%E3%81%9F/)
- [Evaluation function file for check shogi V2 commentary article](https://drive.google.com/open?id=0Bzbi5rbfN85Nci02T3hkWm1yQlE) [解説記事](http://yaneuraou.yaneu.com/2016/11/22/%E7%8E%8B%E6%89%8B%E5%B0%86%E6%A3%8B%E7%94%A8%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%ABv2%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)
- [Evaluation function file for check shogi V3 commentary article](https://drive.google.com/open?id=0Bzbi5rbfN85NVGJ3eHNtaHZhLXc) [解説記事](http://yaneuraou.yaneu.com/2016/11/23/%E7%8E%8B%E6%89%8B%E5%B0%86%E6%A3%8B%E7%94%A8%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%ABv3%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)
- [Evaluation function file for check shogi V4 commentary article](https://drive.google.com/open?id=0Bzbi5rbfN85NcTIzaFVKU0ZfNU0) [解説記事](http://yaneuraou.yaneu.com/2016/11/23/%E7%8E%8B%E6%89%8B%E5%B0%86%E6%A3%8B%E7%94%A8%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%ABv4%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)
- [Evaluation function file for check shogi V5 commentary article](https://drive.google.com/open?id=0Bzbi5rbfN85Na3ZOeE5zNUZpNkE) [解説記事](http://yaneuraou.yaneu.com/2016/11/24/%E7%8E%8B%E6%89%8B%E5%B0%86%E6%A3%8B%E7%94%A8%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%ABv5%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)
- [Evaluation function file for check shogi V6 commentary article](https://drive.google.com/open?id=0Bzbi5rbfN85NeWxUWUFfMFdZSjQ) [解説記事](http://yaneuraou.yaneu.com/2016/11/29/%E7%8E%8B%E6%89%8B%E5%B0%86%E6%A3%8B%E7%94%A8%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%ABv6%E3%82%92%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)

For YaneuraOu nano, nano-plus, classic, classic-tce
- You can [download it from the CSA library download page](http://www.computer-shogi.org/library/).

## "Re: Evaluation Function Life Starting from Zero" Project (abbreviated as "Rezero")

Reinforcement learning was performed using the "elmo aperture" (elmo (WCSC27) method) from the evaluation function of the zero vector (evaluation function of only Komatoku). It features a mysterious enclosure and final power that conventional software does not have.

It can be used by replacing the evaluation function file of YaneuraOu 2018 KPPT type. The larger the epoch number written in the folder name, the newer generation (stronger).

- [Rezero evaluation function epoch 0](https://drive.google.com/open?id=0Bzbi5rbfN85Nb3o1Zkd6cjVNYkE): Evaluation function in the initial state where all parameters are zero.
- [Rezero evaluation function epoch 0.1](https://drive.google.com/open?id=0Bzbi5rbfN85NNTBERmhiMGZlSWs): [Commentary article](http://yaneuraou.yaneu.com/2017/06/20/%E5%BE%93%E6%9D%A5%E6%89%8B%E6%B3%95%E3%81%AB%E5%9F%BA%E3%81%A5%E3%81%8F%E3%83%97%E3%83%AD%E3%81%AE%E6%A3%8B%E8%AD%9C%E3%82%92%E7%94%A8%E3%81%84%E3%81%AA%E3%81%84%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0/)
- [Rezero evaluation function epoch 1 to 4](https://drive.google.com/open?id=0Bzbi5rbfN85NNWY0RTJlc2x5czg): [Commentary article](http://yaneuraou.yaneu.com/2017/06/12/%E4%BA%BA%E9%96%93%E3%81%AE%E6%A3%8B%E8%AD%9C%E3%82%92%E7%94%A8%E3%81%84%E3%81%9A%E3%81%AB%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%81%AE%E5%AD%A6%E7%BF%92%E3%81%AB%E6%88%90%E5%8A%9F/)
- [Rezero evaluation function epoch 5 to 6](https://drive.google.com/open?id=0Bzbi5rbfN85NSS0wWkEwSERZVzQ): [Commentary article](http://yaneuraou.yaneu.com/2017/06/13/%E7%B6%9A-%E4%BA%BA%E9%96%93%E3%81%AE%E6%A3%8B%E8%AD%9C%E3%82%92%E7%94%A8%E3%81%84%E3%81%9A%E3%81%AB%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%81%AE%E5%AD%A6%E7%BF%92/)
- [Rezero evaluation function epoch 7](https://drive.google.com/open?id=0Bzbi5rbfN85NWWloTFdMRjI5LWs): [Commentary article](http://yaneuraou.yaneu.com/2017/06/15/%E7%B6%9A2-%E4%BA%BA%E9%96%93%E3%81%AE%E6%A3%8B%E8%AD%9C%E3%82%92%E7%94%A8%E3%81%84%E3%81%9A%E3%81%AB%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%81%AE%E5%AD%A6%E7%BF%92/)
- [Rezero evaluation function epoch 8](https://drive.google.com/open?id=0Bzbi5rbfN85NMHd0OEUxcUVJQW8): [Commentary article](http://yaneuraou.yaneu.com/2017/06/21/%E3%83%AA%E3%82%BC%E3%83%AD%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0epoch8%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F%E3%80%82/)

## Evaluation function for YaneuraOu KPP_KKPT type

YaneuraOu 2018 Evaluation function that can be used with KPP_KKPT type.

- [Rezero evaluation function KPP_KKPT type epoch4](https://drive.google.com/open?id=0Bzbi5rbfN85NSk1qQ042U0RnUEU): [Commentary article](http://yaneuraou.yaneu.com/2017/09/02/%E3%82%84%E3%81%AD%E3%81%86%E3%82%89%E7%8E%8B%E3%80%81kpp_kkpt%E5%9E%8B%E8%A9%95%E4%BE%A1%E9%96%A2%E6%95%B0%E3%81%AB%E5%AF%BE%E5%BF%9C%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)

## Shivoray Fully automatic rag squeezer

For those who want to create their own evaluation function and play with it, we have released a fully automatic rag squeezer called "Shivoray".

- [ShivorayV4.71](https://drive.google.com/open?id=0Bzbi5rbfN85Nb292azZxRmU0R1U): [Commentary article](http://yaneuraou.yaneu.com/2017/06/26/%E3%80%8Eshivoray%E3%80%8F%E5%85%A8%E8%87%AA%E5%8B%95%E9%9B%91%E5%B7%BE%E7%B5%9E%E3%82%8A%E6%A9%9F%E5%85%AC%E9%96%8B%E3%81%97%E3%81%BE%E3%81%97%E3%81%9F/)
