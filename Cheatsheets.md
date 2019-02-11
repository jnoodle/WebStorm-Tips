# Cheatsheets

- [WebStorm's default keymaps](https://resources.jetbrains.com/storage/products/webstorm/docs/WebStorm_ReferenceCard.pdf)  

## My WebStorm Keymaps



| Note | KeyboradShortcut |
| ----- | :--------------: |
| **提高编写代码生产力** |  |
| **代码补全或生成**  |  |
| ★ Basic Code Completion 基本代码补全 <br />If necessary, press ⌃Space for the second time (this action produces the same effect as pressing ⌃⌥Space). |  ⌃Space  |
| SmartType Code Completion 智能代码补全  |  ⌃⇧Space  |
| ★ Complete Current Statement 语句补全 |  ⇧⌘⏎  |
| Inserting a taglib declaration  |  ⌃⌥Space  |
| ★ Show Intention Action and quick-fixes 意图预测与智能帮助 |  ⌥⏎  |
| ★ Insert a live template 插入模板 |  ⌘J  |
| ★ Surround with...(if..else, try..catch…)  用代码环绕 |  ⌥⌘T  |
| Surround with a live template.  用模板环绕（用代码环绕的子集） |  ⌥⌘J  |
| Override Methods… 创建override方法  |  ⌃O  |
| Implement Methods… 创建接口方法实现  |  ⌃I  |
| Optimize Imports 优化 imports  |  ⌃⌥O  |
| New, Generate code… 测试、方法生成；创建类、文件、目录  |  ⌘N, ⌃⏎  |
| **后向声明** **(Postfix Completion)**<br />先使用元素，再考虑变量声明或结构补全，旨在减少光标经常性的前后移动，提高开发效率 |  |
| !、assert、cast、else、field、for、fori、format、forr、if、inst、instanceof、iter、lambda、nn、not、notnull、null、opt、par、return、sout、stream、switch、synchronized、throw、try、twr、var、while |  Java  |
| ★ !、await、const、else、forin、forof、if、itin、let、log、not、notnull、null、par、return、throw、typeof、undef、var ( To see a full list of postfix completions applicable in the current context, press ⌘J. ) |  Javascript  |
| **快速编辑**  |  |
| ★ Start New Line Before/After Current One 从上/下方开始一行 |  ⌥⌘⏎, ⇧⏎  |
| ★ Move Line Up/Down 与上/下行互换 |  ⌥⇧↑ / ↓  |
| ★ Move Statement Up/Down 与上/下代码块互换 |  ⇧⌘↑ / ↓  |
| ★ Split Line 分割行（光标位置不变） |  ⌘⏎  |
| ★ Join Lines 拼接行 |  ⌃⇧J  |
| ★ Select/Unselect Word at Caret 选中光标所在单词（逐级扩展选择） | ⌥↑ / ↓，*⌃W/⌃⇧W* |
| ★ Duplicate Line or Block 复制当前行或选择块 |  ⌘D  |
| Copy 复制并且不删除当前行（光标在当前行任意位置）  |  ⌘C  |
| Cut 剪切当前行并复制到粘贴板（光标在当前行任意位置）  |  ⌘X  |
| Cut up to Line End 从光标处到行末剪切  |  ⌃K  |
| ★ Delete to Word End/Start 从光标删除到单词结尾/开头 |  ⌥⌦ / ⌫  |
| ★ Paste from recent buffers 从历史粘贴 |  ⇧⌘V  |
| Line Comment 行注释  |  ⌘/  |
| Block Comment 块注释  |  ⌥⌘/  |
| Reformat Code 格式化代码  |  ⌥⌘L  |
| ★ Reformat with Prettier | ⌥⇧⌘P，*⌥F* |
| Auto-Indent Lines 自动缩进  |  ⌃⌥I  |
| ★ Expand Word 快速完成单词（根据最近的单词补全） <br />(Hippie completion ⌥⇧/  (Backward)) |  ⌥ /  |
| Unindent Line or Selection 向左缩进  |  ⇧⇥  |
| ★ Delete Line at Caret 删除光标所在行 |  ⌘⌫  |
| ★ Choose statement to remove 删除包围的表达式（if、while...） |  ⇧⌘⌦  |
| Toggle Case 切换大小写  |  ⇧⌘U  |
| ★ Popup String Manipulation 切换命名（Install String Manipulation plugin） |  *⌥M*  |
| Column Selection Mode 列选择模式  |  ⇧⌘8  |
| Vim Emulator Vim 模式切换（IdeaVim plugin）  |  *⌥V*  |
| **快速移动光标和选择**  |  |
| ★ Right / Left 向右/左 |  →/←, ⌃F / B |
| ★ Up / Down 向上/下 |  ↓/↑, ⌃P / N  |
| ★ Scroll Up / Down 向上/下滚动 |  *⌃⌘P / N*  |
| Home / End  |  ⌘Home, ⌘End  |
| Home / End with Selection  |  ⇧⌘Home, ⇧⌘End  |
| Move to Next/Previous Word 移动到上一个 / 下一个单词  |  ⌥→ / ←  |
| Move to Next/Previous Word Selection 选择上一个 / 下一个单词 |  ⌥⇧→ / ←  |
| ★ Move to Code Block End/Start 移动到代码块开始 / 结束 |  ⌥⌘ ] / [  |
| ★ Move to Code Block End/Start Selection 选择到代码块开始 / 结束 |  ⌥⇧⌘ ] / [  |
| ★ Move caret to Line Start/End 移动光标到开始/结束 |  ⌘← / →, *⌃⇧E/⌃E*  |
| Move caret to Line Start/End with Selection 选中光标到开始/结束 |  ⇧⌘← / →  |
| ★ Next / Previous Method 上一个 / 下一个方法 |  ⌃↑ / ⌃↓  |
| Select Line at Caret 选中光标所在行  |  *⌃L*  |
| ★ Move caret to matching brace 在匹配的括号之间移动光标 |  ⌃M  |
| Next/Previous Emmet Edit Point 下/上一个Emmet编辑点  |  ⌃⌥→ / ←  |
| Next/Previous Template Variable 下/上一个模板变量  |  ⇥ / ⇧⇥  |
| **快速提示**  |  |
| ★ Brief Info 概要信息 |  ⌘+Mouse  |
| ★ Open quick definition lookup 快速显示定义 <br />输入法切换快捷键改为 ⌥⌘Space，防冲突 |  ⌥Space, ⌘Y  |
| ★ Quick Documentation Look-up 快速显示文档 |  F1 , ⌃J  |
| ★ Parameter Info 参数信息 |  ⌘P  |
| ★ Search in Dash 在Dash中搜索文档 |  ⇧⌘D  |
| **展开折叠**  |  |
| Expand/Collapse 展开/折叠  |  ⌘+ / -  |
| Expand/Collapse All  |  ⇧⌘+ / -  |
| Fold Selection / Remove region  |  ⌘.  |
| **搜索**  |  |
| **查找与替换**  |  |
| ★ Search Everywhere 多功能查找 |  Double⇧  |
| ★ Find Action 快速查找指令 |  ⇧⌘A  |
| Find / Replace 查找 / 替换  |  ⌘F / R  |
| ★ Find Next / Previous 查找下 / 上一个 |  ⌘G / ⇧⌘G  |
| ★ Find / Replace in Path 在文件中查找 |  ⇧⌘F / R  |
| ★ Find Usages 查找所有使用 |  ⌥F7  |
| Find usages in file 查找当前文件内的使用  |  ⌘F7  |
| Highlight Usages in File 高亮当前文件内的使用  |  ⇧⌘F7  |
| Show Usages popup 显示所有使用 |  ⌥⌘F7  |
| Expression Type  |  ⌃⇧P  |
| Compare Files  |  ⌘D  |
| **多光标操作**  |  |
| Add or remove caret 增加光标  |  ⌥+Click  |
| ★ Select all occurrences 选择所有相同项 |  ⌃⌘G  |
| ★ Select next occurrence 增加选择下一个相同项 |  ⌃G  |
| Unselect occurrence 撤销选择下一个相同项  |  ⌃⇧G  |
| Unselect all occurrences or carets 取消选择  |  Esc  |
| **导航**  |  |
| **基本导航**  |  |
| ★ Back/Forward 后退/前进 |  ⌘[ / ], ⌥⌘←/→  |
| ★ Recent Files 最近打开的文件 |  ⌘E  |
| ★ Recently Changed Files 最近修改的文件 |  ⇧⌘E  |
| ★ Recently Changed 最近修改 |  ⌥⇧C  |
| Go to Line 转到行...  |  ⌘L  |
| ★ Go to last edit location 回到上一次编辑位置 |  ⇧⌘⌫  |
| ★ Go to next edit location 回到下一次编辑位置 |  *⌃⇧⌘⌫*  |
| ★ Go to Next / Previous Highlighted Error 转到下一个/上一个错误位置 |  F2, ⇧F2  |
| ★ Show Descriptions Of Error At Caret 显示光标所在地错误信息 |  ⌘F1  |
| ★ Select Target Switch between views(Select in…) 在其他视图中选中目标 |  ⌥F1  |
| 定位当前文件所在 Project 组件窗口中的位置  |  ⌥F1 + 1  |
| ★ Go to Project Window |  *⌃P*  |
| **代码语义导航**  |  |
| ★ Go to Declaration 转到定义 |  ⌘B, ⌘Click  |
| Go to Implementation 转到实现  |  ⌥⌘B  |
| Go to Type Declaration 转到类型定义  |  ⇧⌘B  |
| Jump to source 转到源码  |  ⌘↓, F4  |
| Go to Test 转到单元测试  |  ⇧⌘T  |
| Go to Super Method/super-class 跳转到当前类的基类  |  ⌘U  |
| ★ File Structure Pop-up 文件结构 popup |  ⌘F12  |
| Type Hierarchy 类继承体系  |  ⌃H  |
| Call hierarchy 当前方法调用链  |  ⌃⌥H  |
| Method hierarchy 方法继承层次  |  ⇧⌘H  |
| Go to Class 转到类  |  ⌘O  |
| Go to File 转到文件  |  ⇧⌘O  |
| Go to Symbol 转到符号  |  ⌥⌘O  |
| Go to Related Symbol  |  ⌃⌘↑  |
| Go to Next/Previous Method 转到下/上一个方法  |  ⌃↓/↑  |
| Context Info 上下文信息  |  ⌃⇧Q  |
| **收藏和书签**  |  |
| Add to Favorites 添加到收藏夹  |  ⌥⇧F  |
| Go to Bookmark <number>  |  ⌃+Num  |
| ★ Toggle Bookmark <number> |  ⌃⇧+Num  |
| ★ Toggle Bookmark |  F3  |
| Toggle Bookmark with Mnemonic 使用助记符标记书签  |  ⌥F3  |
| ★ Show Bookmarks |  ⌘F3  |
| **窗口**  |  |
| **界面**  |  |
| Close Editor 关闭当前Tab  |  ⌘W  |
| Increase / Decrease Font Size 增大/减小字体尺寸  |  *⌃⇧= / ⌃⇧-*  |
| Toggle Presentation Mode 切换演示模式  |  *⌃F12*  |
| ★ Open Preferences 打开设置窗口 |  ⌘,  |
| Project Structure 项目配置  |  ⌘;  |
| ★ Show the Navigation bar |  ⌘↑  |
| Switch between tool windows and files 在工具窗口和文件之间切换 |  ⌃⇥  |
| **窗口**  |  |
| ★ Select Next Tab 前一个标签 |  ⇧⌘]  |
| ★ Select Previous Tab 后一个标签 |  ⇧⌘[  |
| Go back to previous tool window 转到上一个工具窗口  |  F12  |
| Project Window  |  ⌘1  |
| Favorites Window  |  ⌘2  |
| Search Window  |  ⌘3  |
| Run Window  |  ⌘4  |
| Debug Window  |  ⌘5  |
| TODO Window  |  ⌘6  |
| Structure Window  |  ⌘7  |
| Hierarchy Window  |  ⌘8  |
| Terminal Window  |  ⌥F12  |
| Version Control Window  |  ⌘9  |
| Hide Active Window 隐藏当前工具窗口  |  ⇧⎋  |
| Hide All Tool Windows 隐藏所有工具视图（Toggle maximizing editor） |  ⇧⌘F12  |
| ★ Quick switch current scheme 切换主题 |  ⌃`  |
| **重构**  |  |
| **基本**  |  |
| ★ Rename 元素(类/方法/变量/…)重命名 |  ⇧F6  |
| ★ Copy 复制类/目录等 |  F5  |
| ★ Move 移动类/目录等 |  F6  |
| ★ Refactor This… |  ⌃T  |
| ★ Safe Delete |  ⌘⌦  |
| **高级**  |  |
| Change Method Signature 类/方法签名修改  |  ⌘F6  |
| Field… 字段(类级别)抽取  |  ⌥⌘F  |
| Constant… 常量(类级别)抽取  |  ⌥⌘C  |
| Variable… 变量(方法级别)抽取  |  ⌥⌘V  |
| Parameter… 参数(方法级别)抽取  |  ⌥⌘P  |
| Method… 方法抽取  |  ⌥⌘M  |
| Inline… 方法内联  |  ⌥⌘N  |
| Inspect current file with current profile 校验当前文件  |  ⌥⇧I  |
| **调试**  |  |
| **基本**  |  |
| Run 运行  |  ⌃R  |
| Debug 调试  |  ⌃D  |
| Build Project 编译  |  ⌘F9  |
| Stop 停止调试  |  ⌘F2  |
| ★ Choose configuration and Run/Debug |  ⌃⌥R / D  |
| ★ Step Into 如果当前行断点是一个方法，则进入当前方法体内 |  F7  |
| ★ Step Over 如果当前行断点是一个方法，则不进入当前方法体内 |  F8  |
| Resume Program 继续或到下一个断点  |  ⌥⌘R、(F9)  |
| Evaluate Expression 计算表达式  |  ⌥F8  |
| **高级**  |  |
| Smart Step Into  |  ⇧F7  |
| Step Out  |  ⇧F8  |
| Force Step Over  |  ⌥⇧F8  |
| Force Step Into  |  ⌥⇧F7  |
| Run to Cursor  |  ⌥F9  |
| Force Run To Cursor  |  ⌥⌘F9  |
| Update running application  |  ⌘F10  |
| Rerun tests  |  ⌃⌘R  |
| Quick Evaluate Expression  |  ⌥⌘F8  |
| Toggle Breakpoint  |  ⌘F8  |
| View Breakpoints  |  ⇧⌘F8  |
| Run Gulp/Grunt/npm tasks  |  ⌥F11  |
| **版本管理**  |  |
| ★ VCS’ quick popup |  ⌃V  |
| Commit project to VCS  |  ⌘K  |
| Update project from VCS  |  ⌘T  |
| View recent changes  |  ⌥⇧C  |
| Move to Next Difference  |  F7  |
| Move to Previous Difference  |  ⇧F7  |
| Synchronize  |  ⌥⌘Y  |
|  |  |

*斜体为自定义*