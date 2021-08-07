# PhigrosDB-project
将音游Phigros的收录曲以及难度定数整合为数据库

## 数据库结构

> sqlite <br>
> location: ./sqlite/PhigrosDB-1.0.0-1.6.11.db

    main    // 数据库
        |—— Info                     // 关于
        |—— Overview                // 收录曲总览
        |—— Difficulty             // 难度评级
        |—— Grade                  // 得分评级
        |—— ChapterList         // 章节列表
        |—— Chapter-Legacy      // 章节Legacy
        |—— Chapter-Four      // 章节四 管道迷宫
        |—— Chapter-Five       // 章节五 霓虹灯牌
        |—— Chapter-Six         // 章节六 方舟蜃景
        |—— Side-story-One      // 支线章节一 忘忧宫
        |—— Chapter-Ex-One      // 额外章节一 Muse Dash 精选集
        |—— Chapter-Ex-Two      // 额外章节二 WAVEAT 精选集
        |—— Chapter-Ex-Three    // 额外章节三 GOOD 精选集
        |—— Chapter-Ex-Four     // 额外章节四 HyuN 精选集
        |—— Chapter-Ex-Five     // 额外章节五 Rising Sun Traxx 精选集
        |—— Single                // 单曲 精选集
