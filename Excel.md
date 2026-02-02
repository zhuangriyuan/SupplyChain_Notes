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
Median - 中位数（把数据排好序，站在最中间的那个）
Mode - 众数（出现次数最多）

__TRANSPOSE__ 将横表转为竖表 or vice versa

1. __字符串__ 相加 用 __&__ 连接
2. __TEXTJOIN()__
3. __<>__ 不等于 __!=__
4. __Fixed Reference__ 在行和列前面加$ __快捷键F4__
5. 如果想比较 __True和False__，可以相加，一个是1一个是0
6. __AND()__ 比较True False
7. __COUNT()__ - count number of cells
8. __COUNTA()__ - count number of cells that are not empty
9. __COUNTIF()__ - count number of cells if it meets condition ex, =COUNTIF(C3:C12,">="&L15) 右边参数必须“拼接字符串”
10. __COUNTIFS()__ - 多个count条件比较 =COUNTIFS(E3:E12,">10000",F3:F12,"<7")
11. __IFS()__ 多个if结合
12. __SUMIF()__ SUMIF(country list, country, sum range list), so it will sum the total in sum range list for the country that is in country list
13. __Quartile.INC()__（四分位数）
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
14. __UNIQUE()__ - 找不重复的数据
15. __SUMPRODUCT()__ -两组数据对应位置相乘，再把结果加起来
___
16. __VLOOKUP(lookup value, table array, col index, true/false)__
> 在表格的最左列找一个值，找到后，从右边某一列把对应结果拿出来
> lookup_value（你要找什么） 必须在表格最左列
> table_array（去哪里找）
> col_index_num（拿第几列）
> range_lookup（是否精确匹配）
> 只会return第一个找到的值
17. __HLOOKUP()__
> vlookup的h版本，和vlookup一样已经淘汰
18. __XLOOKUP()__
> lookup value, lookup array, return array

19. __RIGHT()__ - 切割文字，从右往左
20. __FIND__ - return starting position of one text string in another text string
21. __MID()__ - 切割文字, 有starting position和length
22. __MONTH()__ __DAY()__ __YEAR()__ __DATE()__ 提取日期
23. __DATEDIF()__ DATEDIF(start_date, end_date, unit)
> UNIT
> "Y"	完整年数	不看未满一年的部分
> "M"	完整月数	不看未满一月
> "D"	总天数	最直观
> "YM"	剩余月	去掉整年后的月
> "YD"	剩余天	去掉整年后的天
24. __HOUR()__ __MINUTE()__ __SECOND()__ __TIME()__ 提取时间
25. __TEXT()__ TEXT(value, format_text) HH:MM AM/PM