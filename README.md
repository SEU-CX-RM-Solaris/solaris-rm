# 天钺 SOLARIS · SEU CXXY RoboMaster

> ⚠️ **临时镜像站点**：本仓库为东南大学成贤学院天钺（Solaris）机甲大师战队的临时官网镜像，部署在 GitHub Pages 上。正式官网待搭建，内容以本镜像为准。

**在线访问**：<https://hortonwen.github.io/solaris-rm/>

**战队**：东南大学成贤学院 · 天钺（Solaris）RoboMaster 战队
**中文名**：天钺
**英文名**：Solaris
**口号**：秣陵形胜，共赴千山
**学院**：SEU CXXY（Southeast University Chengxian College）

---

## 关于天钺 · Solaris

天钺（Solaris）是东南大学成贤学院的 RoboMaster 机甲大师战队：中文名「天钺」，英文名「Solaris」（源自古拉丁语"太阳"）。我们从南京出发，以太阳为名、以"钺"为志，把机械、嵌入式、视觉、算法和运营拧成一股绳——在赛场上自研机器人，在弹丸与装甲之间找工程的答案。

- **赛事体系**：RoboMaster（RMUC 超级对抗赛 / RMUL 高校联盟赛 / RMUT 技术挑战赛）
- **技术栈**：机械结构、嵌入式控制、机器视觉、自瞄、决策算法、通信、运营宣发
- **招新方向**：机械 / 电控 / 嵌入式 / 视觉算法 / 运营宣发

## 27 赛季目标

- **首站赛事**：[RMUL 高校联盟赛 · 步兵 1v1](https://www.robomaster.com/zh-CN/robo/college-league)
- **机械基线**：采用 [沈阳理工大学 Ambition 战队](https://www.sylu.edu.cn/info/1004/25520.htm) 开源的
  [全向轮中供步兵机械方案](https://bbs-web-static.robomaster.com/c100d9800422437a983d742915cf9ece1749118466361/RM2025-%E5%85%A8%E5%90%91%E4%B8%AD%E4%BE%9B%E6%AD%A5%E5%85%B5%E6%9C%BA%E6%A2%B0%E6%96%B9%E6%A1%88%20%E6%B2%88%E9%98%B3%E7%90%86%E5%B7%A5%E5%A4%A7%E5%AD%A6%20Ambition.pdf)，
  在此基础上做适配与二次开发
- **参考**：[RoboMaster 规则/资料中心](https://bbs.robomaster.com/wiki/20204847) · [赛事公告](https://www.robomaster.com/zh-CN/resource/announcement/competition)

---

## 关联项目

### [rm-open-source-leaderboard](https://github.com/HortonWen/rm-open-source-leaderboard)

机甲大师（RoboMaster）开源资源目录，由东南大学成贤学院机甲大师战队整理。汇总各战队、个人开发者在 GitHub、Gitee 与 RoboMaster 论坛开源专栏的代码、图纸与项目，并收录 DJI 官方及第三方公司的文档与 SDK。

- **在线目录**：<https://hortonwen.github.io/rm-open-source-leaderboard/>
- **分类**：官方资源 / 第三方公司 / 社区框架与工具 / 机械图纸 / 战队开源 / 个人开源 / 论坛开源帖
- **数据口径**：分类目录，已取消排名机制，不对战队做比较或打分

---

## 技术栈

- 纯静态 HTML + CSS + JavaScript，无框架依赖
- 部署在 GitHub Pages（`main` 分支根目录）
- 响应式布局，适配桌面与移动端

## 本地开发

```bash
git clone https://github.com/HortonWen/solaris-rm.git
cd solaris-rm
# 直接用浏览器打开 index.html，或起任意静态服务器
python -m http.server 8000
```

## License

内容以介绍与招新为目的。图片版权归原作者所有；代码采用 MIT License。

---

秣陵形胜，共赴千山 · Built with passion in Nanjing
