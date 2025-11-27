# fourier-options-pricing


Implementation of the Carr–Madan (1999) Fast-Fourier-Transform method for pricing
European call options.

The code supports three models via their characteristic functions:

- **Black–Scholes** (geometric Brownian motion)
- **Merton** jump–diffusion
- **Heston** stochastic volatility (using the “Little Heston Trap” formulation)

The mathematical derivations are in the accompanying note..

## Files

- 'fourier_option_pricing.R'
  Main R script:
  - Implements the FFT pricer ('carr_madan_fft', 'price_call')
  - Defines characteristic functions for Black–Scholes, Merton, and Heston
  - Contains code to generate the tables and figures referenced in the note

- 'fourier_methods_option.pdf'  
  Mathematical background and explanation of the implementation.

- 'fourier_results_montage.pdf'  
  Compact visual summary of numerical results

- 'console_output.txt' – raw R console output from running 'fourier_option_pricing.R'
