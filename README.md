<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>图解：全国碳排放交易体系实务手册 | 核心知识全景图</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #f0f7f0;
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            color: #1a2c1e;
            line-height: 1.45;
            padding: 2rem 1.5rem;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
        }

        /* header */
        .hero {
            background: linear-gradient(135deg, #1b4d1a 0%, #2e7d32 100%);
            color: white;
            border-radius: 2rem;
            padding: 2rem 2rem 1.8rem;
            margin-bottom: 2rem;
            box-shadow: 0 12px 20px rgba(0,32,0,0.1);
        }
        .hero h1 {
            font-size: 2.2rem;
            font-weight: 700;
            letter-spacing: -0.01em;
            display: flex;
            align-items: center;
            gap: 1rem;
            flex-wrap: wrap;
        }
        .hero h1 i {
            font-size: 2.5rem;
            background: rgba(255,255,255,0.2);
            padding: 0.6rem;
            border-radius: 50%;
        }
        .hero .sub {
            font-size: 1.1rem;
            margin-top: 0.8rem;
            opacity: 0.9;
            border-left: 3px solid #a5d6a7;
            padding-left: 1rem;
        }
        .hero-badge {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
            flex-wrap: wrap;
        }
        .badge {
            background: rgba(255,255,255,0.2);
            padding: 0.3rem 1rem;
            border-radius: 40px;
            font-size: 0.85rem;
        }

        /* grid layout */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(380px, 1fr));
            gap: 1.8rem;
        }

        .card {
            background: white;
            border-radius: 1.5rem;
            box-shadow: 0 8px 20px rgba(0,0,0,0.05);
            overflow: hidden;
            transition: transform 0.2s ease, box-shadow 0.2s;
            border: 1px solid #d9ebd6;
        }
        .card:hover {
            transform: translateY(-4px);
            box-shadow: 0 18px 30px rgba(0,0,0,0.1);
        }
        .card-header {
            background: #eaf6e9;
            padding: 1rem 1.5rem;
            border-bottom: 3px solid #2e7d32;
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }
        .card-header i {
            font-size: 1.8rem;
            color: #1b5e20;
        }
        .card-header h2 {
            font-size: 1.45rem;
            font-weight: 700;
            margin: 0;
            color: #1b3b1a;
        }
        .card-content {
            padding: 1.2rem 1.5rem 1.5rem;
        }
        .card-content p {
            margin-bottom: 0.75rem;
            font-size: 0.92rem;
        }
        .feature-list {
            list-style: none;
            padding-left: 0;
        }
        .feature-list li {
            margin-bottom: 0.6rem;
            font-size: 0.9rem;
            display: flex;
            gap: 0.6rem;
            align-items: baseline;
        }
        .feature-list li i {
            color: #2e7d32;
            font-size: 0.85rem;
            width: 1.4rem;
            margin-top: 0.2rem;
        }
        .tag {
            background: #eef2e9;
            padding: 0.2rem 0.6rem;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 500;
            display: inline-block;
            margin-right: 0.4rem;
            margin-bottom: 0.4rem;
        }
        .divider-light {
            height: 1px;
            background: #e0e7df;
            margin: 1rem 0;
        }
        .stat-number {
            font-weight: 800;
            font-size: 1.2rem;
            color: #1b5e20;
        }
        .flex-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 0.5rem;
        }
        hr {
            margin: 0.6rem 0;
        }
        .footnote {
            margin-top: 2rem;
            text-align: center;
            font-size: 0.8rem;
            color: #4f694c;
            border-top: 1px solid #cfe2cc;
            padding-top: 1.5rem;
        }
        @media (max-width: 780px) {
            body { padding: 1rem; }
            .grid { grid-template-columns: 1fr; }
            .hero h1 { font-size: 1.6rem; }
        }
        .process-steps {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            background: #f8fef6;
            border-radius: 1rem;
            padding: 0.8rem;
            margin: 0.6rem 0;
            font-size: 0.8rem;
        }
        .step {
            text-align: center;
            flex: 1;
            font-weight: 500;
        }
    </style>
