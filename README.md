Idea本地工程上传github步骤：
一、idea配置git
1、打开Preference– Version Control，下拉选择Github，填写Host、Login和Password，然后Test是否成功。
2、选择git，指定Git路径后，Test测试功能是否正常。

二、项目提交到缓冲区
1、创建本地仓库，VCS-->>Import into Version Control-->>Create Git Repository
2、提交代码到git，src-->git-->add-->commit

三、项目提交到GitHub
1、GitHub上创建远程仓库
2、本地配置远程仓库，并将本地暂存区代码提交到github
*进入本地仓库目录
*git remote add origin git@github.com:username/projectname
*git push -u origin master
