# Bonds-And-Fixed-Income

## 1. Bond Duraation and Convexity
Interest Rate Sensitivity- Bond duration and convexity 
>>Managing it is a key requirement and in order to do so, market participants need to understand how fixed income prices change when interest rates change.
"Helps ensure that a portfolio of assets keeps pace with a portfolio of liabilities or to hedge one fixed income instrument or portfolio with another"

#### Duration 
"change YTM to observe how duration shifts with yield movements."
##### Macaulay Duration
Weighted average time until cash flows are received, using PV weights.
##### Modified Duration 
Macaulay Duration / (1 + YTM/n), which expresses price sensitivity to yield changes.

#### Convexity Analysis
"Adds the Convexity component, which refines the duration estimate by accounting for non-linear price–yield behavior. Demonstrates how convexity correction improves the accuracy of price change estimates."

#### Price Sensitivity & Immunization
"Duration + Convexity adjustments
##### Plots Price vs. Yield Curve
1. The linear (duration-based) approximation
2. The curved (convexity-adjusted) approximation
3. Includes an immunization example where portfolio duration and convexity are matched to neutralize small rate movements.
   


## 2. Yield curve modelling and bond risk metrics
This workbook walks through the making of a yield curve from the ground up.

>>Starting with pure discount bonds and gradually layering real market complexity.
"Each sheet adds another step in building intuition around how interest rates evolve with time, and how the Nelson-Siegel model captures that shape."
Structure:

#### Pure discount Term Structure 
Begins with a simple zero-coupon setup to outline the foundation of a term structure.

####  Discount with few bonds for t 
Extends the curve using a small sample of bonds to estimate discount factors.

####  d(t) with multiple bond for t 
Builds a more complete curve across multiple maturities and cashflows.

####  NS Curve fitting 
 Fits the Nelson-Siegel parameters to the derived yields, showing the model’s smooth representation.

####  T-notes 
Introduces real Treasury Note data as input for model calibration.

####  NS for T-notes 
  Applies the Nelson-Siegel fitting to Treasury data to validate and visualize the curve behavior.
