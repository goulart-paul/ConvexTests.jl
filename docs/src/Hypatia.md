Table of contents:

```@contents
Pages = ["Hypatia.md"]
Depth = 4
```


Compilation warmup gives an estimate of 1 minute, 22 seconds of compilation time.

## Hypatia 
These tests were run on July 8, 2022 at 02:10 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip"]
```

### Tests

Tests took 7 minutes, 32 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">Hypatia tests</td>
<td style="text-align:center;color:green;">2328</td>
<td style="text-align:center;color:red;">20</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2348</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">721</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">721</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1607</td>
<td style="text-align:center;color:red;">20</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1627</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">443</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">446</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_horn</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_options_pricing</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">495</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">499</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_options_pricing</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_cheby_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_horn</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">669</td>
<td style="text-align:center;color:red;">13</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">682</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_infeasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simple_matrix</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rearrangement</td>
<td style="text-align:center;color:green;">25</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">25</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;maxcut</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=3.9 it should be infeasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=4.1 it should be feasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_rem</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_feasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;chebyshev</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo9</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_horn</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_rem</td>
<td style="text-align:center;color:green;">48</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">48</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;motzkin</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo10</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_maxdegree</td>
<td style="text-align:center;color:green;">56</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">56</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_options_pricing</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;choi</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4_rem</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_2_rem</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr></table>
```

### Errors

