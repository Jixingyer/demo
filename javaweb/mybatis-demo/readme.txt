这是本模块的说明文件：

本模块介绍MyBatis框架的使用：
                MyBatis框架用于简化JDBC的开发
                1.可以直接将mybatis的jar包导入使用
                2.已经学习了maven，所以可以用maven构建项目
*******具体介绍用Maven构建mybatis步骤：
                                 1.在数据库中创建表user，添加数据
                                 2.创建maven模块，导入坐标
                                 3.编写mybatis核心配置文件（mybatis-config.xml） -->替换连接信息，解决硬编码问题
                                 4.编写SQL映射文件（XXXMapper.xml） -->统一管理sql语句解决硬编码问题
                                 5.编码
                                    a.定义pojo类
                                    b.