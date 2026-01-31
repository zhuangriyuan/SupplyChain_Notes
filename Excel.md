# EXCEL TIPS

## 基础
1. 双击可以fill整列
2. Home tab中可以选数据类型 比如日期date
3. Home tab中有 __Sort&Filter__ 可以给title加filter
4. Page Layout tab中可以 __取消Gridlines__ ，如果需要在特定区域增加，可以在Home tab中font size下的田子格选择样式
5. View tab中可以用Freeze Panes来 __冻结最上行__
6. __ctrl+shift+⬇__  __ctrl+shift+➡__ 可以选择全部行列
7. 右键sheet可以move or copy到别的workbook
   

## 公式
1. __字符串__ 相加 用 __&__ 连接
2. __Fixed Reference__ 在行和列前面加$ __快捷键F4__
3. 如果想比较 __True和False__，可以相加，一个是1一个是0
4. __AND()__ 比较True False
5. __COUNT()__ - count number of cells
6. __COUNTA()__ - count number of cells that are not empty
7. __COUNTIF()__ - count number of cells if it meets condition ex, =COUNTIF(C3:C12,">="&L15) 右边参数必须“拼接字符串”
8. __COUNTIFS()__ - 多个count条件比较 =COUNTIFS(E3:E12,">10000",F3:F12,"<7")
9. __IFS()__ 多个if结合
10. __SUMIF()__ SUMIF(country list, country, sum range list), so it will sum the total in sum range list for the country that is in country list
11. __Quartile.INC()__（四分位数）
> 把一堆数排好队，然后每 25% 切一刀，看刀切在什么位置
> 第一步：排序 从小到大 3, 4, 6, 7, 8, 9, 10, 11, 13, 14, 18, 20
> 第二步：找“中间”（Q2）一共 12 个数 中间是第 6 和第 7 个 (Q2 = (9 + 10) / 2 = 9.5)
> 第三步：把数据分成左右两半
> 左半（较小的 50%）：3, 4, 6, 7, 8, 9
> 右半（较大的 50%）：10, 11, 13, 14, 18, 20
> 左边再找一个“中间”（Q1）Q1 = (6 + 7) / 2 = 6.5
> 右边再找一个“中间”（Q3）Q3 = (13 + 14) / 2 = 13.5
> 
| 指标 | 在说什么         |
| -- | ------------ |
| Q1 | 较小那一半里“中间”的数 |
| Q2 | 全部数据的中间      |
| Q3 | 较大那一半里“中间”的数 |

> 50%的数据在Q1和Q3之间
12. __MODE()__ - 重复最多次数的数据
13. __RANK()__ - 排序