```julia
Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 61.74308592833959 ≈ 9.85 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 15528.010847221063 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 15764.317981702452 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset with γ=3.9 it should be infeasible:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:37
  Expression: JuMP.dual_status(model) == MOI.INFEASIBILITY_CERTIFICATE
   Evaluated: MathOptInterface.NEARLY_INFEASIBILITY_CERTIFICATE == MathOptInterface.INFEASIBILITY_CERTIFICATE

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:31
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:32
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset sos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:51
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset sos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:53
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset quadratic_feasible_scaled_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:58
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset quadratic_feasible_scaled_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:59
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset quadratic_feasible_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:58
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset quadratic_feasible_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:59
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             452s /  99.8%           37.2GiB /  99.9%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1     239s   53.0%    239s   17.0GiB   45.9%  17.0GiB
   socp                     1     100s   22.1%    100s   7.18GiB   19.3%  7.18GiB
     sdsos_term_fixed       1    21.6s    4.8%   21.6s   1.33GiB    3.6%  1.33GiB
     sdsos_horn             1    14.1s    3.1%   14.1s    939MiB    2.5%   939MiB
     sdsos_univaria...      1    12.3s    2.7%   12.3s   0.99GiB    2.7%  0.99GiB
     sdsos_concave_...      1    11.0s    2.4%   11.0s    751MiB    2.0%   751MiB
     sdsos_cheby_un...      1    6.68s    1.5%   6.68s    434MiB    1.1%   434MiB
     sdsos_univaria...      1    6.27s    1.4%   6.27s    374MiB    1.0%   374MiB
     sdsos_options_...      1    5.35s    1.2%   5.35s    342MiB    0.9%   342MiB
     sdsos_scaled_u...      1    4.90s    1.1%   4.90s    276MiB    0.7%   276MiB
     sdsos_term             1    4.43s    1.0%   4.43s    273MiB    0.7%   273MiB
     sdsos_quartic_...      1    3.85s    0.9%   3.85s    236MiB    0.6%   236MiB
     sdsos_quartic_...      1    769ms    0.2%   769ms   27.7MiB    0.1%  27.7MiB
     sdsos_scaled_b...      1   46.9ms    0.0%  46.9ms   5.98MiB    0.0%  5.98MiB
     sdsos_bivariat...      1   10.0ms    0.0%  10.0ms    593KiB    0.0%   593KiB
   sdp                      1    97.0s   21.5%   97.0s   6.98GiB   18.8%  6.98GiB
     sosdemo5_infea...      1    7.41s    1.6%   7.41s    511MiB    1.3%   511MiB
     quartic_ideal_rem      1    7.00s    1.6%   7.00s    548MiB    1.4%   548MiB
     rearrangement          1    6.56s    1.5%   6.56s    429MiB    1.1%   429MiB
     sos_concave_th...      1    5.03s    1.1%   5.03s    411MiB    1.1%   411MiB
     sos_horn               1    4.51s    1.0%   4.51s    287MiB    0.8%   287MiB
     quartic_ideal          1    4.23s    0.9%   4.23s    209MiB    0.6%   209MiB
     simple_matrix          1    4.20s    0.9%   4.20s    369MiB    1.0%   369MiB
     sos_scaled_biv...      1    3.94s    0.9%   3.94s    217MiB    0.6%   217MiB
     chebyshev              1    3.89s    0.9%   3.89s    270MiB    0.7%   270MiB
     quartic_ideal_4        1    3.84s    0.9%   3.84s    266MiB    0.7%   266MiB
     sos_term_fixed         1    3.62s    0.8%   3.62s    203MiB    0.5%   203MiB
     sos_cheby_univ...      1    3.47s    0.8%   3.47s    191MiB    0.5%   191MiB
     maxcut                 1    3.47s    0.8%   3.47s    190MiB    0.5%   190MiB
     sos_term               1    2.95s    0.7%   2.95s    174MiB    0.5%   174MiB
     BPT12e399_rem          1    2.86s    0.6%   2.86s   79.0MiB    0.2%  79.0MiB
     sos_quartic_co...      1    2.82s    0.6%   2.82s    162MiB    0.4%   162MiB
     quartic_ideal_...      1    2.73s    0.6%   2.73s    164MiB    0.4%   164MiB
     sos_options_pr...      1    2.73s    0.6%   2.73s    193MiB    0.5%   193MiB
     quartic_feasib...      1    2.69s    0.6%   2.69s    117MiB    0.3%   117MiB
     sosdemo10              1    1.80s    0.4%   1.80s    181MiB    0.5%   181MiB
     sos_univariate...      1    1.51s    0.3%   1.51s    100MiB    0.3%   100MiB
     quadratic_feas...      1    1.11s    0.2%   1.11s   51.9MiB    0.1%  51.9MiB
     sos_univariate...      1    907ms    0.2%   907ms   35.0MiB    0.1%  35.0MiB
     sosdemo9               1    814ms    0.2%   814ms   50.0MiB    0.1%  50.0MiB
     quadratic_infe...      1    703ms    0.2%   703ms   41.5MiB    0.1%  41.5MiB
     choi                   1    572ms    0.1%   572ms   63.8MiB    0.2%  63.8MiB
     sosdemo5_feasible      1    374ms    0.1%   374ms   73.8MiB    0.2%  73.8MiB
     BPT12e399_maxd...      1    350ms    0.1%   350ms   9.28MiB    0.0%  9.28MiB
     sos_quartic_co...      1    209ms    0.0%   209ms   21.2MiB    0.1%  21.2MiB
     motzkin                1   90.1ms    0.0%  90.1ms   4.91MiB    0.0%  4.91MiB
     sos_bivariate_...      1   30.5ms    0.0%  30.5ms    590KiB    0.0%   590KiB
     quartic_infeas...      1   23.8ms    0.0%  23.8ms   2.11MiB    0.0%  2.11MiB
     quadratic_feas...      1   19.2ms    0.0%  19.2ms   1.98MiB    0.0%  1.98MiB
     quartic_ideal_...      1   15.3ms    0.0%  15.3ms   1.15MiB    0.0%  1.15MiB
     quartic_infeas...      1   11.6ms    0.0%  11.6ms   1.46MiB    0.0%  1.46MiB
     sos_scaled_uni...      1   9.87ms    0.0%  9.87ms    588KiB    0.0%   588KiB
     quadratic_infe...      1   6.24ms    0.0%  6.24ms   1.17MiB    0.0%  1.17MiB
     quartic_feasib...      1   4.55ms    0.0%  4.55ms    759KiB    0.0%   759KiB
   lp                       1    42.0s    9.3%   42.0s   2.87GiB    7.7%  2.87GiB
     dsos_options_p...      1    5.96s    1.3%   5.96s    427MiB    1.1%   427MiB
     dsos_concave_t...      1    5.59s    1.2%   5.59s    429MiB    1.1%   429MiB
     dsos_univariat...      1    4.94s    1.1%   4.94s    251MiB    0.7%   251MiB
     dsos_cheby_biv...      1    4.56s    1.0%   4.56s    271MiB    0.7%   271MiB
     dsos_term_fixed        1    3.61s    0.8%   3.61s    212MiB    0.6%   212MiB
     dsos_horn              1    3.46s    0.8%   3.46s    236MiB    0.6%   236MiB
     dsos_scaled_bi...      1    3.45s    0.8%   3.45s    204MiB    0.5%   204MiB
     dsos_term              1    3.05s    0.7%   3.05s    183MiB    0.5%   183MiB
     dsos_quartic_c...      1    2.99s    0.7%   2.99s    170MiB    0.4%   170MiB
     dsos_bivariate...      1    967ms    0.2%   967ms   38.2MiB    0.1%  38.2MiB
     dsos_quartic_c...      1    139ms    0.0%   139ms   21.5MiB    0.1%  21.5MiB
     dsos_univariat...      1   8.59ms    0.0%  8.59ms    656KiB    0.0%   656KiB
     dsos_cheby_uni...      1   7.17ms    0.0%  7.17ms    681KiB    0.0%   681KiB
     dsos_scaled_un...      1   6.60ms    0.0%  6.60ms    656KiB    0.0%   656KiB
 Convex                     1     212s   47.0%    212s   20.1GiB   54.1%  20.1GiB
   sdp                      1     114s   25.2%    114s   10.6GiB   28.6%  10.6GiB
     sdp_quantum_re...      1    19.2s    4.2%   19.2s   1.75GiB    4.7%  1.75GiB
     sdp_lieb_ando          1    10.0s    2.2%   10.0s    894MiB    2.4%   894MiB
     sdp_trace_logm...      1    6.10s    1.4%   6.10s    608MiB    1.6%   608MiB
     sdp_operator_n...      1    4.62s    1.0%   4.62s    320MiB    0.8%   320MiB
     sdp_geom_mean_...      1    3.74s    0.8%   3.74s    124MiB    0.3%   124MiB
     sdp_quantum_re...      1    3.52s    0.8%   3.52s    264MiB    0.7%   264MiB
     sdp_quantum_re...      1    2.62s    0.6%   2.62s    147MiB    0.4%   147MiB
     sdp_Partial_trace      1    2.40s    0.5%   2.40s    207MiB    0.5%   207MiB
     sdp_relative_e...      1    2.30s    0.5%   2.30s    200MiB    0.5%   200MiB
     sdp_quantum_re...      1    2.28s    0.5%   2.28s    143MiB    0.4%   143MiB
     sdp_trace_mpow...      1    2.09s    0.5%   2.09s    223MiB    0.6%   223MiB
     sdp_geom_mean_...      1    2.06s    0.5%   2.06s    234MiB    0.6%   234MiB
     sdp_sum_larges...      1    2.01s    0.4%   2.01s    130MiB    0.3%   130MiB
     sdp_matrix_fra...      1    1.86s    0.4%   1.86s    147MiB    0.4%   147MiB
     sdp_quantum_re...      1    1.86s    0.4%   1.86s   18.4MiB    0.0%  18.4MiB
     sdp_trace_mpow...      1    1.84s    0.4%   1.84s   26.9MiB    0.1%  26.9MiB
     sdp_quantum_re...      1    1.79s    0.4%   1.79s    141MiB    0.4%   141MiB
     sdp_quantum_re...      1    1.59s    0.4%   1.59s   13.2MiB    0.0%  13.2MiB
     sdp_quantum_ch...      1    1.46s    0.3%   1.46s   60.6MiB    0.2%  60.6MiB
     sdp_geom_mean_...      1    1.23s    0.3%   1.23s    122MiB    0.3%   122MiB
     sdp_min_maxeig...      1    1.01s    0.2%   1.01s    111MiB    0.3%   111MiB
     sdp_dual_lambd...      1    1.01s    0.2%   1.01s   66.0MiB    0.2%  66.0MiB
     sdp_lambda_min...      1    880ms    0.2%   880ms   95.2MiB    0.3%  95.2MiB
     sdp_nuclear_no...      1    833ms    0.2%   833ms   87.7MiB    0.2%  87.7MiB
     sdp_geom_mean_...      1    805ms    0.2%   805ms   85.3MiB    0.2%  85.3MiB
     sdp_Complex_Va...      1    739ms    0.2%   739ms   36.6MiB    0.1%  36.6MiB
     sdp_relative_e...      1    672ms    0.1%   672ms   18.0MiB    0.0%  18.0MiB
     sdp_trace_mpow...      1    652ms    0.1%   652ms   21.6MiB    0.1%  21.6MiB
     sdp_socp_sumsq...      1    645ms    0.1%   645ms   54.0MiB    0.1%  54.0MiB
     sdp_geom_mean_...      1    576ms    0.1%   576ms   51.5MiB    0.1%  51.5MiB
     sdp_socp_norm2...      1    552ms    0.1%   552ms   46.7MiB    0.1%  46.7MiB
     sdp_trace_logm...      1    550ms    0.1%   550ms   38.0MiB    0.1%  38.0MiB
     sdp_geom_mean_...      1    532ms    0.1%   532ms   82.3MiB    0.2%  82.3MiB
     sdp_trace_mpow...      1    436ms    0.1%   436ms   12.4MiB    0.0%  12.4MiB
     sdp_sdp_variables      1    329ms    0.1%   329ms   28.6MiB    0.1%  28.6MiB
     sdp_socp_abs_atom      1    322ms    0.1%   322ms   21.9MiB    0.1%  21.9MiB
     sdp_geom_mean_...      1    322ms    0.1%   322ms   35.7MiB    0.1%  35.7MiB
     sdp_quantum_re...      1    312ms    0.1%   312ms   22.6MiB    0.1%  22.6MiB
     sdp_Complex_Se...      1    303ms    0.1%   303ms   27.5MiB    0.1%  27.5MiB
     sdp_geom_mean_...      1    276ms    0.1%   276ms   19.7MiB    0.1%  19.7MiB
     sdp_trace_mpow...      1    256ms    0.1%   256ms   18.4MiB    0.0%  18.4MiB
     sdp_trace_mpow...      1    247ms    0.1%   247ms   17.6MiB    0.0%  17.6MiB
     sdp_trace_mpow...      1    242ms    0.1%   242ms   14.7MiB    0.0%  14.7MiB
     sdp_geom_mean_...      1    232ms    0.1%   232ms   15.9MiB    0.0%  15.9MiB
     sdp_quantum_re...      1    223ms    0.0%   223ms   15.8MiB    0.0%  15.8MiB
     sdp_operator_n...      1    221ms    0.0%   221ms   23.2MiB    0.1%  23.2MiB
     sdp_geom_mean_...      1    221ms    0.0%   221ms   11.9MiB    0.0%  11.9MiB
     sdp_matrix_fra...      1    208ms    0.0%   208ms   18.1MiB    0.0%  18.1MiB
     sdp_quantum_re...      1    186ms    0.0%   186ms   13.4MiB    0.0%  13.4MiB
     sdp_nuclear_no...      1    181ms    0.0%   181ms   18.7MiB    0.0%  18.7MiB
     sdp_geom_mean_...      1    172ms    0.0%   172ms   18.5MiB    0.0%  18.5MiB
     sdp_geom_mean_...      1    166ms    0.0%   166ms   18.9MiB    0.0%  18.9MiB
     sdp_trace_logm...      1    162ms    0.0%   162ms   6.75MiB    0.0%  6.75MiB
     sdp_sigma_max_...      1    153ms    0.0%   153ms   16.6MiB    0.0%  16.6MiB
     sdp_Real_Varia...      1    131ms    0.0%   131ms   5.45MiB    0.0%  5.45MiB
     sdp_geom_mean_...      1    121ms    0.0%   121ms   17.9MiB    0.0%  17.9MiB
     sdp_geom_mean_...      1    121ms    0.0%   121ms   18.1MiB    0.0%  18.1MiB
     sdp_sdp_constr...      1    116ms    0.0%   116ms   10.0MiB    0.0%  10.0MiB
     sdp_geom_mean_...      1    113ms    0.0%   113ms   18.3MiB    0.0%  18.3MiB
     sdp_kron_atom          1    105ms    0.0%   105ms   11.2MiB    0.0%  11.2MiB
     sdp_geom_mean_...      1    104ms    0.0%   104ms   17.7MiB    0.0%  17.7MiB
     sdp_Issue_198          1   80.1ms    0.0%  80.1ms   5.39MiB    0.0%  5.39MiB
     sdp_geom_mean_...      1   76.3ms    0.0%  76.3ms   13.9MiB    0.0%  13.9MiB
     sdp_quantum_re...      1   69.9ms    0.0%  69.9ms   3.10MiB    0.0%  3.10MiB
     sdp_quantum_re...      1   7.44ms    0.0%  7.44ms    426KiB    0.0%   426KiB
   affine                   1    40.3s    8.9%   40.3s   3.76GiB   10.1%  3.76GiB
     affine_Partial...      1    4.40s    1.0%   4.40s    515MiB    1.4%   515MiB
     affine_hcat_atom       1    3.02s    0.7%   3.02s    249MiB    0.7%   249MiB
     affine_multipl...      1    3.02s    0.7%   3.02s    246MiB    0.6%   246MiB
     affine_permute...      1    2.95s    0.7%   2.95s    376MiB    1.0%   376MiB
     affine_dot_mul...      1    2.76s    0.6%   2.76s    174MiB    0.5%   174MiB
     affine_vcat_atom       1    2.54s    0.6%   2.54s    230MiB    0.6%   230MiB
     affine_transpo...      1    1.84s    0.4%   1.84s    105MiB    0.3%   105MiB
     affine_add_atom        1    1.47s    0.3%   1.47s   80.1MiB    0.2%  80.1MiB
     affine_Diagona...      1    1.42s    0.3%   1.42s    125MiB    0.3%   125MiB
     affine_satisfy...      1    1.22s    0.3%   1.22s   55.7MiB    0.1%  55.7MiB
     affine_conv_atom       1    985ms    0.2%   985ms   49.5MiB    0.1%  49.5MiB
     affine_reshape...      1    856ms    0.2%   856ms   31.3MiB    0.1%  31.3MiB
     affine_dot_atom        1    846ms    0.2%   846ms   27.2MiB    0.1%  27.2MiB
     affine_index_atom      1    840ms    0.2%   840ms   44.1MiB    0.1%  44.1MiB
     affine_dualvalue       1    741ms    0.2%   741ms   75.4MiB    0.2%  75.4MiB
     affine_sum_atom        1    375ms    0.1%   375ms   24.0MiB    0.1%  24.0MiB
     affine_kron_atom       1    263ms    0.1%   263ms   16.3MiB    0.0%  16.3MiB
     affine_single_...      1    221ms    0.0%   221ms   22.6MiB    0.1%  22.6MiB
     affine_diag_atom       1    203ms    0.0%   203ms   16.2MiB    0.0%  16.2MiB
     affine_single_...      1    159ms    0.0%   159ms   17.7MiB    0.0%  17.7MiB
     affine_dot_ato...      1    144ms    0.0%   144ms   6.21MiB    0.0%  6.21MiB
     affine_negate_...      1    122ms    0.0%   122ms   3.87MiB    0.0%  3.87MiB
     affine_trace_atom      1   73.2ms    0.0%  73.2ms   3.44MiB    0.0%  3.44MiB
   socp                     1    24.8s    5.5%   24.8s   2.65GiB    7.1%  2.65GiB
     socp_dual_mini...      1    5.06s    1.1%   5.06s    510MiB    1.3%   510MiB
     socp_quad_form...      1    2.95s    0.7%   2.95s   98.7MiB    0.3%  98.7MiB
     socp_rational_...      1    1.55s    0.3%   1.55s    161MiB    0.4%   161MiB
     socp_inv_pos_atom      1    1.36s    0.3%   1.36s   99.1MiB    0.3%  99.1MiB
     socp_sum_squar...      1    1.30s    0.3%   1.30s    108MiB    0.3%   108MiB
     socp_quad_over...      1    833ms    0.2%   833ms   41.1MiB    0.1%  41.1MiB
     socp_dual_norm...      1    832ms    0.2%   832ms   81.0MiB    0.2%  81.0MiB
     socp_norm_cons...      1    757ms    0.2%   757ms   57.3MiB    0.2%  57.3MiB
     socp_rational_...      1    608ms    0.1%   608ms   54.9MiB    0.1%  54.9MiB
     socp_square_atom       1    445ms    0.1%   445ms   27.4MiB    0.1%  27.4MiB
     socp_huber_atom        1    418ms    0.1%   418ms   37.1MiB    0.1%  37.1MiB
     socp_fix_multi...      1    408ms    0.1%   408ms   42.1MiB    0.1%  42.1MiB
     socp_geo_mean_...      1    357ms    0.1%   357ms   25.8MiB    0.1%  25.8MiB
     socp_dual_frob...      1    268ms    0.1%   268ms   37.7MiB    0.1%  37.7MiB
     socp_fix_and_f...      1    257ms    0.1%   257ms   20.9MiB    0.1%  20.9MiB
     socp_rational_...      1    190ms    0.0%   190ms   11.0MiB    0.0%  11.0MiB
     socp_sqrt_atom         1   70.0ms    0.0%  70.0ms   1.29MiB    0.0%  1.29MiB
   constant                 1    11.0s    2.4%   11.0s   0.95GiB    2.5%  0.95GiB
     constant_fix!_...      1    3.93s    0.9%   3.93s    291MiB    0.8%   291MiB
     constant_Issue...      1    2.83s    0.6%   2.83s    242MiB    0.6%   242MiB
     constant_Issue...      1    1.07s    0.2%   1.07s   81.5MiB    0.2%  81.5MiB
     constant_fix!_...      1    851ms    0.2%   851ms   61.5MiB    0.2%  61.5MiB
     constant_Test_...      1    449ms    0.1%   449ms   19.2MiB    0.1%  19.2MiB
     constant_fix!_...      1    401ms    0.1%   401ms   19.1MiB    0.1%  19.1MiB
   exp                      1    9.29s    2.1%   9.29s    913MiB    2.4%   913MiB
     exp_log_atom           1    6.55s    1.5%   6.55s    653MiB    1.7%   653MiB
     exp_entropy_atom       1    501ms    0.1%   501ms   42.1MiB    0.1%  42.1MiB
     exp_log_sum_ex...      1    389ms    0.1%   389ms   32.2MiB    0.1%  32.2MiB
     exp_logistic_l...      1    348ms    0.1%   348ms   17.1MiB    0.0%  17.1MiB
     exp_exp_atom           1    346ms    0.1%   346ms   25.1MiB    0.1%  25.1MiB
     exp_log_perspe...      1    243ms    0.1%   243ms   13.7MiB    0.0%  13.7MiB
     exp_relative_e...      1   67.5ms    0.0%  67.5ms   5.47MiB    0.0%  5.47MiB
   lp                       1    7.11s    1.6%   7.11s    711MiB    1.9%   711MiB
     lp_dotsort_atom        1    1.16s    0.3%   1.16s   91.2MiB    0.2%  91.2MiB
     lp_min_atom            1    799ms    0.2%   799ms   64.1MiB    0.2%  64.1MiB
     lp_sumlargest_...      1    625ms    0.1%   625ms   48.1MiB    0.1%  48.1MiB
     lp_max_atom            1    526ms    0.1%   526ms   44.0MiB    0.1%  44.0MiB
     lp_minimum_atom        1    515ms    0.1%   515ms   40.6MiB    0.1%  40.6MiB
     lp_sumsmallest...      1    408ms    0.1%   408ms   31.3MiB    0.1%  31.3MiB
     lp_dual_abs_atom       1    316ms    0.1%   316ms   21.2MiB    0.1%  21.2MiB
     lp_neg_atom            1    262ms    0.1%   262ms   19.6MiB    0.1%  19.6MiB
     lp_maximum_atom        1    233ms    0.1%   233ms   13.5MiB    0.0%  13.5MiB
     lp_pos_atom            1    101ms    0.0%   101ms   9.42MiB    0.0%  9.42MiB
     lp_dual_norm_i...      1    100ms    0.0%   100ms   4.29MiB    0.0%  4.29MiB
     lp_dual_norm_1...      1   70.5ms    0.0%  70.5ms   4.14MiB    0.0%  4.14MiB
     lp_hinge_loss_...      1    163μs    0.0%   163μs   57.3KiB    0.0%  57.3KiB
   sdp_and_exp              1    5.61s    1.2%   5.61s    504MiB    1.3%   504MiB
     sdp_and_exp_lo...      1    5.52s    1.2%   5.52s    488MiB    1.3%   488MiB
 ────────────────────────────────────────────────────────────────────────────────

```

