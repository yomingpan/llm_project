# Quantitative Analysis of Project Risks

## Introduction
Quantitative risk analysis is a technique used to evaluate the potential impact of identified risks on project objectives. This analysis provides a numerical estimate of the likelihood and impact of risks, allowing for informed decision-making.

## Purpose
The purpose of this document is to outline the methodology for conducting quantitative risk analysis, present the results, and recommend actions based on the findings.

## Methodology
1. **Risk Identification**: Review the Risk Register to identify risks that require quantitative analysis.
2. **Data Collection**: Gather relevant data for each identified risk, including historical data, expert judgment, and statistical analysis.
3. **Modeling Techniques**:
   - **Monte Carlo Simulation**: A statistical technique used to model the probability of different outcomes in a process that cannot easily be predicted due to the intervention of random variables.
   - **Decision Tree Analysis**: A graphical representation of decisions and their possible consequences, including chance event outcomes, resource costs, and utility.

4. **Risk Assessment**: Analyze the data using the chosen modeling techniques to determine the potential impact on project objectives.


## Results

### Quantitative Risk Analysis Table
| Risk ID | Description                   | Analysis Method      | Most Likely Impact (NTD) | Pessimistic (NTD) | Optimistic (NTD) | Expected Monetary Value (EMV) | Probability (%) | Schedule Impact (days) | Notes |
|---------|-------------------------------|---------------------|-------------------------|-------------------|------------------|-------------------------------|-----------------|------------------------|-------|
| R1      | Delay in project deliverables | Monte Carlo         | 200,000                 | 300,000           | 100,000          | 180,000                       | 40              | 15                     | Based on historical data |
| R2      | Budget overruns               | Decision Tree       | 150,000                 | 250,000           | 80,000           | 120,000                       | 20              | 0                      | Cost only |
| R3      | Resource availability issues  | Monte Carlo         | 100,000                 | 180,000           | 50,000           | 90,000                        | 30              | 10                     | Includes overtime cost |

#### Example: Monte Carlo Simulation Summary
- Simulated 10,000 project runs.
- 80% probability project cost ≤ NTD 5,000,000.
- 10% probability schedule delay > 20 days.

#### Example: Decision Tree Analysis
- If risk R2 occurs, expected additional cost: NTD 120,000.
- If not, no additional cost.

### Probability Distributions
（可於Jira附上Excel/圖表，或於會議簡報展示）

---


## Recommendations
根據量化分析結果，建議如下：
- **風險緩解（Mitigation）**：針對R1，建議增加進度緩衝與資源彈性調度。
- **風險接受（Acceptance）**：針對R3，若影響可控，則接受並持續監控。
- **風險轉移（Transfer）**：針對R2，建議部分高額支出採保險或外包。

建議於Jira建立對應Issue，並追蹤EMV與Schedule Impact指標。

## Conclusion
Quantitative risk analysis is a critical component of effective project management. By understanding the potential impacts of risks, project managers can make informed decisions to enhance project success.

## Appendices

### Appendix A: Data Sources
- 專案歷史數據
- 專家判斷
- 相關專案風險資料庫

### Appendix B: Detailed Risk Analysis Results
（可於Jira或Excel附檔，包含模擬參數、分布圖、詳細計算過程）

### Appendix C: Glossary of Terms
- EMV：期望金額值（Expected Monetary Value）
- Monte Carlo Simulation：蒙地卡羅模擬
- Decision Tree：決策樹