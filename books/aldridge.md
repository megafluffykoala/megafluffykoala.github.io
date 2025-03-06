<link href="../whirlwind.css" rel="stylesheet">

<whirlheader>
    <p>megafluffykoala</p>
    <p>High Frequency Trading</p>
    <p>2025</p>
</whirlheader>

# 1. Introduction 

<details>
<summary>Introduction to HFT</summary>

  - HFT has become highly profitable, with Jim Simons of Renaissance Technologies earning $2.5 billion in 2008.
  - In 2008, high-frequency managers performed better than low-frequency managers, with 70% of the latter losing money.
  - HFT accounted for over 60% of total trading volume as of 2009.
  - The demand for HFT professionals surged, even during the 2008 financial crisis, making up 50% of open finance positions.
  - HFT strategies focus on rapid computer-driven responses with high turnover of capital, generating small returns per trade.

</details>

<details>
<summary>Advantages of HFT</summary>

  - HFT avoids overnight risk, important in the globalized and volatile markets.
  - Full transparency of account holdings eliminates the need for capital lock-ups.
  - High-frequency strategies eliminate overnight carry costs associated with margin positions.
  - These strategies provide diversification for long-term portfolios, having low correlation with traditional buy-and-hold methods.
  - High-frequency strategies can be evaluated statistically in shorter periods (as little as one month) compared to traditional strategies that require years of observation.

</details>

<details>
<summary>Operational and Societal Benefits</summary>

  - HFT increases market efficiency and liquidity by addressing temporary market inefficiencies.
  - It stimulates innovation in computer technology, particularly in data processing and internet communication.
  - These strategies help stabilize market systems by correcting mispricings quickly.
  - HFT can be compared to human blood circulating in the body, keeping financial markets stable like blood stabilizes the circulatory system.
  - Major financial hubs for HFT include New York, Connecticut, London, Singapore, and Chicago, each focusing on specific markets like equities, currencies, or futures.

</details>

<details>
<summary>Types of HFT Strategies</summary>

  - Automated liquidity provision: Uses quantitative algorithms for pricing and execution in market-making positions with holding periods under 1 minute.
  - Market microstructure trading: Identifies order flow by reverse engineering observed quotes with holding periods under 10 minutes.
  - Event trading: Focuses on short-term trades based on macroeconomic events with holding periods under 1 hour.
  - Deviations arbitrage: Exploits statistical arbitrage opportunities from price deviations, including triangle trades and basis trades with holding periods under 1 day.
  - Each strategy involves rapid execution and precise market signals to maximize small price movements.

</details>

<details>
<summary>Challenges in HFT</summary>

  - Large volumes of intra-day data require new tools for processing and analysis due to irregular spacing.
  - High precision in trading signals is necessary to avoid quick reversals in profitability, as even small misalignments can lead to losses.
  - Speed of execution is crucial; traditional phone-in orders are not feasible, and automation of order generation and execution is essential.
  - Programming high-frequency systems requires advanced skills in software development, and run-time errors are costly.
  - Ongoing maintenance and upgrades are necessary to keep up with technological advancements in IT and hardware from competitors.

</details>

<details>
<summary>HFT System Development</summary>

  - High-frequency systems require at least two years of backtesting, with more than four years of data being ideal for comprehensive analysis.
  - The precision of signals is critical, and even minor errors can lead to significant losses.
  - Human supervision is crucial to monitor the system and ensure it stays within prespecified risk boundaries, though intervention is minimal.
  - The speed of execution is paramount, requiring automated order systems capable of executing trades in fractions of a second.
  - Constant updates to hardware and software are needed to maintain competitiveness in the HFT environment.

</details>

<details>
<summary>HFT and Market Segmentation</summary>

  - The primary markets for HFT include foreign exchange, equities, futures, and derivatives, all of which must be sufficiently liquid.
  - HFT can occur around the clock, with 24-hour trading available for forex markets and extended hours for U.S. equities.
  - The market's geographical segmentation: New York and Connecticut for equities, London for currencies, and Chicago for futures and options.
  - The firms involved in HFT often include hedge funds and proprietary desks of major banks, which are spun out into separate hedge funds.
  - Major global players include Millennium, DE Shaw, Worldquant, and Renaissance Technologies, with firms specializing in various financial instruments.

</details>

<details>
<summary>Book Overview and Target Audience</summary>

  - The book is a guide for understanding HFT and its practical applications, focused on strategies based on academic research.
  - It is structured into five parts: History and business environment, statistical and econometric foundations, modeling strategies, building systems, and operational aspects of trading.
  - Target audience includes senior management, institutional investors, quantitative analysts, IT staff, and aspiring traders.
  - The book presents quantitative trading strategies based on academic literature, providing a roadmap for practical implementation.
  - While strategies in the book may eventually become obsolete due to public knowledge, the goal is to inspire new, profitable innovations in the field.

</details>

# 2. Evolution of HFT 

<details>
<summary>Introduction to HFT</summary>
 
  - Advances in computer technology have supercharged the transmission and execution of orders.
  - These advances have compressed the holding periods required for investments.
  - The application of quantitative simulations of market behavior, based on large sets of historical data, led to the creation of HFT.
  - The chapter discusses the historical evolution of trading and how technological breakthroughs impacted financial markets.
  - It also examines how these breakthroughs facilitated the emergence of HFT.

</details>

## Financial Markets and Technological Innovation

<details>
<summary>Technological Innovation in Financial Markets</summary>

- Technological innovation has been one of the most persistent influences on financial markets.
- Unlike one-time disruptions like new market securities, technological changes have a continuous and subtle impact.
- Improvements in technology have enhanced news dissemination, financial analysis, and communication speed.
- Although technology has reduced inefficiencies in markets, it has also created new arbitrage opportunities.
- Early market communication was slow, error-prone, and expensive, with high costs passed on to clients.

</details>

<details>
<summary>Manual Securities Markets and Early Communication Issues</summary>

- In the past, securities markets operated manually, with clients contacting sales representatives for quotes.
- The communication was slow, involving multiple human steps, leading to errors from misheard data and market fluctuations.
- Market prices could move significantly during the time between quote request and delivery.
- Errors arose from inefficient human communication channels at various steps in the chain.
- This system was costly, with compensation at each step passed on to clients.

</details>

<details>
<summary>Introduction of Electronic Dealing Systems in the 1980s</summary>

- The first electronic dealing systems appeared in the 1980s, revolutionizing market operations.
- These systems aggregated data from multiple dealers and exchanges and distributed it to market participants.
- The systems allowed pre-approved parties to trade with each other at the best available prices.
- They created reliable information logs and transaction histories.
- The New York Stock Exchange (NYSE) introduced DOT (Designated Order Turnaround) as the first electronic execution system.

</details>

<details>
<summary>Adoption and Growth of Systematic Trading</summary>

- Systematic trading gained traction in the 1990s, despite initial obstacles like high computing costs.
- NASDAQ launched electronic execution in 1985 but limited it to smaller orders of up to 1,000 shares.
- Exchanges like AMEX and NYSE introduced hybrid systems that combined electronic and floor trading.
- The adoption of technology by financial institutions fueled increased demand for automated trading.
- Systematic trading saw a rise in hedge funds, particularly in the early 1990s, coinciding with the launch of CME’s Globex platform.

</details>

<details>
<summary>Electronic Trading Expansion and Asset Class Adoption</summary>

- The CME's Globex platform began with currency futures and expanded to equity futures by 1993.
- By 2002, electronic trading on the CME reached 1.2 million contracts daily.
- The first fully electronic U.S. options exchange was launched by the International Securities Exchange (ISE) in 2000.
- By mid-2008, seven exchanges offered fully electronic or hybrid options trading.
- Electronic trading adoption grew rapidly across different asset classes, from equities to futures, options, and fixed income.

</details>

<details>
<summary>Market Structure Changes and Decentralization</summary>

- Technological advances led to a shift from a rigid hierarchical structure to a decentralized network in financial markets.
- Traditional market structures included broker-dealers, exchanges, and inter-dealer networks.
- The internet and online broker-dealers flattened the financial services structure, removing multiple broker layers.
- Dealers often “run books” and charge clients a spread for holding securities inventories.
- With decentralization, competing exchanges and liquidity pools have become more prominent.

</details>

<details>
<summary>Rise of Electronic Communication Networks (ECNs) and Dark Pools</summary>

- Electronic Communication Networks (ECNs) are replacing traditional exchanges and broker-dealers.
- ECNs use sophisticated algorithms to quickly match buyers and sellers while ensuring anonymity.
- Dark pools like Automated Trading Desk (ATD) allow traders to operate without revealing identities or market depth.
- ECNs like Island and ATD allow for anonymous liquidity, ensuring privacy for traders.
- Algorithms are used to monitor disruptive behaviors like spread manipulation and penalize offenders.

</details>

<details>
<summary>Modern Trading Network Structure</summary>

- Contemporary financial networks incorporate ECNs and dark pools for increased liquidity.
- The network structure is decentralized, allowing direct connections between exchanges, ECNs, and broker-dealers.
- Exchanges, ECNs, and dark pools play key roles in clearing and settling transactions.
- Retail brokerages and institutional clients now interact through these decentralized networks.
- Institutions like Citadel have acquired broker-dealer arms to clear trades in-house, changing the market landscape.

</details>

## Evolution of Trading Methodology 

<details>
<summary>Evolution of Trading Methodology</summary>

- Early traders used technical analysis to identify recurring patterns in security prices.
- Techniques like moving average convergence divergence (MACD) used three exponential moving averages for trading signals.
- Technical analysis prospered when trading technology was limited, allowing analysts to infer future price movements from past data.
- In the post-WWII era, technical analysis became self-fulfilling, as traders acted on patterns like "head-and-shoulders," influencing market behavior.
- Today, technical analysis at low frequencies applies mostly to small, illiquid securities, with some evidence of success in intra-day data.

</details>

