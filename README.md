# IntelligentCommunity

青软实训项目——1组——智慧社区

各版本测试软件可在releases页面下载。

# v1.0 

>版本说明： 

最初的版本发布，整体框架全部搭建完毕，汇集小组部分功能模块。数据库未整合，当前只有账号数据库可用。

账号数据库（mark 0为管理员 1为用户 2为物业 ）：

  用户：id:1234  tel:10086  IDcard:100001 pwd:1234 mark:1 name：张三

  物业：id:2345  tel:10010  IDcard:100002 pwd:2345 mark:2 name：李四
  
  管理员：id：123 tel：10000 IDcard：200001 pwd：123 mark：0 name：王五

>版本添加功能：

1.用户可以通过账号，身份证号，手机号来进行登录，系统自动判断身份，并打开相应的管理界面。其中管理员登录会在左下角专门入口进行登录，在主界面登录会提示请到专用入口进行登录。

2.集成两个功能：物业工作人员业主信息管理模块，管理员人事管理模块。

# V1.1-beta1

>版本说明：

最新测试版本发布，再次汇集了小组的部分模块，数据库未整合，账号数据库和上版本一样。

>版本添加功能：

1.业主管理面板添加维修管理模块：包含故障报修，及故障查询和评价功能。

2.物业管理面板添加人事管理模块：包含请销假，月度出勤，上下班登记功能。

3.物业管理面板添加车位管理模块：包含车位信息管理，车位出租功能。

4.物业管理面板添加维修管理模块：包含维修管理功能。

# V1.1-beta2

>版本说明：

最新测试版本发布，再次汇集了小组的部分模块，数据库未整合，账号数据库和上版本一样。

>版本添加功能：

1.管理员管理面板添加出勤管理模块：包含月度出勤，请假审批功能。

>版本优化功能：

1.对所有已整合的模块进行重新排版优化，使其适合整体界面。

# V1.1-beta3 V1.1-beta4

>版本说明：（beta4版本为beta3版本几小时后优化发布，故两版本整合发布说明）

最新测试版本发布，再次汇集了小组的部分模块，所有开发模块数据库全面整合更新（除登录数据外，其他模块功能都未绑定该新数据库），账号数据库全面更新。

>>更新账号密码数据库如下：

管理员：

id：2017001 tel：10011 IDcard：2020001 pwd：2017001

id：2017002 tel：10012 IDcard：2020002 pwd：2017002

业主：

id：2017003 tel：10013 IDcard：2020003 pwd：2017003

id：2017004 tel：10014 IDcard：2020004 pwd：2017004

id：2017005 tel：10015 IDcard：2020005 pwd：2017005

物业工作人员：

id：2017006 tel：10016 IDcard：2020006 pwd：2017006

id：2017007 tel：10017 IDcard：2020007 pwd：2017007

id：2017008 tel：10018 IDcard：2020008 pwd：2017008

>版本添加功能：

1.业主管理面板添加车位管理模块，包含车位信息功能。

2.管理员管理面板添加系统设置模块，包含系统初始化，About us功能。

3.物业管理面板添加缴费管理模块，包含缴费信息查询功能。

4.业主管理面板添加缴费管理模块，包含缴费查询功能。

5.物业管理员，物业，业主管理主界面左下角添加欢迎登录信息，可以显示登录者姓名，界面右下角添加github页面链接，点击文字即可跳转。

>版本优化功能：

1.对部分模块界面进行优化。

2.添加UI背景图，优化主窗口。

3.提供了一个全局登录id接口，所有模块功能都可直接调用该id来进行匹配登录者数据库信息，优化人机交互。

# V1.2 

> 版本说明：

正式版本发布，集成所有模块功能，数据库全面绑定成功，成功运行并实现基础功能，数据库账号密码同上版本。

> 版本优化：

1.业主车位车辆信息界面布局进行了优化。

2.管理员车位出租界面布局进行了优化，增加业主车位申请信息显示栏可进行信息比对显示。

3.管理员车位管理界面布局进行优化。

4.物业工作人员增加线下缴费界面和业主自主缴费查询界面，实现了显示未缴费查询及根据缴费类型，日期缴费。

5.修改了业主互相保修界面，不需要重复检索姓名，根据登录的用户直接划分到相应的用户信息。

