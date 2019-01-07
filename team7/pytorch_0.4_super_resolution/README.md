第一個test 100張

python example.py --dir_data /tmp/work/NCTU_DLSR_final_project/dataset/ --model wdsr_b --pre_train ./checkpoint/wdsr_b_best.pt --scale 2 --n_resblocks 16 --n_feats 32 --block_feats 128 --res_scale 0.1 --data_range '1-800/1-100' --test_only --n_threads 4


第二個test 10張

python example.py --dir_data /tmp/work/NCTU_DLSR_final_project/dataset/ --model wdsr_b --pre_train ./checkpoint/wdsr_b_best.pt --scale 2 --n_resblocks 16 --n_feats 32 --block_feats 128 --res_scale 0.1 --test_only --n_threads 4
