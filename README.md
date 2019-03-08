
  风控系统的本质是为了能够让企业有能力主动发现业务风险，并快速的实施攻防对
抗，星云采用旁路流量的方式进行数据采集，无需在业务逻辑上做
数据埋点或侵入，同时支持本地私有化部署和Docker镜像云端部署；出于数据隐
私和敏感性的考虑，我们不做任何数据的上传；
  另外考虑到部分使用者风控经验不足，星云会提供基础的风控策略模板，使用者可
以结合业务实际情况，灵活的进行配置和调整。考虑到攻防对抗的时效性，策略调
整之后实时生效，无需重新编译和上线。

星云包含的一些基础功能：
1.总览：观察网站流量和风险事件的情况
2.风险名单管理：由你设置的某个具体的策略出发而产生，风险名单管理页面展示
了风险名单的列别，通过这个页面可以进行风险名单的查询、删除和人工添加等操
作。
3.风险事件管理：风险事件由一组关联风险名单的基础事件组成，风险事件可以对
不同的攻击进行整理成组，以便分析人员快速的针对一组风险事件进行查看。
4.风险分析：风险分析页面提供了IP、USER、PAGE、DEVICEID四个维度的分析
视角、允许分析人员通过不同的维度去查看某个IP、用户、设备或页面的细节以
还原风险事件的整个流程。
5.日志查询：通过自定义的方式去搜索历史日志中的数据
6.策略管理：提供了可视化策略编辑功能，允许用户通过界面方式创建或编辑策
略，并且可通过对策略状态的编辑快速的测试策略的有效程度，以及生产策略的下
限
写在最后
与黑灰产的多年对抗中，我们看到了黑灰产无数次的狂欢，也看到了太多企业遭受
攻击后的无奈和辛酸。但是目前整个互联网行业中的风控系统基础设施普及率还不
到5%。通过开源，我们希望能让更多人意识到风控的重要性，能以更低的成本，
完成风控体系从无到有的搭建。
黑灰产已经是一个分工明确，合作紧密的“庞然大物”，而安全行业绝大多数仍处于
相对封闭，各自为战的状态。虽然协同合作已经是行业共识，但一直缺乏有效的举
措。通过开源星云业务风控系统，我们希望走出这一步，集结社区力量，让更多的
安全从业者可以参与进来，贡献自己的力量。
![kzjzQO.png](https://s2.ax1x.com/2019/03/08/kzjzQO.png)
