Table of contents:

```@contents
Pages = ["SCS.md"]
Depth = 4
```


Compilation warmup gives an estimate of 54 seconds of compilation time.

## SCS 
These tests were run on July 8, 2022 at 02:15 (UTC).

Tests run with `eps=1e-6`.

Excluded problems and classes of problems:
```julia
Regex[r"mip"]
```

### Tests

Tests took 12 minutes, 30 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">SCS tests</td>
<td style="text-align:center;color:green;">2348</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2348</td>
</tr></table>
```

### Errors

```julia
```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             749s /  99.9%           34.1GiB /  99.9%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 Convex                     1     471s   62.9%    471s   17.0GiB   50.0%  17.0GiB
   sdp                      1     371s   49.6%    371s   8.77GiB   25.7%  8.77GiB
     sdp_lieb_ando          1     178s   23.8%    178s    385MiB    1.1%   385MiB
     sdp_quantum_re...      1    46.3s    6.2%   46.3s   17.2MiB    0.0%  17.2MiB
     sdp_quantum_re...      1    30.2s    4.0%   30.2s   17.2MiB    0.0%  17.2MiB
     sdp_quantum_re...      1    18.6s    2.5%   18.6s   1.52GiB    4.5%  1.52GiB
     sdp_quantum_re...      1    10.9s    1.5%   10.9s    126MiB    0.4%   126MiB
     sdp_quantum_re...      1    5.64s    0.8%   5.64s   17.2MiB    0.0%  17.2MiB
     sdp_operator_n...      1    4.87s    0.7%   4.87s    307MiB    0.9%   307MiB
     sdp_trace_logm...      1    4.62s    0.6%   4.62s    440MiB    1.3%   440MiB
     sdp_geom_mean_...      1    3.88s    0.5%   3.88s    104MiB    0.3%   104MiB
     sdp_quantum_re...      1    3.65s    0.5%   3.65s   11.0MiB    0.0%  11.0MiB
     sdp_trace_mpow...      1    3.40s    0.5%   3.40s    206MiB    0.6%   206MiB
     sdp_Partial_trace      1    2.53s    0.3%   2.53s    195MiB    0.6%   195MiB
     sdp_quantum_re...      1    2.18s    0.3%   2.18s   18.4MiB    0.1%  18.4MiB
     sdp_trace_mpow...      1    2.13s    0.3%   2.13s   25.6MiB    0.1%  25.6MiB
     sdp_relative_e...      1    2.06s    0.3%   2.06s    156MiB    0.4%   156MiB
     sdp_quantum_re...      1    2.00s    0.3%   2.00s   13.2MiB    0.0%  13.2MiB
     sdp_sum_larges...      1    1.98s    0.3%   1.98s    113MiB    0.3%   113MiB
     sdp_matrix_fra...      1    1.98s    0.3%   1.98s    130MiB    0.4%   130MiB
     sdp_geom_mean_...      1    1.82s    0.2%   1.82s    196MiB    0.6%   196MiB
     sdp_quantum_ch...      1    1.59s    0.2%   1.59s   47.7MiB    0.1%  47.7MiB
     sdp_geom_mean_...      1    1.32s    0.2%   1.32s    109MiB    0.3%   109MiB
     sdp_dual_lambd...      1    1.09s    0.1%   1.09s   65.1MiB    0.2%  65.1MiB
     sdp_lambda_min...      1    1.04s    0.1%   1.04s   82.4MiB    0.2%  82.4MiB
     sdp_min_maxeig...      1    1.03s    0.1%   1.03s   98.4MiB    0.3%  98.4MiB
     sdp_nuclear_no...      1    859ms    0.1%   859ms   74.1MiB    0.2%  74.1MiB
     sdp_geom_mean_...      1    832ms    0.1%   832ms   72.0MiB    0.2%  72.0MiB
     sdp_trace_mpow...      1    822ms    0.1%   822ms   18.2MiB    0.1%  18.2MiB
     sdp_Complex_Va...      1    788ms    0.1%   788ms   35.6MiB    0.1%  35.6MiB
     sdp_quantum_re...      1    752ms    0.1%   752ms   3.77MiB    0.0%  3.77MiB
     sdp_geom_mean_...      1    748ms    0.1%   748ms   48.9MiB    0.1%  48.9MiB
     sdp_relative_e...      1    733ms    0.1%   733ms   18.0MiB    0.1%  18.0MiB
     sdp_socp_sumsq...      1    685ms    0.1%   685ms   53.2MiB    0.2%  53.2MiB
     sdp_trace_mpow...      1    588ms    0.1%   588ms   12.4MiB    0.0%  12.4MiB
     sdp_socp_norm2...      1    577ms    0.1%   577ms   46.3MiB    0.1%  46.3MiB
     sdp_geom_mean_...      1    514ms    0.1%   514ms   69.1MiB    0.2%  69.1MiB
     sdp_trace_logm...      1    513ms    0.1%   513ms   31.6MiB    0.1%  31.6MiB
     sdp_geom_mean_...      1    413ms    0.1%   413ms   25.0MiB    0.1%  25.0MiB
     sdp_sdp_constr...      1    353ms    0.0%   353ms   9.12MiB    0.0%  9.12MiB
     sdp_geom_mean_...      1    342ms    0.0%   342ms   19.7MiB    0.1%  19.7MiB
     sdp_sdp_variables      1    333ms    0.0%   333ms   27.2MiB    0.1%  27.2MiB
     sdp_trace_mpow...      1    327ms    0.0%   327ms   16.1MiB    0.0%  16.1MiB
     sdp_socp_abs_atom      1    321ms    0.0%   321ms   21.3MiB    0.1%  21.3MiB
     sdp_Complex_Se...      1    306ms    0.0%   306ms   21.1MiB    0.1%  21.1MiB
     sdp_geom_mean_...      1    275ms    0.0%   275ms   15.9MiB    0.0%  15.9MiB
     sdp_trace_mpow...      1    275ms    0.0%   275ms   13.0MiB    0.0%  13.0MiB
     sdp_trace_mpow...      1    259ms    0.0%   259ms   16.0MiB    0.0%  16.0MiB
     sdp_operator_n...      1    236ms    0.0%   236ms   22.6MiB    0.1%  22.6MiB
     sdp_geom_mean_...      1    230ms    0.0%   230ms   16.3MiB    0.0%  16.3MiB
     sdp_matrix_fra...      1    225ms    0.0%   225ms   17.4MiB    0.1%  17.4MiB
     sdp_geom_mean_...      1    219ms    0.0%   219ms   16.6MiB    0.0%  16.6MiB
     sdp_geom_mean_...      1    198ms    0.0%   198ms   15.4MiB    0.0%  15.4MiB
     sdp_geom_mean_...      1    197ms    0.0%   197ms   15.3MiB    0.0%  15.3MiB
     sdp_nuclear_no...      1    195ms    0.0%   195ms   18.0MiB    0.1%  18.0MiB
     sdp_sigma_max_...      1    191ms    0.0%   191ms   16.1MiB    0.0%  16.1MiB
     sdp_geom_mean_...      1    164ms    0.0%   164ms   15.8MiB    0.0%  15.8MiB
     sdp_geom_mean_...      1    143ms    0.0%   143ms   12.9MiB    0.0%  12.9MiB
     sdp_Real_Varia...      1    134ms    0.0%   134ms   5.10MiB    0.0%  5.10MiB
     sdp_quantum_re...      1    129ms    0.0%   129ms   3.68MiB    0.0%  3.68MiB
     sdp_trace_logm...      1    127ms    0.0%   127ms   6.75MiB    0.0%  6.75MiB
     sdp_geom_mean_...      1    118ms    0.0%   118ms   16.0MiB    0.0%  16.0MiB
     sdp_geom_mean_...      1    111ms    0.0%   111ms   11.4MiB    0.0%  11.4MiB
     sdp_kron_atom          1   84.2ms    0.0%  84.2ms   10.8MiB    0.0%  10.8MiB
     sdp_Issue_198          1   83.6ms    0.0%  83.6ms   5.22MiB    0.0%  5.22MiB
     sdp_quantum_re...      1   76.4ms    0.0%  76.4ms   2.99MiB    0.0%  2.99MiB
     sdp_quantum_re...      1   9.60ms    0.0%  9.60ms    313KiB    0.0%   313KiB
   affine                   1    41.6s    5.6%   41.6s   3.52GiB   10.3%  3.52GiB
     affine_Partial...      1    4.07s    0.5%   4.07s    344MiB    1.0%   344MiB
     affine_hcat_atom       1    3.27s    0.4%   3.27s    238MiB    0.7%   238MiB
     affine_permute...      1    3.24s    0.4%   3.24s    379MiB    1.1%   379MiB
     affine_dot_mul...      1    3.03s    0.4%   3.03s    169MiB    0.5%   169MiB
     affine_multipl...      1    2.80s    0.4%   2.80s    244MiB    0.7%   244MiB
     affine_vcat_atom       1    2.50s    0.3%   2.50s    207MiB    0.6%   207MiB
     affine_transpo...      1    2.00s    0.3%   2.00s    111MiB    0.3%   111MiB
     affine_add_atom        1    1.57s    0.2%   1.57s   79.6MiB    0.2%  79.6MiB
     affine_Diagona...      1    1.40s    0.2%   1.40s    115MiB    0.3%   115MiB
     affine_satisfy...      1    1.32s    0.2%   1.32s   55.0MiB    0.2%  55.0MiB
     affine_conv_atom       1    1.07s    0.1%   1.07s   48.8MiB    0.1%  48.8MiB
     affine_index_atom      1    900ms    0.1%   900ms   43.3MiB    0.1%  43.3MiB
     affine_dot_atom        1    885ms    0.1%   885ms   27.6MiB    0.1%  27.6MiB
     affine_dualvalue       1    845ms    0.1%   845ms   75.0MiB    0.2%  75.0MiB
     affine_reshape...      1    772ms    0.1%   772ms   30.4MiB    0.1%  30.4MiB
     affine_sum_atom        1    387ms    0.1%   387ms   23.3MiB    0.1%  23.3MiB
     affine_kron_atom       1    275ms    0.0%   275ms   16.3MiB    0.0%  16.3MiB
     affine_single_...      1    245ms    0.0%   245ms   21.9MiB    0.1%  21.9MiB
     affine_diag_atom       1    165ms    0.0%   165ms   15.7MiB    0.0%  15.7MiB
     affine_dot_ato...      1    156ms    0.0%   156ms   5.99MiB    0.0%  5.99MiB
     affine_single_...      1    143ms    0.0%   143ms   17.4MiB    0.0%  17.4MiB
     affine_negate_...      1    110ms    0.0%   110ms   3.70MiB    0.0%  3.70MiB
     affine_trace_atom      1   73.2ms    0.0%  73.2ms   3.26MiB    0.0%  3.26MiB
   socp                     1    26.0s    3.5%   26.0s   2.23GiB    6.5%  2.23GiB
     socp_quad_form...      1    3.76s    0.5%   3.76s   98.0MiB    0.3%  98.0MiB
     socp_dual_mini...      1    2.92s    0.4%   2.92s    162MiB    0.5%   162MiB
     socp_rational_...      1    1.54s    0.2%   1.54s    133MiB    0.4%   133MiB
     socp_sum_squar...      1    1.53s    0.2%   1.53s    107MiB    0.3%   107MiB
     socp_inv_pos_atom      1    1.30s    0.2%   1.30s   84.3MiB    0.2%  84.3MiB
     socp_quad_over...      1    1.04s    0.1%   1.04s   40.7MiB    0.1%  40.7MiB
     socp_norm_cons...      1    1.02s    0.1%   1.02s   57.4MiB    0.2%  57.4MiB
     socp_dual_norm...      1    1.02s    0.1%   1.02s   79.0MiB    0.2%  79.0MiB
     socp_rational_...      1    822ms    0.1%   822ms   58.8MiB    0.2%  58.8MiB
     socp_fix_multi...      1    512ms    0.1%   512ms   41.1MiB    0.1%  41.1MiB
     socp_square_atom       1    506ms    0.1%   506ms   25.6MiB    0.1%  25.6MiB
     socp_huber_atom        1    503ms    0.1%   503ms   36.5MiB    0.1%  36.5MiB
     socp_geo_mean_...      1    420ms    0.1%   420ms   25.2MiB    0.1%  25.2MiB
     socp_dual_frob...      1    337ms    0.0%   337ms   37.1MiB    0.1%  37.1MiB
     socp_fix_and_f...      1    302ms    0.0%   302ms   20.3MiB    0.1%  20.3MiB
     socp_rational_...      1    201ms    0.0%   201ms   8.91MiB    0.0%  8.91MiB
     socp_sqrt_atom         1   70.1ms    0.0%  70.1ms   1.29MiB    0.0%  1.29MiB
   constant                 1    13.3s    1.8%   13.3s   1.06GiB    3.1%  1.06GiB
     constant_fix!_...      1    4.63s    0.6%   4.63s    304MiB    0.9%   304MiB
     constant_Issue...      1    3.98s    0.5%   3.98s    325MiB    0.9%   325MiB
     constant_Issue...      1    1.39s    0.2%   1.39s   99.0MiB    0.3%  99.0MiB
     constant_fix!_...      1    867ms    0.1%   867ms   61.0MiB    0.2%  61.0MiB
     constant_Test_...      1    437ms    0.1%   437ms   18.4MiB    0.1%  18.4MiB
     constant_fix!_...      1    399ms    0.1%   399ms   21.0MiB    0.1%  21.0MiB
   lp                       1    7.80s    1.0%   7.80s    641MiB    1.8%   641MiB
     lp_dotsort_atom        1    1.22s    0.2%   1.22s   75.8MiB    0.2%  75.8MiB
     lp_sumlargest_...      1    753ms    0.1%   753ms   47.5MiB    0.1%  47.5MiB
     lp_min_atom            1    689ms    0.1%   689ms   37.4MiB    0.1%  37.4MiB
     lp_minimum_atom        1    548ms    0.1%   548ms   39.3MiB    0.1%  39.3MiB
     lp_max_atom            1    527ms    0.1%   527ms   31.9MiB    0.1%  31.9MiB
     lp_sumsmallest...      1    517ms    0.1%   517ms   30.0MiB    0.1%  30.0MiB
     lp_dual_abs_atom       1    387ms    0.1%   387ms   20.6MiB    0.1%  20.6MiB
     lp_neg_atom            1    327ms    0.0%   327ms   19.3MiB    0.1%  19.3MiB
     lp_maximum_atom        1    276ms    0.0%   276ms   13.1MiB    0.0%  13.1MiB
     lp_dual_norm_i...      1    127ms    0.0%   127ms   3.91MiB    0.0%  3.91MiB
     lp_pos_atom            1    121ms    0.0%   121ms   9.05MiB    0.0%  9.05MiB
     lp_dual_norm_1...      1   94.3ms    0.0%  94.3ms   3.84MiB    0.0%  3.84MiB
     lp_hinge_loss_...      1    359μs    0.0%   359μs   57.3KiB    0.0%  57.3KiB
   sdp_and_exp              1    5.71s    0.8%   5.71s    430MiB    1.2%   430MiB
     sdp_and_exp_lo...      1    5.59s    0.7%   5.59s    414MiB    1.2%   414MiB
   exp                      1    5.02s    0.7%   5.02s    376MiB    1.1%   376MiB
     exp_log_atom           1    1.88s    0.3%   1.88s    122MiB    0.3%   122MiB
     exp_entropy_atom       1    563ms    0.1%   563ms   41.5MiB    0.1%  41.5MiB
     exp_log_sum_ex...      1    448ms    0.1%   448ms   31.7MiB    0.1%  31.7MiB
     exp_logistic_l...      1    420ms    0.1%   420ms   16.1MiB    0.0%  16.1MiB
     exp_exp_atom           1    392ms    0.1%   392ms   23.1MiB    0.1%  23.1MiB
     exp_log_perspe...      1    274ms    0.0%   274ms   13.3MiB    0.0%  13.3MiB
     exp_relative_e...      1   75.9ms    0.0%  75.9ms   5.12MiB    0.0%  5.12MiB
 SumOfSquares               1     278s   37.1%    278s   17.0GiB   50.0%  17.0GiB
   socp                     1     116s   15.5%    116s   7.36GiB   21.6%  7.36GiB
     sdsos_term_fixed       1    29.7s    4.0%   29.7s   1.88GiB    5.5%  1.88GiB
     sdsos_horn             1    15.7s    2.1%   15.7s   0.93GiB    2.7%  0.93GiB
     sdsos_concave_...      1    12.5s    1.7%   12.5s    745MiB    2.1%   745MiB
     sdsos_univaria...      1    12.2s    1.6%   12.2s    805MiB    2.3%   805MiB
     sdsos_cheby_un...      1    8.05s    1.1%   8.05s    435MiB    1.2%   435MiB
     sdsos_univaria...      1    6.94s    0.9%   6.94s    375MiB    1.1%   375MiB
     sdsos_options_...      1    5.50s    0.7%   5.50s    206MiB    0.6%   206MiB
     sdsos_scaled_u...      1    5.18s    0.7%   5.18s    277MiB    0.8%   277MiB
     sdsos_term             1    5.13s    0.7%   5.13s    244MiB    0.7%   244MiB
     sdsos_quartic_...      1    4.75s    0.6%   4.75s    236MiB    0.7%   236MiB
     sdsos_quartic_...      1    842ms    0.1%   842ms   26.1MiB    0.1%  26.1MiB
     sdsos_scaled_b...      1   56.8ms    0.0%  56.8ms   5.75MiB    0.0%  5.75MiB
     sdsos_bivariat...      1   17.6ms    0.0%  17.6ms    371KiB    0.0%   371KiB
   sdp                      1     112s   15.0%    112s   6.83GiB   20.1%  6.83GiB
     quartic_ideal_rem      1    8.22s    1.1%   8.22s    549MiB    1.6%   549MiB
     sosdemo5_infea...      1    8.11s    1.1%   8.11s    457MiB    1.3%   457MiB
     rearrangement          1    7.76s    1.0%   7.76s    450MiB    1.3%   450MiB
     sos_options_pr...      1    6.20s    0.8%   6.20s    183MiB    0.5%   183MiB
     sos_concave_th...      1    5.52s    0.7%   5.52s    411MiB    1.2%   411MiB
     sos_horn               1    5.24s    0.7%   5.24s    283MiB    0.8%   283MiB
     simple_matrix          1    4.96s    0.7%   4.96s    370MiB    1.1%   370MiB
     chebyshev              1    4.58s    0.6%   4.58s    252MiB    0.7%   252MiB
     quartic_ideal          1    4.54s    0.6%   4.54s    211MiB    0.6%   211MiB
     sos_term_fixed         1    4.40s    0.6%   4.40s    205MiB    0.6%   205MiB
     sos_scaled_biv...      1    4.33s    0.6%   4.33s    218MiB    0.6%   218MiB
     quartic_ideal_4        1    4.22s    0.6%   4.22s    268MiB    0.8%   268MiB
     sos_cheby_univ...      1    4.10s    0.5%   4.10s    193MiB    0.6%   193MiB
     maxcut                 1    3.61s    0.5%   3.61s    168MiB    0.5%   168MiB
     sos_term               1    3.35s    0.4%   3.35s    175MiB    0.5%   175MiB
     quartic_ideal_...      1    3.22s    0.4%   3.22s    165MiB    0.5%   165MiB
     quartic_feasib...      1    3.16s    0.4%   3.16s    116MiB    0.3%   116MiB
     sos_quartic_co...      1    3.11s    0.4%   3.11s    163MiB    0.5%   163MiB
     BPT12e399_rem          1    2.95s    0.4%   2.95s   79.2MiB    0.2%  79.2MiB
     sosdemo10              1    1.98s    0.3%   1.98s    180MiB    0.5%   180MiB
     sos_univariate...      1    1.77s    0.2%   1.77s    101MiB    0.3%   101MiB
     sos_univariate...      1    1.42s    0.2%   1.42s   35.1MiB    0.1%  35.1MiB
     sosdemo9               1    895ms    0.1%   895ms   49.8MiB    0.1%  49.8MiB
     quadratic_feas...      1    831ms    0.1%   831ms   50.1MiB    0.1%  50.1MiB
     quadratic_infe...      1    749ms    0.1%   749ms   40.7MiB    0.1%  40.7MiB
     choi                   1    671ms    0.1%   671ms   63.6MiB    0.2%  63.6MiB
     BPT12e399_maxd...      1    350ms    0.0%   350ms   8.93MiB    0.0%  8.93MiB
     sos_quartic_co...      1    173ms    0.0%   173ms   21.0MiB    0.1%  21.0MiB
     sosdemo5_feasible      1    168ms    0.0%   168ms   17.4MiB    0.0%  17.4MiB
     motzkin                1   90.8ms    0.0%  90.8ms   4.22MiB    0.0%  4.22MiB
     quartic_infeas...      1   86.0ms    0.0%  86.0ms   1.33MiB    0.0%  1.33MiB
     quartic_ideal_...      1   26.1ms    0.0%  26.1ms   1.02MiB    0.0%  1.02MiB
     sos_bivariate_...      1   12.7ms    0.0%  12.7ms    370KiB    0.0%   370KiB
     sos_scaled_uni...      1   10.2ms    0.0%  10.2ms    368KiB    0.0%   368KiB
     quartic_infeas...      1   6.71ms    0.0%  6.71ms    557KiB    0.0%   557KiB
     quartic_feasib...      1   6.07ms    0.0%  6.07ms    453KiB    0.0%   453KiB
     quadratic_infe...      1   5.98ms    0.0%  5.98ms    531KiB    0.0%   531KiB
     quadratic_feas...      1   5.37ms    0.0%  5.37ms    409KiB    0.0%   409KiB
   lp                       1    49.3s    6.6%   49.3s   2.84GiB    8.3%  2.84GiB
     dsos_options_p...      1    7.18s    1.0%   7.18s    425MiB    1.2%   425MiB
     dsos_concave_t...      1    7.14s    1.0%   7.14s    431MiB    1.2%   431MiB
     dsos_cheby_biv...      1    5.45s    0.7%   5.45s    271MiB    0.8%   271MiB
     dsos_univariat...      1    4.82s    0.6%   4.82s    229MiB    0.7%   229MiB
     dsos_term_fixed        1    4.36s    0.6%   4.36s    213MiB    0.6%   213MiB
     dsos_scaled_bi...      1    4.04s    0.5%   4.04s    206MiB    0.6%   206MiB
     dsos_horn              1    4.00s    0.5%   4.00s    228MiB    0.7%   228MiB
     dsos_term              1    3.82s    0.5%   3.82s    185MiB    0.5%   185MiB
     dsos_quartic_c...      1    3.44s    0.5%   3.44s    171MiB    0.5%   171MiB
     dsos_bivariate...      1    1.05s    0.1%   1.05s   38.4MiB    0.1%  38.4MiB
     dsos_quartic_c...      1    242ms    0.0%   242ms   21.0MiB    0.1%  21.0MiB
     dsos_scaled_un...      1   10.6ms    0.0%  10.6ms    346KiB    0.0%   346KiB
     dsos_univariat...      1   10.4ms    0.0%  10.4ms    345KiB    0.0%   345KiB
     dsos_cheby_uni...      1   9.71ms    0.0%  9.71ms    371KiB    0.0%   371KiB
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
      Status `~/work/ConvexTests.jl/ConvexTests.jl/SCS/Manifest.toml`
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
  [d5909c97] GroupsCore v0.4.0
  [18e54dd8] IntegerMathUtils v0.1.0
  [3587e190] InverseFunctions v0.1.7
  [92d709cd] IrrationalConstants v0.1.1
  [82899510] IteratorInterfaceExtensions v1.0.0
  [692b3bcd] JLLWrappers v1.4.1
  [682c06a0] JSON v0.21.3
  [4076af6c] JuMP v1.1.1
  [40e66cde] LDLFactorizations v0.8.2
  [8ac3fa9e] LRUCache v1.3.0
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
  [21216c6a] Preferences v1.3.0
  [27ebfcd6] Primes v0.5.3
  [fb686558] RandomExtensions v0.4.3
  [189a3867] Reexport v1.2.2
  [ae029012] Requires v1.3.0
  [af85af4c] RowEchelon v0.2.1
  [c946c3f1] SCS v1.1.2
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
  [656ef2d0] OpenBLAS32_jll v0.3.12+1
  [efe28fd5] OpenSpecFun_jll v0.5.5+0
  [af6e375f] SCS_GPU_jll v3.2.0+0
  [f4f2fc5b] SCS_jll v3.2.0+0
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
