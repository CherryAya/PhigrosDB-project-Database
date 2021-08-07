# Grade 表
> 该表记录现版本得分评级信息
> location: main>Grade

### 字段
| Key | DataType | Nullable | isPrimaryKey | isAutoincrement | p.s. |
|:--|:-:|:-:|:-:|:-:|:--|
| id | integer | not null | true | true | 主键 |
| Symbol | text | -- | false | -- | 得分评级（符号） |
| Fraction | text | -- | false | -- | 得分区间 |

### 值
<table><tr><th>id</th><th>Symbol</th><th>Fraction</th><tr><tr><td>1</td><td>φ</td><td>100000000</td></tr><tr><td>2</td><td>V</td><td>9600000~999999</td></tr><tr><td>3</td><td>S</td><td>920000~959999</td></tr><tr><td>4</td><td>A</td><td>880000~919999</td></tr><tr><td>5</td><td>B</td><td>820000~879999</td></tr><tr><td>6</td><td>C</td><td>700000~819999</td></tr><tr><td>7</td><td>False</td><td>0~699999</td></tr></table>