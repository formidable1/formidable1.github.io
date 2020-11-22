用例名称	Go To File
用例说明	User和Administrator可以对文件进行查看与修改，User修改要向
Administrator提出修改申请，Administrator接收User的申请进行审批
参与者	Adminstrator、User
元素	Document Changes、Submit Document Change Request To Administrator、FindFile、Approve User's Change Request、Findfile、Updatefile、Deletefile
关系	User对于Go To File用例是关联关系
Adminstrator对于Document Changes是关联关系
FindFile、Submit Document Change Request To Administrator对于Go To File是包含关系
Document Changes对于Go To File是泛化关系
Approve User's Change Request、Findfile、Updatefile、Deletefile对于Document Changes是包含关系
建模思路	User和Administrator对文件均可以进行查看修改等操作，但游客也就是User修改时要提交修改申请，得到Administrator的审批后方可进行修改操作。
