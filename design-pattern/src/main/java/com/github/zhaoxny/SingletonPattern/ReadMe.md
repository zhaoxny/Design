# 单例模式
 ## 饿汉式单例
 单例类首次加载时就创建实例
  缺点：占用太多内存
  
 ## 懒汉式单例
 被外部类调用的时候才创建实例
    1,简单版
    2,同步锁版
    3,双重检验锁版
    4,静态内部类--最屌写法