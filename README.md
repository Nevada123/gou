#班级:20级3班 姓名:高永康 学号:2020012193  
##***我对信息素养实践课程的认识：***  
&emsp;不知不觉学习信息素养已将近三个月了，仔细回想学到了很多也遗漏了很多。但是一路学来我很开心，老师也很幽默。除了有时候讲的很快以外，一节课上下来很开心，收获也很多。在我看来，信息素养实践课程的内容比较基础，但是很实用。通过学习，我们掌握了cmd命令，Markdown语法，Guthub的使用与命令，XMind的使用以及一些电脑的基本操作，我也坚信这些技能必会渗透到我未来的生活之中，成为橙白人的必备素养。另外我认为该课程注重实践，万万不能只停留到听懂这一步，要学会学以致用，课下积极探索，积极练习。  
###插入超链接  
[这里是我要显示的网页的地址]  
(http://www.4399.com/)  
###插入代码块  
```
import random
count=1
right=0
o = []
p = []
q = []
r = []
l = []
a = ['+','-','*','/']
while count<11:
    b = random.randint(1,10)
    d = random.randint(1,10)
    c = random.choice(a)
    print("第%s题：%s%s%s="%(count,b,c,d),end="")
    if c=='/':
      e = float(input(""))
    else:
        e = int(input(""))
    if c=='+':
        f = b+d
    elif c=='-':
        f = b-d
    elif c=='*':
        f = b*d
    elif c=='/':
        f = round(b/d,2)
    count+=1
    o.append(b)
    p.append(c)
    q.append(d)
    r.append(e)
    l.append(f)
print("答题完毕，您的答题结果为:")
for i in range(0,10):
 if r[i]==l[i]:
   print("第"+str(i+1)+"题"+":"+str(o[i])+str(p[i])+str(q[i])+"="+str(r[i])+" "+"正确")
   right+=1
 else:
     print("第"+str(i+1)+"题"+":"+str(o[i])+str(p[i])+str(q[i])+"="+str(r[i])+" "+"正确答案为"+str(l[i]))
right1=right*10
print("您本次测试最终得分为%s分"%right1)
```
###插入表格  
|章节|名称|课时|课件|
|:-:|:-|-:|:-:|
|第一章|虚拟机|2|[下载](http://www.4399.com/)|
|第二章|计算机基础操作|2|[下载](http://www.4399.com/)|
|第三章|cmd命令|4|[下载](http://www.4399.com/)|
|第四章|Markdown语法|4|[下载](http://www.4399.com/)|
|第五章|Guthub的使用与命令|4|[下载](http://www.4399.com/)|
|第六章|XMind的使用|2|[下载](http://www.4399.com/)|
###列表  
+ 虚拟机
+ 计算机基础操作
+ cmd命令
+ Markdown语法
+ Guthub的使用与命令
+ XMind的使用