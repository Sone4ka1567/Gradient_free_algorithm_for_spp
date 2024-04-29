# Gradient_free_algorithm_for_spp
Experiments for ZOS-SEG algorithm for paper E. Statkevich et. al "Gradient-free algorithm for saddle point problems under overparametrization".

For stochastic noise we use standard normal distribution, multiplied by Delta. For deterministic noise we use function, depending on argument norm.

Notebook "Parameters_Fitting" contains algorithm implementation and fitting of the following parameters: batch_size B, step_size and smoothing parameter tau.

Notebook "Comparison" contains calculations of convergence rates for three different algorithms for solving Saddle point problem. Here you can see comparison results for stochastic and deterministic noise respecctively.

<img width="817" alt="Screenshot 2024-04-29 at 11 59 14" src="https://github.com/Sone4ka1567/Gradient_free_algorithm_for_spp/assets/42847357/3af430e1-2b0c-4a7e-9c78-31d8ae12d8ff">


<img width="799" alt="Screenshot 2024-04-29 at 11 59 25" src="https://github.com/Sone4ka1567/Gradient_free_algorithm_for_spp/assets/42847357/e7c7354c-6094-4610-97bd-526d0a8610b0">
