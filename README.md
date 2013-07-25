btrace_extend
=============

btrace 拓展，可以方便的诊断java应用程序的性能问题

BTrace is a safe, dynamic tracing system for the Java platform. BTrace project 
is hosted at http://kenai.com/projects/btrace. See also "docs" directory.


  	First,execute 
                    btrace pid
                       connect to my version
		ConsolePrint.println("-------------------------------------------------------------------------------------------------");
		ConsolePrint.println("| CommandName  CommandArgs                       CommandUsage");
		ConsolePrint.println("| time         {clazzname methodname}[interval]  收集响应时间并显示 ,并支持设计迭代时间（s）,;如 ");
		ConsolePrint.println("|                                                time java.lang.Thread start 2");
		ConsolePrint.println("| aggre        {clazzname methodname}[interval]  收集响应时间并聚集显示 ,并支持设计迭代时间（s）;如 ");
		ConsolePrint.println("|                                                aggre java.lang.Thread start 2");
		ConsolePrint.println("| call         {clazzname methodname}[interval]  判断函数是否被调用;如 ");
		ConsolePrint.println("|                                                call java.lang.Thread start 2");
		ConsolePrint.println("| jstack       {clazzname methodname}[interval]  打印指定函数的调用堆栈;如 ");
		ConsolePrint.println("|                                                jstack java.lang.Thread start 2");
		ConsolePrint.println("| file         {filePath}                        支持btrace原有方式，加载btrace file文件;如 ");
		ConsolePrint.println("|                                                file Test.java");
		ConsolePrint.println("| druid                                          监控当前druid数据源的链接情况；如 ");
		ConsolePrint.println("|                                                druid");
		ConsolePrint.println("| isearch                                        监控当前isearch请求的响应时间；如 ");
		ConsolePrint.println("|                                                isearch");
		ConsolePrint.println("| sql                                            监控当前Sql请求的响应时间，聚合显示；如 ");
		ConsolePrint.println("|                                                sql");
		ConsolePrint.println("| sqlde                                          监控当前Sql请求的响应时间，聚合显示,且显示详细sql；如 ");
		ConsolePrint.println("|                                                sql");
		ConsolePrint.println("| quit                                           退出btrace交互 ");
		ConsolePrint.println("|                                                quit");
		ConsolePrint.println("| ------------------------------------------------------------------------------------------------");	
