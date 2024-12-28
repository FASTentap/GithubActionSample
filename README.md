## 原作者： https://github.com/tech-shrimp/GithubActionSample

## 签到薅羊毛
Fork本项目
网页上打开：www.jd.com/ 再按F12打开控制台，再点击切换模式，切换到手机模式，刷新一下页面。如图所示
![image](https://github.com/tech-shrimp/GithubActionSample/assets/154193368/44d01795-8c1e-4a56-bb0e-a36f74062dcb)
在网络->m.jd.com找到Cookie

<img width="935" alt="image" src="https://github.com/tech-shrimp/GithubActionSample/assets/154193368/97139add-a410-4e73-82d3-055c8136ed57">

将其填入  Settings  ----> Secrets and variables ---> Actions --> New repository secret -->新增JD_COOKIE
<img width="685" alt="image" src="https://github.com/tech-shrimp/GithubActionSample/assets/154193368/e28ee156-642a-4c25-94ff-d42af072aa15">

进入自己项目的Action  ----> 签到薅羊毛 ---> daily_sign.yml --> 修改cron表达式的执行时间
