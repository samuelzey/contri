# 🗣 Discord activity regulation

### 介绍

通过设置任务，让社区成员保持高活跃度，以下为一个例子，可以根据系统自助设计活动。用户可以通过领取任务，在社区内活跃，提交任务获得积分（经验值）的方式完成任务，项目方可以针对该任务进行抽奖或者在最后白名单发放时把积分作为主要考量因素。

### 流程

1.  在Contri.build后台点击New Quest\


    <figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption><p>点击红色箭头所示位置创建任务</p></figcaption></figure>
2.  在Quest Name区域填入任务名称，如：\[ Contri Discord Contest]\


    <figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption><p>点击红色箭头位置输入任务名称</p></figcaption></figure>
3.  点击 + 号，添加子任务

    <figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption><p>点击红色箭头位置创建子任务</p></figcaption></figure>
4. 目前支持Discord上的子任务为
   1. 加入某个特定的Discord
   2. 点击某段文字的表情
   3. 获得某个特定的角色
   4. 在Discord文字频道内活跃
   5.  在语音频道内活跃\


       <figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption><p>Discord的自动审核任务类型</p></figcaption></figure>
5.  比如项目希望用户在未来的一周内，每天都至少在频道里发言3次，并且收听语音频道，那么可以这样设置：

    <figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption><p>左边可以选择任务类型，右边填入要求的链接，最右方可以删除一条小任务</p></figcaption></figure>
6.  注意，如果之前没有把Contri的机器人邀请进入Discord，需要先进行邀请，点击绿色的链接即可。\


    <figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>通过两个步骤，就可以把Contri的机器人拉近Discord内，帮助项目方检测用户在Discord内行为</p></figcaption></figure>
7.  填写信息如下，需要注意的是，需要设置想让用户活跃的天数以及界定最少说几句话算作是活跃，语音频道需要指定最少听多少秒的AMA才算是完成。

    <figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption><p>按照自己的需求填写即可</p></figcaption></figure>
8.  如果不知道怎么获得频道ID，请看下图

    <figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption><p>在Discord内右键点击某个频道，最下方即为CopyID</p></figcaption></figure>
9.  填入任务介绍

    <figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption><p>任务介绍区域可以解析Markdown文本</p></figcaption></figure>
10. 选择想要给用户的标记，积分或者是勋章（常规转发任务一般选择积分）

    <figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption><p>积分（经验值）和勋章可以都选择也可以只选一个</p></figcaption></figure>
11. 选择领取任务的门槛，上方是选择该任务的最多人数，下方是等级限制，最低1级

    <figure><img src="../.gitbook/assets/image (71).png" alt=""><figcaption><p>如果对任务要求较高，可以选择设置更高的等级起点，让对项目有一定了解的用户才能领取任务</p></figcaption></figure>
12. 可以选择是否让用户提交文字信息（不影响自动审核），收集用户对该任务的反馈\


    <figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption><p>想要收集用户对这个任务的反馈才需要添加，默认可以不添加</p></figcaption></figure>
13. 任务生成成功，可以在后台看到任务提交情况

    <figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>可以通过页面右边的ON/OFF来控制任务可见性，任务结束可以设置成OFF</p></figcaption></figure>
14. 在首页可以看到任务发布成功，用户可以领取并且完成

    <figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption><p> 只要到达开始时间，用户就可以看到了</p></figcaption></figure>
15. 点击任务中上方的Share按钮，在推特/discord上分享任务链接即可！(文字可以自行编辑)，用户点击link可以直达任务\


    <figure><img src="../.gitbook/assets/image (64).png" alt=""><figcaption><p>页面红色箭头可以复制任务链接</p></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption><p>可以在twitter上发布</p></figcaption></figure>
16. 可以每一周发放一次奖励，比如从Contri后台导出所有人的参与情况，抽取3位奖励白名单，也可以在最后发放白名单时，根据用户拥有的积分来发放白名单
17. 在Discord内寻找到这些用户，加白名单role
18. 通过Contri，导出拥有白名单role所有用户的地址（无论是通过Contri添加还是自行添加）
19. 上传至合约内
