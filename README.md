# Bonds-And-Fixed-Income
Yield curve modelling and bond risk metrics
This workbook walks through the making of a yield curve from the ground up.
>Starting with pure discount bonds and gradually layering real market complexity.

"Each sheet adds another step in building intuition around how interest rates evolve with time, and how the Nelson-Siegel model captures that shape."
Structure:

** Pure discount Term Structure **
Begins with a simple zero-coupon setup to outline the foundation of a term structure.

** Discount with few bonds for t **
Extends the curve using a small sample of bonds to estimate discount factors.

** d(t) with multiple bond for t **
Builds a more complete curve across multiple maturities and cashflows.

** NS Curve fitting **
 Fits the Nelson-Siegel parameters to the derived yields, showing the model’s smooth representation.

** T-notes **
Introduces real Treasury Note data as input for model calibration.

** NS for T-notes **
  Applies the Nelson-Siegel fitting to Treasury data to validate and visualize the curve behavior.
