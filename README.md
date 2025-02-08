# NBAStatsCrawler

爬取espn中NBA比赛数据,包括主队，客队，比分情况，球队数据统计，球员数据统计，比赛概览，以及比赛过程。

## 示例

## 📊 比赛信息
**比赛 ID:** 401705297
**主队:** Los Angeles Lakers  
**客队:** Golden State Warriors  
**比分:** Los Angeles Lakers 120 - Golden State Warriors 112

## 🏀 球员统计
| 球队 | 球员 | 号码 | 位置 | 时间 | 得分 | 助攻 | 篮板 |
|------|------|------|------|------|------|------|------|
| Los Angeles Lakers | LeBron James | 23 | SF | 38:12 | 30 | 8 | 10 |
| Los Angeles Lakers | Anthony Davis | 3 | PF | 36:45 | 25 | 5 | 12 |
| Golden State | Stephen Curry | 30 | PG | 40:10 | 35 | 6 | 5 |

## 📜 比赛摘要
湖人队在主场以 120-112 击败勇士，詹姆斯砍下 30 分 10 板 8 助...

## 🎭 比赛过程（完整）
- **[1st - 10:25]** Curry 投中三分，勇士 3-0
- **[1st - 9:50]** 詹姆斯快攻扣篮，湖人 2-3


## 使用方式

```
node espn_scraper.js
```