# bugs
bugs,daily

<1> SVN中 “containing working copy admin area is missing” 问题  
    场景描述：  
    通过SVN中创建了一个目录 ，结果没有在svn中删除 ，而是直接到资源管理器或者finder中删除 了。这时SVN会报错，说找不到建立的那个目录了，错误信息就是：         
    “containing working copy admin area is missing”  
    如  
    Directory 'XX/.svn' containing working copy admin area is missing  

    那么如何处理呢  
    二、解决方案  
    1，删除XX目录。  
    2, 使用SVN Update命令更新XX 及其子目录资源，具体到eclipse项目中，就是在删除的目录的父目录处右击选择Team-》Update  

    搞定。
