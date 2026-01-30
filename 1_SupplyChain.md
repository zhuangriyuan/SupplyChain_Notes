# Supply Chain Analyst

__Supply Chain Network__
> It's everyone involved in getting a raw material turned into a product and delivering it to consumers

__Different Components__
1. Suppliers
2. Manufacturers
3. Logistics(物流)
> Also include __reverse logistics__(returns)
4. Customers
   
__Supply Chain Process__
1. Inventory Planning
> Determining the quantities of products available to meet customer demand
2. Inventory Levels
> Do we have too much or too little? Tracks inventory movement, both inbound and outbound
3. Transportation
4. manufacturing
5. Warehousing and Distribution

__Inventory Planning__
1. Meet customer demand
2. Minimize costs
3. Optimize working capital(优化运营资本)
4. Streamline operations(简化运营)

__What data do you look at for inventory planning__
1. Lead Time(交货时间)
> The time taken from placing an order to receiving the inventory
2. Demand variability(变异性)
> the fluctuation in customer demand over time(客户需求随时间变化的波动)
3. Access inventory performance metrics, monitor stock levels and analyze demand patterns

__Supply Chain Gears__
1. Procurement(采购)
2. Manufacturing
3. Warehousing and Distribution

__Future Trends__
__IOT__
> Internet of Things(物联网)
> The network of physical objects that are embedded with sensors, software and other technology so they can connect and exchange data with other systems
__Blockchain Technology(区块链)__
> allows information sharing within a network
__Robotics and automation__
> warehouse robots, autonomous vehicles, drones
__Resilient Supply Chains(弹性供应链)__
> risk management, scenario planning


## Supply Chain Planning
__What is supply chain planning?__
> It helps determine optimal inventory levels(确定最佳库存水平), reorder points, safety stock quantities and replenishment(补货) strategies based on various factors

1. Lowering transportation costs
2. reducing excess inventory
3. improving warehouse operations
4. streamlining order fullfillment(简化订单履行)
5. optimizing supplier relationships

__The Five C's__
1. Collaboration
2. Connectivity
3. Control
4. Compliance
5. Customer-centricity

__ABC Analysis__ 将库存分为ABC三类
> It's a technique used to categorize inventory items into different groups based on their importance and usage
Typically as __A, B or C items__
__A:__ High value items with higher sales volume and critical importance
__B:__ Moderate value items with moderate sales volume and moderate importance
__C:__ Low value items with relatively lower sales volume and less significance

__EOQ Models(Economic order quantity)经济订货量__
> Its a mathematical formula used to find the optimal order quantity for inventory items, balancing holding costs, storage handling and the cost of ordering too frequently, administrative transportation

__Optimize inventory levels__
1. Safety Stock
> acts as a buffer to mitigate uncertainties in demand variability and supply distruptions(起到缓冲作用，以减轻需求波动和供应中断带来的不确定性)
2. Reorder point
> 当库存水平下降到某一特定数量时，就必须立刻下新订单，以确保在补货到达前不会断货。
3. Minimum order quantity(MOQ)
> 低于这个数量，供应商要么不接单，要么会显著提高单价。
4. Lead time
5. Demand

__Quantitative Forecasting Methods(定量预测)__
1. Time series forecasting(时间序列)
> use historical data and statistics to predict future demand
2. Regression analysis(回归分析)
> is used to understand relationships between variables and make predictions
3. ARIMA(autoregressive integrated moving average)自回归积分移动平均 and SARIMA(seasonal autoregressive integrated moving average)季节性积分移动平均
> Capture trends, seasonal patterns and other time-dependent structures such as trends, cycles, auto-correlation and irregular fluctuations
4. Machine learning
5. Neural networks

__Qualitative forecasting Methods(定性预测)__
1. Expert opinion
2. Surveys and market research
3. Delphi method
> A group of experts provide predictions anonymously which elimates bias
4. Scenario planning
5. Grassroots forecasting(基层预测)
> Collecting insights from individuals at the operational level
6. Casual(因果)
> Using cause and effect relationships to predict demand
7. Judgment forecast
> Using expert opinions, market knowledge and qualitative assessments to make predictions

__Demand Planning__
> 中长期、结构化的需求规划过程，用于支撑生产、采购和库存决策
> 基于历史数据、趋势、季节性和业务假设，对未来需求进行中长期预测与规划的过程。
__Demand Sensing__
> 短期、近实时的需求“感知与修正”机制，用于捕捉最新市场信号并快速调整
> 利用最新、最接近真实消费的信号，对短期需求进行动态修正。

__Baseline demand__(基准需求)
> Baseline Demand 指在没有任何促销、异常事件或一次性因素影响下，产品在正常市场条件下的稳定需求水平。
__Promotional demand__(促销需求)
> Promotional Demand 指由于促销活动而额外产生的需求增量（Incremental Demand），不包含原本就会发生的基准需求。

__Supply Chain Manufacturing__
> process of managing and coordinating the production and distribution of goods within a supply chain network
> Involves movement of raw materials and finished products

__Manufacture Strategy__
1. Lean(精益制造)
> 消除一切浪费（Waste），在不增加成本的情况下最大化价值。
> 常见的浪费：
    过度生产
    等待
    运输
    过度加工
    库存
    返工
> __需求相对稳定 产品生命周期较长 以成本、效率为主要竞争力__
> 👉 典型：汽车制造、电子装配、成熟消费品

（扩展）未充分利用人才
2. Agile
> 快速响应变化的市场和客户需求。
> 高柔性（Flexible）
> 模块化设计
> 快速换线 / 快速切换
> 信息透明、响应快
> __需求高度不确定__
> __产品更新快__
> __定制化程度高__
> 👉 典型：时尚（ZARA）、高科技产品、定制装备

