# git-cooperation
For git training demonstration
| 操作                | 预期结果      |涉及文件|
|  ----               | ----         |----   |
| main和dev编辑同一行  | 保留main的改动 |edit-retainMain.txt|
| main和dev编辑同一行  | 保留dev的改动 |edit-retainDev.txt|
| main和dev编辑同一行  | 保留main,dev的改动 |edit-retainMainDev.txt|
| main添加新文件，dev添加不同名的文件  | 两个新文件都存在 |add-main.txt,add-dev.txt|
| main添加新文件，dev添加同名的文件,且内容相同  |使用main改动覆盖dev文件 |bothAdd-sameContent.txt|
| main添加新文件，dev添加同名的文件,内容不相同  |保留双方内容改动 |bothAdd-differentContent.txt|
| main删除一个文件，dev删除另一个文件  |dev分支不存在main删除的文件,同时dev删除的文件会被更新下来 |mainDelete-devStet.txt，mainStet-devDelete.txt|
| main，dev删除相同文件  |此文件被删除 |mainDelete-devDelete.txt|
| main删除文件，dev编辑此文件  |保留文件和文件改动 |mainDelete-devEdit.txt|
| main编辑此文件，dev删除此文件  |保留main的改动 |mainEdit-devDelete.txt|
