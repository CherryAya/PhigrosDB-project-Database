# Info 表
> 该表记录现数据库版本信息 <br>
> location: main>Info

### 字段
| Key | DataType | Nullable | isPrimaryKey | isAutoincrement | p.s. |
|:--|:-:|:-:|:-:|:-:|:--|
| id | integer | not null | true | true | 主键 |
| Database_Version | text | -- | false | -- | 数据库版本 |
| Publish_Type | text | -- | false | -- | 推送类型 |
| Author | text | -- | false | -- | 作者 |
| Phigros_Version | text | -- | false | -- | Phigros版本 |
| Total | integer | -- | false | -- | 收入曲总数 |
| Reference | text | -- | false | -- | 当前版本参考文档 |
| Reference_Author | text | -- | false | -- | 文档作者 |

### 值
| id | Database_Version | Publish_Type | Author | Phigros_Version | Total | Reference | Reference_Author |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 1 | 1.1.0 | SNAPSHOT | CherryAya | 2.0.0 | 117 | (以数据库版本决定) | (以数据库版本决定) |