<details>
<summary>Fundamental and Microstructure Analysis</summary>

- Fundamental analysis evaluates securities based on economic factors like cash flows and macroeconomic variables.
- The method was expanded to include non-cash flow-based pricing models, like those used in foreign exchange and commodities.
- Event arbitrage is a high-frequency strategy where fundamental analysis is used to predict and capitalize on market reactions to news events.
- HFT models often integrate both fundamental analysis and market microstructure to detect latent market information.
- Quantitative analysis, developed by "quants," has taken over from traditional technical and fundamental approaches, leading to statistical arbitrage.

</details>

<details>
<summary>Rise of Quantitative Trading</summary>

- Quants used advanced mathematical models for trading, radically departing from traditional methods.
- Statistical arbitrage (stat-arb) strategies became a key focus in the finance world, driven by high-speed computation.
- The competition for speed in executing quant models became crucial, as faster identification of market inefficiencies led to higher profits.
- Advances in computer technology led to the adoption of systematic trading, where algorithms made buy-and-sell decisions based on runtime data.
- HFT emerged in the 1990s, fueled by technological advancements, becoming a billion-dollar industry.

</details>

<details>
<summary>Algorithmic and HFT</summary>

- Algorithmic trading optimizes the execution of trades, deciding the most efficient way to process orders based on market conditions.
- Algorithms can execute trades passively (on limit prices) or aggressively (near market prices) and decide how to split large orders.
- HFT systems are distinguished by their extremely short position holding times (often no overnight positions).
- Algorithmic execution typically focuses on optimizing the timing and routing of orders, while high-frequency models focus on generating trading signals.
- HFT requires both signal generation algorithms and execution optimization algorithms, with signal generation being more complex.

</details>

<details>
<summary>Systematic Trading vs. HFT</summary>

- Systematic trading refers to computer-driven trading that may involve longer holding periods (from minutes to days) and may not be high-frequency.
- HFT, characterized by rapid execution, has no overnight positions, and executes decisions in real-time, often using systematic and algorithmic strategies.
- Algorithmic trading has become the standard in many markets, though HFT is distinct by its short-term, rapid execution style.
- Institutional and retail investors are drawn to HFT for its low correlation with traditional strategies, offering additional alpha to portfolios.
- HFT has become more widespread as computer technology has improved and its costs have decreased, leading to more widespread adoption.

</details>

<details>
<summary>Adoption of Algorithmic Trading</summary>

- Algorithmic trading adoption in equities increased significantly, with more than 50% of equity trades expected to be executed by algorithms by 2010.
- Futures trading followed closely in algorithm adoption, while foreign exchange, options, and fixed income markets lagged due to OTC trading structures.
- Institutional investors and buy-side traders have increased their use of algorithms for better execution and anonymity, which helps avoid order poaching.
- Anonymity in algorithmic execution protects large investors from revealing their positions and intentions, thereby improving profitability.
- Systematic and algorithmic trading has been shown to outperform human-led trading strategies, particularly during crises, due to the lack of emotion in automated models.

</details>

<details>
<summary>Performance of Systematic Trading</summary>

- Systematic funds outperform traditional trading operations on several key metrics, particularly in terms of raw returns and risk-adjusted measures like Jensen's alpha.
- Automated strategies, devoid of human emotion, have proven more consistent and successful during periods of market stress or crisis.
- Quantitative models, used in both systematic and HFT, perform better by exploiting market inefficiencies with speed and precision.
- Research by Aldridge (2009) shows that systematic funds outperformed nonsystematic funds during financial crises, attributing success to their objective, emotion-free nature.
- The adoption of systematic trading is linked to its ability to generate alpha and enhance portfolio performance compared to traditional strategies.

</details>

# 3. Overview of the Business of HFT 

<details>
<summary>HFT Survey and Characteristics</summary>

- According to a 2009 survey by FINalternatives.com, 90% of asset managers thought HFT had a bright future.
- Only 50% of respondents believed the investment management industry had favorable prospects.
- 42% considered the U.S. economy to have a positive outlook.
- Key characteristics of HFT identified by respondents: tick-by-tick data processing, high capital turnover, intra-day entry and exit of positions, and algorithmic trading.
- "High-frequency" refers to fast entry and exit of trading positions, with 86% of respondents associating it with holding periods of one day or less.

</details>

<details>
<summary>Tick-by-Tick Data Processing and High Capital Turnover</summary>

- Tick-by-tick data processing involves identifying small changes in the quote stream to send signals for opening and closing positions.
- High capital turnover refers to quickly entering and exiting positions, a hallmark of HFT.
- This fast trading allows HFT firms to capitalize on micro market movements.
- The term "high-frequency" refers to fast trade execution, often with positions held for one day or less.
- The survey results highlighted that 86% of respondents saw HFT as involving very short holding periods (one day or less).

</details>

<details>
<summary>Intra-Day Position Management and Carry Costs</summary>

- Intra-day position management helps reduce the cost of holding positions overnight, known as carry costs.
- Carry costs are calculated based on the margin portion of account holdings after North American trading sessions close.
- Carry charges can significantly impact trading profitability, especially during periods of high interest rates or tight lending.
- Reducing overnight holdings lowers the exposure to carry charges, increasing the overall profitability of trading strategies.
- Minimizing the need to hold positions overnight through intra-day trading allows for better capital utilization.

</details>

<details>
<summary>Closing Positions and Risk Exposure</summary>

- Closing positions at the end of each trading day minimizes exposure to passive overnight risk.
- Overnight positions can result in risk exposure as market conditions may change after the close.
- By reducing overnight risk, traders can avoid carry costs and potential market changes that could impact positions.
- Smaller overnight risk exposure results in improved risk-adjusted returns.
- This practice is crucial in HFT for optimizing profitability by avoiding unnecessary risk.

</details>

<details>
<summary>Algorithmic Trading in HFT</summary>

- Algorithmic trading is an essential component of HFT platforms, automating the decision-making process.
- Evaluating tick-by-tick data and making continuous trading decisions is impractical for humans due to speed and volume.
- Algorithms make fast, efficient, and emotionless trading decisions, which are necessary in HFT environments.
- The ability of algorithms to process market information in real-time allows for more precise and faster trade execution.
- As a result, algorithmic trading is fundamental to executing high-frequency strategies effectively.

</details>

## Comparison With Traditional Approaches To Trading

<details>
<summary>Technical, Fundamental, or Quant?</summary>

  - **Technical trading** focuses on identifying persistent price change patterns through technical analysis.  
  - Technical analysis suggests buying securities deemed too low in price or selling those deemed too high based on past price trajectories.  
  - **Fundamental trading** relies on fundamental analysis, which uses available information and economic equilibrium theories to derive equilibrium price levels.  
  - Fundamental trading involves buying undervalued securities and selling overvalued ones, based on an analytically determined value.  
  - **Quantitative (Quant) trading** uses scientific principles (including fundamental or technical data, or statistical relationships) to make portfolio allocation decisions, without discretionary judgment.  

</details>

<details>
<summary>Quantitative Trading in HFT</summary>

  - Quant frameworks are well-suited for HFT because HFT does not allow time for subjective decisions or discretion.  
  - Quantitative trading can incorporate both technical and fundamental models within high-frequency settings.  
  - HFT models use **statistical relationships** to drive decisions, ensuring rapid execution without human input.  
  - Quants rely on **data-driven approaches**, minimizing the need for personal analysis or interpretations in decision-making processes.  
  - Unlike technical or fundamental traders, quants rely heavily on automated systems that handle complex data processing and trading logic.  

</details>

<details>
<summary>Algorithmic, Systematic, Electronic, or Low-Latency?</summary>

  - **HFT** refers to the fast reallocation or turnover of trading capital.  
  - Most HFT systems are built using **algorithmic trading** models, which employ complex computer algorithms to analyze data, make decisions, and execute trades.  
  - **Electronic trading** refers to trading systems that automatically route orders; all HFT systems fall under this category, but not all electronic trading systems are algorithmic.  
  - **Low-latency trading** focuses on minimizing the time taken to execute orders. Low-latency execution is crucial for arbitraging instantaneous price differences.  
  - **Algorithmic trading systems** may or may not be high-frequency but are integral to HFT systems due to their need for fast data processing and trade execution.  

</details>

<details>
<summary>Low-Latency Trading</summary>

  - **Low-latency trading** refers to the ability to execute orders with minimal delay, independent of the time a position is held.  
  - **Low-latency execution** is critical for exploiting arbitrage opportunities, where price discrepancies on the same security occur across different exchanges.  
  - Low-latency systems aim to reduce transmission and processing delays to achieve faster order placement and execution.  
  - In the context of HFT, **low-latency** is a necessary feature to quickly capitalize on rapid market changes.  
  - **Low-latency trading** can be a strategy by itself, leveraging speed to make trading decisions based on momentary price differences.  

</details>

<details>
<summary>Confusion Between Terms</summary>

  - There is often confusion between **HFT**, **algorithmic trading**, **systematic trading**, **electronic trading**, and **low-latency trading**.  
  - **HFT** is specifically about rapid capital turnover and fast reallocation of trading positions.  
  - **Algorithmic trading** is the use of computer algorithms to manage the trading process, which may or may not involve high-frequency strategies.  
  - **Electronic trading** is a broader category that encompasses any trading done electronically, including but not limited to high-frequency or algorithmic trading.  
  - **Low-latency** is associated with the **speed** of order execution rather than the frequency or method of trading.  

</details>

## Market Participants 

<details>
<summary>Market Participants</summary>

  - **Competitors**: HFT firms compete with proprietary trading divisions of investment banks, hedge funds, and independent proprietary trading operations.  
  - The largest independent HFT firms are **DE Shaw**, **Tower Research Capital**, and **Renaissance Technologies**.  
  - **Investors**: Investors in HFT include fund of funds, hedge funds, and private equity firms looking for opportunities to create wealth and diversify their portfolios.  
  - Most investment banks offer **prime services**, providing leverage to investors in the HFT space.  
  - HFT firms target quick access to market inefficiencies, trading capital, and recruitment of talented strategists.  