强调速度和客户价值，而不是极致成本
3. Just in Time
> 在“需要的时间、需要的数量、生产需要的产品”。
> 极低库存
> 强依赖供应商
> 小批量、高频次
> 精确的生产与物流协同
> __供应链非常稳定__
> 交期可靠
> 供应商距离近 / 协作深
> 👉 典型：丰田体系

__IOT(物联网)Internet of Things__
> 通过传感器、网络和软件，把“物”连接到互联网，实现数据采集、传输、分析和自动决策的系统。

__RPA(机器人流程自动化)Robotic Process Automation__
> 用软件“机器人”来模拟人类在电脑上的操作，自动执行规则明确、重复性的业务流程

__AI__
> Predictive analysis, autonomous Systems

__ERP System(Enterprise Resource Planning，企业资源计划系统)__
> 把企业各个核心业务流程整合到一个统一系统中的管理平台，用于共享数据、协同流程和支持决策。
> 客户下单 → ERP 自动联动：
> Sales Order 创建
> 库存检查
> 不够 → MRP 生成采购/生产建议Material Requirements Planning，物料需求计划
> 采购下 PO (Purchase Order，采购订单)
> 收货 → 库存更新
> 财务自动入账
> 👉 一次输入，全系统联动

__QMS(Quality Management System，质量管理体系)__
> 一套用于确保产品和服务持续满足质量要求，并通过标准化流程实现持续改进的管理体系。
> Quality planning
> Quality assurance
> Quality control
> Continuous improvement

__PSI Planning(Purchase, Sales Inventory)__ 生产、销售、库存的平衡计划
> 用合适的生产，满足销售需求，同时把库存控制在合理水平
> __Production（生产）__ 产能 物料可得性
> __Sales（销售）__ Forecast（预测）Confirmed Orders（已确认订单）
> __Inventory（库存）__ 成品库存（FG）在制品（WIP）

__Supply Chain Finance（SCF，供应链金融）__
> 买方：想延长付款周期
> 供应商：想尽快回款
> 银行：想要低风险、可控现金流
> 👉 SCF 的作用：
> 在不牺牲供应商现金流的前提下，改善买方营运资本，同时降低整体融资成本。
> 1. __Accounts Payable Financing/Reverse Factoring（反向保理 / 买方保理）⭐最重要__
> 流程：
> 供应商发货 → 开票
> 买方确认应付账款（AP）
> 银行基于 买方信用 提前付款给供应商
> 买方在账期到期时再付给银行
> 2. __Accounts Receivable Financing(应收账款融资)__
> 用“已经卖出去、但还没收钱的账款”来换现金
> Factoring（保理）⭐
> 企业把应收账款 卖给银行/保理公司
> 银行立刻付 80–90%
> 客户付款后再结清余额 − 手续费
> 3. __Inventory Financing(库存融资)__
> 用“还没卖出去的库存”做抵押来融资
> Warehouse Financing
> 银行控制第三方仓库
> 出库需要银行放行

__Cost Control__
1. Incurred Cost(已发生成本)
> Actual expenses
2. Cost Constraints
> Predetermined limits set to manage and control cost in the supply chain
3. Fixed Cost(固定成本)
4. Variable Cost(变动成本)
5. Accruals(应计费用)
> 收入或费用在“发生时”确认，而不是在“现金实际收付时”确认。
> 货或服务已经“用掉 / 收到”，但发票还没来 → 要做 accrual
> 货已经运完 Carrier 账单下个月才来 但这批货 已经用于当月销售 👉 运费属于当月成本

__Transportation__
1. Inbound Transportation(入站运输)
> 供应商 → 公司
> 物料、零部件、原材料从供应商 → 企业仓库 / 工厂 / 配送中心 这一段的运输活动。
> 它发生在生产或销售之前，属于上游供应链（upstream supply chain）。
> ___
> 选择更便宜的运输模式（海运 vs 空运）
> 通过集中采购运力获得更低运价
2. Outbound Transportation(出站运输)
> 公司 → 客户
> 产品从企业 → 客户 / 经销商 / 零售商 / 最终消费者 这一段的运输活动。
> 它发生在销售之后或销售履约过程中，属于下游供应链（downstream supply chain）。
> ___
> __Batch picking(批量拣货)__
> 一次拣多个订单中“相同的 SKU”，而不是一个订单一个订单地拣。
> 传统拣货（Discrete Picking）拣货员走 10 次到 A 的货位
> Batch Picking  一次去 A 的货位拣 10 件A 再在分拣区按订单分配
> __Cross-docking(越库 / 直通配送)__
> 货物几乎不入库存，直接从 inbound → outbound 转运
> 不存、不堆、快进快出
> 供应商送来 100 箱商品 已提前分配到 10 家门店, DC(Distribution Center配送中心) 只负责拆分、贴标、转运
> __路线优化（route optimization）__

__RFID__
> RFID 是 Radio Frequency Identification（射频识别） 的缩写。
> 仓库门口装 RFID Gate
> 托盘一进门
> 系统自动知道：是什么、多少、来自哪里、去了哪里

__Secutiry Risks in Supply Chain__
1. Natural disasters
2. Theft and Pilferage 偷窃
3. Counterfeit products 假冒产品
4. Supply Chain disruptions
5. Unauthorized Access
6. Cyber Security Risks
7. Regulatory non-compliance 监管不合规
8. Transportation and logistics risks
9. Supplier and vendor risks
10. Information risks

__DATA__
1. Qualitative data 定性数据（主观）
> 
2. Quantitative data 定量数据 (可以计算)