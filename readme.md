本项目修改自https://github.com/arcturus-script/bilibili code_lite.zip为精简版的代码压缩包 只保留最基本的功能 去除push

## BiliBili(云函数版)

### 实现功能

- [x] 获取用户信息
- [x] 直播签到
- [x] 漫画签到
- [x] 投币
- [x] 分享视频
- [x] 每日看视频
- [x] 多账户支持
- [x] 自动兑换银瓜子
- [ ] 大会员积分签到(等我有大会员了再搞(╹ڡ╹ ))

### 步骤

注意把子模块也一起下载

```bash
git clone --recursive https://github.com/arcturus-script/bilibili.git
```

直接配置 config.py 即可, 入口改为 index.main
