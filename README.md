## 上马自动签到 [![Run Auto Sign](https://github.com/angyyang/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/angyyang/shangma_auto_sign/actions/workflows/auto-sign.yaml)

## 上马2025年6月改版后原有代码无法自动签到了，重新分析新的签到接口后对代码做了改动，需要重新配置系统参数来签到，此代码可运行。具体使用方式待更新。 20250707

## 具体使用方式已更新。 20250708

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. //在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret
3. 在Repo的Setting页面，Secrets and Variables添加如下actions变量：登陆信息`SM_LOGIN`和上马用户id：`SM_USER_ID`
    登陆信息获取方式：登陆上马网： https://static.shang-ma.com/web/login/index.html 找到login的请求，把request payload整个复制出来放入SM_LOGIN
   ![image](https://github.com/user-attachments/assets/537f5ed0-f6ba-48fb-972a-2a3d19ded875)
   找到一个纯数字的请求，把这个数字复制出来放入SM_USER_ID
   ![image](https://github.com/user-attachments/assets/463f04e8-f6e6-419d-876a-de9211ee594d)




5. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Jul 23 03:49:42 UTC 2025
- Auto Sign-in run successful on Thu Jul 24 01:56:54 UTC 2025
- Auto Sign-in run successful on Fri Jul 25 01:56:38 UTC 2025
- Auto Sign-in run successful on Sat Jul 26 01:53:19 UTC 2025
- Auto Sign-in run successful on Sun Jul 27 02:06:10 UTC 2025
- Auto Sign-in run successful on Mon Jul 28 02:03:49 UTC 2025
- Auto Sign-in run successful on Tue Jul 29 02:09:17 UTC 2025
- Auto Sign-in run successful on Wed Jul 30 01:59:48 UTC 2025
- Auto Sign-in run successful on Thu Jul 31 01:59:22 UTC 2025
- Auto Sign-in run successful on Fri Aug  1 02:09:24 UTC 2025
- Auto Sign-in run successful on Sat Aug  2 01:53:37 UTC 2025
- Auto Sign-in run successful on Sun Aug  3 02:07:45 UTC 2025
- Auto Sign-in run successful on Mon Aug  4 02:07:50 UTC 2025
- Auto Sign-in run successful on Tue Aug  5 02:02:33 UTC 2025
- Auto Sign-in run successful on Wed Aug  6 02:00:30 UTC 2025
- Auto Sign-in run successful on Thu Aug  7 02:01:06 UTC 2025
- Auto Sign-in run successful on Fri Aug  8 02:00:21 UTC 2025
- Auto Sign-in run successful on Sat Aug  9 01:49:43 UTC 2025
- Auto Sign-in run successful on Sun Aug 10 02:04:08 UTC 2025
- Auto Sign-in run successful on Mon Aug 11 02:00:40 UTC 2025
- Auto Sign-in run successful on Tue Aug 12 01:48:50 UTC 2025
- Auto Sign-in run successful on Wed Aug 13 01:51:01 UTC 2025
- Auto Sign-in run successful on Thu Aug 14 01:51:14 UTC 2025
- Auto Sign-in run successful on Fri Aug 15 01:51:53 UTC 2025
- Auto Sign-in run successful on Sat Aug 16 01:46:17 UTC 2025
- Auto Sign-in run successful on Sun Aug 17 01:57:18 UTC 2025
- Auto Sign-in run successful on Mon Aug 18 01:58:01 UTC 2025
- Auto Sign-in run successful on Tue Aug 19 01:45:26 UTC 2025
- Auto Sign-in run successful on Wed Aug 20 01:43:56 UTC 2025
- Auto Sign-in run successful on Thu Aug 21 01:42:55 UTC 2025
- Auto Sign-in run successful on Fri Aug 22 01:43:24 UTC 2025
- Auto Sign-in run successful on Sat Aug 23 01:40:01 UTC 2025
- Auto Sign-in run successful on Sun Aug 24 01:53:06 UTC 2025
- Auto Sign-in run successful on Mon Aug 25 01:47:53 UTC 2025
- Auto Sign-in run successful on Tue Aug 26 01:44:10 UTC 2025
- Auto Sign-in run successful on Wed Aug 27 01:41:06 UTC 2025
- Auto Sign-in run successful on Thu Aug 28 01:40:43 UTC 2025
- Auto Sign-in run successful on Fri Aug 29 01:40:31 UTC 2025
- Auto Sign-in run successful on Sat Aug 30 01:28:00 UTC 2025
- Auto Sign-in run successful on Sun Aug 31 01:45:14 UTC 2025
- Auto Sign-in run successful on Mon Sep  1 01:54:51 UTC 2025
- Auto Sign-in run successful on Tue Sep  2 01:42:12 UTC 2025
- Auto Sign-in run successful on Wed Sep  3 01:28:02 UTC 2025
- Auto Sign-in run successful on Thu Sep  4 01:28:00 UTC 2025
- Auto Sign-in run successful on Fri Sep  5 01:38:22 UTC 2025
- Auto Sign-in run successful on Sat Sep  6 01:27:40 UTC 2025
- Auto Sign-in run successful on Sun Sep  7 01:43:21 UTC 2025
- Auto Sign-in run successful on Mon Sep  8 01:42:54 UTC 2025
- Auto Sign-in run successful on Tue Sep  9 01:39:49 UTC 2025
- Auto Sign-in run successful on Wed Sep 10 01:36:38 UTC 2025
- Auto Sign-in run successful on Thu Sep 11 01:39:01 UTC 2025
- Auto Sign-in run successful on Fri Sep 12 01:27:40 UTC 2025
- Auto Sign-in run successful on Sat Sep 13 01:23:54 UTC 2025
- Auto Sign-in run successful on Sun Sep 14 01:42:50 UTC 2025
- Auto Sign-in run successful on Mon Sep 15 01:44:25 UTC 2025
- Auto Sign-in run successful on Tue Sep 16 01:36:26 UTC 2025
- Auto Sign-in run successful on Wed Sep 17 01:36:42 UTC 2025
- Auto Sign-in run successful on Thu Sep 18 01:36:15 UTC 2025
- Auto Sign-in run successful on Fri Sep 19 01:38:56 UTC 2025
- Auto Sign-in run successful on Sat Sep 20 01:27:07 UTC 2025
- Auto Sign-in run successful on Sun Sep 21 01:45:21 UTC 2025
- Auto Sign-in run successful on Mon Sep 22 01:45:38 UTC 2025
- Auto Sign-in run successful on Tue Sep 23 01:37:06 UTC 2025
- Auto Sign-in run successful on Wed Sep 24 01:38:29 UTC 2025
- Auto Sign-in run successful on Thu Sep 25 01:38:52 UTC 2025
- Auto Sign-in run successful on Fri Sep 26 01:38:17 UTC 2025
- Auto Sign-in run successful on Sat Sep 27 01:26:52 UTC 2025
- Auto Sign-in run successful on Sun Sep 28 01:46:24 UTC 2025
- Auto Sign-in run successful on Mon Sep 29 01:41:00 UTC 2025
- Auto Sign-in run successful on Tue Sep 30 01:36:27 UTC 2025
- Auto Sign-in run successful on Wed Oct  1 01:48:05 UTC 2025
- Auto Sign-in run successful on Thu Oct  2 01:36:28 UTC 2025
- Auto Sign-in run successful on Fri Oct  3 01:36:03 UTC 2025
- Auto Sign-in run successful on Sat Oct  4 01:25:58 UTC 2025
- Auto Sign-in run successful on Sun Oct  5 01:45:42 UTC 2025
- Auto Sign-in run successful on Mon Oct  6 01:39:23 UTC 2025
- Auto Sign-in run successful on Tue Oct  7 01:37:05 UTC 2025
- Auto Sign-in run successful on Wed Oct  8 01:37:39 UTC 2025
- Auto Sign-in run successful on Thu Oct  9 01:38:07 UTC 2025
- Auto Sign-in run successful on Fri Oct 10 01:38:49 UTC 2025
- Auto Sign-in run successful on Sat Oct 11 01:27:04 UTC 2025
- Auto Sign-in run successful on Sun Oct 12 01:41:35 UTC 2025
- Auto Sign-in run successful on Mon Oct 13 01:45:01 UTC 2025
- Auto Sign-in run successful on Tue Oct 14 01:38:34 UTC 2025
- Auto Sign-in run successful on Wed Oct 15 01:41:37 UTC 2025
- Auto Sign-in run successful on Thu Oct 16 01:40:39 UTC 2025
- Auto Sign-in run successful on Fri Oct 17 01:39:41 UTC 2025
- Auto Sign-in run successful on Sat Oct 18 01:27:44 UTC 2025
- Auto Sign-in run successful on Sun Oct 19 01:50:21 UTC 2025
- Auto Sign-in run successful on Mon Oct 20 01:48:10 UTC 2025
- Auto Sign-in run successful on Tue Oct 21 01:42:33 UTC 2025
- Auto Sign-in run successful on Wed Oct 22 01:45:17 UTC 2025
- Auto Sign-in run successful on Thu Oct 23 01:41:22 UTC 2025
- Auto Sign-in run successful on Fri Oct 24 01:37:37 UTC 2025
- Auto Sign-in run successful on Sat Oct 25 01:39:00 UTC 2025
- Auto Sign-in run successful on Sun Oct 26 01:46:58 UTC 2025
- Auto Sign-in run successful on Mon Oct 27 01:50:58 UTC 2025
- Auto Sign-in run successful on Tue Oct 28 01:41:13 UTC 2025
- Auto Sign-in run successful on Wed Oct 29 01:47:41 UTC 2025
- Auto Sign-in run successful on Thu Oct 30 01:47:19 UTC 2025
- Auto Sign-in run successful on Fri Oct 31 01:43:58 UTC 2025
- Auto Sign-in run successful on Sat Nov  1 01:47:37 UTC 2025
- Auto Sign-in run successful on Sun Nov  2 01:49:12 UTC 2025
- Auto Sign-in run successful on Mon Nov  3 01:48:51 UTC 2025
- Auto Sign-in run successful on Tue Nov  4 01:44:48 UTC 2025
- Auto Sign-in run successful on Wed Nov  5 01:46:04 UTC 2025
- Auto Sign-in run successful on Thu Nov  6 01:45:49 UTC 2025
- Auto Sign-in run successful on Fri Nov  7 01:44:43 UTC 2025
- Auto Sign-in run successful on Sat Nov  8 01:39:18 UTC 2025
- Auto Sign-in run successful on Sun Nov  9 01:48:39 UTC 2025
- Auto Sign-in run successful on Mon Nov 10 01:49:42 UTC 2025
- Auto Sign-in run successful on Tue Nov 11 01:46:38 UTC 2025
- Auto Sign-in run successful on Wed Nov 12 01:45:39 UTC 2025
- Auto Sign-in run successful on Thu Nov 13 01:47:10 UTC 2025
- Auto Sign-in run successful on Fri Nov 14 01:46:44 UTC 2025
- Auto Sign-in run successful on Sat Nov 15 01:42:24 UTC 2025
- Auto Sign-in run successful on Sun Nov 16 01:51:21 UTC 2025
- Auto Sign-in run successful on Mon Nov 17 01:47:10 UTC 2025
- Auto Sign-in run successful on Tue Nov 18 01:45:34 UTC 2025
- Auto Sign-in run successful on Wed Nov 19 01:45:35 UTC 2025
- Auto Sign-in run successful on Thu Nov 20 01:44:04 UTC 2025
- Auto Sign-in run successful on Fri Nov 21 01:44:59 UTC 2025
- Auto Sign-in run successful on Sat Nov 22 01:41:26 UTC 2025
- Auto Sign-in run successful on Sun Nov 23 01:58:19 UTC 2025
- Auto Sign-in run successful on Mon Nov 24 01:53:06 UTC 2025
- Auto Sign-in run successful on Tue Nov 25 01:47:04 UTC 2025
- Auto Sign-in run successful on Wed Nov 26 01:46:47 UTC 2025
- Auto Sign-in run successful on Thu Nov 27 01:44:54 UTC 2025
- Auto Sign-in run successful on Fri Nov 28 01:44:38 UTC 2025
- Auto Sign-in run successful on Sat Nov 29 01:43:55 UTC 2025
- Auto Sign-in run successful on Sun Nov 30 01:57:15 UTC 2025
- Auto Sign-in run successful on Mon Dec  1 02:05:13 UTC 2025
- Auto Sign-in run successful on Tue Dec  2 01:48:57 UTC 2025
- Auto Sign-in run successful on Wed Dec  3 01:48:29 UTC 2025
- Auto Sign-in run successful on Thu Dec  4 01:49:39 UTC 2025
- Auto Sign-in run successful on Fri Dec  5 01:49:52 UTC 2025
- Auto Sign-in run successful on Sat Dec  6 01:43:34 UTC 2025
- Auto Sign-in run successful on Sun Dec  7 01:57:57 UTC 2025
- Auto Sign-in run successful on Mon Dec  8 01:50:17 UTC 2025
- Auto Sign-in run successful on Tue Dec  9 01:49:34 UTC 2025
- Auto Sign-in run successful on Wed Dec 10 01:51:39 UTC 2025
- Auto Sign-in run successful on Thu Dec 11 01:52:56 UTC 2025
- Auto Sign-in run successful on Fri Dec 12 01:52:07 UTC 2025
- Auto Sign-in run successful on Sat Dec 13 01:46:14 UTC 2025
- Auto Sign-in run successful on Sun Dec 14 01:58:19 UTC 2025
- Auto Sign-in run successful on Mon Dec 15 01:56:15 UTC 2025
- Auto Sign-in run successful on Tue Dec 16 01:52:56 UTC 2025
- Auto Sign-in run successful on Wed Dec 17 01:48:25 UTC 2025
- Auto Sign-in run successful on Thu Dec 18 01:48:49 UTC 2025
- Auto Sign-in run successful on Fri Dec 19 01:52:07 UTC 2025
- Auto Sign-in run successful on Sat Dec 20 01:46:14 UTC 2025
- Auto Sign-in run successful on Sun Dec 21 01:58:21 UTC 2025
- Auto Sign-in run successful on Mon Dec 22 01:57:43 UTC 2025
- Auto Sign-in run successful on Tue Dec 23 01:53:19 UTC 2025
- Auto Sign-in run successful on Wed Dec 24 01:51:33 UTC 2025
- Auto Sign-in run successful on Thu Dec 25 01:53:39 UTC 2025
- Auto Sign-in run successful on Fri Dec 26 01:52:45 UTC 2025
- Auto Sign-in run successful on Sat Dec 27 01:50:23 UTC 2025
- Auto Sign-in run successful on Sun Dec 28 02:04:01 UTC 2025
- Auto Sign-in run successful on Mon Dec 29 02:02:12 UTC 2025
- Auto Sign-in run successful on Tue Dec 30 01:53:49 UTC 2025
- Auto Sign-in run successful on Wed Dec 31 01:54:31 UTC 2025
- Auto Sign-in run successful on Thu Jan  1 02:04:29 UTC 2026
- Auto Sign-in run successful on Fri Jan  2 01:55:44 UTC 2026
- Auto Sign-in run successful on Sat Jan  3 01:49:31 UTC 2026
- Auto Sign-in run successful on Sun Jan  4 02:05:40 UTC 2026
- Auto Sign-in run successful on Mon Jan  5 02:05:24 UTC 2026
- Auto Sign-in run successful on Tue Jan  6 01:55:55 UTC 2026
- Auto Sign-in run successful on Wed Jan  7 01:55:28 UTC 2026
- Auto Sign-in run successful on Thu Jan  8 01:55:51 UTC 2026
- Auto Sign-in run successful on Fri Jan  9 01:57:12 UTC 2026
- Auto Sign-in run successful on Sat Jan 10 01:52:58 UTC 2026
- Auto Sign-in run successful on Sun Jan 11 02:05:34 UTC 2026
- Auto Sign-in run successful on Mon Jan 12 02:01:57 UTC 2026
- Auto Sign-in run successful on Tue Jan 13 01:53:38 UTC 2026
- Auto Sign-in run successful on Wed Jan 14 02:00:57 UTC 2026
- Auto Sign-in run successful on Thu Jan 15 01:55:49 UTC 2026
- Auto Sign-in run successful on Fri Jan 16 01:57:23 UTC 2026
- Auto Sign-in run successful on Sat Jan 17 01:51:34 UTC 2026
- Auto Sign-in run successful on Sun Jan 18 02:04:10 UTC 2026
- Auto Sign-in run successful on Mon Jan 19 02:02:19 UTC 2026
- Auto Sign-in run successful on Tue Jan 20 01:57:27 UTC 2026
- Auto Sign-in run successful on Wed Jan 21 01:59:47 UTC 2026
- Auto Sign-in run successful on Thu Jan 22 02:00:53 UTC 2026
- Auto Sign-in run successful on Fri Jan 23 01:56:48 UTC 2026
- Auto Sign-in run successful on Sat Jan 24 01:53:26 UTC 2026
- Auto Sign-in run successful on Sun Jan 25 02:07:31 UTC 2026
- Auto Sign-in run successful on Mon Jan 26 02:06:49 UTC 2026
- Auto Sign-in run successful on Tue Jan 27 02:03:39 UTC 2026
- Auto Sign-in run successful on Wed Jan 28 01:59:28 UTC 2026
- Auto Sign-in run successful on Thu Jan 29 02:21:24 UTC 2026
- Auto Sign-in run successful on Fri Jan 30 02:21:19 UTC 2026
- Auto Sign-in run successful on Sat Jan 31 02:09:57 UTC 2026
- Auto Sign-in run successful on Sun Feb  1 02:39:53 UTC 2026
- Auto Sign-in run successful on Mon Feb  2 02:30:24 UTC 2026
- Auto Sign-in run successful on Tue Feb  3 02:28:00 UTC 2026
- Auto Sign-in run successful on Wed Feb  4 02:22:13 UTC 2026
- Auto Sign-in run successful on Thu Feb  5 02:23:59 UTC 2026
- Auto Sign-in run successful on Fri Feb  6 02:23:44 UTC 2026
- Auto Sign-in run successful on Sat Feb  7 02:12:37 UTC 2026
- Auto Sign-in run successful on Sun Feb  8 02:46:09 UTC 2026
- Auto Sign-in run successful on Mon Feb  9 02:31:41 UTC 2026
- Auto Sign-in run successful on Tue Feb 10 02:39:44 UTC 2026
- Auto Sign-in run successful on Wed Feb 11 02:37:08 UTC 2026
- Auto Sign-in run successful on Thu Feb 12 02:31:39 UTC 2026
- Auto Sign-in run successful on Fri Feb 13 02:33:08 UTC 2026
- Auto Sign-in run successful on Sat Feb 14 02:21:22 UTC 2026
- Auto Sign-in run successful on Sun Feb 15 02:33:13 UTC 2026
- Auto Sign-in run successful on Mon Feb 16 02:29:39 UTC 2026
- Auto Sign-in run successful on Tue Feb 17 02:26:14 UTC 2026
- Auto Sign-in run successful on Wed Feb 18 02:29:36 UTC 2026
- Auto Sign-in run successful on Thu Feb 19 02:28:36 UTC 2026
- Auto Sign-in run successful on Fri Feb 20 02:24:20 UTC 2026
- Auto Sign-in run successful on Sat Feb 21 02:11:07 UTC 2026
- Auto Sign-in run successful on Sun Feb 22 02:29:11 UTC 2026
- Auto Sign-in run successful on Mon Feb 23 02:30:06 UTC 2026
- Auto Sign-in run successful on Tue Feb 24 02:26:21 UTC 2026
- Auto Sign-in run successful on Wed Feb 25 02:27:37 UTC 2026
- Auto Sign-in run successful on Thu Feb 26 02:23:49 UTC 2026
- Auto Sign-in run successful on Fri Feb 27 02:22:46 UTC 2026
- Auto Sign-in run successful on Sat Feb 28 02:05:35 UTC 2026
- Auto Sign-in run successful on Sun Mar  1 02:35:30 UTC 2026
- Auto Sign-in run successful on Mon Mar  2 02:25:16 UTC 2026
- Auto Sign-in run successful on Tue Mar  3 02:27:49 UTC 2026
- Auto Sign-in run successful on Wed Mar  4 02:21:43 UTC 2026
- Auto Sign-in run successful on Thu Mar  5 02:24:24 UTC 2026
- Auto Sign-in run successful on Fri Mar  6 02:22:24 UTC 2026
- Auto Sign-in run successful on Sat Mar  7 02:08:58 UTC 2026
- Auto Sign-in run successful on Sun Mar  8 02:26:51 UTC 2026
- Auto Sign-in run successful on Mon Mar  9 02:27:51 UTC 2026
- Auto Sign-in run successful on Tue Mar 10 02:13:13 UTC 2026
