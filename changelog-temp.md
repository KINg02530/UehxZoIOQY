- fix: 修复批量操作异步执行首次出现`NoSuchElementException`错误
- fix: 修复`entity.java.btl`生成`toString`方法样式错误
- fix: 修复`entity.java.ftl`模板类注释与导包缺少换行
- opt: 支持手动指定`CompatibleSet`实现
- opt: 去除`entity.kt.btl`模板`@Override`注解
- opt: 解决`serviceImpl.java.ej`生成格式不统一
- opt: 去除`mapper.java.ftl`多余的换行生成
- opt: 去除`entity.kt.vm`,`entity.kt.ej`,`entity.kt.btl`导包结束分隔符
- opt: 去除`controller.java.ej`,`controller.java.vm`多余的换行
- opt: 去除`entity.kt.btl`生成属性多余的空格
- opt: 代码生成器处理`PRIMARY_KEY_`为开头的主键索引情况
- opt: 统一`entity.java.btl`,`entity.java.ej`,`entity.java.ftl`,`entity.java.vm` 生成的`toString`方法样式
- opt: 重构`SqlRunner`执行`SQL`语句 (动态传参，不再根据参数值生成执行`SQL`)
- opt: 增强`SqlRunner`执行(支持单参数使用`Map`({key}),`List`({index}),`JavaBean`({property})获取值)
- opt: 改进`MybatisUtils`对自`SqlSessionFactory`的提取(支持自定义sqlSessionTemplate子类)
-