## Version information
`versioninfo()`:
```julia
Julia Version 1.6.6
Commit b8708f954a (2022-03-28 07:17 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) CPU E5-2673 v4 @ 2.30GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, broadwell)
```

Manifest:
```julia
      Status `~/work/ConvexTests.jl/ConvexTests.jl/Hypatia/Manifest.toml`
  [14f7f29c] AMD v0.4.0
  [c3fe647b] AbstractAlgebra v0.22.3
  [1520ce14] AbstractTrees v0.3.4
  [6e4b80f9] BenchmarkTools v1.3.1
  [49dc2e85] Calculus v0.5.1
  [d360d2e6] ChainRulesCore v1.15.1
  [9e997f8a] ChangesOfVariables v0.1.3
  [523fee87] CodecBzip2 v0.7.2
  [944b1d66] CodecZlib v0.7.0
  [861a8166] Combinatorics v1.0.2
  [bbf7d656] CommonSubexpressions v0.3.0
  [34da2185] Compat v4.1.0
  [25c3070e] ComplexOptInterface v0.1.2
  [f65535da] Convex v0.15.1
  [cb7cb77b] ConvexTests v0.1.0 `~/work/ConvexTests.jl/ConvexTests.jl`
  [da8f5974] Cyclotomics v0.3.2
  [9a962f9c] DataAPI v1.10.0
  [864edb3b] DataStructures v0.18.13
  [e2d170a0] DataValueInterfaces v1.0.0
  [163ba53b] DiffResults v1.0.3
  [b552c78f] DiffRules v1.11.0
  [ffbed154] DocStringExtensions v0.8.6
  [7c1d4256] DynamicPolynomials v0.4.5
  [e2ba6199] ExprTools v0.1.8
  [f6369f11] ForwardDiff v0.10.30
  [14197337] GenericLinearAlgebra v0.3.1
  [d5909c97] GroupsCore v0.4.0
  [b99e6be6] Hypatia v0.7.0
  [18e54dd8] IntegerMathUtils v0.1.0
  [3587e190] InverseFunctions v0.1.7
  [92d709cd] IrrationalConstants v0.1.1
  [42fd0dbc] IterativeSolvers v0.9.2
  [82899510] IteratorInterfaceExtensions v1.0.0
  [692b3bcd] JLLWrappers v1.4.1
  [682c06a0] JSON v0.21.3
  [4076af6c] JuMP v1.1.1
  [40e66cde] LDLFactorizations v0.8.2
  [8ac3fa9e] LRUCache v1.3.0
  [7a12625a] LinearMaps v3.8.0
  [2ab3a3ac] LogExpFunctions v0.3.15
  [1914dd2f] MacroTools v0.5.9
  [b8f27783] MathOptInterface v1.6.0
  [c03570c3] Memoize v0.4.4
  [be282fd4] MultivariateBases v0.1.5
  [f4abf1af] MultivariateMoments v0.3.9
  [102ac46a] MultivariatePolynomials v0.4.6
  [d8a4904e] MutableArithmetics v1.0.4
  [77ba4419] NaNMath v1.0.0
  [bac558e1] OrderedCollections v1.4.1
  [69de0a69] Parsers v2.3.2
  [8bc5a954] PermutationGroups v0.3.2
  [ddf597a6] PolyJuMP v0.6.2
  [3a141323] PolynomialRoots v1.0.0
  [21216c6a] Preferences v1.3.0
  [27ebfcd6] Primes v0.5.3
  [fb686558] RandomExtensions v0.4.3
  [3cdcf5f2] RecipesBase v1.2.1
  [189a3867] Reexport v1.2.2
  [ae029012] Requires v1.3.0
  [af85af4c] RowEchelon v0.2.1
  [8e049039] SemialgebraicSets v0.2.5
  [276daf66] SpecialFunctions v2.1.7
  [0c0c59c1] StarAlgebras v0.1.7
  [90137ffa] StaticArrays v1.5.0
  [1e83bf80] StaticArraysCore v1.0.1
  [4b9e565b] SumOfSquares v0.6.2
  [858aa9a9] SymbolicWedderburn v0.3.0
  [f9bf3ced] TableTestSets v0.1.0 `https://github.com/ericphanson/TableTestSets.jl#master`
  [3783bdb8] TableTraits v1.0.1
  [bd369af6] Tables v1.7.0
  [a759f4b9] TimerOutputs v0.5.20
  [3bb67fe8] TranscodingStreams v0.9.6
  [6e34b625] Bzip2_jll v1.0.8+0
  [efe28fd5] OpenSpecFun_jll v0.5.5+0
  [8e850b90] libblastrampoline_jll v3.1.0+2
  [0dad84c5] ArgTools
  [56f22d72] Artifacts
  [2a0f44e3] Base64
  [ade2ca70] Dates
  [f43a241f] Downloads
  [9fa8497b] Future
  [b77e0a4c] InteractiveUtils
  [b27032c2] LibCURL
  [76f85450] LibGit2
  [8f399da3] Libdl
  [37e2e46d] LinearAlgebra
  [56ddb016] Logging
  [d6f4376e] Markdown
  [a63ad114] Mmap
  [ca575930] NetworkOptions
  [44cfe95a] Pkg
  [de0858da] Printf
  [9abbd945] Profile
  [3fa0cd96] REPL
  [9a3f8284] Random
  [ea8e919c] SHA
  [9e88b42a] Serialization
  [6462fe0b] Sockets
  [2f01184e] SparseArrays
  [10745b16] Statistics
  [4607b0f0] SuiteSparse
  [fa267f1f] TOML
  [a4e569a6] Tar
  [8dfed614] Test
  [cf7118a7] UUIDs
  [4ec0a83e] Unicode
  [e66e0078] CompilerSupportLibraries_jll
  [deac9b47] LibCURL_jll
  [29816b5a] LibSSH2_jll
  [c8ffd9c3] MbedTLS_jll
  [14a3606d] MozillaCACerts_jll
  [05823500] OpenLibm_jll
  [83775a58] Zlib_jll
  [8e850ede] nghttp2_jll
  [3f19e933] p7zip_jll
```
