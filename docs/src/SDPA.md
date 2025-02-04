Table of contents:

```@contents
Pages = ["SDPA.md"]
Depth = 4
```


Compilation warmup gives an estimate of 38 seconds of compilation time.

## SDPA `PARAMETER_DEFAULT`
These tests were run on July 8, 2022 at 02:07 (UTC).

Tests with SDPA via SDPA.jl.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 5 minutes, 51 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">2048</td>
<td style="text-align:center;color:red;">268</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2316</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">510</td>
<td style="text-align:center;color:red;">179</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">689</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">141</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">141</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">101</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">101</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">61</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">65</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">15</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">15</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">179</td>
<td style="text-align:center;color:red;">175</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">354</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy4_lowrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_relative_entropy</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_min_maxeig_canon_lmi</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_1</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_fullhyp</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_3_8</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_5_4</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom_complex</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_cplx</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg1_optB</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy3_lowrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy3_fullrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy_const</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_2_3</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy5_lowrank</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_real</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_relative_entropy_argcheck</td>
<td style="text-align:center;color:green;">21</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">21</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_3_5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_1_2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_argcheck</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_argcheck</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom_complex</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_8_5_optA</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lieb_ando</td>
<td style="text-align:center;color:green;">8</td>
<td style="text-align:center;color:red;">72</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">80</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy2_lowrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_channel_capacity</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_neg1_4</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg3_5_optB</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg3_5_optA</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_3_5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy5_fullrank</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy1_lowrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_8_5_optB</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy2_fullrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy_argcheck</td>
<td style="text-align:center;color:green;">16</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">16</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_argcheck</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_1_2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_5_4</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy1_fullrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy4_fullrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_neg1_4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_argcheck</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_2_3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_3_8</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg1_optA</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1538</td>
<td style="text-align:center;color:red;">89</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1627</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">434</td>
<td style="text-align:center;color:red;">12</td>
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
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;color:red;">2</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">440</td>
<td style="text-align:center;color:red;">59</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">499</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_sum</td>
<td style="text-align:center;color:green;">32</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_options_pricing</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
<td style="text-align:center;color:green;">46</td>
<td style="text-align:center;color:red;">7</td>
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
<td style="text-align:center;color:green;">46</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_horn</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">3</td>
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
<td style="text-align:center;color:green;">46</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">46</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">46</td>
<td style="text-align:center;color:red;">7</td>
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
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">46</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">664</td>
<td style="text-align:center;color:red;">18</td>
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
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;color:red;">2</td>
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
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
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
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">1</td>
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
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
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
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
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
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_options_pricing</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
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
Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/lp.jl:307
  Expression: ≈(p.optval, 19, atol = atol, rtol = rtol)
   Evaluated: 18.996700396785855 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/lp.jl:327
  Expression: ≈(p.optval, 19, atol = atol, rtol = rtol)
   Evaluated: 18.16445614291115 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/lp.jl:176
  Expression: ≈(p.optval, 3, atol = atol, rtol = rtol)
   Evaluated: 2.964940355002909 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset lp_pos_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/lp.jl:177
  Expression: ≈(evaluate(sum(pos(x))), 3, atol = atol, rtol = rtol)
   Evaluated: 3.0029386112792054 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.299018785843316 0.09092644585768994 0.15839880303053633; 0.09092645004778888 0.3370700756705105 -0.11011414139147746; 0.15839881448584947 -0.11011414784559292 0.36352168006686725] ≈ [0.36978567242074806 -0.03588755677601767 0.31772907409031115; -0.03588755677601767 0.215395393447707 -0.1466079961392317; 0.31772907409031115 -0.1466079961392317 0.41481893413154497] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [-2.35741026699543e-9 0.1560420041161592 0.0491217283766332; -0.15604200646396293 2.6273028197465464e-10 0.09986249437423567; -0.049121730932199625 -0.0998624976975293 1.0811049833137076e-9] ≈ [0.0 0.18999724164426005 -0.04588632161402458; -0.18999724164426005 0.0 -0.07478694179387721; 0.04588632161402458 0.07478694179387721 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -3889.1326350044274 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1512
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(B, X)), atol = atol, rtol = rtol)
   Evaluated: -3889.1326350044274 ≈ 0.23796541352193798 (atol=0.001, rtol=0.0)

Error in testset sdp_relative_entropy:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1005
  Expression: ≈(Y.value, eye(n) * exp(-1), atol = atol, rtol = rtol)
   Evaluated: [15.822132181261281 0.0 0.0 0.0; 0.0 15.822132151162009 0.0 0.0; 0.0 0.0 15.822132110151415 0.0; 0.0 0.0 0.0 15.822132128923158] ≈ [0.36787944117144233 0.0 0.0 0.0; 0.0 0.36787944117144233 0.0 0.0; 0.0 0.0 0.36787944117144233 0.0; 0.0 0.0 0.0 0.36787944117144233] (atol=0.001, rtol=0.0)

Error in testset sdp_relative_entropy:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1005
  Expression: ≈(Y.value, eye(n) * exp(-1), atol = atol, rtol = rtol)
   Evaluated: ComplexF64[279.76983450406385 + 0.0im 0.0 + 0.0im 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 279.76983450496454 + 0.0im 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im 279.7698345053963 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im 0.0 + 0.0im 279.7698345046279 + 0.0im] ≈ [0.36787944117144233 0.0 0.0 0.0; 0.0 0.36787944117144233 0.0 0.0; 0.0 0.0 0.36787944117144233 0.0; 0.0 0.0 0.0 0.36787944117144233] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_fullhyp:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1230
  Expression: p.status == MOI.INFEASIBLE
   Evaluated: MathOptInterface.INFEASIBLE_OR_UNBOUNDED == MathOptInterface.INFEASIBLE