# V1.3

>版本说明：

在上一个版本基础上进行优化。

>版本优化：

1. 优化了业主查询评价界面，升级优化物业管理界面以及表格展示。

2. 优化人事管理模块，将姓名查询去掉，根据登录用户的用户名自动查询。

3. 优化月度出勤功能，并将英文表格名更改成中文。

4. 增加物业工作人员审批查询功能。

5. 优化物业管理员人事管理，增加了一个界面：人事信息查询功能。

6. 优化物业工作人员人员管理模块，增加了业主密码修改和录入业主信息功能。

# V2.0

>版本说明：

在上一个版本基础上进行优化，全组测试后发布，确定发布版本号为2.0。

>版本优化：

1.修复维修管理模块物业工作人员能够修改业主故障报修问题描述的bug。

2.添加维修管理模块物业工作人员查询成功提示弹窗。

3.修复维修管理模块物业工作人员能修改业主故障报修地址的bug。

4.修复物业管理员系统初始化功能不能完全删除信息的bug。

5.优化管理员人事管理模块，增加显示全部数据库的功能。

6.优化物业业主信息管理模块，增加了修改密码的功能。

7.优化业主车位车辆信息功能，完善业主申请车位功能。

8.优化管理员车位出租功能，增加业主车位申请信息显示栏可进行信息比对显示。

9.优化物业缴费模块物业类型的手动输入，改为了下拉选择框。

10.添加物业缴费模块多种查询，扩大查询范围。

11.优化月度出勤界面的文字形式。

12.优化请销假姓名的插入。

13.优化了上下班的姓名插入。

# V2.1 

>版本说明：

在上一个版本基础上进行优化，测试后发布最终版，确定发布版本号为2.1。

>版本优化：

1.优化管理员人事管理模块，将身份标识显示出文字并改用下拉框修改。

2.优化物业业主信息管理模块，增加房产类型信息录入，性别显示改为下拉框显示选择。

3.优化请假界面时间填写方式，用dateTimeEdit代替原有的lineEdit。

4.优化上下班界面，对上下班打卡采取系统自动获取时间并存于数据库中，添加上班迟到和下班早退提示。

5.优化管理员月度出勤界面，添加单独查询和删除出勤记录。

6.优化业主报修地址不再默认业主的当前住址，业主可以手动输入报修地址。

7.修复物业工作人员可以修改业主报修记录业主个人信息和报修地址的bug。

8.优化客户端界面，添加物业管理员修改客户端主题功能，重启客户端后生效。

9.优化客户端登录，添加登录界面输入账号密码后可用大小键盘Enter键登录。

10.优化客户端登录界面窗口，取消管理员单独登录窗口，三个身份登录合并1个主登陆界面进行登录。

11.优化物业工作人员车位管理模块，增加车位等级录入功能。
>产品使用说明书

登录界面：登录界面分两部分，第一部分为业主和物业工作人员登录界面，管理员登录界面放在其页面的左下角单独进入。在业主和物业工作人员登录界面，你可以输入业主或物业工作人员的帐号和密码，手机号和密码，身份证号和密码任一组合来登陆，系统自动判断登陆者身份来进入不同的管理界面，管理员在此窗口登陆会提示请到左下角登陆。管理员登录也可使用三种登录方式进行登录。

维修管理模块实现了故障上报、维修进度查询、维修评价、修改保修情况和维修进度等功能。

维修管理模块一共分为三个界面：第一个界面用于业主故障报修。第二个界面用于业主查询维修进度以及对物业的维修情况进行评价。第三个界面用于物业工作人员管理维修信息。

维修管理模块使用说明：

1.业主故障报修：业主填写描述故障问题，系统根据业主的信息姓名或者ID将信息提交到后台数据库等待物业工作人员受理。

2.业主查询及评价：业主通过自己的姓名或者ID能查询到维修进度，故障是否被物业工作人员受理。如果故障问题已被解决，业主可以对本次的维修情况进行评价。

3.工作人员维修管理：物业工作人员可以通过显示按钮查看后台所有的故障报修问题。对于已经过期或已经处理完并反馈评价的信息进行删除，工作人员看到新的故障问题后，可以通过查询业主姓名显示全部的业主报修信息，根据信息安排合适的维修人员前往，根据维修人员反馈的信息工作人员可以及时更新维修进度。维修完成后等待业主对本次维修工作的评价

