# Zero-Coupon-Yield-Curve-Bootstrapping-in-Python
 This report demonstrates how to derive zero-coupon (spot) interest rates from market bond prices
 using the bootstrapping method. The method is applied to coupon-bearing bonds to estimate the
 term structure of interest rates, which can then be used to compute forward rates and, as an
 extension, estimate swap curves.
 Project Objective
 To calculate zero-coupon interest rates (spot rates) from market bond prices and visualize the
 resulting yield curve. The project also includes the calculation of forward rates and discusses the
 extension to swap curve estimation.
 Methodology
 1. Load market bond data: Maturity, coupon rate, price, and face value. 2. Apply the bootstrapping
 method to sequentially solve for spot rates starting from the shortest maturity. 3. Calculate forward
 rates from the spot rates to understand future interest rate expectations. 4. Plot the zero-coupon
 yield curve for visual analysis. 5. Discuss extension to swap curve estimation.
 Sample Output
 Maturity (Years) Coupon (%) Price
 Spot Rate (%)
 0.5
 0.00
 98.00
 4.08
 1.0
 1.5
 2.0
 2.5
 Conclusion
 5.00
 6.00
 6.00
 6.50
 101.50 4.95
 103.00 5.12
 104.50 5.25
 106.00 5.38
 This Python-based bootstrapping project provides a practical approach to deriving zero-coupon
 yield curves from bond prices. It is valuable for FRM candidates, risk managers, and fixed-income
 analysts to understand term structure modeling, forward rate derivation, and the fundamentals of
 swap curve estimation
