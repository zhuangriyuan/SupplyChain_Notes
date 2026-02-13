# Supply Chain Management

### Course2 Module 1
### Supply Chain Operations运营

__Supply Chain Operations__
> In supply chain, operation refers to the process of transformation. We transform input, raw material, machinery and labor into outputs, our finished products.

__4 Goals to make operations better__

__1. Cost__
> Minimize the total cost of operations while meeting demand.

__2. Quality__
> Deliver products and services that consistently meet customer and specification requirements.

__3. Speed__
> respond quickly to customer demand and reduce lead time.

__4. Flexibility__
> Adapt efficiently to changes in demand, volume, or product mix.

__Lean Operations(精益运营)__
> Lean Operations focuses on maximizing customer value while minimizing waste across operational processes.
> Lean Operations是一种以消除浪费（waste）为核心、在不牺牲客户价值的前提下持续提升效率与质量的运营管理理念.

__Lean 中最重要的概念：7 大浪费（TIMWOOD）__
1. Transportation – 不必要的运输
2. Inventory – 过多库存
3. Motion – 不必要的动作（多走路、多搬）
4. Waiting – 等待（人等料、料等人）
5. Overproduction – 过量生产
6. Overprocessing – 过度加工
7. Defects – 缺陷与返工

__The 5 Lean Principles(精益五大原则)__
__1. Define Value from the Customer’s Perspective__
> Value is defined by what the customer is willing to pay for.
> 不是公司觉得重要，而是客户觉得有价值
> 非增值活动（inspection、等待、返工）应被消除或最小化

__2. Identify the Value Stream__
> Map all activities required to deliver a product or service.
> 系统性地识别并梳理从客户下单开始，到产品或服务交付结束的所有活动、流程和信息流。
> 从原材料 → 成品 → 客户

__3. Make Value Flow__
> Ensure that value-added activities flow smoothly without interruption.
> 消除瓶颈、等待、返工
> 减少 lead time

__4. Pull from the Customer Back__
> Produce only what is needed, when it is needed, based on actual customer demand.
> 拉动式（Pull）而不是推动式（Push）
> Demand-driven

__5. Strive for Perfection__
> Continuously improve processes to eliminate waste and variability.
> Lean is a journey, not a destination.

__Theory of Constraints(约束理论)__
__1. Identify the Constraint__
> 找出限制系统产出的瓶颈.哪一步排队最长？哪台机器永远最忙？

__2. Exploit the Constraint__
> Exploit the Constraint利用约束
> 充分利用瓶颈现有能力（不增加资源）
> 减少瓶颈等待
> 不让瓶颈做“非必要工作”

__3. Subordinate服从 Everything Else__
> 让其他流程服从瓶颈 非瓶颈不能超产 避免为“看起来很忙”而生产

__4. Elevate提升 the Constraint__
> Elevate the Constraint
> 如果仍不足，增加瓶颈能力
>加班 增加设备/人力  外包

__5. Repeat the Process__
> 瓶颈会转移, 回到第 1 步，持续改善

### Module 2
__Lean Inventory(精益库存)__
> Lean Inventory is an inventory management approach that aims to minimize inventory levels while still meeting customer demand, by eliminating waste and improving process efficiency.
> 精益库存是一种库存管理方法，目标是在满足客户需求的前提下，将库存水平降到最低，通过消除浪费和提升流程效率来实现。

__Economic Order Quantity (EOQ)经济订货批量__
> Economic Order Quantity (EOQ) is a formula used to determine the optimal order quantity that minimizes the total inventory cost, which includes ordering costs and holding (carrying) costs.
> 经济订货批量（EOQ）是一种用于确定最优订货数量的模型，目标是在订货成本和库存持有成本之间取得平衡，从而使总库存成本最低。

__EOQ = $\sqrt{\frac{2DS}{H}}$__

| Symbol | Meaning (EN)                   | 含义（中文）    |
| ------ | ------------------------------ | --------- |
| D      | Annual demand                  | 年需求量      |
| S      | Ordering cost per order        | 每次订货成本    |
| H      | Holding cost per unit per year | 单位年库存持有成本 |
| EOQ    | Optimal order quantity         | 最优订货批量    |

__Cost Logic 成本逻辑__
> Ordering cost decreases as order size increases
> Holding cost increases as order size increases
> EOQ is the point where total cost is minimized
> EOQ 越大 → 每次订得多 → 订货次数少，库存成本高
> EOQ 越小 → 每次订得少 → 库存成本低，订货次数多，订货成本高
> EOQ 是总成本最低的平衡点
> ——————
> 计算出来的值：
> 一个 订货量（单位数量）
> 举例：EOQ = 500 → 每次采购 500 件最经济

举例：EOQ = 500 → 每次采购 500 件最经济

EOQ balances ordering and holding costs to minimize total inventory cost under stable demand conditions.
EOQ 用于在需求稳定的前提下，平衡订货成本和库存持有成本，从而实现总库存成本最小化。

__Total Cost（总库存成本）__
> EOQ 模型中的总成本（TC）是指某一订货批量下所有库存相关成本的总和，帮助管理者找到订货成本和持有成本之间的最优平衡。
__Total Cost (TC)=Ordering Cost+Holding Cost__ 订货成本+库存持有成本
> __Ordering Cost= D/Q × S__

| Symbol | 含义                     |
| ------ | ---------------------- |
| D      | Annual demand（年需求量）    |
| Q      | Order quantity（订货批量）   |
| S      | Cost per order（每次订货成本） |

> __Holding Cost=Q/2 ​× H__

| Symbol | 含义                             |
| ------ | ------------------------------ |
| Q      | 订货批量                           |
| H      | Holding cost per unit per year |

Total Cost: $TC(Q) = \frac{D}{Q}S + \frac{Q}{2}H$

### Module 3
__Six Sigma__
> Six Sigma is a data-driven methodology for process improvement and quality management, aiming to reduce variation and defects and improve process stability and predictability.
> Six Sigma 是一种以数据和统计方法为基础的流程改进与质量管理方法，目标是减少流程变异和缺陷，提升流程稳定性和可预测性。

__5 Measures__
__DMAIC__
1. Define（定义） / Define
> 明确问题、客户需求（CTQ）、项目范围
> Define the problem, customer requirements (CTQs), and project scope

2. Measure（测量） / Measure
> 收集数据，建立当前流程基线
> Collect data and establish the current baseline

3. Analyze（分析） / Analyze
> 找出问题的根本原因
> Identify root causes of defects or variation

4. Improve（改进） / Improve
> 设计并实施解决方案
> Develop and implement solutions

5. Control（控制） / Control
> 维持成果，防止问题反弹
> Sustain improvements and prevent regression