缴费管理模块实现了增加缴费，月期收费、自助缴费、线下收费、缴费查询功能。

缴费管理模块使用说明：

1.价格维护：物业工作人员根据月度消费情况，增加业主的消费信息，把业主的信息及缴费情况发送到数据库中。

2.自主缴费：业主可查询自己的未缴费情况，然后选择缴费类型和缴费日期进行缴费。

3.线下收费：物业工作人员线下收费，对缴费的业主通过缴费类型和缴费日期分类，递送给后台。

4.缴费查询：业主和物业工作人员可实现对不同缴费类型和时间的查询，可视化缴费信息，还可以精准的按照缴费日期和缴费类型查询。

人事管理模块分为两部分，第一部分是管理员的出勤界面，第二部分是物业工作人员的人事管理。

管理员的出勤界面分为两个小部分，分别为请假审批和月度出勤，在请假审批界面，管理员可以看到所有的请假记录，对假条进行审批；在月度出勤界面，管理员可以通过详细按钮查看所有物业工作人员的出勤信息。

物业工作人员的人事管理分为四部分，分别为请销假、上下班登记、月度出勤和审批查询，在请销假界面，工作人员只需填写请假原因、日期、时间，通过点击请假和销假按钮进行本次功能。上下班登记界面，工作人员填写上下班时间，然后点击上班和下班按钮即可；出勤登记界面，工作人员通过点击详细按钮即可查看自己的所有出勤记录。

审批查询界面，工作人员点击查询按钮即可看见自己的假条审批结果。

业主信息管理实现了对业主信息的查询、增加、修改、删除、显示全部信息的功能。

业主信息管理模块的使用说明：

物业工作人员直接对业主的信息进行管理，包括，姓名、性别、年龄、身份证号、手机号码、登陆账号、登陆密码、家庭住址。

1.信息查询：物业工作人员在查询目录输入需要查询业主的名字，点击“查询”按钮，然后会显示出此业主的所有资料。如果输入的名字不对，会提示该业主不在数据库，请重新输入。

2.信息增加：物业工作人员在输入栏输入业主的所有信息，点击“增加”按钮。新业主信息写入数据库成功，如果信息输入不完善则不能写进去。

3.信息修改：如果业主需要修改信息，物业工作人员先在数据库中查询到此业主，然后修改相应的信息，点击“修改”按钮，提示修改成功。

4.信息删除：业主如果需要销户，物业工作人员则在姓名输入框输入业主姓名，点击“删除”按钮，该业主所有的信息全部被删除。

5.显示数据库所有的信息：物业工作人员点击“显示全部业主信息”按钮，则会显示出数据库所有业主信息，此功能方便查看数据是否被写进去数据库。

管理员人事管理模块实现了对管理员、物业工作人员和业主的身份证号、手机号码、登陆账号、登陆密码、身份标识的查询、增加、修改、删除。

管理员人事管理模块分为两个界面：第一个界面用于工作人员的信息查询、增加、修改、删除。第二个界面用于查询所有物业工作人员、物业管理员、业主的身份证号、手机号码、登陆账号、登陆密码、身份标识。

管理员人事管理模块的使用说明：

1、物业管理员在输入查询姓名对话框，输入姓名，点击查询按钮，相应的信息会显示出来。

2、增加工作人员，物业管理员需要在相应的对话框中输入工作人员的全部信息，点击“增加”按钮，则信息将会被插入到数据库。

3、删除工作人员，物业管理员通过查询功能查询出此人信息。点击“删除”按钮。此人所有信息会被删除。

4、修改信息，物业管理员首先通过查询功能，查询出此人信息，在修改需要改的信息，点击“修改”按钮，信息修改成功。

5、物业管理员点击“查询”按钮，文本框中将会显示所有的数据库人事信息。

系统设置模块实现了对数据库中数据清空的功能和查看ABOUT US的功能。

系统设置模块一共分为两个界面：第一个界面是系统初始化，第二个界面是ABOUT US。

系统设置模块使用说明：

1、物业管理员在主界面点击“确定”按钮，系统弹出确认界面，确认后，将数据库置为初始状态。

2、物业管理员直接可以查看并更改本系统的信息。
