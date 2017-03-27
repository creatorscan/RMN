# nn_uni.ndl   -    Unidirectional RMN's
#### Contains 10 layers and these layers are shared thrice to get 30 layers. An extra layer is shared across all 30 layers
* %WER 22.7 | 12643 89979 | 80.0 12.9 7.2 2.7 22.7 52.8 | 11splice_256MB_5skip_1024_right_30l_shared_sp_smbr/decode_eval_it1/ascore_15/eval.ctm.filt.sys
* %WER 25.1 | 12643 89965 | 77.8 14.2 7.9 2.9 25.1 55.4 | 11splice_256MB_5skip_1024_right_30l_shared/decode_eval/ascore_10/eval.ctm.fil    t.sys

# nn_bi.ndl   -    Bidirectional RMN's
#### Contains 15 layers and one extra layer shared across all 15 layers
* %WER 24.0 | 12643 89979 | 78.6 13.5 7.9 2.6 24.0 54.8 | BI_40dim_lr2_rev/decode_eval/ascore_10/eval.ctm.filt.sys
