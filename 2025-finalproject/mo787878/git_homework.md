# Git 应用

## 第一题

### 方式一：

> git reset --hard HEAD

### 方式二：

> git reset HEAD readme.txt
>
> git checkout -- readme.txt

![第一题的图片](task1.png)



## 第二题

### 方式一：（修改历史）

> git reset --hard commit_id

![第二题方式一](task2_1.png)

### 方式二：（不修改历史）

> git revert commit_id

![方式二图片](task2_2.png)

### 方式三：（不修改历史）

> git checkout commit_id --file

![方式三图片](task2_3.png)





## 第三题

### 方式一：

> git rebase

![图1](task3_1.1.png)

![图2](task3_1.2.png)

### 方式二：

> git cherry-pick

![图1](task3_2.1.png)

![图2](task3_2.2.png)









