## Phase 2 - Risk Assessment

**Framework:** ISO 27001:2022  
**Documents:** Asset Inventory | Risk Register | Risk Matrix

The second phase of this project involved conducting a full risk assessment for Pay29 Solutions. Before identifying risks, I started by building an asset inventory to understand what Pay29 has and what needs to be protected. 
From there I worked through the risk assessment process systematically - identifying threats, vulnerabilities, scoring risks and mapping controls.

**Asset Inventory**

I identified 10 key assets across Pay29's environment covering cloud infrastructure, applications, data, endpoints, people and vendor contracts. For each asset I documented the asset type, a brief description, the designated owner and a classification level ranging from Medium to Critical 
based on the sensitivity of the asset and its importance to Pay29's operations.

**Risk Assessment**

For each asset I identified a realistic threat and the underlying vulnerability that makes Pay29 susceptible to it. Each risk was then scored using a 5x5 likelihood and impact matrix producing a risk score and level across four categories - Critical, High, Medium and Low

The final risk distribution across the 10 identified risks came out as:

| Risk Level | Count |
|---|---|
| 🔴 Critical | 3 |
| 🟠 High | 4 |
| 🟡 Medium | 2 |
| 🟢 Low | 1 |

**Control Mapping and Treatment**

Each risk was mapped to a relevant ISO 27001:2022 Annex A control and assigned a treatment decision - Mitigate or Accept. For every risk marked as Mitigate, a specific treatment action was documented along with the risk owner and current status. Most existing controls at Pay29 were found to be absent, which aligns with the findings from the gap analysis in Phase 1.
