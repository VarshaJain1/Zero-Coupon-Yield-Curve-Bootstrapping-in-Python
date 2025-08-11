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
 Conclusion
 This Python-based bootstrapping project provides a practical approach to deriving zero-coupon
 yield curves from bond prices. It is valuable for FRM candidates, risk managers, and fixed-income
 analysts to understand term structure modeling, forward rate derivation, and the fundamentals of
 swap curve estimation
