# DB-PBStruct
通用数据库KEY-VALUE存储方案：借助PB序列化，后续存储时新加字段删除字段不需要修改.proto，DB版本升级只在C++中做，且可以按模块划分，各个模块做自己的，尽量减少开发人员维护成本
