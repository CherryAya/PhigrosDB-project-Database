# Difficulty 表
> 该表记录现版本难度评级 <br>
> location: main>difficulty

### 字段
| Key | DataType | Nullable | isPrimaryKey | isAutoincrement | p.s. |
|:--|:-:|:-:|:-:|:-:|:--|
| id | integer | not null | true | true | 主键 |
| Grade | text | -- | false | -- | 难度 |
| Lv | text | -- | false | -- | 定数区间 |
| FullName | text | -- | false | -- | 难度全称 |

### 值
<table><tr><th>id</th><th>Grade</th><th>Lv</th><th>FullName</th><tr><tr><td>1</td><td>EZ</td><td>1~7</td><td>Easy</td></tr><tr><td>2</td><td>HD</td><td>3~12</td><td>Hard</td></tr><tr><td>3</td><td>IN</td><td>7~15</td><td>Insane</td></tr><tr><td>4</td><td>AT</td><td>14~16</td><td>Another</td></tr><tr><td>5</td><td>Legacy</td><td>12~15</td><td>Legacy</td></tr><tr><td>6</td><td>SP</td><td>?</td><td>Special</td></tr></table>