</details>

<details>
<summary>Services and Technology Providers</summary>

  - **Electronic Execution**: High-frequency traders depend on executing brokers and **electronic communication networks (ECNs)** to route and execute trades.  
  - Major **ECN players**: **ICAP** and **Thomson/Reuters** are significant providers in the ECN space.  
  - **Custody and Clearing**: Broker-dealers offer custody (safekeeping of capital) and clearing (trade reconciliation) services, which carry certain risks.  
  - Transaction cost mark-ups are used to compensate broker-dealers for their **custody** and **clearing** services and associated risks.  
  - HFT operations also rely on specialized **software** for trading, risk management, analysis, and execution.  

</details>

<details>
<summary>Software for HFT</summary>

  - **Computerized Trading Signal Generation**: The core functionality of a HFT system that processes tick data, generates portfolio allocations, and records profit and loss (P&L).  
  - **Computer-Aided Analysis**: Financial modeling software like **MatLab** and **R** are widely used to build new trading models.  
  - **Information-Gathering Software**: Tools for gathering real-time news, rumors, and announcements, which aid in short-term price forecasting; **Thomson/Reuters** provides such machine-readable news feeds.  
  - **Trading Software**: Tools for optimal execution, market aggressiveness decisions, and order sizing to achieve the best execution price; **MarketFactory** offers a suite of tools to improve market performance.  
  - **Run-Time Risk Management**: Applications that ensure systems stay within pre-specified behavioral and P&L bounds; these systems also provide fault tolerance and monitoring functions.  

</details>

<details>
<summary>Legal, Accounting, and Professional Services</summary>

  - HFT firms require **legal** and **accounting** professionals to ensure compliance with regulations and to manage the financial aspects of the operation.  
  - These services are essential to ensure that all legal requirements are met and all financial operations are accounted for accurately.  
  - The financial sector demands that **legal** and **accounting** procedures are meticulous, as errors can result in significant risks.  
  - Firms rely on qualified legal and accounting assistance to build and maintain robust, compliant operations.  
  - Professional services in legal and accounting fields are integral to the structure and operation of HFT businesses.  

</details>

<details>
<summary>Government Regulation</summary>

  - HFT is subject to the same regulations as **day trading**, including rules on avoiding insider trading.  
  - **Regulations**: The industry is governed by common trading rules that prohibit illegal activities like insider trading.  
  - A proposed **surcharge on transaction costs** as an additional regulatory measure was unsuccessfully introduced in February 2009.  
  - Despite the lack of additional regulations, HFT still faces scrutiny under existing trading rules.  
  - The government regulates the industry under broader rules applicable to securities trading, with specific attention to fair trading practices.  

</details>

## Operating Model 

<details>
<summary>Operating Model Overview</summary>

  - HFT systems involve **three main components**: econometric models, advanced computer systems, and capital management.  
  - **Econometric models** forecast short-term price movements based on market conditions, while computer systems quickly execute these models.  
  - **Capital** is applied and monitored within risk and cost-management frameworks.  
  - The main difference between traditional trading and HFT is that HFT systems profit from repeatedly capturing small price deviations during the day.  
  - Developing an HFT business is costly during the **model development phase** but low-cost in **execution and monitoring** once a system is deployed.  

</details>

<details>
<summary>Model Development</summary>

  - The development of HFT begins with **econometric models** that document relationships among securities, followed by back-testing on tick-by-tick data for validation.  
  - **Back-testing** requires at least two years of data to ensure the models are robust across various market conditions.  
  - The modeling process is a blend of **academic research** and proprietary extensions, using tools like **MatLab** or **R** with custom libraries.  
  - For production, models are transitioned into **C++** for faster execution, moving from the **testing phase** (paper trading) to live trading with real capital.  
  - The **back-tested models** are crucial for ensuring that the econometric relationships hold true in real market conditions.  

</details>

<details>
<summary>System Implementation</summary>

  - **C++ programming** is used to optimize econometric models for high-speed execution after initial testing in **MatLab** or **R**.  
  - Systems are first tested in **paper trading** using simulated capital to identify bugs and ensure proper functionality before moving to live capital.  
  - A **HFT system** in production performs six major tasks: receiving real-time data, generating buy/sell signals, tracking positions and P&L, managing risk, evaluating performance, and managing trading costs.  
  - **Block A** handles real-time data reception, while **Block B** processes it through back-tested models to generate trading signals.  
  - **Block C** manages orders and positions, **Block D** monitors trading behavior, **Block E** evaluates performance, and **Block F** ensures trading costs are controlled.  

</details>

<details>
<summary>Run-Time and Post-Trade Workflows</summary>

  - The six functional blocks of an HFT system each have independent alert systems to notify personnel of issues, such as market data disruptions, unexpected high trading costs, or order transmission problems.  
  - **Alerts** are triggered for unusual patterns, like unforeseen market behavior or system malfunctions.  
  - The system operates in **continuous iterative cycles**, with each cycle expanding the scope of execution and performance monitoring.  
  - **Figure 3.6** illustrates the iterative process, where the system moves from planning to production in stages: planning, analysis, design, implementation, and maintenance.  
  - The development cycle continues to evolve as **new iterations** are implemented to enhance the system's capabilities and efficiency.  

</details>

<details>
<summary>Trading Platform and Risk Management</summary>

  - Most HFT systems are designed to be **platform-independent**, allowing flexible interfaces to various brokers, ECNs, and exchanges.  
  - **FIX protocol** is used to facilitate easy switching between brokers and exchanges, enabling rapid re-routing of trades.  
  - **Risk management** is critical in HFT to address potential issues like glitches, bad market data, or changing market conditions that can result in significant losses.  
  - The objective of **risk management** is to assess potential damages and create infrastructure that mitigates risks during run-time.  
  - Comprehensive **risk management** frameworks are detailed further in Chapter 17, ensuring that HFT systems can withstand disruptions and maintain profitability.  

</details>

## Economics

<details>
<summary>Revenue Driven by Leverage and the Sharpe Ratio</summary>

  - For a HFT operation to remain viable, revenues must cover **expenses**, including employee salaries, administrative services, trading costs, and legal/compliance fees.  
  - The business pays out **80%** of revenues to investors, with the remaining amount allocated as **performance fees** for management and a **fixed management fee** for administrative expenses.  
  - Fixed expenses for a trading business with five employees can total **$600,000 per year**, including salaries and office expenses, not including additional incentives.  
  - The **minimum return** required to break even for a trading operation depends on the leverage used. A $20 million unlevered fund with five employees needs a **12% return** per year, while the same fund levered 500% requires just **3%** return.  
  - The **Sharpe ratio** plays a crucial role in determining the risk of losses, with a higher Sharpe ratio lowering the probability of severe losses, regardless of leverage.  

</details>

<details>
<summary>Leverage and Risk of Losses</summary>

  - **Leverage increases the risk** of losses, but the probability of severe losses is more dependent on the **Sharpe ratio** of the trading strategy than on leverage.  
  - A **Sharpe ratio of 0.5** for an unlevered fund expecting 20% return translates into a **15% risk** of losing 20% of the capital, while levering the same fund nine-fold increases the risk only slightly to **30%**.  
  - A **Sharpe ratio of 2.0** for an unlevered fund expecting 20% return results in only **0.1% risk** of losing 20% of the capital, and levering the same fund increases the risk to just **1.5%**.  
  - For any given Sharpe ratio, the probability of losing at least 20% of equity increases with **higher expected returns**, reflecting wider return dispersions.  
  - Investors prefer a lower expected return with a **higher Sharpe ratio**, such as a 5% expected return with a Sharpe ratio of 2, over higher expected returns with a **low Sharpe ratio** (e.g., 35% return with Sharpe of 0.5).  

</details>

<details>
<summary>Impact of Leverage on Risk and Return</summary>

  - **High leverage increases the likelihood** of covering operational costs, but **high Sharpe ratios** mitigate the risks of catastrophic losses.  
  - Leverage increases the potential for higher profits but also raises the probability of **severe losses**, especially if the Sharpe ratio is low.  
  - **Figures 3.8 and 3.9** illustrate how the probability of losing at least 20% of capital depends on leverage and Sharpe ratio, with higher Sharpe ratios dramatically reducing risk.  
  - A **Sharpe ratio over 2** is ideal for HFT strategies, as it significantly reduces the probability of large losses, even under high leverage.  
  - The risk of losing significant capital can be controlled by balancing **leverage** and ensuring a high **Sharpe ratio** in the trading strategies.  

</details>

<details>
<summary>Transparent and Latent Costs</summary>

  - HFT operations must consider both **transparent** and **latent** costs when calculating their cost structures.  
  - **Transparent costs** are easily identifiable and may include commissions, exchange fees, and technology costs.  
  - **Latent costs** are hidden costs that are not immediately visible, such as market impact, slippage, and missed opportunities due to system delays.  
  - These **latent costs** can significantly affect profitability, particularly when there is a high volume of transactions.  
  - Detailed information on these costs is covered in **Chapter 19**, which addresses various cost types that HFT operations must account for.  

</details>

<details>
<summary>Staffing</summary>

  - The initial **development of HFT systems** is costly and risky, requiring staff with **PhD-level expertise** in quantitative finance and econometrics.  
  - **Programming staff** need to be highly experienced in handling complex issues like **system inter-operability**, **computer security**, and **algorithmic efficiency**.  
  - **Designing trading models** requires deep knowledge of finance, statistical methods, and computational modeling.  
  - A well-equipped team must also manage the **integration of various software systems** and ensure that they can operate efficiently across diverse market conditions.  
  - Hiring top-tier **quantitative researchers** and experienced engineers is essential for the successful development and operation of a HFT system.  

</details>

## Capitalizing a HFT Business 

