## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Mar  5 07:41:38 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 00:48:50 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 00:49:03 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 00:38:19 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 00:42:22 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 00:41:08 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 00:49:35 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 00:48:32 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 00:49:51 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 00:48:39 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 00:47:56 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 00:53:42 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 00:51:44 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 00:49:40 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 00:50:13 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 00:48:57 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 00:50:30 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 00:48:09 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 00:54:12 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 00:52:15 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 00:50:55 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 00:50:30 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 00:50:29 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 00:50:25 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 00:49:51 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 00:55:03 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 00:54:05 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 00:57:35 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 00:51:40 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 00:50:45 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 00:50:46 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 00:49:42 UTC 2025
- Auto Sign-in run successful on Sun Apr  6 00:54:41 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 00:52:58 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 00:51:00 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 00:51:22 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 00:51:16 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 00:51:44 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 00:50:48 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 02:21:28 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 00:54:29 UTC 2025
- Auto Sign-in run successful on Tue Apr 15 00:52:52 UTC 2025
- Auto Sign-in run successful on Wed Apr 16 00:52:43 UTC 2025
- Auto Sign-in run successful on Thu Apr 17 00:51:52 UTC 2025
- Auto Sign-in run successful on Sat Apr 19 00:49:20 UTC 2025
- Auto Sign-in run successful on Sun Apr 20 00:56:20 UTC 2025
- Auto Sign-in run successful on Mon Apr 21 00:55:11 UTC 2025
- Auto Sign-in run successful on Tue Apr 22 00:52:16 UTC 2025
- Auto Sign-in run successful on Wed Apr 23 00:52:35 UTC 2025
- Auto Sign-in run successful on Thu Apr 24 00:52:50 UTC 2025
- Auto Sign-in run successful on Fri Apr 25 00:52:47 UTC 2025
- Auto Sign-in run successful on Sat Apr 26 00:51:05 UTC 2025
- Auto Sign-in run successful on Sun Apr 27 00:56:15 UTC 2025
- Auto Sign-in run successful on Mon Apr 28 00:54:39 UTC 2025
- Auto Sign-in run successful on Tue Apr 29 00:52:55 UTC 2025
- Auto Sign-in run successful on Wed Apr 30 00:53:15 UTC 2025
- Auto Sign-in run successful on Thu May  1 00:58:30 UTC 2025
- Auto Sign-in run successful on Fri May  2 00:53:22 UTC 2025
- Auto Sign-in run successful on Sat May  3 00:51:54 UTC 2025
- Auto Sign-in run successful on Sun May  4 00:58:41 UTC 2025
- Auto Sign-in run successful on Mon May  5 00:56:18 UTC 2025
- Auto Sign-in run successful on Tue May  6 00:53:48 UTC 2025
- Auto Sign-in run successful on Wed May  7 00:53:54 UTC 2025
- Auto Sign-in run successful on Thu May  8 00:54:21 UTC 2025
- Auto Sign-in run successful on Fri May  9 00:53:59 UTC 2025
- Auto Sign-in run successful on Sat May 10 00:51:24 UTC 2025
- Auto Sign-in run successful on Sun May 11 00:57:32 UTC 2025
- Auto Sign-in run successful on Mon May 12 00:56:30 UTC 2025
- Auto Sign-in run successful on Tue May 13 00:54:28 UTC 2025
- Auto Sign-in run successful on Wed May 14 00:53:56 UTC 2025
- Auto Sign-in run successful on Thu May 15 00:53:04 UTC 2025
- Auto Sign-in run successful on Fri May 16 00:54:52 UTC 2025
- Auto Sign-in run successful on Sat May 17 00:53:07 UTC 2025
- Auto Sign-in run successful on Sun May 18 00:58:14 UTC 2025
- Auto Sign-in run successful on Mon May 19 00:57:21 UTC 2025
- Auto Sign-in run successful on Tue May 20 00:55:37 UTC 2025
- Auto Sign-in run successful on Wed May 21 00:55:00 UTC 2025
- Auto Sign-in run successful on Thu May 22 00:54:37 UTC 2025
- Auto Sign-in run successful on Fri May 23 00:54:32 UTC 2025
- Auto Sign-in run successful on Sat May 24 00:52:14 UTC 2025
- Auto Sign-in run successful on Sun May 25 00:59:42 UTC 2025
- Auto Sign-in run successful on Mon May 26 00:56:15 UTC 2025
- Auto Sign-in run successful on Tue May 27 00:53:41 UTC 2025
- Auto Sign-in run successful on Wed May 28 00:55:09 UTC 2025
- Auto Sign-in run successful on Thu May 29 00:55:10 UTC 2025
- Auto Sign-in run successful on Fri May 30 00:54:30 UTC 2025
- Auto Sign-in run successful on Sat May 31 00:53:38 UTC 2025
- Auto Sign-in run successful on Sun Jun  1 01:06:04 UTC 2025
- Auto Sign-in run successful on Mon Jun  2 00:57:45 UTC 2025
- Auto Sign-in run successful on Tue Jun  3 00:57:24 UTC 2025
- Auto Sign-in run successful on Wed Jun  4 00:55:53 UTC 2025
- Auto Sign-in run successful on Thu Jun  5 00:55:12 UTC 2025
- Auto Sign-in run successful on Fri Jun  6 00:54:49 UTC 2025
- Auto Sign-in run successful on Sat Jun  7 00:54:41 UTC 2025
- Auto Sign-in run successful on Sun Jun  8 01:00:48 UTC 2025
- Auto Sign-in run successful on Mon Jun  9 00:58:40 UTC 2025
- Auto Sign-in run successful on Tue Jun 10 00:56:06 UTC 2025
- Auto Sign-in run successful on Wed Jun 11 00:55:51 UTC 2025
- Auto Sign-in run successful on Thu Jun 12 00:55:17 UTC 2025
- Auto Sign-in run successful on Fri Jun 13 00:55:55 UTC 2025
- Auto Sign-in run successful on Sat Jun 14 00:53:41 UTC 2025
- Auto Sign-in run successful on Sun Jun 15 01:01:36 UTC 2025
- Auto Sign-in run successful on Mon Jun 16 00:57:50 UTC 2025
- Auto Sign-in run successful on Tue Jun 17 00:55:51 UTC 2025
- Auto Sign-in run successful on Wed Jun 18 00:56:04 UTC 2025
- Auto Sign-in run successful on Thu Jun 19 00:56:04 UTC 2025
- Auto Sign-in run successful on Fri Jun 20 00:55:40 UTC 2025
- Auto Sign-in run successful on Sat Jun 21 00:54:49 UTC 2025
- Auto Sign-in run successful on Sun Jun 22 01:01:22 UTC 2025
- Auto Sign-in run successful on Mon Jun 23 00:59:35 UTC 2025
- Auto Sign-in run successful on Tue Jun 24 00:56:24 UTC 2025
- Auto Sign-in run successful on Wed Jun 25 00:56:54 UTC 2025
- Auto Sign-in run successful on Thu Jun 26 00:56:07 UTC 2025
- Auto Sign-in run successful on Fri Jun 27 00:56:52 UTC 2025
- Auto Sign-in run successful on Sat Jun 28 00:54:36 UTC 2025
- Auto Sign-in run successful on Sun Jun 29 01:02:33 UTC 2025
- Auto Sign-in run successful on Mon Jun 30 00:59:53 UTC 2025
- Auto Sign-in run successful on Tue Jul  1 01:03:04 UTC 2025
- Auto Sign-in run successful on Wed Jul  2 00:56:40 UTC 2025
- Auto Sign-in run successful on Thu Jul  3 00:56:31 UTC 2025
- Auto Sign-in run successful on Fri Jul  4 00:56:05 UTC 2025
- Auto Sign-in run successful on Sat Jul  5 00:54:06 UTC 2025
- Auto Sign-in run successful on Sun Jul  6 01:01:36 UTC 2025
- Auto Sign-in run successful on Mon Jul  7 01:00:40 UTC 2025
