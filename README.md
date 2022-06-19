# notes

#### 介绍
notes库，存储笔记等相关资料，起到备份作用

#### 100M大文件上传步骤
1.下载地址:https://git-lfs.github.com/
2.下载后安装即可
3.在本地库中使用 git lfs help 命令就会得到提示
     1. Setup Git LFS on your system. You only have to do this once per
        repository per machine:

            git lfs install

     2. Choose the type of files you want to track, for examples all ISO
        images, with git lfs track:

            git lfs track "*.iso"

     3. The above stores this information in gitattributes(5) files, so
        that file need to be added to the repository:

            git add .gitattributes

     4. Commit, push and work with the files normally:

            git add file.iso
            git commit -m "Add disk image"
            git push

4.根据需求按1234步来，让lfs管理你的大文件(值得注意的是,如果你是普通用户gitee仍然不支持100M上传，不过github支持)
