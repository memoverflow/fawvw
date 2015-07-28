# SharePoint 列表说明
Fawvw的自助服务门户项目使用sharepoint 2013开发，工作流使用sharepoint自带的工作流进行设计，过程正在摸索，因为使用sharepoint开发，所以数据放到sharepoint中，下面是定义的sharepoint列表项：

| 名称 | 描述 | 类型 | 英文名 |
| -- | -- | -- | -- |
|用户信息表	|存储用户信息|	列表|	fUser |
|部门信息表|	存储用户的相关部门信息|	用户组|	fDepart|
|部门用户对应表|	用户的部门相关信息|	用户组|	fUserDepart|
|角色信息表|	存储角色的相关信息|	用户组|	fRole|
|角色用户对应表	|用户的角色相关信息|	用户组|	fUserRole|
|代理人列表|	相关服务的代理人|	列表|	fProxy|
|通知表	|存储管理员发送给用户的通知信息|	列表|	fNotice|
|常用链接表|	存储系统的常用链接|	列表|	fLinks|
|附件表（使用前培训）|	存储用户可以下载的附件|	文档库|	fAttachments|
|服务表	|存储所有的服务信息|	列表|	fService|
|服务错误定义|	不同序号定义不同的错误信息|	列表|	fErrorMsg|
|服务自定义分组|	定义不同服务的分组列表|	列表|	fServiceGroup|
|服务ICON|	服务审批环节的小图标|	列表|	fIcons|
|服务评分反馈|	服务的评分反馈|	列表|	fFeedback|
|任务表	|自定义任务表|	列表|	fTasks|
|邮件模板表	|邮件模板的定义信息|	列表|	fMailTemplate|
|邮件历史信息表|	邮件发送的历史信息|	列表|	fMailHistory|