<details>
<summary>Capitalizing a HFT Business</summary>

  - Capital in HFT operations consists of **equity** and **leverage**.  
  - **Equity** typically comes from contributions by **founders**, **private equity investors**, or the **parent company**.  
  - **Leverage** is debt obtained through mechanisms like **bank loans**, **margin lending**, or loans from **broker-dealers**.  
  - Leverage allows the trading firm to amplify its **capital base**, increasing the potential for higher profits.  
  - The combination of **equity** and **leverage** is crucial for determining the scale and operational capacity of a HFT business.  

</details>

## Conclusion 

<details>
<summary>Conclusion</summary>

  - Developing a HFT business presents challenges such as the "gray box" or "black box" nature of many systems, where decision-making processes are not fully transparent.  
  - The low transparency of algorithms can frustrate human traders, as they may not fully understand the decisions made by the system prior to executing trades.  
  - High trading frequency can make it difficult to spot malfunctions or errors within the algorithm.  
  - Issues like **computer security** also pose significant challenges in maintaining the integrity and safety of HFT operations.  
  - Despite these challenges, **HFT** can be highly profitable, with **deployment and execution costs decreasing** over time. High-frequency strategies thrive in markets with high **geopolitical** and **economic uncertainty**, where traditional long-term strategies may struggle.  

</details>

# 4. Financial Markets Suitable for HFT

<details>
<summary>Financial Markets and Their Suitability for HFT</summary>

  - A market suitable for HFT must be both liquid and electronic to facilitate quick turnover of capital.
  - Key elements to assess market suitability for HFT:
    - Available liquidity
    - Electronic trading capability
    - Regulatory considerations
  - Table 4.1 provides the average daily volume and dominant execution methods for major security classes.
  - HFT can take place in various markets, with liquidity and electronic trading being crucial factors for efficiency.
  - Regulatory environments vary across markets, and understanding these regulations is vital for implementing HFT strategies.

</details>

<details>
<summary>Optimal Trading Frequency</summary>

  - The optimal trading frequency for instruments depends on liquidity, with high-frequency traders targeting instruments with high liquidity.
  - Figure 4.1 illustrates the relationship between instrument liquidity (daily trading volume) and optimal trading frequency.
  - Markets such as Foreign Exchange (FX), large-cap equities, and futures are more suited to higher-frequency trading.
  - Less liquid markets such as municipal bonds or corporate debt typically require a lower trading frequency.
  - Trading frequencies can range from one year to one second, based on the instrument's liquidity and the trader's strategy.

</details>

<details>
<summary>Fixed-Income Markets</summary>

  - Fixed-income markets consist of the interest rate market and bond market, involving the trade of short- and long-term deargues and debt obligations.
  - Interest rate products and bonds provide fixed or prespecified income to holders, although they differ in other characteristics.
  - Trading methods for fixed-income products include spot, futures, and swaps.
  - Spot trading involves immediate delivery, while futures involve future delivery, and swaps involve cash flow exchanges between two parties.
  - High-frequency traders capitalize on short-term price deviations, profiting from small market movements in both interest rate products and bonds.

</details>

<details>
<summary>Interest Rate Markets</summary>

  - Spot interest rate markets consist of quotes offered by banks to other banks for various maturities (e.g., Overnight, 1M, 3M, 1Y).
  - Interest rate futures and swaps play a significant role in the trading of interest rates, with futures contracts offering a way to trade rates at prespecified future dates.
  - Spot interest rates are influenced by interbank lending rates, which include a credit spread based on the creditworthiness of the borrowing bank.
  - The futures price for interest rate products can be calculated using the formula:  
    - $f_{\text{bid}} = 100 - \frac{r_{\text{bid}}}{100}$
    - $f_{\text{ask}} = 100 - \frac{r_{\text{ask}}}{100}$
  - Swap products are the most popular in interest rate markets, and electronic trading has increased but is still limited for most swap products.

</details>

<details>
<summary>Bond Markets</summary>

  - Bonds are debt obligations issued by various entities and can be customized to the buyer's specifications (e.g., convertible bonds).
  - Spot bonds are mainly traded OTC and do not generate high-frequency data, making them less suitable for HFT.
  - Bond futures, which are standardized by exchanges, offer an opportunity for HFT.
  - Like interest rate futures, bond futures are liquid, with shorter-term contracts being more liquid than longer-term ones.
  - Bonds with shorter maturities are referred to as "bills," and bonds with maturities of 2 to 10 years are referred to as "notes."

</details>

<details>
<summary>Foreign Exchange Markets</summary>

  - Foreign exchange (FX) markets allow for the exchange of interest rates in different currencies and have evolved since the collapse of the gold standard in 1971.
  - The FX market is decentralized, leading to a lack of "one price" at any given time, which can create arbitrage opportunities for high-frequency traders.
  - In 2007, the total FX market had a daily trading volume of $3 trillion, with $1 trillion of that being spot trading.
  - FX markets can be classified into three player categories: high-frequency traders, longer-term investors, and corporations.
  - Foreign exchange products like spot, forward, and swap contracts trade in decentralized OTC markets, with futures and selected options trading on exchanges.

</details>

<details>
<summary>Equity Markets</summary>

  - Equity markets, including stocks, ETFs, warrants, and options, are popular for high-frequency traders due to inefficiencies in the market structure.
  - The NYSE alone had 2,764 stocks listed in 2006, creating numerous opportunities for short-term HFT.
  - Equity futures and options, along with index futures and options, offer profitable trading opportunities for high-frequency strategies.
  - Most stock exchanges provide full electronic trading functionality for these instruments, making them well-suited for algorithmic strategies.
  - Sample daily trading volumes for the most active equity futures on CME (June 2009) include instruments like S&P 500, Nasdaq100, and E-mini futures.

</details>

<details>
<summary>Commodity Markets</summary>

  - Commodities, including agricultural products and energy products, can be traded using spot, futures, and options contracts.
  - Spot commodity contracts provide physical delivery of goods, making them unsuitable for HFT.
  - Futures and options on commodities, particularly liquid contracts, provide opportunities for high-frequency strategies.
  - Commodity futures are contracts to buy or sell underlying commodities at a prespecified time in the future and are smaller than FX or interest rate futures.
  - CME offers electronic futures and options trading in commodities, with selected contracts like corn, wheat, and soybeans being actively traded.

</details>

<details>
<summary>Summary</summary>

  - Electronic trading is rapidly advancing, providing instantaneous execution across most securities.
  - First-to-market high-frequency traders in new electronic markets can capture significant premiums on their speculative activities due to a lack of competition in the early stages.
  - In the long term, no market is a zero-sum game, meaning that the diverse nature of market participants allows for mutual value extraction.
  - The varied investment objectives of different market participants (e.g., speculators, hedgers, long-term investors) ensure that each player can benefit according to their own metrics.
  - HFT in these markets contributes to market efficiency, liquidity, and price discovery, benefitting all participants in the long run.

</details>

# 5. Evaluating Performance of HFT Strategies 

## Basic Return Characteristics 

<details>
<summary>Return and Frequency</summary>

  - Trading strategies are assessed primarily based on their returns.
  - Return can be measured across multiple frequencies: hourly, daily, monthly, quarterly, and annually.
  - To compare strategies accurately, all returns must be measured using the same frequency.
  - Average annual return serves as a simple summary of the return distribution's mean location.
  - While higher average returns are generally preferred, they do not capture the variability or risk associated with the returns.

</details>

<details>
<summary>Volatility and Risk</summary>

  - Volatility measures the dispersion of returns around the average return.
  - Typically calculated as the standard deviation of returns.
  - Standard deviation is often used as a proxy for risk.
  - It summarizes the average deviation from the mean but does not account for the impact of extreme negative returns.
  - Standard deviation alone may not provide a complete picture of the potential for significant loss.

</details>

<details>
<summary>Maximum Drawdown</summary>

  - Maximum drawdown measures the most severe loss from peak to trough before a new peak is established.
  - The highest cumulative return observed in historical data is called the "high water mark."
  - Drawdown is calculated as the lowest return between two successive high water marks.
  - The lowest observed drawdown is considered the "maximum drawdown."
  - Maximum drawdown captures tail risk and the potential for large, sustained losses.

</details>

