English:
Environment setup: JDK 11, Python 3.6, PyCharm, Neo4j Community 4.2.16 (Windows). Step 1: Establish a connection to the knowledge graph: 1. Press Win+R. 2. Type "cmd" and press Enter. 3. Type "neo4j.bat console". Step 2: Run the code: 1. Run "answer_search.py" (used to traverse data; run this after adding, deleting, or modifying data; no need to run if there are no changes). 2. Run "build_graph.py" (used to build the knowledge graph). 3. Run "chatbot_graph.py" (used to set up the retrieval-based Q&A process). 4. Run "code.py" (used to launch the frontend; the port is displayed as http://0.0.0.0:8080/). 5. Access the frontend interface and replace "0.0.0.0" with "127.0.0.1". Step 3: Enter text into the dialog box to display the corresponding retrieval results.

Note: If running "code.py" results in an error, the port is likely occupied. You can identify the process using port 8080, terminate that process, and then run the program again; it should then execute successfully.


中文：
环境配置：jdk11  python3.6  pycharm  neo4j-community-4.2.16-windows
第一步，建立知识图谱的连接：
1、win+R
2、输入cmd，回车
3、输入“neo4j.bat console”
第二步，运行代码：
1、运行“answer_search.py”（用于遍历数据，数据进行增删改之后运行，若无改动，不需要运行）
2、运行“build_graph.py”（用于搭建知识图谱）
3、运行“chatbot_graph.py”（用于搭建检索问答过程）
4、运行“code.py”（用于进入前端，并显示端口：http://0.0.0.0:8080/）
5、点击进入前端界面，将0.0.0.0换成127.0.0.1
第三步，在对话框中输入内容，显示相应的检索结果

注：如果运行code.py报错，那么端口号被占用，可以查看8080所对应的端口，将该进程结束，再运行程序，将运行成功。
