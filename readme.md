本代码是对keep跑步截图记录的伪造，其中代码展示的是3月的随机15次的跑步记录。

本代码可以对其进行以下修改：
```python
#在main.py中的24行
text = "3月{}日".format(i)
#在main.py中的42行
img.save('./3月/{}.jpg'.format(i))
#在main.py中的45行
image_dir = '3月'  # 替换为你的图片文件夹路径
```
这里可以对月份进行修改，由于我设置的随机日期在1到28之间，故无需考虑2月这个特殊情况，注意提前新建号文件夹并将0.jpg放入其中！！！

```python
#在main.py中的80行
new_img.save('combined_image.jpg')
```
这里可以对最后输出的图片名进行修改

最后的最后，若果想要修改随机数生成区间问题请到test.py中修改
# keep-