</head>
<body>
<div class="container">
    <div class="hero">
        <h1><i class="fas fa-leaf"></i> 全国碳排放交易体系 · 实务手册图解</h1>
        <div class="sub">基于生态环境部应对气候变化司审定教材 | 世界银行市场伙伴准备基金支持 · 1.0版本核心全景</div>
        <div class="hero-badge">
            <span class="badge"><i class="fas fa-chart-line"></i> 全球最大碳市场之一</span>
            <span class="badge"><i class="fas fa-industry"></i> 覆盖8大行业</span>
            <span class="badge"><i class="fas fa-coins"></i> 碳价机制·成本有效减排</span>
        </div>
    </div>

    <div class="grid">
        <!-- 综述卡片 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-globe-asia"></i><h2>综述 · 碳交易基础</h2></div>
            <div class="card-content">
                <p><strong>气候变化</strong>：全球气候变暖，主因工业化以来温室气体排放。碳交易是为应对气候变化，以配额/减排信用为标的的政策性市场。</p>
                <p><strong>为什么碳交易？</strong> 最具成本效益的减排工具，引导资本流向低碳，激发技术创新，推动能源结构优化和产业升级。</p>
                <p><strong>全球现状</strong>：约40个司法管辖区 + 20余城市推行碳价机制，覆盖约70亿吨CO₂e（全球15%）。</p>
                <p><strong>vs 碳税</strong>：碳税定价（政府定碳价），碳交易定量（政府定总量，市场定价格）。</p>
                <div class="process-steps">
                    <div class="step">📌 强制性市场</div>
                    <div class="step">📌 自愿性市场</div>
                    <div class="step">📌 一级市场(初始分配)</div>
                    <div class="step">📌 二级市场(现货交易)</div>
                </div>
                <p><i class="fas fa-sync-alt"></i> <strong>协同效益</strong>：改善空气质量、保护生物多样性、提升能源安全、创造绿色就业。</p>
            </div>
        </div>

        <!-- 法律体系 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-gavel"></i><h2>法律体系 · 强制力保障</h2></div>
            <div class="card-content">
                <ul class="feature-list">
                    <li><i class="fas fa-check-circle"></i> <strong>顶层法律设计</strong> – 争取以国务院行政法规出台，确立配额法律地位与处罚依据。</li>
                    <li><i class="fas fa-check-circle"></i> 目前依据《碳排放权交易管理暂行办法》(部门规章)，正推进《碳排放权交易管理条例》。</li>
                    <li><i class="fas fa-check-circle"></i> 配套制度：核算报告核查制度、配额管理制度、市场交易监管制度。</li>
                    <li><i class="fas fa-check-circle"></i> 违约惩罚：行政处罚 + 信用“黑名单”，保障履约强制力。</li>
                </ul>
                <div class="tag">《暂行办法》17号令</div>
                <div class="tag">《条例》建议稿已提交</div>
                <div class="tag">24个行业核算指南</div>
            </div>
        </div>

        <!-- 支撑系统 三合一 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-database"></i><h2>支撑系统 · 三大支柱</h2></div>
            <div class="card-content">
                <p><i class="fas fa-registered"></i> <strong>注册登记系统</strong> – 配额确权、分配、清缴、结算的中央“仓库”。功能：开户、配额管理、履约管理、清结算、信息查询。</p>
                <p><i class="fas fa-exchange-alt"></i> <strong>全国交易系统</strong> – 挂牌交易+协议转让，风控制度（涨跌幅、持仓限额、大户报告、风险警示），与注册登记系统对接实现DVP。</p>
                <p><i class="fas fa-chart-simple"></i> <strong>温室气体排放数据直报系统</strong> – 五大子系统（综合管理/数据报告/核算规则/质量控制/数据分析）。流程：名单确定→监测计划→数据报送→核查→分析发布。</p>
                <div class="flex-badges"><span class="tag">银货对付(DVP)</span><span class="tag">三级等保</span><span class="tag">数据质量模型</span></div>
            </div>
        </div>

        <!-- 覆盖范围 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-chart-pie"></i><h2>覆盖范围 · 控排边界</h2></div>
            <div class="card-content">
                <p><strong>气体种类</strong>：初期仅CO₂（占全国温室气体83.2%），强制报告范围包括其他温室气体。</p>
                <p><strong>排放类别</strong>：化石燃料燃烧排放 + 外购电/热间接排放（防碳泄漏）。</p>
                <p><strong>覆盖行业</strong>：石化、化工、建材、钢铁、有色、造纸、电力(含自备电厂)、航空八大行业，门槛年综合能耗≥1万tce（约2.6万tCO₂）。</p>
                <p><strong>行业子类示例</strong>：原油加工、乙烯、水泥熟料、平板玻璃、粗钢、电解铝、铜冶炼、纯发电、热电联产、航空客运等。</p>
                <div class="tag">自备电厂纳入电力</div><div class="tag">间接排放覆盖</div>
            </div>
        </div>

        <!-- 排放总量 + 特色 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-chart-line"></i><h2>排放总量 · 中国特色设计</h2></div>
            <div class="card-content">
                <p><strong>总量类型</strong>：绝对总量(固定上限) vs 强度总量(相对产出)。中国初期为<strong>基于强度的总量</strong> (Rate-based) —— 可交易绩效基准(TPS)，不同于欧美绝对总量Cap-and-Trade。</p>
                <p>总量由“碳排放绩效基准 × 实际产出”共同决定，兼顾经济增长与减排目标。公式逻辑：自上而下与自下而上结合，确保总量与基准值匹配碳强度下降目标。</p>
                <p><strong>关键关系</strong>：总量设定 = 覆盖行业基准值 × 活动水平，并与国家碳强度目标挂钩，实现成本有效减排。</p>
                <div class="tag">强度总量</div><div class="tag">行业基准驱动</div><div class="tag">总量灵活可控</div>
            </div>
        </div>

        <!-- 配额分配 核心 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-hand-holding-usd"></i><h2>配额分配 · 方法与流程</h2></div>
            <div class="card-content">
                <p><strong>分配方法</strong>：免费分配为主 + 拍卖为辅。免费方法采用<strong>行业基准法</strong>（产品相对单一行业，如发电、水泥、电解铝）和<strong>历史强度下降法</strong>（工艺复杂行业）。</p>
                <p><strong>基准法公式</strong>：配额 = 产品产量 × 行业基准值 × 修正系数。预分配（按历史产量70%/50%）+ 最终核定多退少补。</p>
                <p><strong>配额总量确定</strong>：自下而上由省级核算加总，国家统筹有偿分配及预留调节。</p>
                <p><strong>行业基准值研究</strong>：基于2013-2015年核查数据，取前5%累计产量加权平均等方法，兼顾公平与效率。</p>
                <div class="tag">预分配制度</div><div class="tag">基准值逐步收紧</div>
            </div>
        </div>

        <!-- 核算报告核查 MRV -->
        <div class="card">
            <div class="card-header"><i class="fas fa-clipboard-list"></i><h2>MRV制度 · 数据基石</h2></div>
            <div class="card-content">
                <p><strong>MRV</strong> = 监测(Monitoring) + 报告(Reporting) + 核查(Verification)。透明、准确、完整、一致为核算原则；核查坚持客观独立、诚实守信、公平公正。</p>
                <p><strong>工作流程</strong>：企业制定监测计划→备案→年度核算→提交排放报告→第三方核查→主管部门复查→确定排放量→用于履约。</p>
                <p><strong>技术支撑</strong>：24个行业核算指南 + 补充数据表 + 核查参考指南。国家碳市场帮助平台提供官方答疑。</p>
                <div class="flex-badges"><span class="tag">2013-15历史核查</span><span class="tag">2016-2018持续完善</span><span class="tag">外购电力因子0.6101 tCO₂/MWh</span></div>
            </div>
        </div>

        <!-- 履约机制 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-check-double"></i><h2>履约机制 · 清缴与处罚</h2></div>
            <div class="card-content">
                <p><strong>履约方式</strong>：自身减排、购买配额、购买抵消信用（CCER）。</p>
                <p><strong>两级管理</strong>：生态环境部负责顶层，省级生态环境部门主管辖区内配额分配、排放报告核查、配额清缴监督。</p>
                <p><strong>违约处罚</strong>：责令限期履行，逾期依法行政处罚；纳入全国信用信息共享平台，实施联合惩戒，建立“黑名单”。</p>
                <p><strong>履约流程</strong>：监测计划→排放报告→第三方核查→配额清缴（每年规定时间）→公布清缴情况。</p>
                <div class="tag">强制履约+信用惩戒</div>
            </div>
        </div>

        <!-- 市场监管 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-chart-simple"></i><h2>市场监管 · 风险防控</h2></div>
            <div class="card-content">
                <p><strong>监管范围</strong>：一级市场与二级市场，场内及场外交易，衍生品市场。</p>
                <p><strong>核心措施</strong>：涨跌幅限制、配额最大持有量限制、大户报告、风险警示、异常交易监控（自买自卖、虚假申报等）、风险准备金制度。</p>
                <p><strong>监管架构</strong>：国务院生态环境部门监管交易管理机构，交易管理机构监管交易参与人行为，并与清算所/注册登记系统协同防范系统性风险。</p>
                <i class="fas fa-shield-alt"></i> 重点防范操纵市场、异常波动，保障市场公平有序。
            </div>
        </div>

        <!-- 交易机制 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-chart-line"></i><h2>交易机制 · 产品与方式</h2></div>
            <div class="card-content">
                <p><strong>交易产品</strong>：国家配额、国家核证自愿减排量(CCER)，以及期货/期权等衍生品（未来探索）。</p>
                <p><strong>交易方式</strong>：<br/>🔹 挂牌交易（价格优先、时间优先，全额资金/配额）<br/>🔹 协议转让（大宗、关联交易适用，涨跌幅基准）</p>
                <p><strong>市场分层</strong>：一级市场(政府拍卖/分配) + 二级市场(现货/衍生品交易)。</p>
                <p>远期、期货合约有助于风险管理与价格发现，提升市场流动性。</p>
                <div class="tag">现货为主，衍生品逐步完善</div>
            </div>
        </div>

        <!-- 抵消机制 CCER 重点 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-recycle"></i><h2>抵消机制 · CCER补充履约</h2></div>
            <div class="card-content">
                <p><strong>定义</strong>：碳排放权交易体系外项目产生的减排量（国家核证自愿减排量，CCER），用于抵消配额清缴，降低履约成本。</p>
                <p><strong>原则</strong>：额外性、真实性、可核查。地理范围可本地或外省；需限制使用比例（试点地区5%-10%不等），防范低价冲击。</p>
                <p><strong>试点规则示例</strong>：北京≤5%且京外≤2.5%；广东≤10%且70%来自省内；湖北≤10%优先农村沼气/林业项目等。</p>
                <p><strong>CCER方法学</strong>：国家备案198个，覆盖可再生能源、林业碳汇、甲烷利用等。全国市场抵消机制将依托《温室气体自愿减排交易管理暂行办法》完善。</p>
                <div class="tag">增加灵活性</div><div class="tag">促进未覆盖行业减排</div>
            </div>
        </div>

        <!-- 额外卡片：工作原理 + 核心环节一览 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-cogs"></i><h2>工作原理 · 核心闭环</h2></div>
            <div class="card-content">
                <div class="process-steps" style="flex-direction:column; gap:0.3rem;">
                    <div>🏛️ 政府设定排放总量 → 发放/拍卖配额</div>
                    <div>🏭 控排企业获得配额 → 实际排放需与配额匹配</div>
                    <div>📊 核算报告与核查 (MRV) 确定真实排放量</div>
                    <div>🔄 配额富余者可出售，缺口者购买配额/抵消信用</div>
                    <div>⚖️ 履约清缴 → 违约处罚 → 信用约束</div>
                </div>
                <p><strong>15个关键环节</strong>：覆盖范围、总量设定、配额分配、MRV、履约、市场监管、抵消、法律基础、注册登记、交易平台等，环环相扣。</p>
                <i class="fas fa-link"></i> 配额价格信号引导长期低碳投资。
            </div>
        </div>

        <!-- 中国试点经验与全国进程 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-china-timeline"></i><h2>建设进程 · 试点到全国</h2></div>
            <div class="card-content">
                <p>2011年七省市试点（北京、天津、上海、重庆、湖北、广东、深圳）→ 2017年12月《全国碳排放权交易市场建设方案（发电行业）》发布，全国市场正式启动 → 发电行业首批纳入，逐步扩展至石化、化工、建材、钢铁、有色、造纸、航空。</p>
                <p>“十四五”深化，完善法律法规，扩大覆盖范围，探索配额有偿分配，强化数据质量与监管能力，建成国际影响力碳市场。</p>
                <div class="flex-badges"><span class="tag">发电行业先行</span><span class="tag">八大行业全覆盖</span><span class="tag">全球最大碳市场</span></div>
            </div>
        </div>
        
        <!-- 数据/关键指标 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-chart-simple"></i><h2>关键指标 · 速览</h2></div>
            <div class="card-content">
                <ul class="feature-list">
                    <li><i class="fas fa-chart-line"></i> 全国碳市场初期覆盖约40亿吨CO₂排放（发电行业）</li>
                    <li><i class="fas fa-building"></i> 纳入门槛：年综合能耗≥1万tce（约2.6万tCO₂）</li>
                    <li><i class="fas fa-calculator"></i> 核算指南：24个重点行业</li>
                    <li><i class="fas fa-percent"></i> CCER抵消比例：试点普遍5%~10%</li>
                    <li><i class="fas fa-coins"></i> 配额分配以免费为主，逐步引入拍卖机制</li>
                    <li><i class="fas fa-globe"></i> 中国碳强度目标：2030年前碳达峰，2060碳中和，碳市场为核心政策工具</li>
                </ul>
            </div>
        </div>

        <!-- 额外总结图解：履约年度闭环 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-calendar-alt"></i><h2>年度履约闭环 (典型流程)</h2></div>
            <div class="card-content">
                <div style="background:#eef3ec; border-radius:1rem; padding:0.8rem; font-size:0.85rem;">
                    <p><i class="far fa-calendar-check"></i> <strong>年初</strong>：省级确定名单，企业制定监测计划备案</p>
                    <p><i class="far fa-calendar-alt"></i> <strong>3~4月</strong>：企业提交上年度排放报告 & 第三方核查机构出具核查报告</p>
                    <p><i class="fas fa-chart-line"></i> <strong>5~6月</strong>：主管部门复查，确认最终排放量；配额最终核定多退少补</p>
                    <p><i class="fas fa-hand-holding-usd"></i> <strong>6~7月</strong>：配额清缴截止，不足部分通过市场购买或使用CCER</p>
                    <p><i class="fas fa-balance-scale"></i> <strong>逾期未缴</strong>：行政处罚 + 信用惩戒 + 强制收缴配额</p>
                </div>
            </div>
        </div>

        <!-- 协同效益与碳泄漏预防 -->
        <div class="card">
            <div class="card-header"><i class="fas fa-hand-holding-heart"></i><h2>协同效益 & 防泄漏设计</h2></div>
            <div class="card-content">
                <p><strong>协同效益</strong>：改善空气质量（协同治污）、保护生物多样性、促进清洁能源、技术创新、绿色就业。</p>
                <p><strong>防碳泄漏</strong>：覆盖间接排放（外购电/热），使用行业基准法保护高效企业，减少竞争力损失；免费配额向碳泄漏风险行业倾斜。</p>
                <p><strong>调节机制</strong>：预留配额用于市场调节，价格稳定机制(涨跌幅、配额结转等)防范剧烈波动。</p>
                <i class="fas fa-tree"></i> 碳市场与环保、能源政策形成合力，助推高质量发展。
            </div>
        </div>
    </div>

    <div class="footnote">
        <i class="fas fa-book-open"></i> 图解基于《全国碳排放交易体系实务手册》(1.0版) 核心内容 | 覆盖法律、支撑系统、覆盖范围、总量、配额分配、MRV、履约、监管、交易、抵消十大篇章<br>
        全国碳市场建设持续推进，本图解旨在快速掌握框架，详细操作请参考最新官方技术指南及政策文件。
    </div>
</div>
</body>
</html>
