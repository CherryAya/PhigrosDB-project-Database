# PhigrosDB-project-Database
将音游Phigros的收录曲以及难度定数整合为数据库
+ 制表: [KaguraYayoi](https://github.com/Fjaxzhy)
+ 校对: [SakuraiCora](https://github.com/Hajimarino-HOPE)

## 数据库结构
> sqlite3 <br>
> location: ./sqlite/PhigrosDB-1.0.1-1.6.11.db

      main    // 数据库
        |—— Info                 // 关于
        |—— Overview            // 收录曲总览
        |—— Difficulty         // 难度评级
        |—— Grade              // 得分评级
        |—— ChapterList         // 章节列表
        |—— Chapter-Legacy      // 章节Legacy
        |—— Chapter-Four      // 章节四 管道迷宫
        |—— Chapter-Five       // 章节五 霓虹灯牌
        |—— Chapter-Six         // 章节六 方舟蜃景
        |—— Chapter-Seven    // 章节七 时钟链接
        |—— Side-story-One      // 支线章节一 忘忧宫
        |—— Chapter-Ex-One      // 额外章节一 Muse Dash 精选集
        |—— Chapter-Ex-Two      // 额外章节二 WAVEAT 精选集
        |—— Chapter-Ex-Three    // 额外章节三 GOOD 精选集
        |—— Chapter-Ex-Four     // 额外章节四 HyuN 精选集
        |—— Chapter-Ex-Five     // 额外章节五 Rising Sun Traxx 精选集
        |—— Single                // 单曲 精选集
        |—— sqlite sequence         // sqlite系统表

## Documents 文档
详见 [docs](https://github.com/CherryAya/PhigrosDB-project-database/tree/main/docs) 目录

## Change-Log 更新日志
> v1.1.0-snapshot <br>
+ Chapter 7 时钟链接 : total 5 （预期还有1~2首隐藏曲） <br>
    |-- Clock Paradox <br>
    |-- Chronologika <br>
    |-- Chronomia <br>
    |-- Chronos Collapse - La Campanella <br>
    |-- Nick of Time <br>
+ Single 单曲精选集  : total 1 <br>
    |-- Nhelv <br>
+ Legacy 旧谱 : total 12 <br>
    |-- 混乱-Confusion --> 14 <br>
    |-- Dash --> 11 <br>
    |-- 云女孩 --> 12 <br>
    |-- Pixel Rebelz --> 15 <br>
    |-- ENERGY SYNERGY MATRIX --> 15 <br>
    |-- 華灯爱 --> 14 <br>
    |-- RIPPER --> 15 <br>
    |-- Khronostasis Katharsis -->14 <br>
    |-- 狂喜蘭舞 --> 14 <br>
    |-- Winter ↑ cube ↓ --> 13 <br>
    |-- Drop It --> 14 <br>
    |-- Another Me --> 13 <br>
> v1.0.1 <br>
+ 新增 : 在Overview表中加入曲绘（Illustration）
> v1.0.0
+ 完成各表初步录入
+ Phigros v1.6.11 全部收录曲难度系数录入
+ 收录曲基本信息录入

## References 参考
> v1.0.0~v1.0.1
+ Phigros1.6.11RankingScore计算器.xlsx  by [东城eastown](https://tieba.baidu.com/home/main/?un=%E4%B8%9C%E5%9F%8Eeastown)

## Open-Source 开源
> GNU General Public License v3.0

+ 商业/专利/私人 使用
+ 二次分发
+ 进行修改
>+ 二次分发必须包括版权申明与此协议
>+ 必须标注于何处修改
>+ 二次分发必须以相同协议