Error in testset sdp_geom_mean_hypocone_fullhyp:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1240
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sdp_geom_mean_hypocone_cplx_3_8:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1178
  Expression: ≈(real.(B.value), real.(A ^ (-5 // 3)), atol = atol, rtol = rtol)
   Evaluated: [54.70166967734201 1.1171999036209854 0.2561405720161929 -0.10514322022811484; 1.117199903621099 54.779831790693834 -1.9023992717569627 -0.4819314689341354; 0.2561405720160792 -1.90239927175719 58.46107972673042 0.19509594472697245; -0.10514322022811484 -0.4819314689341354 0.19509594472674507 53.0783899259261] ≈ [1.315460769832164 1.04437080284095 0.22256128711222356 -0.1750590819987554; 1.04437080284095 1.8955720833243355 -1.7934397093682177 -0.3309540093941876; 0.22256128711222356 -1.7934397093682177 5.305967514590667 0.1803744458002045; -0.1750590819987554 -0.3309540093941876 0.1803744458002045 0.14956947673685878] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_cplx_3_8:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1179
  Expression: ≈(imag.(B.value), imag.(A ^ (-5 // 3)), atol = atol, rtol = rtol)
   Evaluated: [0.0 -0.8406094456893243 2.0821742300379356 -0.13528072525707557; 0.8406094456895516 0.0 2.6307607799409425 -0.07955500473713073; -2.0821742300380492 -2.630760779940829 0.0 0.47849046096428083; 0.13528072525718926 0.07955500473701704 -0.47849046096393977 0.0] ≈ [0.0 -0.8498474532383115 2.185148123407751 0.013482122658601612; 0.8498474532383115 0.0 2.5263325341726737 -0.0888971063664881; -2.185148123407751 -2.5263325341726737 0.0 0.48688652099235136; -0.013482122658601612 0.0888971063664881 -0.48688652099235136 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_5_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1953
  Expression: ≈(p.optval, tr(C * A ^ t), atol = atol, rtol = rtol)
   Evaluated: -247.44093908318436 ≈ 21.580919775263297 + 0.0im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_5_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1954
  Expression: ≈(p.optval, trace_mpower(A, t, C), atol = atol, rtol = rtol)
   Evaluated: -247.44093908318436 ≈ 21.580919775263297 + 0.0im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_5_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1955
  Expression: ≈(p.optval, evaluate(trace_mpower(B, t, C)), atol = atol, rtol = rtol)
   Evaluated: -247.44093908318436 ≈ 21.58091962405303 + 3.6848919471310637e-9im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_cplx:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2100
  Expression: ≈(real.(X.value), real.(eye(n)), atol = atol, rtol = rtol)
   Evaluated: [0.7279239070695098 -0.0004320688996131139 0.0010833007483483925; -0.0004320688996131139 0.728963745299211 -0.00014291940613020415; 0.0010833007479504886 -0.00014291940613020415 0.727867466702719] ≈ [1.0 0.0 0.0; 0.0 1.0 0.0; 0.0 0.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_cplx:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2101
  Expression: ≈(imag.(X.value), imag.(eye(n)), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.0013401877947671892 0.00010318065619685513; -0.0013401877946535024 0.0 -0.0008707982375995016; -0.00010318065619685513 0.0008707982379974055 0.0] ≈ [0.0 0.0 0.0; 0.0 0.0 0.0; 0.0 0.0 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_cplx:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2102
  Expression: ≈(p.optval, tr(C * log(evaluate(X))), atol = atol, rtol = rtol)
   Evaluated: 3098.2422541472724 ≈ -2.57894673803139 - 3.0518029535146133e-13im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_cplx:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2103
  Expression: ≈(p.optval, trace_logm(evaluate(X), C), atol = atol, rtol = rtol)
   Evaluated: 3098.2422541472724 ≈ -2.578946738031391 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_cplx:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2104
  Expression: ≈(p.optval, evaluate(trace_logm(X, C)), atol = atol, rtol = rtol)
   Evaluated: 3098.2422541472724 ≈ -2.578946738031391 (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_real_0:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1030
  Expression: ≈(A.value, eye(n), atol = atol, rtol = rtol)
   Evaluated: [1.003444219967605 0.0 0.0 0.0; 0.0 1.0034442266369297 0.0 0.0; 0.0 0.0 1.0034442235037204 0.0; 0.0 0.0 0.0 1.0034442063770257] ≈ [1.0 0.0 0.0 0.0; 0.0 1.0 0.0 0.0; 0.0 0.0 1.0 0.0; 0.0 0.0 0.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_epicone_real_neg1_optB:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1291
  Expression: ≈(B.value, A ^ 2, atol = atol, rtol = rtol)
   Evaluated: [0.2474891080037196 -0.045020652663879446 -0.04829564334067982; -0.04502065189217319 0.10328199077412137 0.09098581741318412; -0.0482956433088475 0.09098581686930629 0.16614307018380714] ≈ [0.23026532123502869 -0.04390787742767548 -0.045341182899617395; -0.04390787742767548 0.07504533193846732 0.0990086475396798; -0.045341182899617395 0.0990086475396798 0.144320523852154] (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:285
  Expression: ≈(p.optval, 7, atol = atol, rtol = rtol)
   Evaluated: 6.946962033055116 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_matrix_frac_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:286
  Expression: ≈((evaluate(matrixfrac(x, P)))[1], 7, atol = atol, rtol = rtol)
   Evaluated: 7.027685793992177 ≈ 7 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.3332352304859114 0.0003227441026183442 0.0010086663287438569; 0.0003227439589181813 0.3332067139170931 -0.0006140007051271823; 0.001008666290772453 -0.0006140007569683803 0.3335469540336362] ≈ [0.36978567242074806 -0.03588755677601767 0.31772907409031115; -0.03588755677601767 0.215395393447707 -0.1466079961392317; 0.31772907409031115 -0.1466079961392317 0.41481893413154497] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.0008492453561075308 0.00014324744586247107; -0.000849245352469552 -2.2737367544323206e-13 0.00031293342794924683; -0.00014324742289772985 -0.00031293346751226636 7.958078640513122e-13] ≈ [0.0 0.18999724164426005 -0.04588632161402458; -0.18999724164426005 0.0 -0.07478694179387721; 0.04588632161402458 0.07478694179387721 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -496.88392979542124 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1509
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(B, A)), atol = atol, rtol = rtol)
   Evaluated: -496.88392979542124 ≈ 4.066603689818533 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.33324371254661855 -5.650867137774185e-5 0.00018197330314251303; -5.6508681495870405e-5 0.33344247408240335 -1.935836507982458e-6; 0.00018197335077729804 -1.935836507982458e-6 0.33331352385687296] ≈ [0.2711254983422405 -0.08115418667033518 0.20988357591128406; -0.08115418667033518 0.461823617408757 -0.02577661836708371; 0.20988357591128406 -0.02577661836708371 0.26705088424900264] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.00016342687149517587 1.252889762781706e-5; -0.00016342687445103365 0.0 -4.7406956582563e-5; -1.2528896945696033e-5 4.74069574920577e-5 0.0] ≈ [0.0 0.25088157716289344 0.01947438845457262; -0.25088157716289344 0.0 -0.15899119231204217; -0.01947438845457262 0.15899119231204217 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -1360.0660177346713 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy3_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1509
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(B, A)), atol = atol, rtol = rtol)
   Evaluated: -1360.0660177346713 ≈ 0.6541945771070112 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1847
  Expression: ≈(real.(B.value), real.(A), atol = atol, rtol = rtol)
   Evaluated: [4.093636634157974 -0.4840654258414361 -0.3867460410383501; -0.4840654262306998 1.7296366926989322 1.849564937179366; -0.38674604089874265 1.8495649372416665 3.002205205059454] ≈ [4.7552031540882505 -0.5567713322321636 -0.4609346552954; -0.5567713322321636 1.8430317683614281 1.9205881999357683; -0.4609346552954 1.9205881999357683 3.237406179379494] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1849
  Expression: ≈(p.optval, tr(C * A ^ t), atol = atol, rtol = rtol)
   Evaluated: 98.92706672935671 ≈ 14.336113345423662 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1850
  Expression: ≈(p.optval, trace_mpower(A, t, C), atol = atol, rtol = rtol)
   Evaluated: 98.92706672935671 ≈ 14.336113345423662 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1851
  Expression: ≈(p.optval, evaluate(trace_mpower(B, t, C)), atol = atol, rtol = rtol)
   Evaluated: 98.92706672935671 ≈ 13.620744904715668 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_real:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2072
  Expression: ≈(real.(X.value), real.(eye(n)), atol = atol, rtol = rtol)
   Evaluated: [0.7955744080793465 -0.0070851250354735384 -0.005307745679829168; -0.007085125035246165 0.7539187571392176 0.027686028073844682; -0.005307745679601794 0.027686028072366753 0.7741762300414621] ≈ [1.0 0.0 0.0; 0.0 1.0 0.0; 0.0 0.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_real:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2074
  Expression: ≈(p.optval, tr(C * log(evaluate(X))), atol = atol, rtol = rtol)
   Evaluated: 67.65842543616857 ≈ -2.2851949372979234 + 0.0im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_real:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2075
  Expression: ≈(p.optval, trace_logm(evaluate(X), C), atol = atol, rtol = rtol)
   Evaluated: 67.65842543616857 ≈ -2.2851949372979234 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_logm_real:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2076
  Expression: ≈(p.optval, evaluate(trace_logm(X, C)), atol = atol, rtol = rtol)
   Evaluated: 67.65842543616857 ≈ -2.2851949372979234 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:324
  Expression: ≈(p.optval, 3, atol = atol, rtol = rtol)
   Evaluated: 2.9637270299685903 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:325
  Expression: ≈(evaluate(x), ones(3, 3), atol = atol, rtol = rtol)
   Evaluated: [1.0279589298770588 1.019568597610487 1.019568597128; 1.0195685972189494 1.027958929624674 1.019568598565911; 1.0195685982503164 1.019568598447222 1.0279589296992526] ≈ [1.0 1.0 1.0; 1.0 1.0 1.0; 1.0 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:338
  Expression: ≈(p.optval, 8.4853, atol = atol, rtol = rtol)
   Evaluated: 8.451250986615126 ≈ 8.4853 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:354
  Expression: ≈(p.optval, sum((eigvals(A))[2:end]), atol = atol, rtol = rtol)
   Evaluated: 13.789384831146663 ≈ 21.381108915609733 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:368
  Expression: ≈(p1.optval, p2.optval, atol = atol, rtol = rtol)
   Evaluated: 3.9696196045843286 ≈ 3.9979070973432926 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:386
  Expression: ≈(p1.optval, p2.optval, atol = atol, rtol = rtol)
   Evaluated: 8.436082947950382 ≈ 8.43187886045022 (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_cplx_3_5:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1204
  Expression: ≈(real.(B.value), real.(A ^ (-2 // 3)), atol = atol, rtol = rtol)
   Evaluated: [372.0466206877336 -6.514163410183755 -1.6559028091351138 -1.2222745138933533; -6.514163410183755 382.49071459940114 10.364773011100624 6.623479371672147; -1.6559028091351138 10.364773011100624 360.77034328736545 -0.3438275530406827; -1.2222745138942628 6.623479371672147 -0.3438275530406827 387.5834248050828] ≈ [0.8461014871001193 0.2696807457004615 0.06556260296066188 -0.008368323349824607; 0.2696807457004615 0.7545816760100486 -0.45585802559958655 -0.14281969293652216; 0.06556260296066188 -0.45585802559958655 1.6478895345066764 0.047394048492253656; -0.008368323349824607 -0.14281969293652216 0.047394048492253656 0.3783613955594149] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_cplx_3_5:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1205
  Expression: ≈(imag.(B.value), imag.(A ^ (-2 // 3)), atol = atol, rtol = rtol)
   Evaluated: [0.0 3.7935913791438907 -6.609362591924764 3.4105989994268384; -3.793591379143436 0.0 -13.369667447128904 -0.1709154588788806; 6.609362591925674 13.369667447128904 0.0 -1.3012207106062306; -3.4105989994263837 0.1709154588788806 1.3012207106066853 0.0] ≈ [0.0 -0.1888363296463946 0.4495354855132745 -0.06357644490785266; 0.1888363296463946 0.0 0.6201916009492621 -0.016001881015441144; -0.4495354855132745 -0.6201916009492621 0.0 0.10663061062195232; 0.06357644490785266 0.016001881015441144 -0.10663061062195232 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_real_1_2:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1078
  Expression: ≈(B.value, A ^ -1, atol = atol, rtol = rtol)
   Evaluated: [1.4475698576156901 -1.5552864870896883 0.017480476564287528 -0.5089027003550655; -1.5552864870896883 3.380300377641106 -0.26577725642255245 1.4449411735472495; 0.017480476564287528 -0.2657772564230072 0.16974371462310955 -0.05284569448440379; -0.5089027003550655 1.4449411735472495 -0.05284569448440379 0.9910204721495575] ≈ [1.4410909121334567 -1.5552311723017145 0.017583008281393156 -0.5089664451027598; -1.555231172301714 3.3738612715196328 -0.26563775782764115 1.444848318292351; 0.017583008281393114 -0.2656377578276411 0.1636398806965174 -0.052979794255076526; -0.5089664451027595 1.4448483182923504 -0.052979794255076526 0.984617149099868] (atol=0.001, rtol=0.0)

Error in testset sdp_nuclear_norm_atom_complex:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:132
  Expression: ≈(p.optval, sum(svdvals(A)), atol = atol, rtol = rtol)
   Evaluated: 6.236037936235191 ≈ 19.274984576275095 (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_epicone_real_8_5_optA:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1368
  Expression: ≈(B, A.value ^ (3 // 8), atol = atol, rtol = rtol)
   Evaluated: [0.4748345698875842 -0.05335286321168826 -0.04416927056015819; -0.05335286321168826 0.19577443766280186 0.1840412276730296; -0.04416927056015819 0.1840412276730296 0.32939099244961395] ≈ [3.8537145922596334 -0.0015527153213114042 -0.002396957260797472; -0.0015527153213021894 3.8577543806333425 -0.0020170501594209966; -0.0023969572607791256 -0.002017050159412115 3.8542496087478306] (atol=0.001, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 1.1953858678052374 ≈ 0.5470694479762079 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.5782026573724488 ≈ 0.5470694479762079 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.559321305527422 ≈ 0.5470694479762079 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 18.101878637662146 ≈ 0.9132464462858453 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 2.143986018577612 ≈ 0.9132464462858453 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 27.269347671287697 ≈ 0.9132464462858453 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 1.964814618192629 ≈ 0.8694593557985324 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 2.9473183078822442 ≈ 0.8694593557985324 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 153.249518998503 ≈ 0.8694593557985324 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 45.45663406104103 ≈ 0.9186946706219417 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 189.8145153247934 ≈ 0.9186946706219417 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 81.00421138493232 ≈ 0.9186946706219417 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.7622676685902079 ≈ 0.5217563621969785 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 3.0407128528822556 ≈ 0.5217563621969785 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 44.88052597674824 ≈ 0.5217563621969785 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 64.97905588942398 ≈ 0.45713022485357946 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 180.06054691743643 ≈ 0.45713022485357946 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 122.34084068252608 ≈ 0.45713022485357946 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 4.090404286322804 ≈ 0.9422458263546698 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 38.68833155044666 ≈ 0.9422458263546698 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 48.90331425740054 ≈ 0.9422458263546698 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 300.5215084185577 ≈ 0.9176087100278648 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 134.77185408795876 ≈ 0.9176087100278648 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 239.10255088347742 ≈ 0.9176087100278648 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.8884009268911364 ≈ 1.0053124915954001 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.9752173031987245 ≈ 1.0053124915954001 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -32.80921818722991 ≈ 1.0053124915954001 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -38.13874045936173 ≈ 1.76937190924586 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -56.63878909460694 ≈ 1.76937190924586 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -68.85389653921175 ≈ 1.76937190924586 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.7878944337132997 ≈ 1.0028180382306984 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.961930247833449 ≈ 1.0028180382306984 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -57.83981161509261 ≈ 1.0028180382306984 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -65.84754848944893 ≈ 1.0939861015544436 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -84.32759415934824 ≈ 1.0939861015544436 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -122.93888497184503 ≈ 1.0939861015544436 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.6906504449344375 ≈ 0.6620900398424552 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 1.6071808859063852 ≈ 0.6620900398424552 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 31.808344311842557 ≈ 0.6620900398424552 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 22.76398555825598 ≈ 0.7671870085583241 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 21.161433628114107 ≈ 0.7671870085583241 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 56.867906733698206 ≈ 0.7671870085583241 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 3.5046889448247387 ≈ 0.7945874875606724 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 1.0369065627692347 ≈ 0.7945874875606724 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 94.90695579704658 ≈ 0.7945874875606724 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 92.54163035957166 ≈ 0.7540322167910498 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 52.37572494526565 ≈ 0.7540322167910498 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 254.84519153175177 ≈ 0.7540322167910498 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 4.631703950652811 ≈ 0.9357996610463297 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 1.1463707111943136 ≈ 0.9357996610463297 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 79.7649500898741 ≈ 0.9357996610463297 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 58.563571898523335 ≈ 0.8889257127695427 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 55.56858330154255 ≈ 0.8889257127695427 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 139.40551514538396 ≈ 0.8889257127695427 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 39.06991178456519 ≈ 0.9627180527189039 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 45.56531526485442 ≈ 0.9627180527189039 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 113.5744593490862 ≈ 0.9627180527189039 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 120.32123417277369 ≈ 0.8492705460515002 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 479.89510400507953 ≈ 0.8492705460515002 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 302.41529121985855 ≈ 0.8492705460515002 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 3.7781736709600464 ≈ 3.8092659935092614 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 3.632454630716797 ≈ 3.8092659935092614 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -25.109045658622975 ≈ 3.8092659935092614 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -49.688137887857906 ≈ 5.149659210682255 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -64.30539264223806 ≈ 5.149659210682255 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -174.2007518774913 ≈ 5.149659210682255 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -21.317362014239805 ≈ 1.837895297363038 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -31.465765535547067 ≈ 1.837895297363038 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -72.37121839662073 ≈ 1.837895297363038 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2197
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -142.37735322168493 ≈ 2.6712832695878577 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2208
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -252.06754729073944 ≈ 2.6712832695878577 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -431.1987591940788 ≈ 2.6712832695878577 (atol=0.005, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.3333944820694228 -6.626365882311802e-5 0.0004554109942773721; -6.626365882311802e-5 0.3331376443988461 -0.00019077565713132572; 0.0004554109942773721 -0.00019077565713132572 0.3334677803156296] ≈ [0.36978567242074806 -0.03588755677601767 0.31772907409031115; -0.03588755677601767 0.215395393447707 -0.1466079961392317; 0.31772907409031115 -0.1466079961392317 0.41481893413154497] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.0002475034861504355 -7.363178781361057e-5; -0.00024750348632096575 0.0 -0.00012316837410253356; 7.363178787045399e-5 0.00012316837398884672 0.0] ≈ [0.0 0.18999724164426005 -0.04588632161402458; -0.18999724164426005 0.0 -0.07478694179387721; 0.04588632161402458 0.07478694179387721 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -1954.7815549946883 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1506
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(X, B)), atol = atol, rtol = rtol)
   Evaluated: -1954.7815549946883 ≈ 0.6086240905985691 (atol=0.001, rtol=0.0)

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:573
  Expression: p.status == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sdp_Issue_198:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:575
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -70.01409407102767 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_channel_capacity:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1772
  Expression: ≈(p.optval, v, atol = atol, rtol = rtol)
   Evaluated: 31.380620290542105 ≈ 0.9735706760772929 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_channel_capacity:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1772
  Expression: ≈(p.optval, v, atol = atol, rtol = rtol)
   Evaluated: 4110.280413184583 ≈ 0.7560144722208858 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1987
  Expression: ≈(real.(B.value), real.(A), atol = atol, rtol = rtol)
   Evaluated: [3.7988555569049822 -0.4219389876691366 -0.34406176307857095; -0.42193898748564607 1.6126806522690913 1.4989012857126909; -0.3440617630722045 1.498901286427099 2.667048353195014] ≈ [4.955203154088251 -0.5567713322321636 -0.4609346552954; -0.5567713322321636 2.0430317683614283 1.9205881999357683; -0.4609346552954 1.9205881999357683 3.437406179379494] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1989
  Expression: ≈(p.optval, tr(C * A ^ t), atol = atol, rtol = rtol)
   Evaluated: -22.210931607512183 ≈ 5.142207125143154 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1990
  Expression: ≈(p.optval, trace_mpower(A, t, C), atol = atol, rtol = rtol)
   Evaluated: -22.210931607512183 ≈ 5.142207125143154 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1991
  Expression: ≈(p.optval, evaluate(trace_mpower(B, t, C)), atol = atol, rtol = rtol)
   Evaluated: -22.210931607512183 ≈ 5.459536197118434 (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_epicone_real_neg3_5_optB:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1342
  Expression: ≈(B.value, A ^ (8 // 3), atol = atol, rtol = rtol)
   Evaluated: [36.504465172441996 -0.03922956726250959 -0.06053722392698546; -0.03922956726228222 36.60659054979533 -0.05098092800812992; -0.060537223926530714 -0.05098092800790255 36.51799035146496] ≈ [0.1435730604377619 -0.03388859558710332 -0.037556021533105485; -0.03388859558710332 0.04497681287895787 0.06147469538829427; -0.037556021533105485 0.06147469538829427 0.08685411596783318] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_epicone_real_neg3_5_optA:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1316
  Expression: ≈(B, A.value ^ (8 // 3), atol = atol, rtol = rtol)
   Evaluated: [4.955203154088251 -0.5567713322321636 -0.4609346552954; -0.5567713322321636 2.0430317683614283 1.9205881999357683; -0.4609346552954 1.9205881999357683 3.437406179379494] ≈ [2.037839003152568 -0.23204830707861054 -0.19519526185996947; -0.2320483064627185 0.8497638364746104 0.7824720555223752; -0.19519526161930076 0.7824720555448462 1.4169378128466763] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_real_3_5:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1128
  Expression: ≈(B.value, A ^ (-2 // 3), atol = atol, rtol = rtol)
   Evaluated: [26.891346389389582 0.19467584972289842 -0.009196371557663952 0.08866861314390917; 0.19467584972358054 26.61510041251472 0.028381564984783836 -0.16382335156640693; -0.009196371557663952 0.028381564984556462 26.986644534592415 0.0038775289842760685; 0.08866861314345442 -0.16382335156686167 0.003877528984503442 26.913473040951203] ≈ [1.141167925106056 -0.8150484252029027 -0.032033036037636756 -0.19962056888791846; -0.8150484252029027 2.0698167827627474 -0.18345924649712483 0.8010828297306194; -0.032033036037636756 -0.18345924649712483 0.2765921861394946 0.004156597855480414; -0.19962056888791846 0.8010828297306194 0.004156597855480414 0.8248539246766685] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.33339244141041036 -8.073214257819927e-5 0.0005293026755452956; -8.073214257819927e-5 0.3331131007763588 -0.00023710585776370863; 0.0005293026752042351 -0.00023710585730896128 0.3334593696425827] ≈ [0.36978567242074806 -0.03588755677601767 0.31772907409031115; -0.03588755677601767 0.215395393447707 -0.1466079961392317; 0.31772907409031115 -0.1466079961392317 0.41481893413154497] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.0003047106281428569 -9.03010534329951e-5; -0.0003047106282565437 0.0 -0.0001509875544343231; 9.03010534329951e-5 0.0001509875544343231 0.0] ≈ [0.0 0.18999724164426005 -0.04588632161402458; -0.18999724164426005 0.0 -0.07478694179387721; 0.04588632161402458 0.07478694179387721 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -1123.484932350581 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1503
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(A, B)), atol = atol, rtol = rtol)
   Evaluated: -1123.484932350581 ≈ 0.6083082519886857 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:225
  Expression: ≈(p.optval, 4, atol = atol, rtol = rtol)
   Evaluated: 3.9696196045843286 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:226
  Expression: ≈(evaluate(eigmax(y)), 4, atol = atol, rtol = rtol)
   Evaluated: 4.003107994205038 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:238
  Expression: ≈(p.optval, 1.5, atol = atol, rtol = rtol)
   Evaluated: 1.4935498207513207 ≈ 1.5 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:239
  Expression: ≈((p.constraints[1]).dual, im, atol = atol, rtol = rtol)
   Evaluated: 0.0 + 1.003173655436896im ≈ im (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:240
  Expression: ≈((p.constraints[2]).dual, 0.75, atol = atol, rtol = rtol)
   Evaluated: 0.7451880822501423 + 0.0im ≈ 0.75 (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_epicone_real_8_5_optB:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1393
  Expression: ≈(B.value, A ^ (3 // 8), atol = atol, rtol = rtol)
   Evaluated: [1.302217270127585 -0.06581276431450078 -0.0412176769883672; -0.06581276412146053 0.8481671857994115 0.30442707643499034; -0.04121767695937706 0.30442707643828726 1.0730250089001174] ≈ [1.8173320533682031 -0.09121124621662058 -0.055261324994749894; -0.09121124621662058 1.1726051248311842 0.4327661980826218; -0.055261324994749894 0.4327661980826218 1.4926698921645578] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.3332309772309827 -0.00011251651568500165 0.00028550864288945377; -0.00011251651568500165 0.3335487731607145 -4.074694732025819e-5; 0.00028550864288945377 -4.074694732025819e-5 0.33322015902547264] ≈ [0.2711254983422405 -0.08115418667033518 0.20988357591128406; -0.08115418667033518 0.461823617408757 -0.02577661836708371; 0.20988357591128406 -0.02577661836708371 0.26705088424900264] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.0003649549250326345 2.616617877038152e-5; -0.0003649549250894779 0.0 -0.0002422861782633845; -2.616617877038152e-5 0.0002422861782633845 0.0] ≈ [0.0 0.25088157716289344 0.01947438845457262; -0.25088157716289344 0.0 -0.15899119231204217; -0.01947438845457262 0.15899119231204217 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -1866.3734282080472 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1506
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(X, B)), atol = atol, rtol = rtol)
   Evaluated: -1866.3734282080472 ≈ 0.4664074111163067 (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_cplx_1_2:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1152
  Expression: ≈(real.(B.value), real.(A ^ -1), atol = atol, rtol = rtol)
   Evaluated: [10.569801253390551 0.45093496936851807 0.1088899323771102 -0.019169034234892024; 0.4509349693682907 10.449269095683462 -0.7640922469608995 -0.22918175023676213; 0.10888993237722389 -0.7640922469606721 11.942067942567746 0.08048678822569855; -0.019169034235119398 -0.2291817502369895 0.08048678822569855 9.807815511410809] ≈ [0.890133446918722 0.44005827360720823 0.10150694973073766 -0.04316059284615992; 0.4400582736072084 0.9282832229968533 -0.7513742073400999 -0.18307765066184234; 0.10150694973073751 -0.7513742073400999 2.3770118897482653 0.08015739119719445; -0.04316059284616014 -0.18307765066184228 0.08015739119719481 0.2509225098422484] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_cplx_1_2:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1153
  Expression: ≈(imag.(B.value), imag.(A ^ -1), atol = atol, rtol = rtol)
   Evaluated: [0.0 -0.3193900163601029 0.7675469763132696 -0.09803813892733615; 0.31939001635976183 0.0 1.042515831756873 -0.02821968704347455; -0.767546976313497 -1.042515831756873 0.0 0.1818818502903241; 0.09803813892767721 0.028219687043360864 -0.1818818502903241 0.0] ≈ [1.3877787807814457e-17 -0.33091775899700504 0.8247761690263712 -0.05301650724275819; 0.33091775899700493 -1.68881901742339e-16 1.0395957371903513 -0.032898233483408645; -0.8247761690263713 -1.0395957371903508 -2.9660473289615053e-16 0.19155655222648127; 0.05301650724275814 0.032898233483408826 -0.19155655222648166 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_5_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1917
  Expression: ≈(p.optval, tr(C * A ^ t), atol = atol, rtol = rtol)
   Evaluated: 7.7385063323542616 ≈ 32.833690484902405 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_5_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1918
  Expression: ≈(p.optval, trace_mpower(A, t, C), atol = atol, rtol = rtol)
   Evaluated: 7.7385063323542616 ≈ 32.833690484902405 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_real_5_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1919
  Expression: ≈(p.optval, evaluate(trace_mpower(B, t, C)), atol = atol, rtol = rtol)
   Evaluated: 7.7385063323542616 ≈ 32.83369046030417 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.3332202263597992 -0.00016164588089395693 0.0004096519958238787; -0.0001616458807802701 0.3335845954505885 -5.50975597661818e-5; 0.0004096519958238787 -5.50975597661818e-5 0.33319507643125235] ≈ [0.2711254983422405 -0.08115418667033518 0.20988357591128406; -0.08115418667033518 0.461823617408757 -0.02577661836708371; 0.20988357591128406 -0.02577661836708371 0.26705088424900264] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 0.0005023566849331473 3.903162746610178e-5; -0.0005023566848194605 0.0 -0.0003315275437216769; -3.903162746610178e-5 0.0003315275437216769 0.0] ≈ [0.0 0.25088157716289344 0.01947438845457262; -0.25088157716289344 0.0 -0.15899119231204217; -0.01947438845457262 0.15899119231204217 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -1271.9486538859 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy1_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1503
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(A, B)), atol = atol, rtol = rtol)
   Evaluated: -1271.9486538859 ≈ 0.4659127388140923 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.3333993549253478 5.267185474622238e-5 -0.00017594823225408618; 5.267185429147503e-5 0.3332571615649158 -1.01644252481492e-6; -0.0001759482305487836 -1.0164426385017578e-6 0.3333435013314556] ≈ [0.2711254983422405 -0.08115418667033518 0.20988357591128406; -0.08115418667033518 0.461823617408757 -0.02577661836708371; 0.20988357591128406 -0.02577661836708371 0.26705088424900264] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [0.0 -0.00015034538898817118 -1.1498002777443617e-5; 0.00015034538864711067 0.0 3.303410613852975e-5; 1.1498002777443617e-5 -3.303410613852975e-5 0.0] ≈ [0.0 0.25088157716289344 0.01947438845457262; -0.25088157716289344 0.0 -0.15899119231204217; -0.01947438845457262 0.15899119231204217 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -5135.291212563261 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy4_fullrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1512
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(B, X)), atol = atol, rtol = rtol)
   Evaluated: -5135.291212563261 ≈ 0.6558097474397712 (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2023
  Expression: ≈(real.(B.value), real.(A), atol = atol, rtol = rtol)
   Evaluated: [1.833240624045061 -0.4991246979367361 1.2912937900650832; -0.4991246977282344 3.002960916988968 -0.15813305597635008; 1.2912937900817951 -0.15813305595509064 1.8092558273640407] ≈ [2.4205563924615694 -0.6646643310484845 1.7189763375711407; -0.6646643310484845 3.9824011098072774 -0.21111417052636713; 1.7189763375711407 -0.21111417052636713 2.387184723522737] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2024
  Expression: ≈(imag.(B.value), imag.(A), atol = atol, rtol = rtol)
   Evaluated: [0.0 1.5417707654679589 0.120188051059813; -1.5417707657796882 0.0 -0.977259443488947; -0.12018805109812547 0.9772594434703024 0.0] ≈ [0.0 2.0547557987950027 0.1594980112032633; -2.0547557987950027 0.0 -1.3021604776838065; -0.1594980112032633 1.3021604776838065 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2025
  Expression: ≈(p.optval, tr(C * A ^ t), atol = atol, rtol = rtol)
   Evaluated: -294.6251321113368 ≈ 5.450375203095211 + 1.3877787807814457e-17im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2026
  Expression: ≈(p.optval, trace_mpower(A, t, C), atol = atol, rtol = rtol)
   Evaluated: -294.6251321113368 ≈ 5.450375203095211 + 1.3877787807814457e-17im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_neg1_4:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2027
  Expression: ≈(p.optval, evaluate(trace_mpower(B, t, C)), atol = atol, rtol = rtol)
   Evaluated: -294.6251321113368 ≈ 5.817772123566532 + 9.068013007151876e-11im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1879
  Expression: ≈(real.(B.value), real.(A), atol = atol, rtol = rtol)
   Evaluated: [2.1355268491606694 -0.6420830098059014 1.7095047521079323; -0.6420830117476726 3.4781148854253843 -0.20830159078923316; 1.7095048246346778 -0.20830159275283222 2.110477117543269] ≈ [2.220556392461569 -0.6646643310484845 1.7189763375711407; -0.6646643310484845 3.782401109807277 -0.21111417052636713; 1.7189763375711407 -0.21111417052636713 2.1871847235227366] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1880
  Expression: ≈(imag.(B.value), imag.(A), atol = atol, rtol = rtol)
   Evaluated: [0.0 1.979931777247657 0.16894595342455432; -1.979931788423528 0.0 -1.3150371406163686; -0.16894595033500082 1.3150371351657668 0.0] ≈ [0.0 2.0547557987950027 0.1594980112032633; -2.0547557987950027 0.0 -1.3021604776838065; -0.1594980112032633 1.3021604776838065 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1881
  Expression: ≈(p.optval, tr(C * A ^ t), atol = atol, rtol = rtol)
   Evaluated: 142.55990762443997 ≈ 9.523168722966851 - 5.551115123125783e-17im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1882
  Expression: ≈(p.optval, trace_mpower(A, t, C), atol = atol, rtol = rtol)
   Evaluated: 142.55990762443997 ≈ 9.523168722966851 - 5.551115123125783e-17im (atol=0.001, rtol=0.0)

Error in testset sdp_trace_mpower_cplx_2_3:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1883
  Expression: ≈(p.optval, evaluate(trace_mpower(B, t, C)), atol = atol, rtol = rtol)
   Evaluated: 142.55990762443997 ≈ 9.19721682829482 + 1.1002586342012677e-8im (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_hypocone_real_3_8:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1103
  Expression: ≈(B.value, A ^ (-5 // 3), atol = atol, rtol = rtol)
   Evaluated: [11.530351516861629 -3.2391966858992873 0.15586335156535824 -1.3025095177024468; -3.2391966858992873 15.856378409316903 -0.4363137323525734 2.8439975535222857; 0.15586335156513087 -0.43631373235234605 9.521113131042512 -0.17098731360920283; -1.3025095177026742 2.843997553521831 -0.17098731360897546 10.87731085492237] ≈ [3.01315237807785 -4.804552505545763 0.24190677574266412 -1.9532902603692408; -4.804552505545763 9.457040282556978 -0.6366149452070583 4.203883122445992; 0.24190677574266412 -0.6366149452070583 0.093211762396588 -0.25932818288244264; -1.9532902603692408 4.203883122445992 -0.25932818288244264 2.0709884547052324] (atol=0.001, rtol=0.0)

Error in testset sdp_geom_mean_epicone_real_neg1_optA:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1265
  Expression: ≈(B, A.value ^ 2, atol = atol, rtol = rtol)
   Evaluated: [4.955203154088251 -0.5567713322321636 -0.4609346552954; -0.5567713322321636 2.0430317683614283 1.9205881999357683; -0.4609346552954 1.9205881999357683 3.437406179379494] ≈ [4.234879549917751 -0.5146002564943312 -0.437770423335797; -0.5146027321489569 1.6405665709082315 1.7066089929403243; -0.43776981835146545 1.7065915509479002 2.8761646162100307] (atol=0.001, rtol=0.0)

Error in testset sdsos_concave_then_convex_cubic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:25
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sdsos_concave_then_convex_cubic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:27
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 10.657765466899995 ≈ 21.51 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 6.907830562483182 ≈ 17.17 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 3.157745378800956 ≈ 13.2 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -0.5922322786180636 ≈ 9.85 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -4.342176629632673 ≈ 7.3 (atol=0.1, rtol=0.0)

Error in testset dsos_univariate_sum:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:19
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset dsos_univariate_sum:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:21
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 11.512637023333276 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 7.794511250777582 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 4.067511145391021 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 0.34272152188535465 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -3.3470695027012236 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:38
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:39
  Expression: ≈(objective_value(model), 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:42
  Expression: ≈(value(α), 2.0, atol = atol, rtol = rtol)
   Evaluated: 1.9715671259909868 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:47
  Expression: ≈(getmat(p), ones(2, 2), atol = atol, rtol = rtol)
   Evaluated: [1.0001140186795965 0.9858184161130339; 0.9858184161130339 0.9999628964578733] ≈ [1.0 1.0; 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:56
  Expression: ≈(a[1] + a[3], 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:58
  Expression: dual_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_cheby_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:67
  Expression: ≈(getmat(ν), [a[1] a[2]; a[2] a[3]], atol = atol, rtol = rtol)
   Evaluated: [1.010798577234469 -1.0112399488453514; -1.0112399488453514 1.0116813204562338] ≈ [1.0107985668102621 -0.9999999998956702; -0.9999999998956702 1.011681310032027] (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:38
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:39
  Expression: ≈(objective_value(model), 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:42
  Expression: ≈(value(α), 2.0, atol = atol, rtol = rtol)
   Evaluated: 1.9715671259909868 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:47
  Expression: ≈(getmat(p), ones(2, 2), atol = atol, rtol = rtol)
   Evaluated: [1.0001140186795965 0.9858184161130339; 0.9858184161130339 0.9999628964578733] ≈ [1.0 1.0; 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:56
  Expression: ≈(a[1] + a[3], 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:58
  Expression: dual_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_cheby_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:67
  Expression: ≈(getmat(ν), [a[1] a[2]; a[2] a[3]], atol = atol, rtol = rtol)
   Evaluated: [1.010798577234469 -1.0112399488453514; -1.0112399488453514 1.0116813204562338] ≈ [1.0107985668102621 -0.9999999998956702; -0.9999999998956702 1.011681310032027] (atol=0.001, rtol=0.0)

Error in testset dsos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:35
  Expression: termination_status(model) == MOI.INFEASIBLE
   Evaluated: MathOptInterface.INFEASIBLE_OR_UNBOUNDED == MathOptInterface.INFEASIBLE

Error in testset dsos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:42
  Expression: termination_status(model) == MOI.INFEASIBLE
   Evaluated: MathOptInterface.INFEASIBLE_OR_UNBOUNDED == MathOptInterface.INFEASIBLE

Error in testset dsos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:60
  Expression: termination_status(model) == MOI.INFEASIBLE
   Evaluated: MathOptInterface.INFEASIBLE_OR_UNBOUNDED == MathOptInterface.INFEASIBLE

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:38
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:39
  Expression: ≈(objective_value(model), 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:42
  Expression: ≈(value(α), 2.0, atol = atol, rtol = rtol)
   Evaluated: 1.9715671259909868 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:47
  Expression: ≈(getmat(p), ones(2, 2), atol = atol, rtol = rtol)
   Evaluated: [1.0001140186795965 0.9858184161130339; 0.9858184161130339 0.9999628964578733] ≈ [1.0 1.0; 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:56
  Expression: ≈(a[1] + a[3], 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:58
  Expression: dual_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_scaled_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:67
  Expression: ≈(getmat(ν), [a[1] a[2]; a[2] a[3]], atol = atol, rtol = rtol)
   Evaluated: [1.010798577234469 -1.0112399488453514; -1.0112399488453514 1.0116813204562338] ≈ [1.0107985668102621 -0.9999999998956702; -0.9999999998956702 1.011681310032027] (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:38
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:39
  Expression: ≈(objective_value(model), 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:42
  Expression: ≈(value(α), 2.0, atol = atol, rtol = rtol)
   Evaluated: 1.9715671259909868 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:47
  Expression: ≈(getmat(p), ones(2, 2), atol = atol, rtol = rtol)
   Evaluated: [1.0001140186795965 0.9858184161130339; 0.9858184161130339 0.9999628964578733] ≈ [1.0 1.0; 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:56
  Expression: ≈(a[1] + a[3], 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:58
  Expression: dual_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_scaled_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:67
  Expression: ≈(getmat(ν), [a[1] a[2]; a[2] a[3]], atol = atol, rtol = rtol)
   Evaluated: [1.010798577234469 -1.0112399488453514; -1.0112399488453514 1.0116813204562338] ≈ [1.0107985668102621 -0.9999999998956702; -0.9999999998956702 1.011681310032027] (atol=0.001, rtol=0.0)

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:38
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:39
  Expression: ≈(objective_value(model), 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:42
  Expression: ≈(value(α), 2.0, atol = atol, rtol = rtol)
   Evaluated: 1.9715671259909868 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:47
  Expression: ≈(getmat(p), ones(2, 2), atol = atol, rtol = rtol)
   Evaluated: [1.0001140186795965 0.9858184161130339; 0.9858184161130339 0.9999628964578733] ≈ [1.0 1.0; 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:56
  Expression: ≈(a[1] + a[3], 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:58
  Expression: dual_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_bivariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:67
  Expression: ≈(getmat(ν), [a[1] a[2]; a[2] a[3]], atol = atol, rtol = rtol)
   Evaluated: [1.010798577234469 -1.0112399488453514; -1.0112399488453514 1.0116813204562338] ≈ [1.0107985668102621 -0.9999999998956702; -0.9999999998956702 1.011681310032027] (atol=0.001, rtol=0.0)

Error in testset dsos_concave_then_convex_cubic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:25
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset dsos_concave_then_convex_cubic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:27
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:38
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:39
  Expression: ≈(objective_value(model), 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:42
  Expression: ≈(value(α), 2.0, atol = atol, rtol = rtol)
   Evaluated: 1.9715671259909868 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:47
  Expression: ≈(getmat(p), ones(2, 2), atol = atol, rtol = rtol)
   Evaluated: [1.0001140186795965 0.9858184161130339; 0.9858184161130339 0.9999628964578733] ≈ [1.0 1.0; 1.0 1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:56
  Expression: ≈(a[1] + a[3], 2.0, atol = atol, rtol = rtol)
   Evaluated: 2.022479876842289 ≈ 2.0 (atol=0.001, rtol=0.0)

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:58
  Expression: dual_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_univariate_quadratic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quadratic.jl:67
  Expression: ≈(getmat(ν), [a[1] a[2]; a[2] a[3]], atol = atol, rtol = rtol)
   Evaluated: [1.010798577234469 -1.0112399488453514; -1.0112399488453514 1.0116813204562338] ≈ [1.0107985668102621 -0.9999999998956702; -0.9999999998956702 1.011681310032027] (atol=0.001, rtol=0.0)

Error in testset sos_concave_then_convex_cubic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:25
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ITERATION_LIMIT == MathOptInterface.OPTIMAL

Error in testset sos_concave_then_convex_cubic:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:27
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset with γ=3.9 it should be infeasible:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:37
  Expression: JuMP.dual_status(model) == MOI.INFEASIBILITY_CERTIFICATE
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.INFEASIBILITY_CERTIFICATE

Error in testset sos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:51
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset quartic_infeasible_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:66
  Expression: JuMP.termination_status(model) == MOI.INFEASIBLE
   Evaluated: MathOptInterface.INFEASIBLE_OR_UNBOUNDED == MathOptInterface.INFEASIBLE

Error in testset quartic_infeasible_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:67
  Expression: JuMP.dual_status(model) == MOI.INFEASIBILITY_CERTIFICATE
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.INFEASIBILITY_CERTIFICATE

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 10.657525574279285 ≈ 21.51 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 6.9075334949151825 ≈ 17.17 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 3.15754538377981 ≈ 13.2 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -0.5924368611065812 ≈ 9.85 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -4.342414855469504 ≈ 7.3 (atol=0.1, rtol=0.0)

Error in testset quartic_infeasible_scaled_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:66
  Expression: JuMP.termination_status(model) == MOI.INFEASIBLE
   Evaluated: MathOptInterface.INFEASIBLE_OR_UNBOUNDED == MathOptInterface.INFEASIBLE

Error in testset quartic_infeasible_scaled_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:67
  Expression: JuMP.dual_status(model) == MOI.INFEASIBILITY_CERTIFICATE
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.INFEASIBILITY_CERTIFICATE

```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             351s /  99.8%           33.9GiB /  99.8%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1     190s   54.3%    190s   16.6GiB   48.9%  16.6GiB
   sdp                      1    79.4s   22.7%   79.4s   6.76GiB   20.0%  6.76GiB
     quartic_ideal_rem      1    5.78s    1.6%   5.78s    545MiB    1.6%   545MiB
     sosdemo5_infea...      1    5.36s    1.5%   5.36s    439MiB    1.3%   439MiB
     rearrangement          1    5.28s    1.5%   5.28s    421MiB    1.2%   421MiB
     sos_concave_th...      1    3.79s    1.1%   3.79s    408MiB    1.2%   408MiB
     sos_horn               1    3.72s    1.1%   3.72s    275MiB    0.8%   275MiB
     simple_matrix          1    3.51s    1.0%   3.51s    366MiB    1.1%   366MiB
     quartic_ideal_4        1    3.22s    0.9%   3.22s    264MiB    0.8%   264MiB
     quartic_ideal          1    3.22s    0.9%   3.22s    207MiB    0.6%   207MiB
     sos_scaled_biv...      1    3.14s    0.9%   3.14s    214MiB    0.6%   214MiB
     chebyshev              1    3.10s    0.9%   3.10s    252MiB    0.7%   252MiB
     sos_term               1    3.00s    0.9%   3.00s    187MiB    0.5%   187MiB
     sos_term_fixed         1    3.00s    0.9%   3.00s    201MiB    0.6%   201MiB
     sos_cheby_univ...      1    2.76s    0.8%   2.76s    188MiB    0.5%   188MiB
     maxcut                 1    2.44s    0.7%   2.44s    152MiB    0.4%   152MiB
     quartic_feasib...      1    2.35s    0.7%   2.35s    116MiB    0.3%   116MiB
     BPT12e399_rem          1    2.32s    0.7%   2.32s   78.6MiB    0.2%  78.6MiB
     quartic_ideal_...      1    2.30s    0.7%   2.30s    161MiB    0.5%   161MiB
     sos_quartic_co...      1    2.24s    0.6%   2.24s    159MiB    0.5%   159MiB
     sos_options_pr...      1    2.23s    0.6%   2.23s    185MiB    0.5%   185MiB
     sosdemo5_feasible      1    1.69s    0.5%   1.69s   27.3MiB    0.1%  27.3MiB
     sosdemo10              1    1.47s    0.4%   1.47s    180MiB    0.5%   180MiB
     sos_univariate...      1    1.31s    0.4%   1.31s    101MiB    0.3%   101MiB
     sosdemo9               1    651ms    0.2%   651ms   49.7MiB    0.1%  49.7MiB
     quadratic_feas...      1    610ms    0.2%   610ms   50.0MiB    0.1%  50.0MiB
     quadratic_infe...      1    533ms    0.2%   533ms   40.7MiB    0.1%  40.7MiB
     sos_univariate...      1    512ms    0.1%   512ms   27.4MiB    0.1%  27.4MiB
     choi                   1    449ms    0.1%   449ms   63.6MiB    0.2%  63.6MiB
     BPT12e399_maxd...      1    300ms    0.1%   300ms   8.71MiB    0.0%  8.71MiB
     sos_quartic_co...      1    127ms    0.0%   127ms   21.0MiB    0.1%  21.0MiB
     motzkin                1   82.9ms    0.0%  82.9ms   4.14MiB    0.0%  4.14MiB
     quartic_infeas...      1   39.8ms    0.0%  39.8ms   1.80MiB    0.0%  1.80MiB
     sos_bivariate_...      1   34.0ms    0.0%  34.0ms    335KiB    0.0%   335KiB
     quartic_infeas...      1   20.8ms    0.0%  20.8ms   1.02MiB    0.0%  1.02MiB
     quartic_ideal_...      1   16.7ms    0.0%  16.7ms   0.98MiB    0.0%  0.98MiB
     sos_scaled_uni...      1   13.3ms    0.0%  13.3ms    333KiB    0.0%   333KiB
     quartic_feasib...      1   5.55ms    0.0%  5.55ms    414KiB    0.0%   414KiB
     quadratic_feas...      1   5.37ms    0.0%  5.37ms    385KiB    0.0%   385KiB
     quadratic_infe...      1   4.40ms    0.0%  4.40ms    505KiB    0.0%   505KiB
   socp                     1    75.2s   21.5%   75.2s   6.73GiB   19.9%  6.73GiB
     sdsos_term_fixed       1    18.1s    5.2%   18.1s   1.49GiB    4.4%  1.49GiB
     sdsos_horn             1    10.5s    3.0%   10.5s    884MiB    2.6%   884MiB
     sdsos_concave_...      1    9.00s    2.6%   9.00s    729MiB    2.1%   729MiB
     sdsos_univaria...      1    7.51s    2.1%   7.51s    667MiB    1.9%   667MiB
     sdsos_cheby_un...      1    5.58s    1.6%   5.58s    432MiB    1.2%   432MiB
     sdsos_univaria...      1    4.60s    1.3%   4.60s    363MiB    1.0%   363MiB
     sdsos_scaled_u...      1    3.50s    1.0%   3.50s    274MiB    0.8%   274MiB
     sdsos_term             1    3.05s    0.9%   3.05s    225MiB    0.6%   225MiB
     sdsos_options_...      1    3.03s    0.9%   3.03s    208MiB    0.6%   208MiB
     sdsos_quartic_...      1    3.00s    0.9%   3.00s    234MiB    0.7%   234MiB
     sdsos_quartic_...      1    581ms    0.2%   581ms   26.1MiB    0.1%  26.1MiB
     sdsos_scaled_b...      1   36.7ms    0.0%  36.7ms   5.71MiB    0.0%  5.71MiB
     sdsos_bivariat...      1   10.4ms    0.0%  10.4ms    337KiB    0.0%   337KiB
   lp                       1    35.6s   10.2%   35.6s   3.06GiB    9.0%  3.06GiB
     dsos_options_p...      1    5.06s    1.4%   5.06s    424MiB    1.2%   424MiB
     dsos_concave_t...      1    4.42s    1.3%   4.42s    420MiB    1.2%   420MiB
     dsos_cheby_biv...      1    4.01s    1.1%   4.01s    297MiB    0.9%   297MiB
     dsos_univariat...      1    3.96s    1.1%   3.96s    260MiB    0.8%   260MiB
     dsos_horn              1    3.13s    0.9%   3.13s    409MiB    1.2%   409MiB
     dsos_term              1    3.11s    0.9%   3.11s    198MiB    0.6%   198MiB
     dsos_term_fixed        1    3.10s    0.9%   3.10s    208MiB    0.6%   208MiB
     dsos_scaled_bi...      1    2.96s    0.8%   2.96s    203MiB    0.6%   203MiB
     dsos_quartic_c...      1    2.40s    0.7%   2.40s    167MiB    0.5%   167MiB
     dsos_bivariate...      1    619ms    0.2%   619ms   30.3MiB    0.1%  30.3MiB
     dsos_quartic_c...      1    116ms    0.0%   116ms   21.5MiB    0.1%  21.5MiB
     dsos_univariat...      1   31.8ms    0.0%  31.8ms   1.67MiB    0.0%  1.67MiB
     dsos_scaled_un...      1   31.5ms    0.0%  31.5ms   1.67MiB    0.0%  1.67MiB
     dsos_cheby_uni...      1   29.5ms    0.0%  29.5ms   1.70MiB    0.0%  1.70MiB
 Convex                     1     160s   45.7%    160s   17.3GiB   51.1%  17.3GiB
   sdp                      1    88.4s   25.2%   88.4s   9.36GiB   27.7%  9.36GiB
     sdp_quantum_re...      1    14.8s    4.2%   14.8s   1.61GiB    4.8%  1.61GiB
     sdp_lieb_ando          1    9.93s    2.8%   9.93s    550MiB    1.6%   550MiB
     sdp_operator_n...      1    3.70s    1.1%   3.70s    307MiB    0.9%   307MiB
     sdp_trace_logm...      1    3.52s    1.0%   3.52s    445MiB    1.3%   445MiB
     sdp_geom_mean_...      1    2.81s    0.8%   2.81s    108MiB    0.3%   108MiB
     sdp_quantum_re...      1    2.59s    0.7%   2.59s    202MiB    0.6%   202MiB
     sdp_relative_e...      1    2.22s    0.6%   2.22s    220MiB    0.6%   220MiB
     sdp_Partial_trace      1    1.86s    0.5%   1.86s    195MiB    0.6%   195MiB
     sdp_quantum_re...      1    1.65s    0.5%   1.65s   18.4MiB    0.1%  18.4MiB
     sdp_trace_mpow...      1    1.63s    0.5%   1.63s    211MiB    0.6%   211MiB
     sdp_trace_mpow...      1    1.56s    0.4%   1.56s   26.9MiB    0.1%  26.9MiB
     sdp_sum_larges...      1    1.55s    0.4%   1.55s    117MiB    0.3%   117MiB
     sdp_quantum_re...      1    1.53s    0.4%   1.53s   93.2MiB    0.3%  93.2MiB
     sdp_quantum_re...      1    1.48s    0.4%   1.48s   93.2MiB    0.3%  93.2MiB
     sdp_quantum_re...      1    1.47s    0.4%   1.47s   93.2MiB    0.3%  93.2MiB
     sdp_quantum_re...      1    1.47s    0.4%   1.47s   13.2MiB    0.0%  13.2MiB
     sdp_matrix_fra...      1    1.47s    0.4%   1.47s    132MiB    0.4%   132MiB
     sdp_geom_mean_...      1    1.45s    0.4%   1.45s    197MiB    0.6%   197MiB
     sdp_quantum_ch...      1    1.15s    0.3%   1.15s   56.3MiB    0.2%  56.3MiB
     sdp_geom_mean_...      1    1.08s    0.3%   1.08s    117MiB    0.3%   117MiB
     sdp_dual_lambd...      1    865ms    0.2%   865ms   68.9MiB    0.2%  68.9MiB
     sdp_geom_mean_...      1    834ms    0.2%   834ms   75.2MiB    0.2%  75.2MiB
     sdp_min_maxeig...      1    776ms    0.2%   776ms   98.5MiB    0.3%  98.5MiB
     sdp_lambda_min...      1    679ms    0.2%   679ms   82.4MiB    0.2%  82.4MiB
     sdp_geom_mean_...      1    636ms    0.2%   636ms   72.5MiB    0.2%  72.5MiB
     sdp_Complex_Va...      1    613ms    0.2%   613ms   36.8MiB    0.1%  36.8MiB
     sdp_trace_mpow...      1    611ms    0.2%   611ms   21.5MiB    0.1%  21.5MiB
     sdp_nuclear_no...      1    609ms    0.2%   609ms   75.3MiB    0.2%  75.3MiB
     sdp_socp_sumsq...      1    513ms    0.1%   513ms   53.5MiB    0.2%  53.5MiB
     sdp_relative_e...      1    511ms    0.1%   511ms   18.0MiB    0.1%  18.0MiB
     sdp_socp_norm2...      1    471ms    0.1%   471ms   46.4MiB    0.1%  46.4MiB
     sdp_geom_mean_...      1    393ms    0.1%   393ms   69.7MiB    0.2%  69.7MiB
     sdp_trace_logm...      1    387ms    0.1%   387ms   33.4MiB    0.1%  33.4MiB
     sdp_trace_mpow...      1    374ms    0.1%   374ms   12.4MiB    0.0%  12.4MiB
     sdp_geom_mean_...      1    326ms    0.1%   326ms   31.1MiB    0.1%  31.1MiB
     sdp_quantum_re...      1    279ms    0.1%   279ms   17.7MiB    0.1%  17.7MiB
     sdp_trace_mpow...      1    269ms    0.1%   269ms   14.2MiB    0.0%  14.2MiB
     sdp_sdp_variables      1    246ms    0.1%   246ms   27.6MiB    0.1%  27.6MiB
     sdp_matrix_fra...      1    244ms    0.1%   244ms   17.6MiB    0.1%  17.6MiB
     sdp_trace_mpow...      1    243ms    0.1%   243ms   18.8MiB    0.1%  18.8MiB
     sdp_geom_mean_...      1    238ms    0.1%   238ms   15.9MiB    0.0%  15.9MiB
     sdp_socp_abs_atom      1    236ms    0.1%   236ms   21.4MiB    0.1%  21.4MiB
     sdp_geom_mean_...      1    233ms    0.1%   233ms   19.7MiB    0.1%  19.7MiB
     sdp_trace_mpow...      1    208ms    0.1%   208ms   17.3MiB    0.1%  17.3MiB
     sdp_geom_mean_...      1    188ms    0.1%   188ms   18.5MiB    0.1%  18.5MiB
     sdp_operator_n...      1    184ms    0.1%   184ms   22.8MiB    0.1%  22.8MiB
     sdp_nuclear_no...      1    146ms    0.0%   146ms   18.4MiB    0.1%  18.4MiB
     sdp_sigma_max_...      1    138ms    0.0%   138ms   16.2MiB    0.0%  16.2MiB
     sdp_geom_mean_...      1    129ms    0.0%   129ms   17.4MiB    0.1%  17.4MiB
     sdp_quantum_re...      1    120ms    0.0%   120ms   8.61MiB    0.0%  8.61MiB
     sdp_sdp_constr...      1    116ms    0.0%   116ms   9.30MiB    0.0%  9.30MiB
     sdp_Real_Varia...      1    108ms    0.0%   108ms   5.75MiB    0.0%  5.75MiB
     sdp_trace_logm...      1   97.4ms    0.0%  97.4ms   6.76MiB    0.0%  6.76MiB
     sdp_geom_mean_...      1   96.9ms    0.0%  96.9ms   17.2MiB    0.0%  17.2MiB
     sdp_geom_mean_...      1   92.6ms    0.0%  92.6ms   17.1MiB    0.0%  17.1MiB
     sdp_geom_mean_...      1   86.2ms    0.0%  86.2ms   16.6MiB    0.0%  16.6MiB
     sdp_geom_mean_...      1   83.2ms    0.0%  83.2ms   11.9MiB    0.0%  11.9MiB
     sdp_geom_mean_...      1   82.5ms    0.0%  82.5ms   17.0MiB    0.0%  17.0MiB
     sdp_quantum_re...      1   75.6ms    0.0%  75.6ms   8.52MiB    0.0%  8.52MiB
     sdp_Issue_198          1   71.5ms    0.0%  71.5ms   5.70MiB    0.0%  5.70MiB
     sdp_geom_mean_...      1   66.1ms    0.0%  66.1ms   13.6MiB    0.0%  13.6MiB
     sdp_kron_atom          1   62.9ms    0.0%  62.9ms   11.0MiB    0.0%  11.0MiB
     sdp_quantum_re...      1   55.7ms    0.0%  55.7ms   3.06MiB    0.0%  3.06MiB
     sdp_quantum_re...      1   7.35ms    0.0%  7.35ms    389KiB    0.0%   389KiB
   affine                   1    31.2s    8.9%   31.2s   3.53GiB   10.4%  3.53GiB
     affine_Partial...      1    3.01s    0.9%   3.01s    358MiB    1.0%   358MiB
     affine_hcat_atom       1    2.41s    0.7%   2.41s    240MiB    0.7%   240MiB
     affine_permute...      1    2.39s    0.7%   2.39s    379MiB    1.1%   379MiB
     affine_dot_mul...      1    2.37s    0.7%   2.37s    178MiB    0.5%   178MiB
     affine_multipl...      1    2.17s    0.6%   2.17s    245MiB    0.7%   245MiB
     affine_vcat_atom       1    1.81s    0.5%   1.81s    207MiB    0.6%   207MiB
     affine_transpo...      1    1.49s    0.4%   1.49s    113MiB    0.3%   113MiB
     affine_add_atom        1    1.16s    0.3%   1.16s   79.6MiB    0.2%  79.6MiB
     affine_Diagona...      1    1.08s    0.3%   1.08s    115MiB    0.3%   115MiB
     affine_satisfy...      1    1.04s    0.3%   1.04s   55.1MiB    0.2%  55.1MiB
     affine_conv_atom       1    809ms    0.2%   809ms   49.0MiB    0.1%  49.0MiB
     affine_dot_atom        1    699ms    0.2%   699ms   27.7MiB    0.1%  27.7MiB
     affine_index_atom      1    659ms    0.2%   659ms   43.7MiB    0.1%  43.7MiB
     affine_dualvalue       1    619ms    0.2%   619ms   75.0MiB    0.2%  75.0MiB
     affine_reshape...      1    598ms    0.2%   598ms   30.6MiB    0.1%  30.6MiB
     affine_sum_atom        1    294ms    0.1%   294ms   23.4MiB    0.1%  23.4MiB
     affine_kron_atom       1    249ms    0.1%   249ms   16.4MiB    0.0%  16.4MiB
     affine_single_...      1    213ms    0.1%   213ms   22.0MiB    0.1%  22.0MiB
     affine_diag_atom       1    130ms    0.0%   130ms   15.9MiB    0.0%  15.9MiB
     affine_dot_ato...      1    127ms    0.0%   127ms   6.02MiB    0.0%  6.02MiB
     affine_single_...      1    113ms    0.0%   113ms   17.6MiB    0.1%  17.6MiB
     affine_negate_...      1   88.6ms    0.0%  88.6ms   3.70MiB    0.0%  3.70MiB
     affine_trace_atom      1   54.8ms    0.0%  54.8ms   3.28MiB    0.0%  3.28MiB
   socp                     1    21.7s    6.2%   21.7s   2.44GiB    7.2%  2.44GiB
     socp_dual_mini...      1    4.28s    1.2%   4.28s    321MiB    0.9%   321MiB
     socp_quad_form...      1    3.02s    0.9%   3.02s    126MiB    0.4%   126MiB
     socp_rational_...      1    1.39s    0.4%   1.39s    134MiB    0.4%   134MiB
     socp_sum_squar...      1    1.35s    0.4%   1.35s    124MiB    0.4%   124MiB
     socp_inv_pos_atom      1    963ms    0.3%   963ms   85.2MiB    0.2%  85.2MiB
     socp_quad_over...      1    796ms    0.2%   796ms   40.9MiB    0.1%  40.9MiB
     socp_dual_norm...      1    756ms    0.2%   756ms   79.5MiB    0.2%  79.5MiB
     socp_norm_cons...      1    722ms    0.2%   722ms   57.4MiB    0.2%  57.4MiB
     socp_rational_...      1    606ms    0.2%   606ms   59.5MiB    0.2%  59.5MiB
     socp_fix_multi...      1    465ms    0.1%   465ms   41.6MiB    0.1%  41.6MiB
     socp_square_atom       1    400ms    0.1%   400ms   26.0MiB    0.1%  26.0MiB
     socp_huber_atom        1    375ms    0.1%   375ms   36.9MiB    0.1%  36.9MiB
     socp_dual_frob...      1    320ms    0.1%   320ms   37.9MiB    0.1%  37.9MiB
     socp_geo_mean_...      1    319ms    0.1%   319ms   25.5MiB    0.1%  25.5MiB
     socp_fix_and_f...      1    277ms    0.1%   277ms   20.5MiB    0.1%  20.5MiB
     socp_rational_...      1    162ms    0.0%   162ms   10.2MiB    0.0%  10.2MiB
     socp_sqrt_atom         1   56.1ms    0.0%  56.1ms   1.29MiB    0.0%  1.29MiB
   constant                 1    10.1s    2.9%   10.1s   1.10GiB    3.3%  1.10GiB
     constant_fix!_...      1    3.39s    1.0%   3.39s    304MiB    0.9%   304MiB
     constant_Issue...      1    2.96s    0.8%   2.96s    329MiB    0.9%   329MiB
     constant_Issue...      1    1.06s    0.3%   1.06s   99.0MiB    0.3%  99.0MiB
     constant_fix!_...      1    644ms    0.2%   644ms   61.0MiB    0.2%  61.0MiB
     constant_Test_...      1    336ms    0.1%   336ms   18.4MiB    0.1%  18.4MiB
     constant_fix!_...      1    288ms    0.1%   288ms   19.8MiB    0.1%  19.8MiB
   lp                       1    8.37s    2.4%   8.37s    832MiB    2.4%   832MiB
     lp_dotsort_atom        1    3.67s    1.0%   3.67s    253MiB    0.7%   253MiB
     lp_min_atom            1    547ms    0.2%   547ms   41.3MiB    0.1%  41.3MiB
     lp_sumlargest_...      1    521ms    0.1%   521ms   48.0MiB    0.1%  48.0MiB
     lp_max_atom            1    402ms    0.1%   402ms   35.8MiB    0.1%  35.8MiB
     lp_minimum_atom        1    374ms    0.1%   374ms   40.4MiB    0.1%  40.4MiB
     lp_sumsmallest...      1    354ms    0.1%   354ms   31.2MiB    0.1%  31.2MiB
     lp_dual_abs_atom       1    288ms    0.1%   288ms   20.7MiB    0.1%  20.7MiB
     lp_neg_atom            1    253ms    0.1%   253ms   19.4MiB    0.1%  19.4MiB
     lp_maximum_atom        1    182ms    0.1%   182ms   13.3MiB    0.0%  13.3MiB
     lp_dual_norm_i...      1   94.3ms    0.0%  94.3ms   4.03MiB    0.0%  4.03MiB
     lp_pos_atom            1   90.7ms    0.0%  90.7ms   9.52MiB    0.0%  9.52MiB
     lp_dual_norm_1...      1   70.2ms    0.0%  70.2ms   3.93MiB    0.0%  3.93MiB
     lp_hinge_loss_...      1    227μs    0.0%   227μs   57.3KiB    0.0%  57.3KiB
 ────────────────────────────────────────────────────────────────────────────────

```

## SDPA `PARAMETER_DEFAULT` (dualized)
These tests were run on July 8, 2022 at 02:09 (UTC).

Tests with SDPA via SDPA.jl using Dualization.jl.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 2 minutes, 13 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">SDPA tests</td>
<td style="text-align:center;color:green;">1962</td>
<td style="text-align:center;color:red;">82</td>
<td style="text-align:center;color:red;">32</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2076</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">666</td>
<td style="text-align:center;color:red;">23</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">689</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">138</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">141</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_satisfy_problems</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_transpose_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_diag_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_conv_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style="text-align:center;color:green;">19</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">19</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_hcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_vcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_index_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_Partial_transpose</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_single_vcat_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_add_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dualvalue</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_sum_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_reshape_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_multiply_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_trace_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_single_hcat_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_negate_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">101</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">101</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">63</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">65</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_abs_atom</td>
<td style="text-align:center;color:green;">15</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">15</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_inf_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_hinge_loss_atom</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_maximum_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_minimum_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_sumlargest_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dotsort_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_neg_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_sumsmallest_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_pos_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lp_dual_norm_1_atom</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">336</td>
<td style="text-align:center;color:red;">18</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">354</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy4_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_relative_entropy</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_min_maxeig_canon_lmi</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_1</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_fullhyp</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_3_8</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_5_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom_complex</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_cplx</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_0</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg1_optB</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy3_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy3_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy_const</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_2_3</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy5_lowrank</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_real</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_relative_entropy_argcheck</td>
<td style="text-align:center;color:green;">21</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">21</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_3_5</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_1_2</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_argcheck</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_argcheck</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom_complex</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_8_5_optA</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lieb_ando</td>
<td style="text-align:center;color:green;">72</td>
<td style="text-align:center;color:red;">8</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">80</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy2_lowrank</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_channel_capacity</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_neg1_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg3_5_optB</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg3_5_optA</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_3_5</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy5_fullrank</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy1_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_8_5_optB</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy2_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy_argcheck</td>
<td style="text-align:center;color:green;">16</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">16</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_argcheck</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_1_2</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_5_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy1_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy4_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_neg1_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_argcheck</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_2_3</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_3_8</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg1_optA</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1296</td>
<td style="text-align:center;color:red;">59</td>
<td style="text-align:center;color:red;">32</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1387</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">379</td>
<td style="text-align:center;color:red;">19</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">401</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_sum</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_comparison</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term</td>
<td style="text-align:center;color:green;">37</td>
<td style="text-align:center;color:red;">7</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">434</td>
<td style="text-align:center;color:red;">17</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">454</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_sum</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_options_pricing</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term</td>
<td style="text-align:center;color:green;">37</td>
<td style="text-align:center;color:red;">7</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">483</td>
<td style="text-align:center;color:red;">23</td>
<td style="text-align:center;color:red;">26</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">532</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_infeasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simple_matrix</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_concave_then_convex_cubic</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rearrangement</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;maxcut</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=3.9 it should be infeasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=4.1 it should be feasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term</td>
<td style="text-align:center;color:green;">37</td>
<td style="text-align:center;color:red;">7</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_feasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;chebyshev</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
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
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_horn</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_rem</td>
<td style="text-align:center;color:green;">48</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">48</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;motzkin</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_maxdegree</td>
<td style="text-align:center;color:green;">56</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">56</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_options_pricing</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_sum</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;choi</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4_rem</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_comparison</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_2_rem</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr></table>
```

### Errors

```julia
Error in testset affine_dualvalue:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/affine.jl:765
  Expression: ≈((p.constraints[1]).dual, 1, atol = atol, rtol = rtol)
   Evaluated: 0.009627038541049071 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dualvalue:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/affine.jl:773
  Expression: ≈((p.constraints[1]).dual, 1, atol = atol, rtol = rtol)
   Evaluated: 0.009627038541049071 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_negate_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/affine.jl:17
  Expression: ≈(evaluate(-x), 0, atol = atol, rtol = rtol)
   Evaluated: 27.19233338363381 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset lp_sumlargest_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/lp.jl:221
  Expression: ≈(evaluate(sumlargest(x, 2)), 2, atol = atol, rtol = rtol)
   Evaluated: 2.0797145857654744 ≈ 2 (atol=0.001, rtol=0.0)

Error in testset lp_dotsort_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/lp.jl:307
  Expression: ≈(p.optval, 19, atol = atol, rtol = rtol)
   Evaluated: 18.865908267720442 ≈ 19 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:354
  Expression: ≈(p.optval, sum((eigvals(A))[2:end]), atol = atol, rtol = rtol)
   Evaluated: 21.37967275066694 ≈ 21.381108915609733 (atol=0.001, rtol=0.0)

Error in testset sdp_sum_largest_eigs:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:368
  Expression: ≈(p1.optval, p2.optval, atol = atol, rtol = rtol)
   Evaluated: 3.9825063989698117 ≈ 2.2321923511056116 (atol=0.001, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.9456039072103977 ≈ 1.0053124915954001 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -8.796780218309465 ≈ 1.76937190924586 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 0.6816497855714942 ≈ 1.0028180382306984 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -24.46402930598674 ≈ 1.0939861015544436 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -1.349869605344793 ≈ 3.8092659935092614 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -9.278300714328537 ≈ 5.149659210682255 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -23.422143607460384 ≈ 1.837895297363038 (atol=0.005, rtol=0.0)

Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: -100.12266850827947 ≈ 2.6712832695878577 (atol=0.005, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1498
  Expression: ≈(real.(evaluate(B)), real.(X), atol = atol, rtol = rtol)
   Evaluated: [0.33594603139449464 -0.002447859286225493 0.023681135698434257; -0.002447859286225493 0.3247277987340612 -0.010950410008490714; 0.02368113569843426 -0.010950410008490714 0.33932558921994355] ≈ [0.36978567242074806 -0.03588755677601767 0.31772907409031115; -0.03588755677601767 0.215395393447707 -0.1466079961392317; 0.31772907409031115 -0.1466079961392317 0.41481893413154497] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1499
  Expression: ≈(imag.(evaluate(B)), imag.(X), atol = atol, rtol = rtol)
   Evaluated: [3.050639774502172e-25 0.014241592488239679 -0.0032689032787784106; -0.014241592488239679 -1.3923214686790032e-24 -0.005374394450159472; 0.0032689032787784106 0.005374394450159472 3.566910488691638e-24] ≈ [0.0 0.18999724164426005 -0.04588632161402458; -0.18999724164426005 0.0 -0.07478694179387721; 0.04588632161402458 0.07478694179387721 0.0] (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1501
  Expression: ≈(p.optval, 0, atol = atol, rtol = rtol)
   Evaluated: -108.11660779298904 ≈ 0 (atol=0.001, rtol=0.0)

Error in testset sdp_quantum_relative_entropy2_lowrank:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:1506
  Expression: ≈(p.optval, evaluate(quantum_relative_entropy(X, B)), atol = atol, rtol = rtol)
   Evaluated: -108.11660779298904 ≈ 0.5348065609631882 (atol=0.001, rtol=0.0)

Error in testset sdp_Real_Variables_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:507
  Expression: x1 == x2
   Evaluated: [0.5765533867218999, 0.5646090901276699, 0.8623164621790367, 0.928589887456979, 0.3424113793629989, 0.3141903470912999, 0.5438413190715335, 0.28064454042217835, 0.3959433276183497, 0.11884427264255662] == [0.5765533867219002, 0.5646090901276685, 0.8623164621790372, 0.9285898874569789, 0.3424113793630001, 0.3141903470913003, 0.5438413190715325, 0.28064454042217873, 0.3959433276183501, 0.11884427264255722]

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:225
  Expression: ≈(p.optval, 4, atol = atol, rtol = rtol)
   Evaluated: 3.9825063989698117 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_dual_lambda_max_atom:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:226
  Expression: ≈(evaluate(eigmax(y)), 4, atol = atol, rtol = rtol)
   Evaluated: 4.007657858117368 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/FQF1R/src/problem_depot/problems/sdp.jl:86
  Expression: ≈(p.optval, 1, atol = atol, rtol = rtol)
   Evaluated: 0.9975861428372372 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset sdsos_horn:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] horn_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, cone::SumOfSquares.SDSOSCone)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:33
   [16] sdsos_horn_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:65 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sdsos_horn_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sdsos_univariate_sum:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] univariate_sum_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, cone::SumOfSquares.SDSOSCone)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:17
   [16] sdsos_univariate_sum_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:43 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sdsos_univariate_sum_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sdsos_quartic_comparison:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_comparison.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset sdsos_quartic_comparison:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_comparison.jl:32
  Expression: ≈(JuMP.objective_value(model), expected_objective_value, atol = atol, rtol = rtol)
   Evaluated: -3.163175545996637 ≈ -3.172412 (atol=0.001, rtol=0.0)

Error in testset sdsos_concave_then_convex_cubic:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] concave_then_convex_cubic_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, MCT::Type{SumOfSquares.ScaledDiagonallyDominantConeTriangle})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:23
   [16] sdsos_concave_then_convex_cubic_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:48 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sdsos_concave_then_convex_cubic_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:22
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:25
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:26
  Expression: ≈(value(α), 0.0, atol = atol, rtol = rtol)
   Evaluated: 27.192333383634246 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:31
  Expression: ≈(getmat(p), zeros(1, 1), atol = atol, rtol = rtol)
   Evaluated: [27.19233339390131] ≈ [0.0] (atol=0.001, rtol=0.0)

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:38
  Expression: ≈(moment_value((moments(μ))[1]), 1.0, atol = atol, rtol = rtol)
   Evaluated: 0.01886656880378723 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:38
  Expression: ≈(moment_value((moments(μ))[1]), 1.0, atol = atol, rtol = rtol)
   Evaluated: 0.01886656880378723 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset sdsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:43
  Expression: ≈(getmat(ν), ones(1, 1), atol = atol, rtol = rtol)
   Evaluated: [0.009627038541049071] ≈ [1.0] (atol=0.001, rtol=0.0)

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -4.661782890558243 ≈ 21.51 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 6.7841140031814575 ≈ 17.17 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 9.485316216945648 ≈ 13.2 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 4.514163970947266 ≈ 9.85 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -16.241799354553223 ≈ 7.3 (atol=0.1, rtol=0.0)

Error in testset dsos_univariate_sum:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] univariate_sum_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, cone::SumOfSquares.DSOSCone)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:17
   [16] dsos_univariate_sum_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:45 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.dsos_univariate_sum_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 12.161896459758282 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -0.18757832050323486 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 19.644132494926453 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 134.76072144508362 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 64.31968450546265 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset dsos_horn:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] horn_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, cone::SumOfSquares.DSOSCone)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:33
   [16] dsos_horn_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:67 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.dsos_horn_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:22
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:25
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:26
  Expression: ≈(value(α), 0.0, atol = atol, rtol = rtol)
   Evaluated: 27.192333383634246 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:31
  Expression: ≈(getmat(p), zeros(1, 1), atol = atol, rtol = rtol)
   Evaluated: [27.19233339390131] ≈ [0.0] (atol=0.001, rtol=0.0)

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:38
  Expression: ≈(moment_value((moments(μ))[1]), 1.0, atol = atol, rtol = rtol)
   Evaluated: 0.01886656880378723 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:38
  Expression: ≈(moment_value((moments(μ))[1]), 1.0, atol = atol, rtol = rtol)
   Evaluated: 0.01886656880378723 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset dsos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:43
  Expression: ≈(getmat(ν), ones(1, 1), atol = atol, rtol = rtol)
   Evaluated: [0.009627038541049071] ≈ [1.0] (atol=0.001, rtol=0.0)

Error in testset dsos_concave_then_convex_cubic:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] concave_then_convex_cubic_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, MCT::Type{SumOfSquares.DiagonallyDominantConeTriangle})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:23
   [16] dsos_concave_then_convex_cubic_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:53 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.dsos_concave_then_convex_cubic_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sosdemo5_infeasible:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] sosdemo5_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, feasible::Bool, γ::Float64)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/sosdemo5.jl:62
   [16] sosdemo5_infeasible_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/sosdemo5.jl:72 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo5_infeasible_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset simple_matrix:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] simple_matrix_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/simple_matrix.jl:20
   [16] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.simple_matrix_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [28] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ ./timing.jl:368 [inlined]
   [38] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [40] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [41] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [42] _start()
      @ Base ./client.jl:485

Error in testset sos_concave_then_convex_cubic:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] concave_then_convex_cubic_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, MCT::Type{MathOptInterface.PositiveSemidefiniteConeTriangle})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:23
   [16] sos_concave_then_convex_cubic_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/concave_then_convex_cubic.jl:43 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sos_concave_then_convex_cubic_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset rearrangement:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] rearrangement_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/rearrangement.jl:23
   [16] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.rearrangement_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [28] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ ./timing.jl:368 [inlined]
   [38] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [40] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [41] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [42] _start()
      @ Base ./client.jl:485

Error in testset with γ=3.9 it should be infeasible:
Error During Test at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:29
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] macro expansion
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:32 [inlined]
   [16] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1226 [inlined]
   [17] maxcut_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:29
   [18] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [19] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [22] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [23] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [24] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.maxcut_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [25] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [28] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [29] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [30] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [33] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [34] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [35] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [38] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [39] macro expansion
      @ ./timing.jl:368 [inlined]
   [40] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [41] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [42] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [43] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [44] _start()
      @ Base ./client.jl:485

Error in testset with γ=4.1 it should be feasible:
Error During Test at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:29
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] macro expansion
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:32 [inlined]
   [16] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1226 [inlined]
   [17] maxcut_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:29
   [18] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [19] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [22] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [23] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [24] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.maxcut_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [25] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [28] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [29] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [30] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [33] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [34] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [35] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [38] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [39] macro expansion
      @ ./timing.jl:368 [inlined]
   [40] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [41] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [42] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [43] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [44] _start()
      @ Base ./client.jl:485

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:22
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:25
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:26
  Expression: ≈(value(α), 0.0, atol = atol, rtol = rtol)
   Evaluated: 27.192333383634246 ≈ 0.0 (atol=0.001, rtol=0.0)

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:31
  Expression: ≈(getmat(p), zeros(1, 1), atol = atol, rtol = rtol)
   Evaluated: [27.19233339390131] ≈ [0.0] (atol=0.001, rtol=0.0)

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:38
  Expression: ≈(moment_value((moments(μ))[1]), 1.0, atol = atol, rtol = rtol)
   Evaluated: 0.01886656880378723 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:38
  Expression: ≈(moment_value((moments(μ))[1]), 1.0, atol = atol, rtol = rtol)
   Evaluated: 0.01886656880378723 ≈ 1.0 (atol=0.001, rtol=0.0)

Error in testset sos_term:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/term.jl:43
  Expression: ≈(getmat(ν), ones(1, 1), atol = atol, rtol = rtol)
   Evaluated: [0.009627038541049071] ≈ [1.0] (atol=0.001, rtol=0.0)

Error in testset quartic_ideal_rem:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] quartic_ideal_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Nothing, remainder::Bool)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:17
   [16] quartic_ideal_rem_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:39 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_rem_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sosdemo5_feasible:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] sosdemo5_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, feasible::Bool, γ::Float64)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/sosdemo5.jl:62
   [16] sosdemo5_feasible_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/sosdemo5.jl:73 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo5_feasible_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:31
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.SLOW_PROGRESS == MathOptInterface.OPTIMAL

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:32
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:34
  Expression: isapprox(JuMP.value(p), (((128 * x ^ 8 - 256 * x ^ 6) + 160 * x ^ 4) - 32 * x ^ 2) + 1, ztol = 4 * config.atol, atol = 4 * config.atol, rtol = 4 * config.rtol)
   Evaluated: isapprox(127.96135432403561x⁸ - 3.7895539851176466e-8x⁷ - 255.92353104490886x⁶ + 6.631973276602914e-8x⁵ + 159.95274604335617x⁴ - 3.346433673016532e-8x³ - 31.990665612915567x² + 4.486480847583222e-9x + 0.9997124744170724, 128x⁸ - 256x⁶ + 160x⁴ - 32x² + 1; ztol = 0.004, atol = 0.004, rtol = 0.0)

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:35
  Expression: isapprox(JuMP.value(γ), 128, atol = config.atol, rtol = config.rtol)
   Evaluated: isapprox(127.96135432403561, 128; atol = 0.001, rtol = 0.0)

Error in testset sosdemo9:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] sosdemo9_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/sosdemo9.jl:17
   [16] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo9_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [28] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ ./timing.jl:368 [inlined]
   [38] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [40] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [41] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [42] _start()
      @ Base ./client.jl:485

Error in testset quartic_ideal:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] quartic_ideal_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Nothing, remainder::Bool)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:17
   [16] quartic_ideal_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:35 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quartic_feasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.MonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quartic_feasible_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:93 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_feasible_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sos_horn:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] horn_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, cone::SumOfSquares.SOSCone)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:33
   [16] sos_horn_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:63 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sos_horn_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quadratic_infeasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.MonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quadratic_infeasible_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:81 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_infeasible_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quadratic_feasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.ScaledMonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quadratic_feasible_scaled_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:87 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_feasible_scaled_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quartic_ideal_4:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] quartic_ideal_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, remainder::Bool)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:17
   [16] quartic_ideal_4_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:37 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_4_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quadratic_infeasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.ScaledMonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quadratic_infeasible_scaled_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:83 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_infeasible_scaled_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quadratic_feasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.MonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quadratic_feasible_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:85 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_feasible_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset motzkin:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] motzkin_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/motzkin.jl:17
   [16] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.motzkin_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [28] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ ./timing.jl:368 [inlined]
   [38] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [40] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [41] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [42] _start()
      @ Base ./client.jl:485

Error in testset sosdemo10:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] sosdemo10_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/sosdemo10.jl:31
   [16] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo10_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [28] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ ./timing.jl:368 [inlined]
   [38] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [40] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [41] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [42] _start()
      @ Base ./client.jl:485

Error in testset quartic_infeasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.MonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quartic_infeasible_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:89 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_infeasible_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 11.349259816110134 ≈ 21.51 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 20.925458252429962 ≈ 17.17 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 4.005596250295639 ≈ 13.2 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 1.0453258007764816 ≈ 9.85 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: -3.8828549683094025 ≈ 7.3 (atol=0.1, rtol=0.0)

Error in testset quartic_infeasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.ScaledMonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quartic_infeasible_scaled_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:91 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_infeasible_scaled_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sos_univariate_sum:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] univariate_sum_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, cone::SumOfSquares.SOSCone)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:17
   [16] sos_univariate_sum_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/univariate_sum.jl:41 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sos_univariate_sum_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset choi:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] choi_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/choi.jl:32
   [16] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [20] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.choi_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [26] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [28] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [31] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [36] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion
      @ ./timing.jl:368 [inlined]
   [38] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [40] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [41] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [42] _start()
      @ Base ./client.jl:485

Error in testset quartic_feasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] lyapunov_switched_system_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, γ::Float64, feasible::Bool, basis::Type{MultivariateBases.ScaledMonomialBasis})
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:55
   [16] quartic_feasible_scaled_lyapunov_switched_system_test (repeats 2 times)
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:95 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_feasible_scaled_lyapunov_switched_system_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset quartic_ideal_4_rem:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] quartic_ideal_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, remainder::Bool)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:17
   [16] quartic_ideal_4_rem_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:43 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_4_rem_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

Error in testset sos_quartic_comparison:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_comparison.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset sos_quartic_comparison:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_comparison.jl:32
  Expression: ≈(JuMP.objective_value(model), expected_objective_value, atol = atol, rtol = rtol)
   Evaluated: -0.18221930979780154 ≈ -0.184667 (atol=0.001, rtol=0.0)

Error in testset quartic_ideal_2_rem:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
    [1] error(::MathOptInterface.OptimizationSense, ::String)
      @ Base ./error.jl:42
    [2] set_dual_model_sense(dual_model::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}, primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/objective_coefficients.jl:18
    [3] dualize(primal_model::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, dual_problem::Dualization.DualProblem{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, dual_names::DualNames, variable_parameters::Vector{MathOptInterface.VariableIndex}, ignore_objective::Bool, consider_constrained_variables::Bool)
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:58
    [4] #dualize#10
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [5] dualize
      @ ~/.julia/packages/Dualization/c7X4I/src/dualize.jl:32 [inlined]
    [6] copy_to(dest::DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, src::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ Dualization ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204
    [7] copy_to
      @ ~/.julia/packages/Dualization/c7X4I/src/MOI_wrapper.jl:204 [inlined]
    [8] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:86 [inlined]
    [9] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [10] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/Bridges/bridge_optimizer.jl:379 [inlined]
   [11] optimize!
      @ ~/.julia/packages/MathOptInterface/AiEiQ/src/MathOptInterface.jl:87 [inlined]
   [12] optimize!(m::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64, MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{SDPA.Optimizer, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.GenericModel{Float64, MathOptInterface.Utilities.ObjectiveContainer{Float64}, MathOptInterface.Utilities.VariablesContainer{Float64}, Dualization.DualizableModelFunctionConstraints{Float64}}}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}, MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}})
      @ MathOptInterface.Utilities ~/.julia/packages/MathOptInterface/AiEiQ/src/Utilities/cachingoptimizer.jl:316
   [13] optimize!(model::JuMP.Model; ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ JuMP ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:161
   [14] optimize!
      @ ~/.julia/packages/JuMP/Y4piv/src/optimizer_interface.jl:143 [inlined]
   [15] quartic_ideal_test(optimizer::Function, config::MathOptInterface.Test.Config{Float64}, degree::Int64, remainder::Bool)
      @ ConvexTests.SumOfSquaresBench.Tests ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:17
   [16] quartic_ideal_2_rem_test
      @ ~/.julia/packages/SumOfSquares/JDoOM/test/Tests/quartic_ideal.jl:41 [inlined]
   [17] _test
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [18] #3
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [19] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [21] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [22] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [23] (::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}})(name::String, problem_func::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_2_rem_test)})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [24] foreach_problem(apply::ConvexTests.var"#3#4"{DataType, Float64, Float64, TimerOutputs.TimerOutput, var"#3#4"{var"#1#2"}}, class::String, problems::Nothing; exclude::Vector{Regex})
      @ ConvexTests.SumOfSquaresBench ~/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [25] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [27] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [28] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [29] _run_tests(handle_problem!::Function, problems::Dict{String, Dict{String, Function}}, foreach_problem::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), problems_exclude::Nothing; exclude::Vector{Regex}, T::Type, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput)
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [30] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [32] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [33] macro expansion
      @ ~/.julia/packages/TimerOutputs/jgSVI/src/TimerOutput.jl:236 [inlined]
   [34] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Vector{Module}, kws::Base.Iterators.Pairs{Symbol, Any, Tuple{Symbol, Symbol}, NamedTuple{(:T, :exclude), Tuple{DataType, Vector{Regex}}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [35] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion
      @ /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.6/Test/src/Test.jl:1151 [inlined]
   [37] macro expansion
      @ ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [38] macro expansion
      @ ./timing.jl:368 [inlined]
   [39] do_tests(name::String, opt::var"#3#4"{var"#1#2"}; variant::String, first::Bool, last::Bool, description::String, T::Type, exclude::Vector{Regex}, kwargs::Base.Iterators.Pairs{Union{}, Union{}, Tuple{}, NamedTuple{(), Tuple{}}})
      @ ConvexTests ~/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [40] top-level scope
      @ ~/work/ConvexTests.jl/ConvexTests.jl/SDPA/test.jl:36
   [41] include(mod::Module, _path::String)
      @ Base ./Base.jl:384
   [42] exec_options(opts::Base.JLOptions)
      @ Base ./client.jl:285
   [43] _start()
      @ Base ./client.jl:485

```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             132s / 100.0%           9.50GiB / 100.0%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1    80.1s   60.6%   80.1s   4.04GiB   42.5%  4.04GiB
   socp                     1    30.8s   23.3%   30.8s   1.61GiB   16.9%  1.61GiB
     sdsos_term_fixed       1    8.58s    6.5%   8.58s    425MiB    4.4%   425MiB
     sdsos_univaria...      1    4.33s    3.3%   4.33s    272MiB    2.8%   272MiB
     sdsos_horn             1    4.22s    3.2%   4.22s    240MiB    2.5%   240MiB
     sdsos_options_...      1    2.82s    2.1%   2.82s   63.8MiB    0.7%  63.8MiB
     sdsos_term             1    1.92s    1.5%   1.92s    121MiB    1.2%   121MiB
     sdsos_concave_...      1    1.83s    1.4%   1.83s   82.0MiB    0.8%  82.0MiB
     sdsos_cheby_un...      1    1.63s    1.2%   1.63s   56.1MiB    0.6%  56.1MiB
     sdsos_scaled_u...      1    1.55s    1.2%   1.55s   57.9MiB    0.6%  57.9MiB
     sdsos_quartic_...      1    1.01s    0.8%   1.01s   38.8MiB    0.4%  38.8MiB
     sdsos_univaria...      1    917ms    0.7%   917ms   36.6MiB    0.4%  36.6MiB
     sdsos_scaled_b...      1    210ms    0.2%   210ms   1.29MiB    0.0%  1.29MiB
     sdsos_bivariat...      1    196ms    0.1%   196ms   1.29MiB    0.0%  1.29MiB
     sdsos_quartic_...      1    179ms    0.1%   179ms   1.67MiB    0.0%  1.67MiB
   sdp                      1    30.6s   23.1%   30.6s   1.54GiB   16.2%  1.54GiB
     chebyshev              1    1.80s    1.4%   1.80s    121MiB    1.2%   121MiB
     sos_options_pr...      1    1.75s    1.3%   1.75s   43.8MiB    0.5%  43.8MiB
     sos_scaled_biv...      1    1.60s    1.2%   1.60s   55.9MiB    0.6%  55.9MiB
     sos_cheby_univ...      1    1.56s    1.2%   1.56s   54.1MiB    0.6%  54.1MiB
     sos_term_fixed         1    1.53s    1.2%   1.53s   54.1MiB    0.6%  54.1MiB
     rearrangement          1    1.51s    1.1%   1.51s   68.9MiB    0.7%  68.9MiB
     sosdemo5_infea...      1    1.51s    1.1%   1.51s   88.0MiB    0.9%  88.0MiB
     sos_horn               1    1.42s    1.1%   1.42s   57.6MiB    0.6%  57.6MiB
     quartic_ideal_rem      1    1.34s    1.0%   1.34s   59.8MiB    0.6%  59.8MiB
     sos_term               1    1.29s    1.0%   1.29s   49.9MiB    0.5%  49.9MiB
     sos_quartic_co...      1    1.03s    0.8%   1.03s   37.5MiB    0.4%  37.5MiB
     quartic_ideal_4        1    998ms    0.8%   998ms   38.8MiB    0.4%  38.8MiB
     quartic_ideal          1    948ms    0.7%   948ms   33.5MiB    0.3%  33.5MiB
     BPT12e399_rem          1    937ms    0.7%   937ms   28.4MiB    0.3%  28.4MiB
     sos_concave_th...      1    923ms    0.7%   923ms   44.6MiB    0.5%  44.6MiB
     quartic_ideal_...      1    892ms    0.7%   892ms   32.0MiB    0.3%  32.0MiB
     simple_matrix          1    774ms    0.6%   774ms   33.4MiB    0.3%  33.4MiB
     sos_univariate...      1    771ms    0.6%   771ms   22.0MiB    0.2%  22.0MiB
     BPT12e399_maxd...      1    683ms    0.5%   683ms   16.8MiB    0.2%  16.8MiB
     quadratic_infe...      1    338ms    0.3%   338ms   15.0MiB    0.2%  15.0MiB
     sos_univariate...      1    309ms    0.2%   309ms   11.9MiB    0.1%  11.9MiB
     maxcut                 1    249ms    0.2%   249ms   9.92MiB    0.1%  9.92MiB
     quadratic_feas...      1    198ms    0.1%   198ms   1.97MiB    0.0%  1.97MiB
     quartic_ideal_...      1    194ms    0.1%   194ms   1.89MiB    0.0%  1.89MiB
     quadratic_infe...      1    188ms    0.1%   188ms   1.90MiB    0.0%  1.90MiB
     sos_scaled_uni...      1    187ms    0.1%   187ms   1.28MiB    0.0%  1.28MiB
     sos_bivariate_...      1    186ms    0.1%   186ms   1.28MiB    0.0%  1.28MiB
     sosdemo5_feasible      1    185ms    0.1%   185ms   17.4MiB    0.2%  17.4MiB
     sosdemo10              1    178ms    0.1%   178ms   3.24MiB    0.0%  3.24MiB
     quartic_feasib...      1    176ms    0.1%   176ms   1.97MiB    0.0%  1.97MiB
     quadratic_feas...      1    166ms    0.1%   166ms   1.88MiB    0.0%  1.88MiB
     choi                   1    155ms    0.1%   155ms   2.29MiB    0.0%  2.29MiB
     quartic_infeas...      1    155ms    0.1%   155ms   1.89MiB    0.0%  1.89MiB
     quartic_feasib...      1    154ms    0.1%   154ms   1.94MiB    0.0%  1.94MiB
     quartic_infeas...      1    152ms    0.1%   152ms   1.87MiB    0.0%  1.87MiB
     sosdemo9               1    150ms    0.1%   150ms   2.36MiB    0.0%  2.36MiB
     motzkin                1    146ms    0.1%   146ms   1.74MiB    0.0%  1.74MiB
     sos_quartic_co...      1   97.2ms    0.1%  97.2ms   1.22MiB    0.0%  1.22MiB
   lp                       1    18.7s   14.2%   18.7s    907MiB    9.3%   907MiB
     dsos_options_p...      1    3.51s    2.7%   3.51s    141MiB    1.4%   141MiB
     dsos_cheby_biv...      1    2.77s    2.1%   2.77s    140MiB    1.4%   140MiB
     dsos_univariat...      1    1.84s    1.4%   1.84s   76.1MiB    0.8%  76.1MiB
     dsos_scaled_bi...      1    1.60s    1.2%   1.60s   54.2MiB    0.6%  54.2MiB
     dsos_term_fixed        1    1.45s    1.1%   1.45s   52.4MiB    0.5%  52.4MiB
     dsos_concave_t...      1    1.40s    1.1%   1.40s   54.4MiB    0.6%  54.4MiB
     dsos_term              1    1.36s    1.0%   1.36s   51.5MiB    0.5%  51.5MiB
     dsos_quartic_c...      1    973ms    0.7%   973ms   37.2MiB    0.4%  37.2MiB
     dsos_quartic_c...      1    860ms    0.7%   860ms   28.7MiB    0.3%  28.7MiB
     dsos_bivariate...      1    749ms    0.6%   749ms   22.0MiB    0.2%  22.0MiB
     dsos_horn              1    234ms    0.2%   234ms   2.26MiB    0.0%  2.26MiB
     dsos_univariat...      1    183ms    0.1%   183ms   1.25MiB    0.0%  1.25MiB
     dsos_scaled_un...      1    179ms    0.1%   179ms   1.26MiB    0.0%  1.26MiB
     dsos_cheby_uni...      1    157ms    0.1%   157ms   1.28MiB    0.0%  1.28MiB
 Convex                     1    52.0s   39.4%   52.0s   5.46GiB   57.5%  5.46GiB
   sdp                      1    21.2s   16.0%   21.2s   2.10GiB   22.1%  2.10GiB
     sdp_lieb_ando          1    3.57s    2.7%   3.57s    236MiB    2.4%   236MiB
     sdp_quantum_re...      1    965ms    0.7%   965ms   54.2MiB    0.6%  54.2MiB
     sdp_quantum_re...      1    895ms    0.7%   895ms   28.1MiB    0.3%  28.1MiB
     sdp_quantum_re...      1    869ms    0.7%   869ms   28.1MiB    0.3%  28.1MiB
     sdp_quantum_re...      1    729ms    0.6%   729ms   28.1MiB    0.3%  28.1MiB
     sdp_quantum_re...      1    718ms    0.5%   718ms   28.1MiB    0.3%  28.1MiB
     sdp_min_maxeig...      1    475ms    0.4%   475ms   74.5MiB    0.8%  74.5MiB
     sdp_quantum_ch...      1    316ms    0.2%   316ms   29.7MiB    0.3%  29.7MiB
     sdp_geom_mean_...      1    275ms    0.2%   275ms   22.6MiB    0.2%  22.6MiB
     sdp_trace_mpow...      1    247ms    0.2%   247ms   16.1MiB    0.2%  16.1MiB
     sdp_trace_mpow...      1    233ms    0.2%   233ms   15.3MiB    0.2%  15.3MiB
     sdp_trace_mpow...      1    222ms    0.2%   222ms   17.9MiB    0.2%  17.9MiB
     sdp_trace_logm...      1    221ms    0.2%   221ms   20.7MiB    0.2%  20.7MiB
     sdp_sum_larges...      1    220ms    0.2%   220ms   18.7MiB    0.2%  18.7MiB
     sdp_trace_mpow...      1    220ms    0.2%   220ms   17.0MiB    0.2%  17.0MiB
     sdp_relative_e...      1    214ms    0.2%   214ms   28.2MiB    0.3%  28.2MiB
     sdp_sdp_variables      1    203ms    0.2%   203ms   27.0MiB    0.3%  27.0MiB
     sdp_trace_mpow...      1    202ms    0.2%   202ms   13.4MiB    0.1%  13.4MiB
     sdp_Partial_trace      1    199ms    0.2%   199ms   23.2MiB    0.2%  23.2MiB
     sdp_trace_logm...      1    196ms    0.1%   196ms   17.2MiB    0.2%  17.2MiB
     sdp_trace_mpow...      1    193ms    0.1%   193ms   15.5MiB    0.2%  15.5MiB
     sdp_Real_Varia...      1    192ms    0.1%   192ms   14.2MiB    0.1%  14.2MiB
     sdp_dual_lambd...      1    192ms    0.1%   192ms   23.3MiB    0.2%  23.3MiB
     sdp_socp_sumsq...      1    186ms    0.1%   186ms   28.9MiB    0.3%  28.9MiB
     sdp_socp_norm2...      1    182ms    0.1%   182ms   20.9MiB    0.2%  20.9MiB
     sdp_Complex_Va...      1    181ms    0.1%   181ms   18.4MiB    0.2%  18.4MiB
     sdp_sigma_max_...      1    163ms    0.1%   163ms   15.8MiB    0.2%  15.8MiB
     sdp_geom_mean_...      1    162ms    0.1%   162ms   17.3MiB    0.2%  17.3MiB
     sdp_kron_atom          1    158ms    0.1%   158ms   10.9MiB    0.1%  10.9MiB
     sdp_geom_mean_...      1    139ms    0.1%   139ms   21.0MiB    0.2%  21.0MiB
     sdp_nuclear_no...      1    123ms    0.1%   123ms   17.9MiB    0.2%  17.9MiB
     sdp_quantum_re...      1    117ms    0.1%   117ms   6.48MiB    0.1%  6.48MiB
     sdp_operator_n...      1    108ms    0.1%   108ms   15.0MiB    0.2%  15.0MiB
     sdp_matrix_fra...      1    107ms    0.1%   107ms   12.6MiB    0.1%  12.6MiB
     sdp_nuclear_no...      1    104ms    0.1%   104ms   9.11MiB    0.1%  9.11MiB
     sdp_socp_abs_atom      1    100ms    0.1%   100ms   11.3MiB    0.1%  11.3MiB
     sdp_matrix_fra...      1   96.4ms    0.1%  96.4ms   11.3MiB    0.1%  11.3MiB
     sdp_geom_mean_...      1   90.5ms    0.1%  90.5ms   16.1MiB    0.2%  16.1MiB
     sdp_geom_mean_...      1   89.2ms    0.1%  89.2ms   15.8MiB    0.2%  15.8MiB
     sdp_geom_mean_...      1   85.6ms    0.1%  85.6ms   17.2MiB    0.2%  17.2MiB
     sdp_geom_mean_...      1   84.9ms    0.1%  84.9ms   16.4MiB    0.2%  16.4MiB
     sdp_geom_mean_...      1   83.6ms    0.1%  83.6ms   16.2MiB    0.2%  16.2MiB
     sdp_geom_mean_...      1   83.6ms    0.1%  83.6ms   16.3MiB    0.2%  16.3MiB
     sdp_geom_mean_...      1   81.2ms    0.1%  81.2ms   16.3MiB    0.2%  16.3MiB
     sdp_lambda_min...      1   77.5ms    0.1%  77.5ms   7.48MiB    0.1%  7.48MiB
     sdp_sdp_constr...      1   68.6ms    0.1%  68.6ms   9.32MiB    0.1%  9.32MiB
     sdp_operator_n...      1   68.3ms    0.1%  68.3ms   7.30MiB    0.1%  7.30MiB
     sdp_geom_mean_...      1   67.1ms    0.1%  67.1ms   13.0MiB    0.1%  13.0MiB
     sdp_geom_mean_...      1   65.0ms    0.0%  65.0ms   13.1MiB    0.1%  13.1MiB
     sdp_quantum_re...      1   63.2ms    0.0%  63.2ms   6.77MiB    0.1%  6.77MiB
     sdp_Issue_198          1   63.2ms    0.0%  63.2ms   5.33MiB    0.1%  5.33MiB
     sdp_geom_mean_...      1   62.2ms    0.0%  62.2ms   13.2MiB    0.1%  13.2MiB
     sdp_geom_mean_...      1   57.3ms    0.0%  57.3ms   11.5MiB    0.1%  11.5MiB
     sdp_geom_mean_...      1   57.0ms    0.0%  57.0ms   12.4MiB    0.1%  12.4MiB
     sdp_quantum_re...      1   45.9ms    0.0%  45.9ms   5.49MiB    0.1%  5.49MiB
     sdp_trace_mpow...      1   41.3ms    0.0%  41.3ms   30.1KiB    0.0%  30.1KiB
     sdp_relative_e...      1   37.0ms    0.0%  37.0ms   35.0KiB    0.0%  35.0KiB
     sdp_quantum_re...      1   33.1ms    0.0%  33.1ms   46.7KiB    0.0%  46.7KiB
     sdp_trace_logm...      1   32.7ms    0.0%  32.7ms   26.6KiB    0.0%  26.6KiB
     sdp_geom_mean_...      1   24.2ms    0.0%  24.2ms   28.0KiB    0.0%  28.0KiB
     sdp_geom_mean_...      1   21.1ms    0.0%  21.1ms   27.5KiB    0.0%  27.5KiB
     sdp_quantum_re...      1   2.70ms    0.0%  2.70ms    365KiB    0.0%   365KiB
     sdp_quantum_re...      1   2.55ms    0.0%  2.55ms    357KiB    0.0%   357KiB
     sdp_quantum_re...      1    251μs    0.0%   251μs   66.4KiB    0.0%  66.4KiB
   constant                 1    13.1s    9.9%   13.1s   1.27GiB   13.3%  1.27GiB
     constant_Issue...      1    11.7s    8.9%   11.7s   1.10GiB   11.6%  1.10GiB
     constant_fix!_...      1    251ms    0.2%   251ms   15.5MiB    0.2%  15.5MiB
     constant_fix!_...      1    225ms    0.2%   225ms   16.7MiB    0.2%  16.7MiB
     constant_Issue...      1   84.2ms    0.1%  84.2ms   14.3MiB    0.1%  14.3MiB
     constant_Test_...      1   77.3ms    0.1%  77.3ms   4.03MiB    0.0%  4.03MiB
     constant_fix!_...      1   52.8ms    0.0%  52.8ms   3.58MiB    0.0%  3.58MiB
   socp                     1    7.96s    6.0%   7.96s    942MiB    9.7%   942MiB
     socp_dual_mini...      1    3.08s    2.3%   3.08s    198MiB    2.0%   198MiB
     socp_dual_norm...      1    473ms    0.4%   473ms   65.2MiB    0.7%  65.2MiB
     socp_quad_form...      1    388ms    0.3%   388ms   43.5MiB    0.4%  43.5MiB
     socp_square_atom       1    316ms    0.2%   316ms   25.7MiB    0.3%  25.7MiB
     socp_inv_pos_atom      1    279ms    0.2%   279ms   22.6MiB    0.2%  22.6MiB
     socp_sum_squar...      1    278ms    0.2%   278ms   26.1MiB    0.3%  26.1MiB
     socp_rational_...      1    241ms    0.2%   241ms   24.1MiB    0.2%  24.1MiB
     socp_dual_frob...      1    232ms    0.2%   232ms   31.5MiB    0.3%  31.5MiB
     socp_fix_multi...      1    196ms    0.1%   196ms   41.0MiB    0.4%  41.0MiB
     socp_rational_...      1    159ms    0.1%   159ms   26.3MiB    0.3%  26.3MiB
     socp_geo_mean_...      1    105ms    0.1%   105ms   7.17MiB    0.1%  7.17MiB
     socp_quad_over...      1    104ms    0.1%   104ms   12.4MiB    0.1%  12.4MiB
     socp_huber_atom        1   90.5ms    0.1%  90.5ms   13.6MiB    0.1%  13.6MiB
     socp_rational_...      1   82.3ms    0.1%  82.3ms   7.39MiB    0.1%  7.39MiB
     socp_fix_and_f...      1   52.8ms    0.0%  52.8ms   3.14MiB    0.0%  3.14MiB
     socp_norm_cons...      1    386μs    0.0%   386μs   62.6KiB    0.0%  62.6KiB
     socp_sqrt_atom         1   78.2μs    0.0%  78.2μs   22.2KiB    0.0%  22.2KiB
   affine                   1    6.93s    5.2%   6.93s    804MiB    8.3%   804MiB
     affine_transpo...      1    582ms    0.4%   582ms   29.5MiB    0.3%  29.5MiB
     affine_Partial...      1    506ms    0.4%   506ms   41.6MiB    0.4%  41.6MiB
     affine_dot_mul...      1    443ms    0.3%   443ms   36.2MiB    0.4%  36.2MiB
     affine_multipl...      1    377ms    0.3%   377ms   29.3MiB    0.3%  29.3MiB
     affine_vcat_atom       1    376ms    0.3%   376ms   56.5MiB    0.6%  56.5MiB
     affine_reshape...      1    337ms    0.3%   337ms   18.2MiB    0.2%  18.2MiB
     affine_index_atom      1    257ms    0.2%   257ms   23.8MiB    0.2%  23.8MiB
     affine_hcat_atom       1    255ms    0.2%   255ms   23.2MiB    0.2%  23.2MiB
     affine_sum_atom        1    237ms    0.2%   237ms   22.2MiB    0.2%  22.2MiB
     affine_Diagona...      1    220ms    0.2%   220ms   22.1MiB    0.2%  22.1MiB
     affine_dualvalue       1    165ms    0.1%   165ms   13.3MiB    0.1%  13.3MiB
     affine_add_atom        1    144ms    0.1%   144ms   10.0MiB    0.1%  10.0MiB
     affine_conv_atom       1    128ms    0.1%   128ms   12.5MiB    0.1%  12.5MiB
     affine_diag_atom       1    119ms    0.1%   119ms   15.7MiB    0.2%  15.7MiB
     affine_satisfy...      1   80.0ms    0.1%  80.0ms   4.34MiB    0.0%  4.34MiB
     affine_dot_ato...      1   61.8ms    0.0%  61.8ms   3.88MiB    0.0%  3.88MiB
     affine_single_...      1   61.2ms    0.0%  61.2ms   14.0MiB    0.1%  14.0MiB
     affine_dot_atom        1   60.5ms    0.0%  60.5ms   6.66MiB    0.1%  6.66MiB
     affine_single_...      1   59.6ms    0.0%  59.6ms   14.4MiB    0.1%  14.4MiB
     affine_negate_...      1   56.2ms    0.0%  56.2ms   2.72MiB    0.0%  2.72MiB
     affine_trace_atom      1   47.6ms    0.0%  47.6ms   3.30MiB    0.0%  3.30MiB
     affine_permute...      1   17.2ms    0.0%  17.2ms    382KiB    0.0%   382KiB
     affine_kron_atom       1    170μs    0.0%   170μs   29.2KiB    0.0%  29.2KiB
   lp                       1    2.80s    2.1%   2.80s    401MiB    4.1%   401MiB
     lp_dual_abs_atom       1    230ms    0.2%   230ms   19.1MiB    0.2%  19.1MiB
     lp_minimum_atom        1    214ms    0.2%   214ms   28.2MiB    0.3%  28.2MiB
     lp_dotsort_atom        1    206ms    0.2%   206ms   23.4MiB    0.2%  23.4MiB
     lp_sumlargest_...      1    193ms    0.1%   193ms   34.3MiB    0.4%  34.3MiB
     lp_sumsmallest...      1    177ms    0.1%   177ms   18.7MiB    0.2%  18.7MiB
     lp_max_atom            1    146ms    0.1%   146ms   17.2MiB    0.2%  17.2MiB
     lp_min_atom            1    144ms    0.1%   144ms   17.2MiB    0.2%  17.2MiB
     lp_neg_atom            1   77.7ms    0.1%  77.7ms   10.3MiB    0.1%  10.3MiB
     lp_pos_atom            1   73.7ms    0.1%  73.7ms   9.08MiB    0.1%  9.08MiB
     lp_dual_norm_1...      1   68.9ms    0.1%  68.9ms   3.86MiB    0.0%  3.86MiB
     lp_dual_norm_i...      1   68.7ms    0.1%  68.7ms   3.73MiB    0.0%  3.73MiB
     lp_maximum_atom        1   64.2ms    0.0%  64.2ms   12.7MiB    0.1%  12.7MiB
     lp_hinge_loss_...      1   57.2μs    0.0%  57.2μs   21.5KiB    0.0%  21.5KiB
 ────────────────────────────────────────────────────────────────────────────────

```

