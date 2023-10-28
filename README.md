# 面向对象——UML构件图（Component Diagram)

# 一、基本概念
构件图描述构件及其相互依赖关系，构件是逻辑体系结构---类、对象和它们间的关系和协作中定义的概念和功能在物理体系结构中的实现。

构件：相对逻辑设计上的类和对象，构件是和物理系统相关的一个概念，不同的语言对构件的定义有所不同，UML中的构件含义包括代码文件，也指数据库、动态链接库、web页面等。
# 二、基本元素
构件图的主要元素包括构件、接口和依赖关系。
## 1. 构件
构件是定义了良好接口的物理实现单元，是系统中可替换的物理部件。

构件可以是源代码构件、二进制构件或一个可执行的构件。

在UML中，构件用一个左侧带有突出两个小矩形的矩形来表示。
![1](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/513392b3-ca20-40ab-bc8b-fce3a62e81d9)

对于一个构件而言，它有两类接口：提供（provided）接口和所需（required）的接口。


标识接口的构件表示方法有3种。
![2](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/4d159c36-34f1-42a8-ac1c-b2813e1beed7)
![3](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/0bdd57bc-016a-4a82-bdaa-dc3a0354eaee)

## 2. 依赖关系
构件间的关系以依赖的形式表达。把提供服务的构件称为提供者，把使用服务的构件称为客户。

在UML中，构件图中依赖关系的表示方法与类图中依赖关系相同，都是一个由客户指向提供者的虚线箭头。
![4](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/dddd8140-da18-43af-a2f0-dc0ca9e02030)

## 3. 接口
接口用于描述构件所提供的服务的一组操作集合，指定了构件的外部可见操作。可以通过接口访问一个构件。

接口和构件之间的关系分为两种：

实现关系（Realization）
依赖关系（Dependency）
在UML图中，接口和构件之间用实线连接表示实现关系；而接口和构件之间用虚线箭头连接则表示依赖关系。
![5](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/7ac35763-260b-4394-98b1-9e72b911a0be)

导出接口由提供操作的构件提供。

导入接口供访问操作的构件使用。

![例題1](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/c44af40b-a499-4db9-92a3-dc7684864507)
![例題2](https://github.com/curryluku/UML-Component-Diagram/assets/91310381/dba247d0-e71d-452d-a65e-912735d37877)


實作圖於https://drive.google.com/file/d/1dTb3IRKANY6XDBcHPHu95n1cLvJT1_P5/view?usp=sharing