<details>
<summary>Illustration of Maximum Drawdown</summary>

  - At time $t_A$, the return $R_A$ is the highest cumulative return, serving as the high water mark.
  - At time $t_B$, the return $R_B$ represents a drop, creating a drawdown $R_B - R_A$.
  - A new high water mark is established at time $t_{A'}$ when the cumulative return surpasses $R_A$.
  - The peak value $R_C$ at time $t_C$ sets a new high water mark.
  - The maximum drawdown is recalculated at a point $X$ if $R_X - R_C < R_B - R_A$.
  - The new maximum drawdown becomes $R_D - R_C$ if this condition holds.

</details>

<details>
<summary>Performance Metrics for Strategy Evaluation</summary>

  - Average return, volatility, and maximum drawdown are core metrics for evaluating trading strategies.
  - These metrics are measured over a predefined window and frequency.
  - Skewness and kurtosis are additional measures used to describe the distribution of returns.
  - Positive skewness suggests a dominance of positive returns; negative skewness indicates prevalent losses.
  - Kurtosis measures the "fatness" of the distribution tails, with high kurtosis indicating a higher probability of extreme returns.

</details>

## Comparative Ratios 

<details>
<summary>Performance Metrics Overview</summary>

- Traditional metrics like average return, standard deviation, and maximum drawdown are used to assess trading strategies but do not offer a direct point comparison.
- Comparative performance metrics summarize mean, variance, and tail risk into a single number, helping compare different strategies.
- Several generations of point measures have been developed, including Sharpe ratio, Jensen's alpha, and Treynor ratio.
- **Table 5.1** summarizes the most popular performance measures and their respective formulas and applications.
- The metrics aim to provide a comprehensive way to measure trading strategy performance with respect to risk and return.

</details>

<details>
<summary>The Big Trio: Sharpe, Treynor, and Jensen's Alpha</summary>

- Developed by William Sharpe in 1966, the Sharpe ratio is one of the most widely used performance measures.
- The formula for Sharpe ratio is:  
  $SR = \frac{ \bar{R} - R_F }{ \sigma_R }$
  where:
  - $\bar{R}$ = annualized average return from trading
  - $\sigma_R$ = annualized standard deviation of trading returns
  - $R_F$ = risk-free rate (e.g., Fed Funds)
- The Sharpe ratio captures three important metrics: average return, standard deviation, and the cost of capital.
- The ratio helps to select mean-variance efficient securities and is used widely in finance.
- The Sharpe ratio's appeal lies in its ability to quantify performance adjusted for risk, especially in scenarios where no positions are carried overnight (e.g., HFT).
- **Treynor Ratio**: Measures return in excess of a chosen benchmark per unit of risk (represented by beta in CAPM).
  - Formula: $Treynor = \frac{E[r] - r_f}{\beta}$, where $\beta$ is the regression coefficient of trading returns on market returns.
- **Jensen's Alpha**: Measures performance above or below the expected return based on the Capital Asset Pricing Model (CAPM).
  - Formula: $\alpha_i = E[r_i] - r_f - \beta_i (r_M - r_f)$
  - Measures risk-adjusted return with respect to market influences, accounting for systematic risk.
- Both ratios are useful but do not consider the tail risk of extreme adverse returns.
- Treynor ratio is particularly useful for investors who split holdings between trading strategies and the market portfolio.
- Jensen’s alpha focuses on performance relative to the market and is helpful in portfolio optimization.

| Measure | Formula | Interpretation/Assumptions |
|---------|---------|-----------------------------|
| **Sharpe Ratio (Sharpe [1966])** | $$ SR = \frac{E[r] - r_f}{\sigma[r]} $$<br>where $E[r] = \frac{r_1 + \cdots + r_T}{T}$ and $\sigma[r] = \sqrt{\frac{(r_1 - E[r])^2 + \cdots + (r_T - E[r])^2}{T - 1}}$ | Suitable if returns are normally distributed. |
| **High-Frequency Sharpe Ratio** | $$ SR = \frac{E[r]}{\sigma[r]} $$ | Used when there are no overnight positions. |
| **Treynor Ratio (Treynor [1965])** | $$ Treynor_i = \frac{E[r_i] - r_f}{\beta_i} $$<br>where $\beta_i$ is the regression coefficient. | Suitable for normally distributed returns and combining strategy with market portfolio. |
| **Jensen’s Alpha (Jensen [1968])** | $$ \alpha_i = E[r_i] - r_f - \beta_i (r_M - r_f) $$ | Measures excess return over CAPM prediction; leverage-sensitive. |

</details>

<details>
<summary>Measures Based on Lower Partial Moments (LPMs): Omega, Sortino, Kappa 3, Upside Potential</summary>

- **LPM Formula** for security $i$:
  - $\text{LPM}_{ni} (\tau) = \frac{1}{T} \sum_{t=1}^{T} \max(\tau - r_{it}, 0)^n$
  - Where:
    - $\tau$ = minimal acceptable return
    - $n$ = order of the moment
    - $r_{it}$ = return of security $i$ at time $t$
- **Moment Orders**:
  - $n = 0$: Shortfall probability
  - $n = 1$: Expected shortfall
  - $n = 2$ for $\tau = E[r]$: Semi-variance
- Higher order $n$ should be used by more risk-averse investors (Eling & Schuhmacher, 2007).
- LPMs consider **only negative deviations** from the minimal acceptable return.
- LPMs are considered a **better risk measure** than standard deviation, which includes both positive and negative deviations (Sortino & van der Meer, 1991).
- Minimal acceptable return ($\tau$) can be set to 0, the risk-free rate, or the average return.

| Measure | Formula | Interpretation/Assumptions |
|---------|---------|-----------------------------|
| **Omega (Shadwick & Keating [2002])** | $$ \Omega_i = \frac{E[r_i] - \tau}{LPM_{1,i}(\tau)} + 1 $$ | Assesses returns relative to downside risk. |
| **Sortino Ratio (Sortino & van der Meer [1991])** | $$ Sortino_i = \frac{E[r_i] - \tau}{\sqrt{LPM_{2,i}(\tau)}} $$ | Accounts only for negative deviations. |
| **Kappa 3 (Kaplan & Knowles [2004])** | $$ Kappa_{3,i} = \frac{E[r_i] - \tau}{\sqrt[3]{LPM_{3,i}(\tau)}} $$ | Uses higher-order moments for risk-averse investors. |
| **Upside Potential Ratio** | $$ UPR_i = \frac{HPM_{1,i}(\tau)}{\sqrt{LPM_{2,i}(\tau)}} $$<br>where $HPM_{1,i}(\tau) = \frac{1}{T}\sum_{t=1}^{T}\max(r_{it} - \tau, 0)$ | Measures upside potential relative to downside risk. |

</details>

<details>
<summary>Measures Based on Drawdown: Calmar, Sterling, Burke</summary>

- These measures are popular among Commodity Trading Advisors (CTAs).
- According to Eling and Schuhmacher (2007, p. 5), CTAs prefer these measures because they "illustrate what the advisors are supposed to do best—continually accumulating gains while consistently limiting losses."
- The focus is on the ability to generate steady profits while controlling downside risk.
- References Lhabitant (2004) to support the perspective of disciplined risk management by CTAs.
- Notation: MDi1 represents the lowest maximum drawdown, MDi2 the second lowest maximum drawdown, and so forth.

| Measure | Formula | Interpretation/Assumptions |
|---------|---------|-----------------------------|
| **Calmar Ratio** | $$ \text{Calmar}_i = \frac{E[r_i] - r_f}{-MD_{i1}} $$ | Uses the maximum drawdown for risk adjustment. |
| **Sterling Ratio** | $$ \text{Sterling}_i = \frac{E[r_i] - r_f}{-\frac{1}{N}\sum_{k=1}^{N} MD_{ij}} $$ | Averages multiple drawdowns. |
| **Burke Ratio** | $$ \text{Burke}_i = \frac{E[r_i] - r_f}{\sqrt{\sum_{k=1}^{N} MD_{ij}^2}} $$ | Adjusts for large, extreme losses. |

</details>

<details>
<summary>Value-At-Risk-Based Measures: Excess Return on VaR, Conditional Sharpe, Modified Sharpe</summary>

- Value at risk (VaRi) describes the possible loss of an investment, which is not exceeded with a given probability of $1-\alpha$ in a certain period. 
- For normally distributed returns, $\text{VaRi} = -(E[r_i]+z_\alpha\sigma_i)$, where $z_\alpha$ is the $\alpha$-quantile of the standard normal distribution 

| Measure | Formula | Interpretation/Assumptions |
|---------|---------|-----------------------------|
| **Excess Return on VaR** | $ERVaR = \frac{E[r] - r_f}{VaR_i}$ | Not ideal for non-normal returns. |
| **Conditional Sharpe Ratio** | $CS = \frac{E[r] - r_f}{CVaR_i} $ where $CVaR_i = E[-r_{it} \mid r_{it} \le -\text{VaRi}]$ | The advantage of CVaR is that it satisfies certain plausible axioms |
| **Modified Sharpe Ratio** | $MSR = \frac{E[r] - r_f}{MVaR_i}$ where $MVaR_i$ uses the Cornish-Fisher expansion. | Suitable for non-normal returns with skewness and kurtosis adjustments. |

</details>

<details>
<summary>Comparing Performance Metrics</summary>

- Metrics such as the Sharpe ratio, Calmar ratio, Sterling ratio, and others yield comparable rankings of strategies.
- **Eling and Schuhmacher (2007)** found that the Sharpe ratio is an adequate measure for hedge fund performance, often used in ranking strategies.
- The Sharpe ratio is particularly effective for mean-variance efficient securities and has become a standard metric in finance.
- However, the Sharpe ratio does not account for tail risk, which led to the development of newer metrics like those based on lower partial moments and drawdowns.
- While some metrics like VaR and CVaR address tail risk more directly, they require careful interpretation, especially in non-normal return distributions.

</details>

## Performance Attribution 
<details>
<summary>Introduction to Performance Attribution Analysis</summary>

  - Originates from arbitrage pricing theory by Ross (1977) and extended to trading strategies by Sharpe (1992) and Fung & Hsieh (1997).
  - Also known as "benchmarking," it analyzes strategy performance by comparing it against a set of market factors.
  - A strategy’s period-t return, $R_{it}$, that invests in individual securities with returns $r_{jt}$ for $j = 1, ..., J$, has a factor-based structure:
    $$
    R_{it} = \sum_{j} x_{jt} r_{jt}
    $$
  - Here, $x_{jt}$ represents the weight of the $j$th security at time $t$ such that:
    $$
    \sum_{j} x_{jt} = 1
    $$
  - The method links the returns of individual securities to underlying systematic factors to evaluate strategy performance.

</details>

<details>
<summary>Systematic Factor Model for Security Returns</summary>

  - Each security’s period-t return, $r_{jt}$, is modeled using systematic factors $F_{kt}$ for $k = 1, ..., K$:
    $$
    r_{jt} = \sum_{k} \lambda_{jk} F_{kt} + \epsilon_{jt}
    $$
  - $\lambda_{jk}$ is the factor loading (sensitivity to factor $k$), and $\epsilon_{jt}$ is the idiosyncratic return of security $j$ at time $t$.
  - Factors $F_{kt}$ represent broad asset classes, individual stocks, or other securities.
  - By combining equations (5.1) and (5.2), overall strategy returns can be expressed as:
    $$
    R_{it} = \sum_{j,k} x_{jt}\lambda_{jk} F_{kt} + \sum_{j} x_{jt}\epsilon_{jt}
    $$
  - This approach simplifies a strategy’s return to a limited set of global systematic factors and idiosyncratic components.

</details>

<details>
<summary>Regression-Based Performance Attribution</summary>

  - Performance attribution involves regressing the strategy’s returns against a set of systematic factors:
    $$
    R_{it} = \alpha_{i} + \sum_{k} b_{ik} F_{kt} + u_{it}
    $$
  - $b_{ik}$: Contribution of factor $k$ to the strategy’s performance.
  - $\alpha_{i}$: Persistent ability of the strategy to generate abnormal returns (alpha).
  - $u_{it}$: Idiosyncratic return of the strategy, not explained by systematic factors.
  - This regression approach isolates the strategy’s excess return beyond systematic factor contributions, indicating its genuine added value.

</details>

<details>
<summary>Advantages of Performance Attribution</summary>

  - Captures the investment styles of "black-box" strategies, even if the strategy’s design details are unknown.
  - Measures the true value-added of the strategy, facilitating comparisons across various strategies.
  - Identifies near-term persistence of trending factors, supporting forecasting of future strategy performance (referencing Jegadeesh and Titman, 1993).
  - Distinguishes systematic factor-driven returns from idiosyncratic returns, enhancing understanding of performance drivers.
  - Useful for both active and passive management evaluations, providing transparency and accountability.

</details>

<details>
<summary>Global Benchmark Asset Classes for Performance Attribution</summary>

  - Fung and Hsieh (1997) identify eight key asset classes as effective performance attribution benchmarks:
    - **Equity Classes**:
      - MSCI U.S. equities
      - MSCI non–U.S. equities
      - IFC emerging market equities
    - **Bond Classes**:
      - JP Morgan U.S. government bonds
      - JP Morgan non–U.S. government bonds
    - **Cash Proxy**:
      - One-month Eurodollar deposit rate
    - **Commodity Proxy**:
      - Gold price
    - **Currency Proxy**:
      - Federal Reserve's trade-weighted dollar index
  - These benchmarks cover a wide spectrum of global systematic risks and help evaluate performance in a comprehensive manner.

</details>

## Other Considerations in Strategy Evaluation

<details>
<summary>Strategy Capacity</summary>

  - Strategy performance is influenced by the amount of capital deployed, primarily due to market liquidity limits for trading instruments.
  - Large position sizes consume liquidity, causing adverse price movements and diminishing strategy profitability.
  - Estimating a strategy's capacity often involves analyzing market impact, covered in detail in Chapter 19.
  - Research on hedge funds with portfolios of strategies shows significant effects of investment size on performance.
  - Key findings from studies:
    - Fransolet (2004): Rapid industry-wide capital increases can reduce the capacity of profitable strategies.
    - Brown, Goetzmann, and Park (2004): Strategy capacity may vary with a manager's skill level.
    - Getmansky, Lo, and Makarov (2004): Capacity is a function of trading costs and asset liquidity.
    - Ding et al. (2008): 
      - If deployed capital is below strategy capacity, performance is positively related to capitalization.
      - If deployed capital exceeds capacity, performance becomes negatively related to capital size.

</details>

<details>
<summary>Length of the Evaluation Period for High-Frequency Strategies</summary>

  - Portfolio managers often face the challenge of determining the required evaluation period to validate a strategy's advertised Sharpe ratio.
  - Evaluation period practices vary:
    - Some use 6 months to 2 years.
    - Others require a track record of at least 6 years.
    - Some accept as little as 1 month of daily data.
  - The required evaluation period depends on the Sharpe ratio (SR); higher SRs need shorter evaluation periods for validation.
  - Assuming normally distributed returns, Jobson and Korkie (1981) demonstrated that the error in Sharpe ratio estimation follows:
    $$
    s = \left[\frac{1}{T}\left(1 + 0.5 SR^2\right)\right]^{\frac{1}{2}}
    $$
    where:
    - $s$ = standard deviation of Sharpe ratio errors
    - $T$ = number of evaluation periods
    - $SR$ = Sharpe ratio
  - To achieve a 90% confidence level, the claimed SR must be at least 1.645 times greater than the standard deviation of errors $s$.
  - The minimum number of evaluation periods $T_{min}$ needed for verification:
    $$
    T_{min} = \left(\frac{1.645^2}{SR^2}\right)\left(1 + 0.5 SR^2\right)
    $$
  - The Sharpe ratio $SR$ should correspond to the evaluation period frequency (monthly or daily).

</details>

<details>
<summary>Adjusting Sharpe Ratios for Frequency</summary>

  - If the annual Sharpe ratio claimed is 2 and is based on monthly data:
    $$
    SR_{monthly} = \frac{2}{\sqrt{12}} = 0.5774
    $$
  - If based on daily data with approximately 250 trading days per year:
    $$
    SR_{daily} = \frac{2}{\sqrt{250}} = 0.1054
    $$
  - The minimum required monthly observations for verification at a 90% confidence level:
    - Monthly data: Just over 9 months.
    - Daily data: Just over 8 months.
  - For higher Sharpe ratios (e.g., SR = 6), less than one month of daily data may suffice for verification.

</details>

<details>
<summary>Minimum Evaluation Periods for Verification of Sharpe Ratios</summary>

  - Summary of minimum required evaluation periods for verifying claimed annualized Sharpe ratios:
    - **Sharpe Ratio 0.5:** 
      - Monthly Data: ~130.95 months 
      - Daily Data: ~129.65 months
    - **Sharpe Ratio 1.0:** 
      - Monthly Data: ~33.75 months 
      - Daily Data: ~32.45 months
    - **Sharpe Ratio 1.5:** 
      - Monthly Data: ~15.75 months 
      - Daily Data: ~14.45 months
    - **Sharpe Ratio 2.0:** 
      - Monthly Data: ~9.45 months 
      - Daily Data: ~8.15 months
    - **Sharpe Ratio 2.5:** 
      - Monthly Data: ~6.53 months 
      - Daily Data: ~5.23 months
    - **Sharpe Ratio 3.0:** 
      - Monthly Data: ~4.95 months 
      - Daily Data: ~3.65 months
    - **Sharpe Ratio 4.0:** 
      - Monthly Data: ~3.38 months 
      - Daily Data: ~2.07 months
  - Demonstrates that strategies with higher Sharpe ratios require less time for performance validation.

</details>

## Conclusion 

<details>
<summary>Conclusion</summary>

  - Statistical tools for strategy evaluation help managers determine if high-frequency strategies fit their portfolios.
  - Various statistical evaluation methods exist, each with distinct approaches and insights.
  - Despite the availability of alternative techniques, the **Sharpe ratio** remains the most widely used metric for evaluating strategy performance.
  - The Sharpe ratio's popularity is due to its simplicity and its ability to standardize performance relative to risk.
  - Effective use of these tools supports informed decision-making, optimizing the integration of high-frequency strategies in portfolio management.

</details>

# 6. Orders, Traders, And Their Applicability To HFT

<details>
<summary>Introduction to HFT and Market Orders</summary>

  - HFT seeks to exploit and arbitrage temporary market inefficiencies arising from conflicting interests among market participants.
  - Success in HFT relies on understanding the different types of orders that traders use to achieve their objectives.
  - Analyzing these order types provides insights into the strategies and intentions of various traders.
  - Anticipating and forecasting the actions of market participants is crucial for effective HFT.
  - This chapter focuses on examining the various order types present in contemporary markets, providing a foundation for understanding market dynamics and strategic decision-making.

</details>

## Order Types 

<details>
<summary>Contemporary Exchanges and ECNs</summary>

- Contemporary exchanges and Electronic Communication Networks (ECNs) provide various ordering capabilities that differ in terms of price, timing, size, and disclosure.
- Market orders aim for the best available price, while limit orders target a specified price.
- ECNs and exchanges handle the execution of these orders based on the market conditions and order books.
- The execution mechanism and the potential for partial fulfillment of orders impact the profitability and transaction costs.
- These order types cater to different trading strategies, including HFT.

</details>

<details>
<summary>Market Orders vs. Limit Orders</summary>

- Market orders execute immediately at the best available price, prioritizing speed and certainty over price precision.
- Limit orders execute at a specified price or better, offering price control but with uncertain execution timing.
- Market orders can lead to "walking through the order book," filling against multiple price levels until completed.
- Example calculation for a market order selling 100,000 SPY shares:
  $$
  P = \frac{10,000 \times 935 + 40,000 \times 930 + 50,000 \times 925}{100,000} = 928
  $$
- Limit orders provide market liquidity, with aggregate size indicating market depth and the variety of price points showing market breadth.

</details>

<details>
<summary>Characteristics and Trade-offs</summary>

- Market orders: Fast execution, guaranteed fulfillment, uncertain price, high transaction costs.
- Limit orders: Possible non-execution, lower transaction costs, potential need for order resubmission, price certainty.
- Limit orders act as pre-commitments, whereas market orders are requests for immediate fulfillment.
- Limit orders may result in missed opportunities or exposure to better-informed traders ("being picked off").
- Despite potential drawbacks, limit order trading remains popular, especially in volatile markets.

</details>

<details>
<summary>Profitability of Limit Orders</summary>

- Handa and Schwartz (1996) find limit orders can earn premiums between 0.1% to 1.6%, depending on the strategy.
- Profitability measured by comparing the execution price of limit orders vs. market orders:
  $$
  \Pi_t = P_{t,M} - P_{t,L}
  $$
  $$
  \text{Average profitability} = \frac{1}{T}\sum_{t=1}^{T}(P_{t,M} - P_{t,L})
  $$
- Experimental design: Orders evaluated periodically, simulated limit orders compared to market orders.
- Findings: Limit order strategies outperform market orders, particularly effective in volatile, range-bound markets.
- Limit orders face delayed execution risk, impacting profitability if market prices shift adversely.

</details>

<details>
<summary>Order Timing Specifications</summary>

- "Good till canceled" (GTC) orders remain active until filled or canceled.
- "Good till date" (GTD) orders have specific expiration dates.
- "Good for the day" (GFD) orders last until the end of the trading day; "good for the extended day" (GFE) extend to after-hours.
- "Good till time" (GTT) orders expire at a set time, useful for HFT and markets with cancellation fees.
- Different timing specifications help traders control exposure and adapt to market conditions effectively.

</details>

<details>
<summary>Order Size Specifications</summary>

- "Vanilla" order sizes are standard round lots (e.g., 100 shares on NYSE); smaller orders are "odd lots."
- "Mixed lots" combine round lots and odd lots, processed accordingly.
- Large market orders may face liquidity constraints, leading to the use of "fill or kill" (FOK) or "fill and kill" (FAK) orders.
- "All or none" (AON) orders require complete fulfillment before execution.
- Order size affects liquidity, transaction costs, and execution strategies.

</details>

<details>
<summary>Order Disclosure Specifications</summary>

- Exchanges vary in the extent of order transparency, influencing market dynamics.
- "Iceberg orders" reveal only a portion of the total size, reducing market impact.
- Anonymity in orders can prevent adverse reactions from other traders, beneficial for large orders.
- Full transparency vs. selective disclosure affects the ability to gauge market sentiment and depth.
- Strategic use of iceberg and anonymous orders can protect large traders from predatory practices.

</details>

<details>
<summary>Stop-Loss and Take-Profit Orders</summary>

- Stop-loss orders automatically sell a security if its price falls below a specific level, limiting potential losses.
- Take-profit orders secure gains by selling a security once it reaches a desired price level.
- These orders can function as market or limit orders, depending on trader preferences and risk tolerance.
- In volatile markets, stop-losses are more commonly placed as market orders to ensure execution.
- Failure to execute stop-loss or take-profit orders can result in exacerbated losses or missed gains.

</details>

<details>
<summary>Impact of Market Volatility and Bid-Ask Spreads</summary>

- Limit orders are favored during high market volatility due to greater potential profitability.
- Increases in bid-ask spreads incentivize limit orders, as the spread cost outweighs the opportunity cost of non-execution.
- High volatility increases limit order volume, reducing cumulative profitability due to missed trades and wider spreads.
- Traders with confidence in their information may prefer limit orders during expected price movements.
- Studies show a strong correlation between market conditions and traders’ choice between market and limit orders.

</details>

## Order Distributions 

<details>
<summary>General Overview of Oanda FXTrade Order Statistics</summary>
  
  - Order statistics from Oanda’s FXTrade platform are rarely made public; the data presented offers a unique insight into retail FX order flows.
  - The dataset spans from October 1, 2003, to May 14, 2004, reflecting typical retail trader behavior.
  - Majority of Oanda’s customers are retail traders; the data may not fully represent broker-dealer or ECN order flows.
  - Most common order types by both count and volume are stop-loss and take-profit orders, followed by buy market open and sell market open orders.
  - The data provides a basis for comparing retail trading behavior versus institutional trading in the FX market.

</details>

<details>
<summary>Table 6.3: Daily Distributions of Trades by Order Category</summary>
  
  - Most common orders by count: Change Stop-Loss or Take-Profit (22.36%), Buy Market (open) (13.10%), Sell Market (open) (10.61%).
  - Highest daily trading volume in EUR: Change Stop-Loss or Take-Profit (268,568 EUR), Buy Market (open) (167,096 EUR), Sell Market (open) (135,754 EUR).
  - Least common orders by count: Buy Margin Call (close) (0.12%), Sell Margin Call (close) (0.17%), Order Expired (0.65%).
  - Minimum daily trading volume in EUR: Buy Margin Call (close) (733 EUR), Sell Margin Call (close) (1,213 EUR), Order Expired (4,683 EUR).
  - Total daily trading volume across all order types: 1,182,611 EUR.

</details>

<details>
<summary>Table 6.4: Popularity of Orders and Execution Rates</summary>
  
  - Distribution of buy orders: 55% of all open orders and market orders are buy orders, indicating a slight preference for long positions.
  - Execution rates for limit orders: 60% of buy limit orders and 61% of sell limit orders are executed (hits).
  - Execution by volume: Only 39% of buy limit orders and 29% of sell limit orders are executed by volume, suggesting larger volume traders place more distant limit orders.
  - Long position closures: Predominantly closed through sell market orders (63% by count, 73% by volume), followed by take-profit and stop-loss orders.
  - Short position closures: Primarily through buy market orders (61% by count, 74% by volume), with similar take-profit and stop-loss usage.

</details>

<details>
<summary>Discrepancies in Trading Behavior</summary>
  
  - Larger customers prefer market orders to close positions, while smaller customers use take-profit and stop-loss orders more frequently.
  - Hypothesis: Larger customers are more sophisticated and may avoid the risk of proprietary manipulation by Oanda’s trading desk.
  - Smaller customers show a higher success rate in using take-profit and stop-loss strategies: 
    - 21% of orders closed in profit by count vs. 9% by volume.
    - 16% of orders closed by stop-loss by count vs. 13% by volume.
  - The gap between count and volume suggests larger order sizes might face execution challenges or strategic delays.
  - Limit order “hit” rates show a discrepancy between count and volume, potentially reflecting large traders’ strategic placement of distant orders.

</details>

<details>
<summary>Insights for HFT</summary>
  
  - The preference for market orders over take-profit and stop-loss orders by larger customers indicates a potential HFT opportunity to exploit market inefficiencies.
  - HFT strategies could capitalize on the discrepancy between retail traders' predictable stop-loss and take-profit behavior and institutional traders' market orders.
  - Retail traders’ reliance on stop-loss orders could be targeted by HFT algorithms aiming to trigger and capitalize on these orders.
  - Analysis of hit rates for limit orders can help design HFT strategies to optimize order placement and timing, exploiting gaps in retail trader behavior.
  - The apparent aversion of sophisticated traders to limit orders highlights a potential area of market microstructure research for HFT model development.

</details>

## Conclusion
<details>
<summary>Conclusion</summary>

- Diversity of order types allows traders to build complex trading strategies by changing price, timing, transparency, and other parameters of orders. 
- Still, simple market and limit orders retain their popularity in the trading community because of their versatility and ease of use.

</details>

# 7. Market Inefficiency and Profit Opportunities At Different Frequencies

<details>
<summary>Introduction to HFT</summary>

- HFT opportunities range from microsecond price moves for market-making to several-hour-long strategies based on market events.
- The identification of persistent trading opportunities is key to HFT strategies.
- A standard academic approach for model development includes:
  1. Documenting observed phenomena.
  2. Developing an explanatory model.
  3. Testing the model’s predictive abilities.
- HFT strategy development begins with identifying recurring profitable opportunities in high-frequency data.
- The debate on the most profitable trading frequency often ends due to limited data access, as successful HFTs protect their data from public scrutiny.

</details>

<details>
<summary>Profitability and Trading Frequency</summary>

- The maximum profit of a trading strategy is constrained by the chosen trading frequency:
  - Daily trading: Limited by the daily price movement range.
  - Hourly trading: More potential due to increased intra-day ranges.
  - Higher frequencies: Smaller ranges, but more frequent, increasing potential gains.
- The total potential gain is the sum of all intra-period ranges at the chosen frequency.
- High-frequency data provides remarkable profit potential but also equally significant loss potential.
- Successful HFT strategies require careful design, extensive backtesting, and solid risk management.

</details>

<details>
<summary>Sharpe Ratios and Risk-Adjusted Returns</summary>

- Sharpe ratio measures risk-adjusted returns and is a standard profitability metric for trading strategies.
- Maximum Sharpe ratios increase with higher trading frequencies:
  - Daily rebalancing of EUR/USD (March 11 - March 22, 2009): Sharpe ratio of 37.3.
  - 10-second rebalancing: Potential Sharpe ratio over 5,000.
- Formula for maximum possible intra-day Sharpe ratio:
$$
SR = \frac{E[\text{Range}]}{\sigma[\text{Range}]} \times \sqrt{(\# \text{Intra-day Periods})(\# \text{Trading Days in a Year})}
$$
- HFT strategies typically avoid overnight positions, avoiding carry costs.
- Real-life HFTs can achieve double-digit Sharpe ratios; daily rebalancing usually results in Sharpe ratios of 1–2.

</details>

<details>
<summary>Gain Potential and Range Statistics for SPY and EUR/USD (April 21, 2009)</summary>

- Maximum gain potential calculated as the sum of price ranges at each frequency, normalized by daily open prices for comparability.
- SPY Statistics:
  - 10-sec frequency: 96.33% gain potential, 0.04% average range, 2340 periods/day.
  - 1-min frequency: 44.59% gain, 0.11% range, 390 periods/day.
  - 1-hour frequency: 5.66% gain, 0.81% range, 7 periods/day.
- EUR/USD Statistics:
  - 10-sec frequency: 319.23% gain potential, 0.04% average range, 8640 periods/day.
  - 1-min frequency: 90.07% gain, 0.06% range, 1440 periods/day.
  - 1-hour frequency: 6.44% gain, 0.27% range, 24 periods/day.

</details>

<details>
<summary>Comparison of Maximum Sharpe Ratios for EUR/USD (Feb 9 - Mar 22, 2009)</summary>

- Maximum Sharpe Ratios demonstrate profitability potential for perfectly predictable strategies:
  - 10-second periods: 0.04% average gain, 0.01% standard deviation, 2,592,000 observations, Sharpe = 5879.8.
  - 1-minute periods: 0.06% gain, 0.02% std. dev., 43,200 observations, Sharpe = 1860.1.
  - 10-minute periods: 0.12% gain, 0.09% std. dev., 4,320 observations, Sharpe = 246.4.
  - 1-hour periods: 0.30% gain, 0.19% std. dev., 720 observations, Sharpe = 122.13.
  - Daily periods: 1.79% gain, 0.76% std. dev., 30 observations, Sharpe = 37.3.
- These results are computed with perfect hindsight, representing theoretical maxima rather than realistic expectations.

</details>

## Predictability of Price Moves at High Frequencies

<details>
<summary>Predictability and Market Efficiency</summary>

- Trading systems aim to generate signals that lead to consistently positive outcomes over many trades.
- Predictability is the opposite of randomness; identifying predictable price moves is crucial for successful trading.
- Historical data analysis is essential for developing and validating trading strategies.
  - Technical analysts examine price charts for patterns.
  - Fundamental analysts use regression to explore the influence of variables.
  - HFT developers test models on tick data.
- Identifying nonrandom price changes can uncover persistent predictability and potential profitability.
</details>

<details>
<summary>Market Inefficiency and Arbitrage Opportunities</summary>

- Market inefficiency is characterized by the slow incorporation of new information into security prices.
- An efficient market reflects all available information in security prices instantly (Fama, 1970).
- Inefficient markets provide arbitrage opportunities due to delayed or incorrect price adjustments.
- Efficient market responses adjust prices immediately after information release, while inefficient responses show information leakage and price overshooting.
- Exploiting information leakage and overshooting is a common strategy for generating consistent profits.
</details>

<details>
<summary>Testing for Market Efficiency and Predictability</summary>

- Inefficient markets present more predictable trading opportunities.
- Tests for market efficiency help identify markets with significant predictability.
- Market efficiency exists in three forms:
  - **Weak form**: Tests if returns can be predicted using past prices and returns.
  - **Semi-strong form**: Excludes non-public information from analysis.
  - **Strong form**: Considers all types of public and non-public information.
- This analysis focuses on weak-form efficiency due to its common use in academic research.
</details>

<details>
<summary>Non-Parametric Runs Test - Overview</summary>

- The first test for market efficiency was developed by Louis Bachelier in 1900, analyzing sequences of positive or negative price changes ("runs").
- The probability of consecutive price changes of the same sign:
  - 2 in a row: 0.25
  - 3 in a row: 0.125
  - 4 in a row: 0.0625 (6.25%)
- Identifying multiple consecutive price changes signals potential trading opportunities.
- Runs tests apply to any desired frequency (e.g., tick-level, 1-minute intervals), considering transaction costs.
</details>

<details>
<summary>Non-Parametric Runs Test - Procedure</summary>

1. Identify sequences of consecutive positive or negative price changes for the chosen frequency.  
   - Example: In a 1-minute interval, positive runs (+) and negative runs (-) are identified.
2. Calculate:
   - Total number of runs, $u$.
   - Number of positive changes, $n_1$.
   - Number of negative changes, $n_2$.
   - Example: If $u = 10$, $n_1 = 9$, and $n_2 = 8$.
3. Compute the expected number of runs and its standard deviation:
   - $\bar{x} = \frac{2n_1n_2}{n_1 + n_2} + 1$
   - $s = \sqrt{\frac{2n_1n_2(2n_1n_2 - n_1 - n_2)}{(n_1 + n_2)^2(n_1 + n_2 - 1)}}$
   - Example: $\bar{x} = 9.47$, $s = 1.99$.
</details>

<details>
<summary>Non-Parametric Runs Test - Statistical Testing</summary>

- Compute the Z-score for statistical testing:
  - $Z = \frac{|u - \bar{x}| - 0.5}{s}$
- The threshold for statistical significance (95% confidence) is $|Z| > 1.645$.
  - If $Z$ exceeds 1.645, the randomness hypothesis is rejected, indicating predictability.
  - If $Z < 1.645$, randomness cannot be rejected.
- Example from data: $Z = 0.0147$; randomness not rejected, indicating no significant predictability.
</details>

<details>
<summary>Applications and Interpretation</summary>

- Runs tests applied to 1-minute price data can reveal inefficiencies at that frequency.
- Table 7.4 shows that some securities display market inefficiency at a 1-minute frequency, suggesting opportunities for HFT.
- Inefficiencies generally diminish at lower frequencies (e.g., 10-minute data), aligning with market efficiency theories.
- Understanding and interpreting runs tests can guide traders in selecting securities and frequencies for potential arbitrage.
</details>

<details>
<summary>Tests of Random Walks</summary>

- Advanced tests for market efficiency help traders find market inefficiencies to maximize profit opportunities.
- Price changes are considered random when they follow a "random walk," mathematically expressed as:
  $$
  \ln P_t = \ln P_{t-1} + \epsilon_t
  $$
- In this model:
  - $\ln P_t$: Logarithm of the price at time $t$
  - $\ln P_{t-1}$: Logarithm of the price one time interval before
  - $\epsilon_t$: Error term with mean 0
- Changes in log price are equally likely to be positive or negative, preventing negative price values due to the logarithmic specification.
- A random walk with drift is expressed as:
  $$
  \ln P_t = \mu + \ln P_{t-1} + \epsilon_t
  $$
  where $\mu$ is the drift term, often due to persistent inflation or other market factors.
</details>

<details>
<summary>Lo and MacKinlay Variance Ratio Test</summary>

- Lo and MacKinlay (1988) developed a variance ratio test to assess random walk behavior.
- Test principle: If price changes at a given frequency are random, lower frequency price changes should also be random.
- The test estimates the following:
  $$
  \hat{\mu} = \frac{1}{2n} \sum_{k=1}^{2n} (\ln P_k - \ln P_{k-1})
  $$
  $$
  \hat{\sigma}_a^2 = \frac{1}{2n} \sum_{k=1}^{2n} (\ln P_k - \ln P_{k-1} - \hat{\mu})^2
  $$
  $$
  \hat{\sigma}_b^2 = \frac{1}{n} \sum_{k=1}^{n} (\ln P_{2k} - \ln P_{2k-2} - 2\hat{\mu})^2
  $$
- Under the null hypothesis (random walk), the parameters should follow:
  $$
  \sqrt{2n} (\hat{\sigma}_a^2 - \sigma_0^2) \sim N(0, 2\sigma_0^4)
  $$
  $$
  \sqrt{2n} (\hat{\sigma}_b^2 - \sigma_0^2) \sim N(0, 4\sigma_0^4)
  $$
- Market efficiency test statistic:
  $$
  J_r = \frac{\hat{\sigma}_b^2}{\hat{\sigma}_a^2} - 1, \quad \sqrt{2n} J_r \sim N(0, 2)
  $$
- Empirical findings: Weekly and monthly equity data show efficiency; daily data show inefficiency.
</details>

<details>
<summary>Variance Ratio Test Results</summary>

- Table 7.5 evaluates market efficiency across USD currency pairs using the variance ratio $J_r$.
- S&P 500 daily data: $J_r = 0.7360$, statistically significant, indicating inefficiency and potential arbitrage.
- Major USD currency pairs are generally more efficient than the S&P 500.
- USD/CAD is the most efficient pair with the fewest arbitrage opportunities; spot and futures show decreasing efficiency with higher frequency data.
- 1-hour put and call options are more efficient than spot and futures at the same frequency, despite high-frequency markets having more arbitrage opportunities.
- HFT benefits from inefficiencies in spot foreign exchange at sub-daily intervals.
</details>

<details>
<summary>Autoregression-Based Tests</summary>

- Market efficiency can be evaluated by measuring the influence of past prices on current returns.
- Mech (1993) and Hou & Moskowitz (2005) measure efficiency as the difference between Adjusted $R^2$ of unrestricted and restricted autoregression models.
- Unrestricted model:
  $$
  r_{i,t} = \alpha_i + \beta_{i,1} r_{i,t-1} + \beta_{i,2} r_{i,t-2} + \beta_{i,3} r_{i,t-3} + \beta_{i,4} r_{i,t-4} + \epsilon_{i,t}
  $$
- Restricted model:
  $$
  r_{i,t} = \alpha_i + \epsilon_{i,t}
  $$
- Market inefficiency calculation:
  $$
  \text{Market Inefficiency} = 1 - \frac{R^2_{Restricted}}{R^2_{Unrestricted}}
  $$
- A result closer to 0 indicates greater efficiency and minimal influence from past prices.
</details>

<details>
<summary>Martingale Hypothesis and Market Efficiency</summary>

- Samuelson (1965) argues that in an efficient market, expected future prices equal current prices:
  $$
  E[P_{t+1} | I_t] = P_t
  $$
- Abnormal returns, or returns exceeding expected returns, are given by:
  $$
  Z_{t+1} = P_{t+1} - E[P_{t+1} | I_t]
  $$
- A market is efficient if abnormal returns are a "fair game":
  $$
  E[Z_{t+1} | I_t] = 0
  $$
- Fama (1991) argues that perfect efficiency is unrealistic due to trading costs and noise; testing efficiency involves complex joint hypotheses.
- Froot & Thaler (1990) use uncovered interest rate parity for testing efficiency in foreign exchange markets:
  $$
  E[S_{t+1} | I_t] = r_t - r^d_t + \xi_t
  $$
  where $\xi_t$ is the risk premium.
</details>

## Conclusion

<details>
<summary>Conclusion</summary>

  - Tests of market efficiency examine a security's price and return dependency on other variables.
  - Identifying market inefficiencies requires understanding the specific tests that revealed them.
  - The predictability of a security's price can vary depending on the frequency of observation.
  - Different combinations of securities can show varying levels of efficiency.
  - Individual securities may appear random, but combinations of them might be predictable, and the reverse is also possible.

</details>

# 8. Searching for HFT Opportunities 

## Statistical Properties of Returns

## Linear Econometric Models 

## Volatility Modeling 

## Nonlinear Models 

## Conclusion 

# 9. Working with Tick Data 

## Properties of Tick Data

## Quantity and Quality of Tick Data

## Bid-Ask Spreads

## Bid-Ask Bounce

## Modeling Arrivals of Tick Data

## Applying Traditional Econometric Techniques to Tick Data

## Conclusion

# 10. Trading on Market Microstructure: Inventory Models 

## Overview of Inventory Trading Strategies

## Orders, Traders, and Liquidity

## Profitable Market Making

## Directional Liquidity Provision

## Conclusion