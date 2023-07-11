# CTF-Writeups-Archives-CN

**[ctf-writeups-archives-cn.vercel.app](https://ctf-writeups-archives-cn.vercel.app/)**

**不定期更新，立志于收集大陆范围内各个比赛的优质Writeup**

## 关于此仓库的实现方式
- [Vercel-Github Action与Vercel Cli共同执行](https://vercel.com/guides/how-can-i-use-github-actions-with-vercel)
本质上就是利用Github Action，初始化node & python双基础环境，然后配置mkdocs & vercel两个cli工具，然后编译完，通过vercel的三个token实现将编译后的静态网页数据推送到vercel站点