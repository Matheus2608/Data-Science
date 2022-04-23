Mensagem da primeira iteração

loading annotations into memory...
Done (t=0.05s)
creating index...
index created!
loading annotations into memory...
Done (t=0.01s)
creating index...
index created!
Resuming training, loading weights/yolact_plus_base_54_800000.pth...
Ignoring "Error(s) in loading state_dict for Yolact:
	size mismatch for maskiou_net.maskiou_net.10.weight: copying a param with shape torch.Size([80, 128, 1, 1]) from checkpoint, the shape in current model is torch.Size([7, 128, 1, 1]).
	size mismatch for maskiou_net.maskiou_net.10.bias: copying a param with shape torch.Size([80]) from checkpoint, the shape in current model is torch.Size([7]).
	size mismatch for prediction_layers.0.conf_layer.weight: copying a param with shape torch.Size([729, 256, 3, 3]) from checkpoint, the shape in current model is torch.Size([72, 256, 3, 3]).
	size mismatch for prediction_layers.0.conf_layer.bias: copying a param with shape torch.Size([729]) from checkpoint, the shape in current model is torch.Size([72]).
	size mismatch for semantic_seg_conv.weight: copying a param with shape torch.Size([80, 256, 1, 1]) from checkpoint, the shape in current model is torch.Size([7, 256, 1, 1]).
	size mismatch for semantic_seg_conv.bias: copying a param with shape torch.Size([80]) from checkpoint, the shape in current model is torch.Size([7])."
Begin training!

/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  0]       0 || B: 2.171 | C: 13.125 | M: 3.424 | S: 4.364 | I: 4.270 | T: 27.354 || ETA: 0:00:00 || timer: 4.759

[  0]      10 || B: 2.125 | C: 10.754 | M: 3.363 | S: 3.453 | I: 4.908 | T: 24.604 || ETA: 13 days, 0:48:17 || timer: 1.402

[  0]      20 || B: 1.945 | C: 9.219 | M: 3.079 | S: 2.632 | I: 4.857 | T: 21.732 || ETA: 13 days, 0:27:20 || timer: 1.398

[  0]      30 || B: 1.874 | C: 8.174 | M: 2.869 | S: 2.246 | I: 4.537 | T: 19.700 || ETA: 13 days, 2:39:33 || timer: 1.446

[  0]      40 || B: 1.827 | C: 7.430 | M: 2.788 | S: 1.977 | I: 4.334 | T: 18.356 || ETA: 13 days, 5:33:41 || timer: 1.455

[  0]      50 || B: 1.781 | C: 6.902 | M: 2.746 | S: 1.761 | I: 4.184 | T: 17.374 || ETA: 13 days, 7:56:11 || timer: 1.489

[  0]      60 || B: 1.712 | C: 6.489 | M: 2.672 | S: 1.643 | I: 4.043 | T: 16.558 || ETA: 13 days, 10:45:51 || timer: 1.525

[  0]      70 || B: 1.663 | C: 6.158 | M: 2.585 | S: 1.533 | I: 3.821 | T: 15.761 || ETA: 13 days, 14:08:25 || timer: 1.565

[  0]      80 || B: 1.645 | C: 5.906 | M: 2.554 | S: 1.455 | I: 3.750 | T: 15.312 || ETA: 13 days, 17:53:35 || timer: 1.616

[  0]      90 || B: 1.601 | C: 5.708 | M: 2.512 | S: 1.393 | I: 3.734 | T: 14.948 || ETA: 13 days, 20:31:32 || timer: 1.594

[  0]     100 || B: 1.572 | C: 5.466 | M: 2.469 | S: 1.309 | I: 3.744 | T: 14.559 || ETA: 13 days, 21:46:55 || timer: 1.566

[  0]     110 || B: 1.483 | C: 4.796 | M: 2.367 | S: 1.048 | I: 3.593 | T: 13.287 || ETA: 13 days, 22:56:52 || timer: 1.573

[  0]     120 || B: 1.429 | C: 4.408 | M: 2.302 | S: 0.941 | I: 3.456 | T: 12.536 || ETA: 14 days, 0:00:53 || timer: 1.576

[  0]     130 || B: 1.364 | C: 4.164 | M: 2.241 | S: 0.882 | I: 3.461 | T: 12.112 || ETA: 14 days, 0:59:51 || timer: 1.566

[  0]     140 || B: 1.308 | C: 4.012 | M: 2.179 | S: 0.826 | I: 3.396 | T: 11.720 || ETA: 14 days, 1:57:34 || timer: 1.608

[  0]     150 || B: 1.268 | C: 3.895 | M: 2.123 | S: 0.803 | I: 3.372 | T: 11.462 || ETA: 14 days, 2:42:08 || timer: 1.583

[  0]     160 || B: 1.237 | C: 3.815 | M: 2.074 | S: 0.762 | I: 3.432 | T: 11.321 || ETA: 14 days, 3:20:57 || timer: 1.539

[  0]     170 || B: 1.221 | C: 3.736 | M: 2.073 | S: 0.754 | I: 3.411 | T: 11.195 || ETA: 14 days, 4:04:20 || timer: 1.587

[  0]     180 || B: 1.180 | C: 3.668 | M: 2.064 | S: 0.716 | I: 3.355 | T: 10.983 || ETA: 14 days, 4:22:12 || timer: 1.561
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  1]     190 || B: 1.156 | C: 3.580 | M: 2.033 | S: 0.688 | I: 3.333 | T: 10.790 || ETA: 14 days, 6:27:13 || timer: 1.580

[  1]     200 || B: 1.123 | C: 3.489 | M: 1.997 | S: 0.650 | I: 3.272 | T: 10.531 || ETA: 14 days, 6:39:55 || timer: 1.545

[  1]     210 || B: 1.091 | C: 3.390 | M: 1.919 | S: 0.633 | I: 3.262 | T: 10.296 || ETA: 14 days, 6:58:20 || timer: 1.557

[  1]     220 || B: 1.073 | C: 3.312 | M: 1.878 | S: 0.626 | I: 3.192 | T: 10.081 || ETA: 14 days, 7:23:08 || timer: 1.626

[  1]     230 || B: 1.069 | C: 3.249 | M: 1.891 | S: 0.586 | I: 3.056 | T: 9.851 || ETA: 14 days, 7:33:38 || timer: 1.563

[  1]     240 || B: 1.049 | C: 3.163 | M: 1.876 | S: 0.584 | I: 3.066 | T: 9.737 || ETA: 14 days, 7:41:26 || timer: 1.554

[  1]     250 || B: 1.026 | C: 3.074 | M: 1.850 | S: 0.573 | I: 3.046 | T: 9.569 || ETA: 14 days, 7:41:27 || timer: 1.532

[  1]     260 || B: 1.023 | C: 2.988 | M: 1.846 | S: 0.574 | I: 2.892 | T: 9.324 || ETA: 14 days, 7:48:34 || timer: 1.534

[  1]     270 || B: 0.996 | C: 2.911 | M: 1.809 | S: 0.545 | I: 2.982 | T: 9.244 || ETA: 14 days, 7:58:12 || timer: 1.561

[  1]     280 || B: 0.984 | C: 2.828 | M: 1.767 | S: 0.547 | I: 2.989 | T: 9.115 || ETA: 14 days, 8:04:32 || timer: 1.565

[  1]     290 || B: 1.002 | C: 2.791 | M: 1.769 | S: 0.527 | I: 2.997 | T: 9.086 || ETA: 14 days, 8:11:57 || timer: 1.589

[  1]     300 || B: 1.011 | C: 2.747 | M: 1.774 | S: 0.521 | I: 3.095 | T: 9.147 || ETA: 14 days, 8:18:52 || timer: 1.545

[  1]     310 || B: 1.008 | C: 2.692 | M: 1.761 | S: 0.503 | I: 3.050 | T: 9.015 || ETA: 14 days, 8:26:04 || timer: 1.577

[  1]     320 || B: 0.996 | C: 2.643 | M: 1.750 | S: 0.485 | I: 3.069 | T: 8.943 || ETA: 14 days, 8:32:49 || timer: 1.562

[  1]     330 || B: 0.986 | C: 2.587 | M: 1.709 | S: 0.479 | I: 3.079 | T: 8.840 || ETA: 14 days, 8:44:54 || timer: 1.599

[  1]     340 || B: 0.977 | C: 2.549 | M: 1.680 | S: 0.481 | I: 3.159 | T: 8.846 || ETA: 14 days, 8:51:13 || timer: 1.555

[  1]     350 || B: 0.987 | C: 2.524 | M: 1.685 | S: 0.482 | I: 3.095 | T: 8.772 || ETA: 14 days, 9:00:19 || timer: 1.601

[  1]     360 || B: 0.988 | C: 2.493 | M: 1.692 | S: 0.450 | I: 3.158 | T: 8.781 || ETA: 14 days, 9:03:15 || timer: 1.559
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  2]     370 || B: 0.993 | C: 2.458 | M: 1.692 | S: 0.435 | I: 3.102 | T: 8.680 || ETA: 14 days, 10:09:37 || timer: 1.562

[  2]     380 || B: 0.996 | C: 2.434 | M: 1.679 | S: 0.411 | I: 3.207 | T: 8.729 || ETA: 14 days, 10:12:15 || timer: 1.567

[  2]     390 || B: 0.973 | C: 2.364 | M: 1.637 | S: 0.396 | I: 3.169 | T: 8.539 || ETA: 14 days, 10:16:18 || timer: 1.563

[  2]     400 || B: 0.970 | C: 2.317 | M: 1.610 | S: 0.384 | I: 3.031 | T: 8.312 || ETA: 14 days, 10:22:20 || timer: 1.583

[  2]     410 || B: 0.975 | C: 2.320 | M: 1.620 | S: 0.377 | I: 3.080 | T: 8.371 || ETA: 14 days, 10:23:55 || timer: 1.561

[  2]     420 || B: 0.985 | C: 2.297 | M: 1.621 | S: 0.379 | I: 3.073 | T: 8.354 || ETA: 14 days, 10:28:38 || timer: 1.584

[  2]     430 || B: 0.980 | C: 2.271 | M: 1.615 | S: 0.390 | I: 3.096 | T: 8.351 || ETA: 14 days, 10:31:34 || timer: 1.563

[  2]     440 || B: 0.988 | C: 2.230 | M: 1.611 | S: 0.375 | I: 3.038 | T: 8.242 || ETA: 14 days, 10:33:18 || timer: 1.554

[  2]     450 || B: 0.977 | C: 2.207 | M: 1.582 | S: 0.356 | I: 3.094 | T: 8.216 || ETA: 14 days, 10:35:05 || timer: 1.562

[  2]     460 || B: 0.968 | C: 2.188 | M: 1.577 | S: 0.370 | I: 3.091 | T: 8.193 || ETA: 14 days, 10:38:05 || timer: 1.540

[  2]     470 || B: 0.966 | C: 2.183 | M: 1.575 | S: 0.375 | I: 3.168 | T: 8.266 || ETA: 14 days, 10:44:00 || timer: 1.580

[  2]     480 || B: 0.990 | C: 2.186 | M: 1.611 | S: 0.370 | I: 3.119 | T: 8.275 || ETA: 14 days, 10:45:04 || timer: 1.558

[  2]     490 || B: 0.998 | C: 2.177 | M: 1.615 | S: 0.379 | I: 3.041 | T: 8.209 || ETA: 14 days, 10:47:18 || timer: 1.555

[  2]     500 || B: 0.989 | C: 2.171 | M: 1.627 | S: 0.392 | I: 3.004 | T: 8.183 || ETA: 14 days, 10:50:26 || timer: 1.579

[  2]     510 || B: 0.997 | C: 2.140 | M: 1.621 | S: 0.385 | I: 3.001 | T: 8.144 || ETA: 14 days, 10:52:16 || timer: 1.581

[  2]     520 || B: 1.003 | C: 2.146 | M: 1.621 | S: 0.378 | I: 2.992 | T: 8.140 || ETA: 14 days, 10:52:49 || timer: 1.539

[  2]     530 || B: 1.007 | C: 2.147 | M: 1.631 | S: 0.367 | I: 3.006 | T: 8.158 || ETA: 14 days, 10:53:30 || timer: 1.573

[  2]     540 || B: 1.031 | C: 2.170 | M: 1.660 | S: 0.355 | I: 2.921 | T: 8.138 || ETA: 14 days, 10:53:10 || timer: 1.564

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
    box | 41.14 | 69.80 | 67.26 | 63.69 | 60.37 | 53.24 | 42.26 | 31.36 | 15.78 |  5.91 |  1.75 |
    mask | 40.87 | 60.52 | 57.95 | 57.11 | 56.72 | 53.08 | 44.95 | 36.13 | 26.92 | 11.48 |  3.83 |


/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  3]     550 || B: 1.044 | C: 2.151 | M: 1.657 | S: 0.352 | I: 2.884 | T: 8.087 || ETA: 14 days, 21:33:23 || timer: 1.547

[  3]     560 || B: 1.031 | C: 2.111 | M: 1.624 | S: 0.326 | I: 2.942 | T: 8.035 || ETA: 14 days, 21:24:59 || timer: 1.575

[  3]     570 || B: 1.019 | C: 2.089 | M: 1.587 | S: 0.314 | I: 2.874 | T: 7.882 || ETA: 14 days, 21:13:24 || timer: 1.555

[  3]     580 || B: 0.976 | C: 2.039 | M: 1.512 | S: 0.323 | I: 2.735 | T: 7.585 || ETA: 14 days, 21:04:40 || timer: 1.560

[  3]     590 || B: 0.954 | C: 2.024 | M: 1.515 | S: 0.314 | I: 2.724 | T: 7.531 || ETA: 14 days, 20:54:45 || timer: 1.541

[  3]     600 || B: 0.938 | C: 2.006 | M: 1.481 | S: 0.310 | I: 2.794 | T: 7.528 || ETA: 14 days, 20:47:32 || timer: 1.594

[  3]     610 || B: 0.930 | C: 1.999 | M: 1.465 | S: 0.324 | I: 2.737 | T: 7.456 || ETA: 14 days, 20:38:46 || timer: 1.562

[  3]     620 || B: 0.906 | C: 1.960 | M: 1.446 | S: 0.317 | I: 2.781 | T: 7.409 || ETA: 14 days, 20:30:15 || timer: 1.552

[  3]     630 || B: 0.894 | C: 1.941 | M: 1.416 | S: 0.314 | I: 2.857 | T: 7.422 || ETA: 14 days, 20:21:24 || timer: 1.562

[  3]     640 || B: 0.866 | C: 1.901 | M: 1.392 | S: 0.314 | I: 2.881 | T: 7.354 || ETA: 14 days, 20:14:00 || timer: 1.589

[  3]     650 || B: 0.858 | C: 1.894 | M: 1.398 | S: 0.308 | I: 2.832 | T: 7.290 || ETA: 14 days, 20:05:46 || timer: 1.546

[  3]     660 || B: 0.866 | C: 1.886 | M: 1.399 | S: 0.312 | I: 2.743 | T: 7.205 || ETA: 14 days, 19:59:28 || timer: 1.561

[  3]     670 || B: 0.880 | C: 1.892 | M: 1.419 | S: 0.327 | I: 2.838 | T: 7.356 || ETA: 14 days, 19:51:47 || timer: 1.574

[  3]     680 || B: 0.881 | C: 1.890 | M: 1.423 | S: 0.338 | I: 2.934 | T: 7.466 || ETA: 14 days, 19:41:30 || timer: 1.556

[  3]     690 || B: 0.883 | C: 1.893 | M: 1.403 | S: 0.355 | I: 2.988 | T: 7.521 || ETA: 14 days, 19:32:36 || timer: 1.575

[  3]     700 || B: 0.900 | C: 1.903 | M: 1.426 | S: 0.351 | I: 2.880 | T: 7.459 || ETA: 14 days, 19:27:00 || timer: 1.563

[  3]     710 || B: 0.893 | C: 1.878 | M: 1.423 | S: 0.339 | I: 2.890 | T: 7.424 || ETA: 14 days, 19:19:32 || timer: 1.589

[  3]     720 || B: 0.920 | C: 1.882 | M: 1.443 | S: 0.335 | I: 2.728 | T: 7.307 || ETA: 14 days, 19:12:00 || timer: 1.569
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  4]     730 || B: 0.922 | C: 1.873 | M: 1.462 | S: 0.336 | I: 2.528 | T: 7.121 || ETA: 14 days, 19:31:04 || timer: 1.563

[  4]     740 || B: 0.917 | C: 1.862 | M: 1.445 | S: 0.326 | I: 2.392 | T: 6.942 || ETA: 14 days, 19:25:50 || timer: 1.568

[  4]     750 || B: 0.895 | C: 1.843 | M: 1.426 | S: 0.334 | I: 2.569 | T: 7.068 || ETA: 14 days, 19:20:22 || timer: 1.558

[  4]     760 || B: 0.879 | C: 1.848 | M: 1.421 | S: 0.342 | I: 2.551 | T: 7.042 || ETA: 14 days, 19:14:28 || timer: 1.533

[  4]     770 || B: 0.866 | C: 1.836 | M: 1.415 | S: 0.326 | I: 2.501 | T: 6.943 || ETA: 14 days, 19:08:37 || timer: 1.555

[  4]     780 || B: 0.872 | C: 1.829 | M: 1.421 | S: 0.306 | I: 2.441 | T: 6.869 || ETA: 14 days, 19:02:59 || timer: 1.580

[  4]     790 || B: 0.873 | C: 1.823 | M: 1.432 | S: 0.303 | I: 2.409 | T: 6.840 || ETA: 14 days, 18:57:02 || timer: 1.557

[  4]     800 || B: 0.870 | C: 1.810 | M: 1.417 | S: 0.298 | I: 2.474 | T: 6.870 || ETA: 14 days, 18:51:44 || timer: 1.564

[  4]     810 || B: 0.869 | C: 1.827 | M: 1.425 | S: 0.297 | I: 2.497 | T: 6.914 || ETA: 14 days, 18:46:03 || timer: 1.590

[  4]     820 || B: 0.837 | C: 1.809 | M: 1.391 | S: 0.304 | I: 2.593 | T: 6.934 || ETA: 14 days, 18:39:30 || timer: 1.556

[  4]     830 || B: 0.848 | C: 1.792 | M: 1.390 | S: 0.288 | I: 2.622 | T: 6.939 || ETA: 14 days, 18:33:51 || timer: 1.563

[  4]     840 || B: 0.855 | C: 1.800 | M: 1.399 | S: 0.295 | I: 2.830 | T: 7.179 || ETA: 14 days, 18:29:40 || timer: 1.582

[  4]     850 || B: 0.848 | C: 1.778 | M: 1.385 | S: 0.286 | I: 2.702 | T: 7.000 || ETA: 14 days, 18:25:49 || timer: 1.603

[  4]     860 || B: 0.862 | C: 1.781 | M: 1.378 | S: 0.281 | I: 2.752 | T: 7.053 || ETA: 14 days, 18:20:04 || timer: 1.567

[  4]     870 || B: 0.849 | C: 1.733 | M: 1.364 | S: 0.275 | I: 2.579 | T: 6.800 || ETA: 14 days, 18:15:12 || timer: 1.566

[  4]     880 || B: 0.834 | C: 1.707 | M: 1.336 | S: 0.271 | I: 2.551 | T: 6.700 || ETA: 14 days, 18:11:54 || timer: 1.570

[  4]     890 || B: 0.850 | C: 1.697 | M: 1.328 | S: 0.253 | I: 2.608 | T: 6.735 || ETA: 14 days, 18:07:34 || timer: 1.563

[  4]     900 || B: 0.824 | C: 1.678 | M: 1.321 | S: 0.250 | I: 2.663 | T: 6.736 || ETA: 14 days, 18:02:00 || timer: 1.541

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
    box | 48.37 | 79.80 | 79.68 | 74.48 | 68.44 | 63.92 | 50.64 | 36.19 | 20.06 |  8.84 |  1.66 |
    mask | 50.13 | 68.89 | 67.87 | 66.90 | 63.66 | 61.51 | 57.52 | 50.55 | 40.07 | 17.68 |  6.67 |

/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
Stopping early. Saving network...


---------------------------------------------------------------------------------------------------

loading annotations into memory...
Done (t=0.05s)
creating index...
index created!
loading annotations into memory...
Done (t=0.01s)
creating index...
index created!
Resuming training, loading weights/yolact_plus_base_5_910_interrupt.pth...
Begin training!

/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  5]     910 || B: 0.857 | C: 6.584 | M: 1.156 | S: 1.207 | I: 4.824 | T: 14.627 || ETA: 0:00:00 || timer: 7.214

[  5]     920 || B: 0.769 | C: 4.933 | M: 1.342 | S: 1.321 | I: 3.333 | T: 11.699 || ETA: 36 days, 13:32:16 || timer: 3.979

[  5]     930 || B: 0.735 | C: 3.996 | M: 1.324 | S: 1.075 | I: 3.387 | T: 10.518 || ETA: 36 days, 11:43:51 || timer: 3.958

[  5]     940 || B: 0.735 | C: 3.522 | M: 1.328 | S: 0.934 | I: 3.620 | T: 10.139 || ETA: 36 days, 10:58:46 || timer: 3.882

[  5]     950 || B: 0.728 | C: 3.269 | M: 1.296 | S: 0.813 | I: 3.596 | T: 9.702 || ETA: 36 days, 9:44:49 || timer: 3.927

[  5]     960 || B: 0.745 | C: 3.089 | M: 1.274 | S: 0.758 | I: 3.681 | T: 9.547 || ETA: 36 days, 10:26:29 || timer: 3.887

[  5]     970 || B: 0.748 | C: 2.975 | M: 1.288 | S: 0.699 | I: 3.671 | T: 9.380 || ETA: 36 days, 8:17:16 || timer: 3.903

[  5]     980 || B: 0.747 | C: 2.885 | M: 1.291 | S: 0.666 | I: 3.713 | T: 9.304 || ETA: 36 days, 7:26:25 || timer: 3.900

[  5]     990 || B: 0.749 | C: 2.832 | M: 1.310 | S: 0.662 | I: 3.586 | T: 9.140 || ETA: 36 days, 6:40:31 || timer: 3.934

[  5]    1000 || B: 0.755 | C: 2.758 | M: 1.315 | S: 0.634 | I: 3.600 | T: 9.063 || ETA: 36 days, 6:08:24 || timer: 3.909

[  5]    1010 || B: 0.763 | C: 2.674 | M: 1.310 | S: 0.622 | I: 3.509 | T: 8.879 || ETA: 36 days, 6:04:10 || timer: 3.843

[  5]    1020 || B: 0.767 | C: 2.411 | M: 1.298 | S: 0.527 | I: 3.563 | T: 8.566 || ETA: 36 days, 6:00:00 || timer: 3.957

[  5]    1030 || B: 0.770 | C: 2.312 | M: 1.290 | S: 0.475 | I: 3.629 | T: 8.476 || ETA: 36 days, 6:09:24 || timer: 3.939

[  5]    1040 || B: 0.779 | C: 2.257 | M: 1.283 | S: 0.452 | I: 3.563 | T: 8.333 || ETA: 36 days, 5:49:31 || timer: 3.875

[  5]    1050 || B: 0.779 | C: 2.176 | M: 1.280 | S: 0.445 | I: 3.624 | T: 8.305 || ETA: 36 days, 5:41:18 || timer: 3.893

[  5]    1060 || B: 0.787 | C: 2.167 | M: 1.308 | S: 0.426 | I: 3.592 | T: 8.279 || ETA: 36 days, 5:57:57 || timer: 3.877

[  5]    1070 || B: 0.792 | C: 2.136 | M: 1.320 | S: 0.427 | I: 3.564 | T: 8.240 || ETA: 36 days, 5:47:56 || timer: 3.943

[  5]    1080 || B: 0.796 | C: 2.106 | M: 1.326 | S: 0.414 | I: 3.536 | T: 8.177 || ETA: 36 days, 6:00:38 || timer: 3.908

[  6]    1090 || B: 0.799 | C: 2.041 | M: 1.316 | S: 0.380 | I: 3.656 | T: 8.192 || ETA: 36 days, 8:38:03 || timer: 3.896

[  6]    1100 || B: 0.805 | C: 2.026 | M: 1.323 | S: 0.375 | I: 3.579 | T: 8.107 || ETA: 36 days, 8:19:07 || timer: 3.934

[  6]    1110 || B: 0.790 | C: 1.972 | M: 1.311 | S: 0.352 | I: 3.830 | T: 8.256 || ETA: 36 days, 8:11:41 || timer: 3.894

[  6]    1120 || B: 0.787 | C: 1.947 | M: 1.323 | S: 0.346 | I: 3.762 | T: 8.165 || ETA: 36 days, 8:03:58 || timer: 4.008

[  6]    1130 || B: 0.792 | C: 1.947 | M: 1.337 | S: 0.348 | I: 3.714 | T: 8.137 || ETA: 36 days, 8:01:58 || timer: 3.885

[  6]    1140 || B: 0.779 | C: 1.916 | M: 1.322 | S: 0.339 | I: 3.717 | T: 8.074 || ETA: 36 days, 7:55:04 || timer: 3.872

[  6]    1150 || B: 0.785 | C: 1.924 | M: 1.324 | S: 0.326 | I: 3.652 | T: 8.011 || ETA: 36 days, 7:56:36 || timer: 3.942

[  6]    1160 || B: 0.781 | C: 1.880 | M: 1.306 | S: 0.318 | I: 3.767 | T: 8.052 || ETA: 36 days, 7:48:15 || timer: 3.870

[  6]    1170 || B: 0.781 | C: 1.841 | M: 1.265 | S: 0.302 | I: 3.883 | T: 8.072 || ETA: 36 days, 7:43:51 || timer: 3.902

[  6]    1180 || B: 0.796 | C: 1.819 | M: 1.282 | S: 0.299 | I: 3.742 | T: 7.938 || ETA: 36 days, 7:53:16 || timer: 3.966

[  6]    1190 || B: 0.801 | C: 1.820 | M: 1.286 | S: 0.299 | I: 3.740 | T: 7.945 || ETA: 36 days, 7:46:30 || timer: 3.933

[  6]    1200 || B: 0.785 | C: 1.786 | M: 1.266 | S: 0.290 | I: 3.860 | T: 7.986 || ETA: 36 days, 7:49:55 || timer: 3.910

[  6]    1210 || B: 0.789 | C: 1.803 | M: 1.270 | S: 0.282 | I: 3.564 | T: 7.708 || ETA: 36 days, 7:48:59 || timer: 3.931

[  6]    1220 || B: 0.785 | C: 1.791 | M: 1.256 | S: 0.279 | I: 3.618 | T: 7.728 || ETA: 36 days, 7:45:28 || timer: 3.896

[  6]    1230 || B: 0.783 | C: 1.788 | M: 1.244 | S: 0.274 | I: 3.600 | T: 7.688 || ETA: 36 days, 7:52:21 || timer: 3.894

[  6]    1240 || B: 0.778 | C: 1.804 | M: 1.250 | S: 0.277 | I: 3.650 | T: 7.760 || ETA: 36 days, 7:44:38 || timer: 3.890

[  6]    1250 || B: 0.775 | C: 1.786 | M: 1.251 | S: 0.285 | I: 3.817 | T: 7.915 || ETA: 36 days, 7:51:26 || timer: 3.940

[  6]    1260 || B: 0.766 | C: 1.777 | M: 1.239 | S: 0.292 | I: 3.624 | T: 7.698 || ETA: 36 days, 7:56:43 || timer: 3.925

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
    box | 49.30 | 70.43 | 69.64 | 67.68 | 66.35 | 62.44 | 57.38 | 46.54 | 32.73 | 13.38 |  6.39 |
    mask | 44.28 | 60.19 | 58.86 | 57.91 | 56.45 | 54.32 | 49.59 | 45.53 | 35.73 | 18.83 |  5.34 |

[  7]    1270 || B: 0.754 | C: 1.770 | M: 1.229 | S: 0.290 | I: 3.567 | T: 7.609 || ETA: 38 days, 3:08:08 || timer: 3.869

[  7]    1280 || B: 0.733 | C: 1.743 | M: 1.200 | S: 0.285 | I: 3.746 | T: 7.707 || ETA: 38 days, 1:51:05 || timer: 3.914

[  7]    1290 || B: 0.728 | C: 1.728 | M: 1.189 | S: 0.279 | I: 3.811 | T: 7.735 || ETA: 38 days, 0:43:56 || timer: 3.879

[  7]    1300 || B: 0.727 | C: 1.740 | M: 1.170 | S: 0.276 | I: 3.797 | T: 7.712 || ETA: 37 days, 23:26:31 || timer: 3.938

[  7]    1310 || B: 0.729 | C: 1.721 | M: 1.159 | S: 0.271 | I: 3.805 | T: 7.685 || ETA: 37 days, 22:23:07 || timer: 3.903

[  7]    1320 || B: 0.741 | C: 1.719 | M: 1.171 | S: 0.267 | I: 3.784 | T: 7.683 || ETA: 37 days, 21:20:55 || timer: 3.884

[  7]    1330 || B: 0.750 | C: 1.700 | M: 1.165 | S: 0.260 | I: 3.802 | T: 7.677 || ETA: 37 days, 20:27:17 || timer: 3.957

[  7]    1340 || B: 0.759 | C: 1.686 | M: 1.172 | S: 0.250 | I: 3.733 | T: 7.600 || ETA: 37 days, 19:29:08 || timer: 3.889

[  7]    1350 || B: 0.754 | C: 1.669 | M: 1.166 | S: 0.242 | I: 3.662 | T: 7.493 || ETA: 37 days, 18:32:49 || timer: 3.924

[  7]    1360 || B: 0.766 | C: 1.674 | M: 1.187 | S: 0.237 | I: 3.724 | T: 7.589 || ETA: 37 days, 17:43:49 || timer: 3.930

[  7]    1370 || B: 0.772 | C: 1.676 | M: 1.217 | S: 0.237 | I: 3.760 | T: 7.661 || ETA: 37 days, 16:51:48 || timer: 3.846

[  7]    1380 || B: 0.766 | C: 1.670 | M: 1.215 | S: 0.231 | I: 3.715 | T: 7.598 || ETA: 37 days, 16:05:05 || timer: 3.921

[  7]    1390 || B: 0.753 | C: 1.670 | M: 1.209 | S: 0.228 | I: 3.622 | T: 7.480 || ETA: 37 days, 15:21:40 || timer: 3.922

[  7]    1400 || B: 0.770 | C: 1.647 | M: 1.232 | S: 0.227 | I: 3.678 | T: 7.553 || ETA: 37 days, 14:41:43 || timer: 3.944

[  7]    1410 || B: 0.757 | C: 1.615 | M: 1.240 | S: 0.225 | I: 3.762 | T: 7.598 || ETA: 37 days, 14:06:23 || timer: 3.903

[  7]    1420 || B: 0.745 | C: 1.600 | M: 1.225 | S: 0.227 | I: 3.832 | T: 7.629 || ETA: 37 days, 13:28:34 || timer: 3.927

[  7]    1430 || B: 0.737 | C: 1.596 | M: 1.232 | S: 0.241 | I: 3.743 | T: 7.549 || ETA: 37 days, 12:52:21 || timer: 3.962

[  7]    1440 || B: 0.724 | C: 1.582 | M: 1.221 | S: 0.242 | I: 3.774 | T: 7.544 || ETA: 37 days, 12:19:05 || timer: 3.862
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
/content/yolact/utils/augmentations.py:309: VisibleDeprecationWarning: Creating an ndarray from ragged nested sequences (which is a list-or-tuple of lists-or-tuples-or ndarrays with different lengths or shapes) is deprecated. If you meant to do this, you must specify 'dtype=object' when creating the ndarray.
  mode = random.choice(self.sample_options)
[  8]    1450 || B: 0.722 | C: 1.601 | M: 1.230 | S: 0.242 | I: 3.713 | T: 7.509 || ETA: 37 days, 12:36:48 || timer: 3.957

[  8]    1460 || B: 0.717 | C: 1.574 | M: 1.203 | S: 0.237 | I: 3.733 | T: 7.465 || ETA: 37 days, 12:07:56 || timer: 3.965

[  8]    1470 || B: 0.713 | C: 1.587 | M: 1.199 | S: 0.233 | I: 3.653 | T: 7.385 || ETA: 37 days, 11:30:54 || timer: 3.885

[  8]    1480 || B: 0.726 | C: 1.595 | M: 1.214 | S: 0.232 | I: 3.723 | T: 7.490 || ETA: 37 days, 10:58:04 || timer: 3.862

[  8]    1490 || B: 0.739 | C: 1.600 | M: 1.218 | S: 0.232 | I: 3.669 | T: 7.459 || ETA: 37 days, 10:25:41 || timer: 3.910

[  8]    1500 || B: 0.726 | C: 1.610 | M: 1.202 | S: 0.241 | I: 3.646 | T: 7.426 || ETA: 37 days, 9:53:31 || timer: 3.895

[  8]    1510 || B: 0.734 | C: 1.622 | M: 1.215 | S: 0.247 | I: 3.725 | T: 7.542 || ETA: 37 days, 9:26:26 || timer: 3.969

[  8]    1520 || B: 0.733 | C: 1.615 | M: 1.230 | S: 0.247 | I: 3.704 | T: 7.529 || ETA: 37 days, 8:53:21 || timer: 3.929

[  8]    1530 || B: 0.738 | C: 1.596 | M: 1.225 | S: 0.239 | I: 3.799 | T: 7.596 || ETA: 37 days, 8:24:32 || timer: 3.871

[  8]    1540 || B: 0.760 | C: 1.611 | M: 1.223 | S: 0.232 | I: 3.895 | T: 7.722 || ETA: 37 days, 7:58:51 || timer: 3.921

[  8]    1550 || B: 0.773 | C: 1.620 | M: 1.229 | S: 0.245 | I: 3.743 | T: 7.610 || ETA: 37 days, 7:34:47 || timer: 3.932

[  8]    1560 || B: 0.761 | C: 1.635 | M: 1.229 | S: 0.252 | I: 3.758 | T: 7.634 || ETA: 37 days, 7:13:30 || timer: 3.960

[  8]    1570 || B: 0.768 | C: 1.627 | M: 1.228 | S: 0.251 | I: 3.701 | T: 7.576 || ETA: 37 days, 6:46:29 || timer: 3.911

[  8]    1580 || B: 0.763 | C: 1.626 | M: 1.201 | S: 0.262 | I: 3.565 | T: 7.417 || ETA: 37 days, 6:27:36 || timer: 3.901

[  8]    1590 || B: 0.747 | C: 1.601 | M: 1.170 | S: 0.263 | I: 3.742 | T: 7.523 || ETA: 37 days, 6:08:54 || timer: 3.966

[  8]    1600 || B: 0.752 | C: 1.583 | M: 1.184 | S: 0.257 | I: 3.697 | T: 7.473 || ETA: 37 days, 5:40:01 || timer: 3.894

[  8]    1610 || B: 0.740 | C: 1.560 | M: 1.157 | S: 0.258 | I: 3.733 | T: 7.449 || ETA: 37 days, 5:15:28 || timer: 3.945

[  8]    1620 || B: 0.735 | C: 1.554 | M: 1.141 | S: 0.250 | I: 3.646 | T: 7.327 || ETA: 37 days, 4:50:44 || timer: 3.926

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
    box | 50.16 | 73.89 | 73.05 | 71.07 | 67.70 | 64.11 | 57.71 | 46.55 | 29.31 | 14.78 |  3.46 |
    mask | 46.58 | 63.96 | 61.98 | 61.23 | 59.95 | 56.79 | 52.54 | 47.75 | 38.60 | 20.23 |  2.74 |

[  9]    1630 || B: 0.723 | C: 1.569 | M: 1.121 | S: 0.245 | I: 3.598 | T: 7.256 || ETA: 38 days, 2:05:19 || timer: 3.946
Stopping early. Saving network...


-------------------------------------------------------------
Log file do último treinamento
{"type": "session", "session": 0, "data": {"autoscale": true, "batch_alloc": null, "batch_size": 8, "config": "yolact_plus_base_config", "cuda": true, "dataset": null, "decay": 0.0005, "gamma": 0.1, "interrupt": true, "keep_latest": false, "keep_latest_interval": 100000, "log": true, "log_folder": "logs/", "log_gpu": false, "lr": 0.001, "momentum": 0.9, "num_workers": 4, "resume": "weights/yolact_plus_base_9_1362_interrupt.pth", "save_folder": "weights/", "save_interval": 10000, "start_iter": -1, "validation_epoch": 2, "validation_size": 5000}, "time": 1650728784.6031659}
{"type": "session", "session": 1, "data": {"autoscale": true, "batch_alloc": null, "batch_size": 8, "config": "yolact_plus_base_config", "cuda": true, "dataset": null, "decay": 0.0005, "gamma": 0.1, "interrupt": true, "keep_latest": false, "keep_latest_interval": 100000, "log": true, "log_folder": "logs/", "log_gpu": false, "lr": 0.001, "momentum": 0.9, "num_workers": 4, "resume": "weights/yolact_plus_base_9_1632_interrupt.pth", "save_folder": "weights/", "save_interval": 10000, "start_iter": -1, "validation_epoch": 2, "validation_size": 5000}, "time": 1650728821.4587328}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.53688, "M": 1.02968, "C": 1.84845, "I": 6.8112, "S": 0.11773, "T": 10.34394}, "epoch": 9, "iter": 1632, "lr": 0.001, "elapsed": 6.941524028778076}, "time": 1650728829.3067114}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67217, "M": 1.21934, "C": 1.61043, "I": 0.0401, "S": 0.14081, "T": 3.68285}, "epoch": 9, "iter": 1633, "lr": 0.001, "elapsed": 3.823333740234375}, "time": 1650728833.1300406}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.37643, "M": 1.11489, "C": 0.95663, "I": 2.33591, "S": 0.32753, "T": 5.11139}, "epoch": 9, "iter": 1634, "lr": 0.001, "elapsed": 3.849743127822876}, "time": 1650728836.97971}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.7634, "M": 1.38386, "C": 1.43176, "I": 1.15926, "S": 0.23215, "T": 4.97043}, "epoch": 9, "iter": 1635, "lr": 0.001, "elapsed": 3.8969569206237793}, "time": 1650728840.8767095}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.84842, "M": 1.72798, "C": 1.80241, "I": 4.62361, "S": 0.2571, "T": 9.25952}, "epoch": 9, "iter": 1636, "lr": 0.001, "elapsed": 4.015210866928101}, "time": 1650728844.891889}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.56184, "M": 0.77997, "C": 0.77047, "I": 1.20503, "S": 0.1759, "T": 3.49321}, "epoch": 9, "iter": 1637, "lr": 0.001, "elapsed": 3.8679707050323486}, "time": 1650728848.7598639}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.95309, "M": 1.5438, "C": 2.31737, "I": 0.06013, "S": 0.28145, "T": 5.15584}, "epoch": 9, "iter": 1638, "lr": 0.001, "elapsed": 3.880880355834961}, "time": 1650728852.6407225}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.6494, "M": 1.0283, "C": 1.00594, "I": 3.38714, "S": 0.15426, "T": 6.22504}, "epoch": 9, "iter": 1639, "lr": 0.001, "elapsed": 3.8390986919403076}, "time": 1650728856.479821}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.69618, "M": 0.70772, "C": 1.31771, "I": 4.95605, "S": 0.13272, "T": 7.81038}, "epoch": 9, "iter": 1640, "lr": 0.001, "elapsed": 3.8793883323669434}, "time": 1650728860.359421}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.38585, "M": 0.5478, "C": 1.09986, "I": 7.31085, "S": 0.23981, "T": 9.58416}, "epoch": 9, "iter": 1641, "lr": 0.001, "elapsed": 3.855647325515747}, "time": 1650728864.2148654}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.18641, "M": 2.08224, "C": 1.96826, "I": 4.75161, "S": 0.26499, "T": 10.25352}, "epoch": 9, "iter": 1642, "lr": 0.001, "elapsed": 3.877284526824951}, "time": 1650728868.0921774}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.88299, "M": 1.39912, "C": 1.8801, "I": 3.1387, "S": 0.32094, "T": 7.62185}, "epoch": 9, "iter": 1643, "lr": 0.001, "elapsed": 3.9496090412139893}, "time": 1650728872.0417519}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.46425, "M": 0.88303, "C": 1.98937, "I": 3.02865, "S": 0.20456, "T": 6.56987}, "epoch": 9, "iter": 1644, "lr": 0.001, "elapsed": 3.8700790405273438}, "time": 1650728875.911852}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.74434, "M": 1.02657, "C": 1.1258, "I": 0.05029, "S": 0.26402, "T": 3.21102}, "epoch": 9, "iter": 1645, "lr": 0.001, "elapsed": 3.8617165088653564}, "time": 1650728879.7735543}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.53129, "M": 0.70947, "C": 0.91175, "I": 4.23026, "S": 0.11831, "T": 6.50109}, "epoch": 9, "iter": 1646, "lr": 0.001, "elapsed": 3.844963550567627}, "time": 1650728883.6185136}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.65446, "M": 1.25377, "C": 1.06842, "I": 2.67507, "S": 0.23027, "T": 5.88199}, "epoch": 9, "iter": 1647, "lr": 0.001, "elapsed": 3.863466501235962}, "time": 1650728887.4819827}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.74622, "M": 1.4763, "C": 1.93005, "I": 2.31455, "S": 0.47174, "T": 6.93886}, "epoch": 9, "iter": 1648, "lr": 0.001, "elapsed": 3.8245673179626465}, "time": 1650728891.3065608}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.73612, "M": 0.98629, "C": 1.50514, "I": 2.91596, "S": 0.20902, "T": 6.35253}, "epoch": 9, "iter": 1649, "lr": 0.001, "elapsed": 3.8392832279205322}, "time": 1650728895.1458397}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.75904, "M": 1.4363, "C": 1.66701, "I": 6.51759, "S": 0.21289, "T": 10.59283}, "epoch": 9, "iter": 1650, "lr": 0.001, "elapsed": 3.88472580909729}, "time": 1650728899.0307047}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.80574, "M": 1.22466, "C": 1.65083, "I": 2.82131, "S": 0.1357, "T": 6.63825}, "epoch": 9, "iter": 1651, "lr": 0.001, "elapsed": 3.888747215270996}, "time": 1650728902.9194465}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.17714, "M": 0.80433, "C": 1.90342, "I": 3.96676, "S": 0.27694, "T": 8.12859}, "epoch": 9, "iter": 1652, "lr": 0.001, "elapsed": 3.849229097366333}, "time": 1650728906.7685285}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.53493, "M": 0.92373, "C": 0.86003, "I": 1.98526, "S": 0.13131, "T": 4.43527}, "epoch": 9, "iter": 1653, "lr": 0.001, "elapsed": 3.8280022144317627}, "time": 1650728910.5965285}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.68677, "M": 1.01974, "C": 1.07263, "I": 3.20494, "S": 0.11816, "T": 6.10225}, "epoch": 9, "iter": 1654, "lr": 0.001, "elapsed": 3.845923662185669}, "time": 1650728914.4424686}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.83206, "M": 1.25672, "C": 1.62484, "I": 4.18358, "S": 0.14091, "T": 8.03811}, "epoch": 9, "iter": 1655, "lr": 0.001, "elapsed": 3.875459671020508}, "time": 1650728918.3179226}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.86809, "M": 1.41199, "C": 1.99621, "I": 2.23317, "S": 0.39285, "T": 6.90231}, "epoch": 9, "iter": 1656, "lr": 0.001, "elapsed": 3.8679866790771484}, "time": 1650728922.1859088}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.48511, "M": 0.80187, "C": 1.09514, "I": 6.83731, "S": 0.22027, "T": 9.43971}, "epoch": 9, "iter": 1657, "lr": 0.001, "elapsed": 3.8818447589874268}, "time": 1650728926.0677438}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.5594, "M": 1.11552, "C": 1.28967, "I": 0.04569, "S": 0.15411, "T": 3.16439}, "epoch": 9, "iter": 1658, "lr": 0.001, "elapsed": 3.8696303367614746}, "time": 1650728929.9373848}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.40248, "M": 0.80377, "C": 1.18127, "I": 5.39412, "S": 0.29426, "T": 8.0759}, "epoch": 9, "iter": 1659, "lr": 0.001, "elapsed": 3.8549296855926514}, "time": 1650728933.792314}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.79714, "M": 1.23624, "C": 1.55273, "I": 2.03417, "S": 0.19694, "T": 5.81722}, "epoch": 9, "iter": 1660, "lr": 0.001, "elapsed": 3.8190019130706787}, "time": 1650728937.6116383}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62111, "M": 0.62826, "C": 1.58608, "I": 6.43826, "S": 0.16983, "T": 9.44353}, "epoch": 9, "iter": 1661, "lr": 0.001, "elapsed": 3.86224365234375}, "time": 1650728941.473568}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.98715, "M": 1.38642, "C": 1.33008, "I": 2.62334, "S": 0.26328, "T": 6.59026}, "epoch": 9, "iter": 1662, "lr": 0.001, "elapsed": 3.8364081382751465}, "time": 1650728945.3100643}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.27315, "M": 0.65236, "C": 0.80863, "I": 1.14208, "S": 0.12807, "T": 3.00429}, "epoch": 9, "iter": 1663, "lr": 0.001, "elapsed": 3.8392996788024902}, "time": 1650728949.1492572}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.25622, "M": 1.50457, "C": 1.65797, "I": 3.71818, "S": 0.36747, "T": 8.50441}, "epoch": 9, "iter": 1664, "lr": 0.001, "elapsed": 3.8153579235076904}, "time": 1650728952.9646165}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.30732, "M": 0.94689, "C": 1.24187, "I": 3.54724, "S": 0.1678, "T": 6.21112}, "epoch": 9, "iter": 1665, "lr": 0.001, "elapsed": 3.812919855117798}, "time": 1650728956.7775419}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.00559, "M": 0.95984, "C": 1.46978, "I": 3.72202, "S": 0.15492, "T": 7.31215}, "epoch": 9, "iter": 1666, "lr": 0.001, "elapsed": 3.828447103500366}, "time": 1650728960.6059897}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.08833, "M": 1.08813, "C": 2.46096, "I": 4.40759, "S": 0.46221, "T": 9.50721}, "epoch": 9, "iter": 1667, "lr": 0.001, "elapsed": 3.812715768814087}, "time": 1650728964.4187012}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.49293, "M": 0.75012, "C": 1.44164, "I": 5.29381, "S": 0.1981, "T": 8.1766}, "epoch": 9, "iter": 1668, "lr": 0.001, "elapsed": 3.854717969894409}, "time": 1650728968.2734177}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.88896, "M": 1.4755, "C": 2.1391, "I": 0.07163, "S": 0.28493, "T": 4.86011}, "epoch": 9, "iter": 1669, "lr": 0.001, "elapsed": 3.8436226844787598}, "time": 1650728972.1171412}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.0188, "M": 1.44276, "C": 1.75262, "I": 4.46163, "S": 0.43018, "T": 9.10599}, "epoch": 9, "iter": 1670, "lr": 0.001, "elapsed": 3.868037700653076}, "time": 1650728975.9852352}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.64775, "M": 0.99454, "C": 1.01022, "I": 5.36921, "S": 0.25211, "T": 8.27382}, "epoch": 9, "iter": 1671, "lr": 0.001, "elapsed": 3.861833095550537}, "time": 1650728979.8469586}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.46546, "M": 0.85059, "C": 1.08528, "I": 7.01706, "S": 0.0834, "T": 9.50179}, "epoch": 9, "iter": 1672, "lr": 0.001, "elapsed": 3.8550972938537598}, "time": 1650728983.7020345}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.65658, "M": 0.83445, "C": 1.26176, "I": 6.28565, "S": 0.17802, "T": 9.21646}, "epoch": 9, "iter": 1673, "lr": 0.001, "elapsed": 3.8911712169647217}, "time": 1650728987.593197}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60238, "M": 1.24326, "C": 1.7303, "I": 2.62527, "S": 0.13299, "T": 6.33419}, "epoch": 9, "iter": 1674, "lr": 0.001, "elapsed": 3.866872549057007}, "time": 1650728991.4601004}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.61156, "M": 1.02483, "C": 1.66969, "I": 1.64784, "S": 0.22474, "T": 5.17866}, "epoch": 9, "iter": 1675, "lr": 0.001, "elapsed": 3.85607647895813}, "time": 1650728995.3161602}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.88325, "M": 1.28359, "C": 1.39582, "I": 5.82718, "S": 0.15284, "T": 9.54267}, "epoch": 9, "iter": 1676, "lr": 0.001, "elapsed": 3.899885416030884}, "time": 1650728999.216061}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.59891, "M": 0.73006, "C": 1.03543, "I": 5.19737, "S": 0.08524, "T": 7.64701}, "epoch": 9, "iter": 1677, "lr": 0.001, "elapsed": 3.90382719039917}, "time": 1650729003.119859}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.99652, "M": 1.29616, "C": 1.18836, "I": 3.79974, "S": 0.16471, "T": 7.44548}, "epoch": 9, "iter": 1678, "lr": 0.001, "elapsed": 3.8903300762176514}, "time": 1650729007.010194}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.6642, "M": 1.51608, "C": 1.68764, "I": 1.72766, "S": 0.18652, "T": 5.7821}, "epoch": 9, "iter": 1679, "lr": 0.001, "elapsed": 3.84543514251709}, "time": 1650729010.8556104}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62035, "M": 1.27978, "C": 1.66902, "I": 2.07736, "S": 0.17192, "T": 5.81842}, "epoch": 9, "iter": 1680, "lr": 0.001, "elapsed": 3.890285015106201}, "time": 1650729014.746092}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.42963, "M": 0.6016, "C": 1.88307, "I": 1.14625, "S": 0.1455, "T": 4.20605}, "epoch": 9, "iter": 1681, "lr": 0.001, "elapsed": 3.840700149536133}, "time": 1650729018.5866084}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.1708, "M": 1.40619, "C": 2.27456, "I": 5.86454, "S": 0.14229, "T": 10.85839}, "epoch": 9, "iter": 1682, "lr": 0.001, "elapsed": 3.8384344577789307}, "time": 1650729022.4250586}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.93071, "M": 1.32657, "C": 1.95308, "I": 2.19111, "S": 0.11516, "T": 6.51663}, "epoch": 9, "iter": 1683, "lr": 0.001, "elapsed": 3.888885021209717}, "time": 1650729026.3139622}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.40931, "M": 1.1612, "C": 1.17151, "I": 1.75452, "S": 0.20171, "T": 4.69825}, "epoch": 9, "iter": 1684, "lr": 0.001, "elapsed": 3.834947347640991}, "time": 1650729030.148877}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.48574, "M": 0.94355, "C": 1.20125, "I": 1.34222, "S": 0.10559, "T": 4.07834}, "epoch": 9, "iter": 1685, "lr": 0.001, "elapsed": 3.8102493286132812}, "time": 1650729033.9591284}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.63191, "M": 1.14997, "C": 1.24451, "I": 6.66196, "S": 0.15479, "T": 9.84314}, "epoch": 9, "iter": 1686, "lr": 0.001, "elapsed": 3.824638605117798}, "time": 1650729037.783753}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.31568, "M": 1.43618, "C": 1.94294, "I": 0.07882, "S": 0.1174, "T": 4.89103}, "epoch": 9, "iter": 1687, "lr": 0.001, "elapsed": 3.8139312267303467}, "time": 1650729041.597679}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.35435, "M": 1.57713, "C": 2.12477, "I": 3.35642, "S": 0.14108, "T": 8.55376}, "epoch": 9, "iter": 1688, "lr": 0.001, "elapsed": 3.824666976928711}, "time": 1650729045.4223475}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.86406, "M": 1.26365, "C": 1.81585, "I": 0.07155, "S": 0.15269, "T": 4.16779}, "epoch": 9, "iter": 1689, "lr": 0.001, "elapsed": 3.8125340938568115}, "time": 1650729049.234959}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.80137, "M": 1.16246, "C": 2.73807, "I": 0.89133, "S": 0.50006, "T": 6.0933}, "epoch": 9, "iter": 1690, "lr": 0.001, "elapsed": 3.8501029014587402}, "time": 1650729053.0851707}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.25572, "M": 1.82862, "C": 2.03708, "I": 4.07451, "S": 0.26161, "T": 9.45753}, "epoch": 9, "iter": 1691, "lr": 0.001, "elapsed": 3.860653877258301}, "time": 1650729056.9456465}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.94956, "M": 1.29649, "C": 2.127, "I": 5.41674, "S": 0.17025, "T": 9.96004}, "epoch": 9, "iter": 1692, "lr": 0.001, "elapsed": 3.849156379699707}, "time": 1650729060.794827}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.98499, "M": 1.42615, "C": 1.76888, "I": 2.02179, "S": 0.10158, "T": 6.30338}, "epoch": 9, "iter": 1693, "lr": 0.001, "elapsed": 3.8384692668914795}, "time": 1650729064.633263}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.64243, "M": 0.89082, "C": 1.35842, "I": 2.83579, "S": 0.17172, "T": 5.89917}, "epoch": 9, "iter": 1694, "lr": 0.001, "elapsed": 3.844543218612671}, "time": 1650729068.4778144}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.54872, "M": 1.35396, "C": 2.29456, "I": 2.06934, "S": 0.29557, "T": 6.56216}, "epoch": 9, "iter": 1695, "lr": 0.001, "elapsed": 3.835749387741089}, "time": 1650729072.3135633}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.41776, "M": 0.67697, "C": 1.03011, "I": 2.42044, "S": 0.09656, "T": 4.64184}, "epoch": 9, "iter": 1696, "lr": 0.001, "elapsed": 3.864856481552124}, "time": 1650729076.1784256}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.36182, "M": 0.52461, "C": 1.03793, "I": 5.15097, "S": 0.12068, "T": 7.19602}, "epoch": 9, "iter": 1697, "lr": 0.001, "elapsed": 3.883363723754883}, "time": 1650729080.0617738}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.56661, "M": 0.87126, "C": 1.06615, "I": 0.06246, "S": 0.07821, "T": 2.64469}, "epoch": 9, "iter": 1698, "lr": 0.001, "elapsed": 3.830540418624878}, "time": 1650729083.8923295}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.79409, "M": 1.70662, "C": 2.21954, "I": 2.43435, "S": 0.39407, "T": 7.54866}, "epoch": 9, "iter": 1699, "lr": 0.001, "elapsed": 3.840358257293701}, "time": 1650729087.7328138}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.6764, "M": 0.79372, "C": 1.47932, "I": 5.77457, "S": 0.19808, "T": 8.92209}, "epoch": 9, "iter": 1700, "lr": 0.001, "elapsed": 3.883695602416992}, "time": 1650729091.6165185}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.91519, "M": 1.4128, "C": 1.70812, "I": 2.75419, "S": 0.35799, "T": 7.14828}, "epoch": 9, "iter": 1701, "lr": 0.001, "elapsed": 3.9384331703186035}, "time": 1650729095.5548284}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.4302, "M": 0.6484, "C": 1.25729, "I": 3.38505, "S": 0.19575, "T": 5.9167}, "epoch": 9, "iter": 1702, "lr": 0.001, "elapsed": 3.8414933681488037}, "time": 1650729099.3963175}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.55779, "M": 1.13924, "C": 1.20828, "I": 2.76338, "S": 0.10064, "T": 5.76934}, "epoch": 9, "iter": 1703, "lr": 0.001, "elapsed": 3.870358943939209}, "time": 1650729103.2666678}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.59179, "M": 1.1306, "C": 1.1562, "I": 4.62074, "S": 0.09947, "T": 7.5988}, "epoch": 9, "iter": 1704, "lr": 0.001, "elapsed": 3.8258328437805176}, "time": 1650729107.0924976}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.49913, "M": 0.83773, "C": 1.2797, "I": 4.40037, "S": 0.14918, "T": 7.1661}, "epoch": 9, "iter": 1705, "lr": 0.001, "elapsed": 3.913203477859497}, "time": 1650729111.0056994}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.72701, "M": 1.14602, "C": 1.35329, "I": 3.86694, "S": 0.14292, "T": 7.23617}, "epoch": 9, "iter": 1706, "lr": 0.001, "elapsed": 3.9418790340423584}, "time": 1650729114.947566}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.06455, "M": 1.68998, "C": 1.58882, "I": 4.0297, "S": 0.13891, "T": 8.51197}, "epoch": 9, "iter": 1707, "lr": 0.001, "elapsed": 3.8698222637176514}, "time": 1650729118.8174276}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60694, "M": 1.5188, "C": 1.29155, "I": 5.74046, "S": 0.458, "T": 9.61574}, "epoch": 9, "iter": 1708, "lr": 0.001, "elapsed": 3.83792781829834}, "time": 1650729122.6553218}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.9651, "M": 1.12673, "C": 1.55339, "I": 5.11761, "S": 0.4514, "T": 9.21424}, "epoch": 9, "iter": 1709, "lr": 0.001, "elapsed": 3.8620212078094482}, "time": 1650729126.5173702}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.69461, "M": 0.99648, "C": 1.32403, "I": 7.14089, "S": 0.23156, "T": 10.38757}, "epoch": 9, "iter": 1710, "lr": 0.001, "elapsed": 3.8619775772094727}, "time": 1650729130.3795774}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.77265, "M": 1.12824, "C": 1.90762, "I": 0.83416, "S": 0.37913, "T": 5.02181}, "epoch": 9, "iter": 1711, "lr": 0.001, "elapsed": 3.8518853187561035}, "time": 1650729134.2312112}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.44667, "M": 0.8266, "C": 0.76237, "I": 3.82724, "S": 0.27226, "T": 6.13514}, "epoch": 9, "iter": 1712, "lr": 0.001, "elapsed": 3.897568941116333}, "time": 1650729138.1288483}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58128, "M": 1.21132, "C": 1.55259, "I": 3.07704, "S": 0.24763, "T": 6.66985}, "epoch": 9, "iter": 1713, "lr": 0.001, "elapsed": 3.883439064025879}, "time": 1650729142.0122123}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.78097, "M": 1.15563, "C": 1.14136, "I": 2.17205, "S": 0.20635, "T": 5.45636}, "epoch": 9, "iter": 1714, "lr": 0.001, "elapsed": 3.81390380859375}, "time": 1650729145.8261364}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.61904, "M": 1.09906, "C": 1.2827, "I": 4.69246, "S": 0.29803, "T": 7.99128}, "epoch": 9, "iter": 1715, "lr": 0.001, "elapsed": 3.857933282852173}, "time": 1650729149.684079}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.31268, "M": 1.08831, "C": 1.16571, "I": 2.99457, "S": 0.18491, "T": 5.74618}, "epoch": 9, "iter": 1716, "lr": 0.001, "elapsed": 3.8272781372070312}, "time": 1650729153.5113254}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.54734, "M": 1.46319, "C": 1.28626, "I": 0.14917, "S": 0.4146, "T": 3.86057}, "epoch": 9, "iter": 1717, "lr": 0.001, "elapsed": 3.856523036956787}, "time": 1650729157.3678548}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.5732, "M": 1.04259, "C": 1.22534, "I": 0.05259, "S": 0.19911, "T": 3.09284}, "epoch": 9, "iter": 1718, "lr": 0.001, "elapsed": 3.8437340259552}, "time": 1650729161.2115896}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.77728, "M": 1.20042, "C": 1.52095, "I": 4.05343, "S": 0.72279, "T": 8.27487}, "epoch": 9, "iter": 1719, "lr": 0.001, "elapsed": 3.8675644397735596}, "time": 1650729165.0791688}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62872, "M": 1.08309, "C": 1.78686, "I": 1.57814, "S": 0.39221, "T": 5.46902}, "epoch": 9, "iter": 1720, "lr": 0.001, "elapsed": 3.8445539474487305}, "time": 1650729168.9238968}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.04849, "M": 1.9885, "C": 2.04974, "I": 3.15223, "S": 0.09463, "T": 8.3336}, "epoch": 9, "iter": 1721, "lr": 0.001, "elapsed": 3.8374762535095215}, "time": 1650729172.7611952}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.68278, "M": 1.56844, "C": 1.5928, "I": 4.80573, "S": 0.23583, "T": 8.88558}, "epoch": 9, "iter": 1722, "lr": 0.001, "elapsed": 3.837331533432007}, "time": 1650729176.5985303}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.13255, "M": 1.64261, "C": 1.98992, "I": 3.8443, "S": 0.10051, "T": 8.7099}, "epoch": 9, "iter": 1723, "lr": 0.001, "elapsed": 3.8543355464935303}, "time": 1650729180.4528737}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.00872, "M": 1.25977, "C": 2.7298, "I": 4.61415, "S": 0.81212, "T": 10.42457}, "epoch": 9, "iter": 1724, "lr": 0.001, "elapsed": 3.914182424545288}, "time": 1650729184.367083}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.27616, "M": 0.73155, "C": 1.11272, "I": 2.6551, "S": 0.25197, "T": 5.02751}, "epoch": 9, "iter": 1725, "lr": 0.001, "elapsed": 3.831007242202759}, "time": 1650729188.1980703}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.64164, "M": 1.32627, "C": 1.62483, "I": 2.70279, "S": 0.17091, "T": 6.46644}, "epoch": 9, "iter": 1726, "lr": 0.001, "elapsed": 3.8713133335113525}, "time": 1650729192.0693536}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.34485, "M": 1.79734, "C": 2.09973, "I": 5.1021, "S": 0.12998, "T": 10.47401}, "epoch": 9, "iter": 1727, "lr": 0.001, "elapsed": 3.8741979598999023}, "time": 1650729195.9435477}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58662, "M": 0.91106, "C": 1.56108, "I": 4.24942, "S": 0.29121, "T": 7.59939}, "epoch": 9, "iter": 1728, "lr": 0.001, "elapsed": 3.8334925174713135}, "time": 1650729199.7770767}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.40772, "M": 0.78792, "C": 1.33314, "I": 4.43968, "S": 0.18693, "T": 7.15539}, "epoch": 9, "iter": 1729, "lr": 0.001, "elapsed": 3.849907875061035}, "time": 1650729203.6269794}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.76899, "M": 0.89662, "C": 1.11969, "I": 5.13104, "S": 0.17417, "T": 8.09051}, "epoch": 9, "iter": 1730, "lr": 0.001, "elapsed": 3.870640993118286}, "time": 1650729207.4977398}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.73452, "M": 1.6549, "C": 1.80128, "I": 3.23288, "S": 0.14121, "T": 7.56478}, "epoch": 9, "iter": 1731, "lr": 0.001, "elapsed": 3.904073476791382}, "time": 1650729211.40179}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.50449, "M": 0.81953, "C": 1.01147, "I": 8.5772, "S": 0.14358, "T": 11.05626}, "epoch": 9, "iter": 1732, "lr": 0.001, "elapsed": 3.8414242267608643}, "time": 1650729215.2431066}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.38925, "M": 1.97127, "C": 2.34962, "I": 4.82532, "S": 0.49778, "T": 11.03323}, "epoch": 9, "iter": 1733, "lr": 0.001, "elapsed": 3.840543270111084}, "time": 1650729219.0836334}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.90788, "M": 1.25439, "C": 1.94784, "I": 2.9476, "S": 0.18928, "T": 7.247}, "epoch": 9, "iter": 1734, "lr": 0.001, "elapsed": 3.8294694423675537}, "time": 1650729222.9131246}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.45274, "M": 0.86388, "C": 1.4052, "I": 7.42116, "S": 0.4744, "T": 10.61738}, "epoch": 9, "iter": 1735, "lr": 0.001, "elapsed": 3.903787851333618}, "time": 1650729226.8169346}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.45624, "M": 0.98512, "C": 1.75381, "I": 1.27726, "S": 0.39846, "T": 4.87089}, "epoch": 9, "iter": 1736, "lr": 0.001, "elapsed": 3.8105814456939697}, "time": 1650729230.6274853}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.57248, "M": 1.04019, "C": 1.49537, "I": 4.0668, "S": 0.12681, "T": 7.30164}, "epoch": 9, "iter": 1737, "lr": 0.001, "elapsed": 3.878269672393799}, "time": 1650729234.5057385}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.61279, "M": 0.88808, "C": 1.61576, "I": 3.11462, "S": 0.36718, "T": 6.59843}, "epoch": 9, "iter": 1738, "lr": 0.001, "elapsed": 3.8389930725097656}, "time": 1650729238.3447402}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67485, "M": 0.97767, "C": 1.44078, "I": 1.3654, "S": 0.1536, "T": 4.6123}, "epoch": 9, "iter": 1739, "lr": 0.001, "elapsed": 3.8329946994781494}, "time": 1650729242.1777227}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.11867, "M": 1.48269, "C": 1.52436, "I": 6.38728, "S": 0.15191, "T": 10.66491}, "epoch": 9, "iter": 1740, "lr": 0.001, "elapsed": 3.87713885307312}, "time": 1650729246.0550487}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.11712, "M": 1.13092, "C": 1.96715, "I": 3.52026, "S": 0.12412, "T": 7.85956}, "epoch": 9, "iter": 1741, "lr": 0.001, "elapsed": 3.7995076179504395}, "time": 1650729249.8543816}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58688, "M": 0.83931, "C": 1.34518, "I": 4.12948, "S": 0.22354, "T": 7.12438}, "epoch": 9, "iter": 1742, "lr": 0.001, "elapsed": 3.8689780235290527}, "time": 1650729253.7234488}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.31823, "M": 1.14345, "C": 0.67056, "I": 2.73937, "S": 0.15929, "T": 5.0309}, "epoch": 9, "iter": 1743, "lr": 0.001, "elapsed": 3.808678388595581}, "time": 1650729257.5321016}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.66146, "M": 0.86513, "C": 1.08034, "I": 4.81395, "S": 0.21895, "T": 7.63982}, "epoch": 9, "iter": 1744, "lr": 0.001, "elapsed": 3.83967661857605}, "time": 1650729261.3717225}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.75667, "M": 1.5709, "C": 1.86867, "I": 0.11248, "S": 0.19708, "T": 4.5058}, "epoch": 9, "iter": 1745, "lr": 0.001, "elapsed": 3.810177803039551}, "time": 1650729265.1819007}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.50236, "M": 0.78591, "C": 0.69722, "I": 5.79362, "S": 0.1505, "T": 7.92961}, "epoch": 9, "iter": 1746, "lr": 0.001, "elapsed": 3.835336446762085}, "time": 1650729269.017219}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.9447, "M": 1.06472, "C": 1.45669, "I": 1.10733, "S": 0.19165, "T": 4.76509}, "epoch": 9, "iter": 1747, "lr": 0.001, "elapsed": 3.815692901611328}, "time": 1650729272.8329127}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.47097, "M": 0.92001, "C": 0.92176, "I": 6.15901, "S": 0.25667, "T": 8.72842}, "epoch": 9, "iter": 1748, "lr": 0.001, "elapsed": 3.810255765914917}, "time": 1650729276.643221}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.83104, "M": 1.56023, "C": 1.65499, "I": 3.76731, "S": 0.23405, "T": 8.04762}, "epoch": 9, "iter": 1749, "lr": 0.001, "elapsed": 3.8144946098327637}, "time": 1650729280.4576752}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.71478, "M": 1.00485, "C": 1.80413, "I": 3.70194, "S": 0.62918, "T": 7.85488}, "epoch": 9, "iter": 1750, "lr": 0.001, "elapsed": 3.8445992469787598}, "time": 1650729284.3024755}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.39491, "M": 1.08898, "C": 1.0264, "I": 1.27505, "S": 0.17669, "T": 3.96204}, "epoch": 9, "iter": 1751, "lr": 0.001, "elapsed": 3.8289132118225098}, "time": 1650729288.131177}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.11759, "M": 1.18774, "C": 1.82807, "I": 5.15941, "S": 0.2357, "T": 9.52851}, "epoch": 9, "iter": 1752, "lr": 0.001, "elapsed": 3.856576681137085}, "time": 1650729291.9877636}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.61394, "M": 1.19428, "C": 1.83701, "I": 6.40733, "S": 0.29195, "T": 10.34451}, "epoch": 9, "iter": 1753, "lr": 0.001, "elapsed": 3.8556597232818604}, "time": 1650729295.843425}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.70266, "M": 1.11654, "C": 1.20121, "I": 0.03639, "S": 0.12004, "T": 3.17685}, "epoch": 9, "iter": 1754, "lr": 0.001, "elapsed": 3.813358783721924}, "time": 1650729299.6567888}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.885, "M": 1.03382, "C": 1.47623, "I": 5.20262, "S": 0.25426, "T": 8.85193}, "epoch": 9, "iter": 1755, "lr": 0.001, "elapsed": 3.87355899810791}, "time": 1650729303.5303514}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.10386, "M": 1.69162, "C": 1.78427, "I": 4.39223, "S": 0.10098, "T": 9.07295}, "epoch": 9, "iter": 1756, "lr": 0.001, "elapsed": 3.857041597366333}, "time": 1650729307.3873796}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58808, "M": 0.95818, "C": 1.2782, "I": 3.96709, "S": 0.16453, "T": 6.95608}, "epoch": 9, "iter": 1757, "lr": 0.001, "elapsed": 3.8086578845977783}, "time": 1650729311.196055}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.76699, "M": 1.46065, "C": 1.5805, "I": 2.14394, "S": 0.18012, "T": 6.1322}, "epoch": 9, "iter": 1758, "lr": 0.001, "elapsed": 3.8178889751434326}, "time": 1650729315.0139716}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.57408, "M": 0.9188, "C": 1.73318, "I": 2.41496, "S": 0.17087, "T": 5.81189}, "epoch": 9, "iter": 1759, "lr": 0.001, "elapsed": 3.814279556274414}, "time": 1650729318.8282113}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.57134, "M": 0.78063, "C": 0.97711, "I": 4.39376, "S": 0.10996, "T": 6.83279}, "epoch": 9, "iter": 1760, "lr": 0.001, "elapsed": 3.82151460647583}, "time": 1650729322.6498957}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60785, "M": 1.32315, "C": 1.62099, "I": 4.75284, "S": 0.49556, "T": 8.80038}, "epoch": 9, "iter": 1761, "lr": 0.001, "elapsed": 3.778468370437622}, "time": 1650729326.428212}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.82785, "M": 1.07204, "C": 1.73837, "I": 5.9038, "S": 0.30726, "T": 9.84933}, "epoch": 9, "iter": 1762, "lr": 0.001, "elapsed": 3.7947216033935547}, "time": 1650729330.2229273}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.71871, "M": 0.62452, "C": 1.17898, "I": 6.63823, "S": 0.10325, "T": 9.26369}, "epoch": 9, "iter": 1763, "lr": 0.001, "elapsed": 3.845198154449463}, "time": 1650729334.0681162}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.49249, "M": 0.94219, "C": 1.68672, "I": 4.36516, "S": 0.2158, "T": 7.70237}, "epoch": 9, "iter": 1764, "lr": 0.001, "elapsed": 3.808591365814209}, "time": 1650729337.87676}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.77098, "M": 1.05864, "C": 1.63364, "I": 6.15756, "S": 0.21499, "T": 9.8358}, "epoch": 9, "iter": 1765, "lr": 0.001, "elapsed": 3.830637216567993}, "time": 1650729341.7073407}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.53929, "M": 0.97636, "C": 1.05089, "I": 7.50488, "S": 0.18607, "T": 10.25749}, "epoch": 9, "iter": 1766, "lr": 0.001, "elapsed": 3.829949140548706}, "time": 1650729345.5372894}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67356, "M": 0.81693, "C": 1.24763, "I": 8.18543, "S": 0.1596, "T": 11.08315}, "epoch": 9, "iter": 1767, "lr": 0.001, "elapsed": 3.852558135986328}, "time": 1650729349.3898544}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.6408, "M": 1.17912, "C": 1.37221, "I": 7.07698, "S": 0.1692, "T": 10.43831}, "epoch": 9, "iter": 1768, "lr": 0.001, "elapsed": 3.8199963569641113}, "time": 1650729353.2098343}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.91659, "M": 1.53073, "C": 1.60657, "I": 0.05234, "S": 0.18634, "T": 4.29257}, "epoch": 9, "iter": 1769, "lr": 0.001, "elapsed": 3.8142483234405518}, "time": 1650729357.0241308}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.66288, "M": 1.01694, "C": 0.88334, "I": 5.3288, "S": 0.12452, "T": 8.01648}, "epoch": 9, "iter": 1770, "lr": 0.001, "elapsed": 3.824147939682007}, "time": 1650729360.8484924}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.53537, "M": 0.71318, "C": 1.29175, "I": 5.32582, "S": 0.12684, "T": 7.99295}, "epoch": 9, "iter": 1771, "lr": 0.001, "elapsed": 3.874070644378662}, "time": 1650729364.7223134}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.54919, "M": 0.79531, "C": 1.36379, "I": 7.89967, "S": 0.18955, "T": 10.79751}, "epoch": 9, "iter": 1772, "lr": 0.001, "elapsed": 3.8636536598205566}, "time": 1650729368.5859914}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.92019, "M": 1.34297, "C": 2.04783, "I": 0.62556, "S": 0.11704, "T": 5.05359}, "epoch": 9, "iter": 1773, "lr": 0.001, "elapsed": 3.8235766887664795}, "time": 1650729372.4095259}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.57662, "M": 1.37877, "C": 1.4636, "I": 0.90476, "S": 0.14658, "T": 4.47034}, "epoch": 9, "iter": 1774, "lr": 0.001, "elapsed": 3.86130690574646}, "time": 1650729376.2708535}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.54212, "M": 1.35266, "C": 1.01549, "I": 3.14362, "S": 0.26099, "T": 6.31488}, "epoch": 9, "iter": 1775, "lr": 0.001, "elapsed": 3.790708303451538}, "time": 1650729380.061547}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.52257, "M": 0.7721, "C": 1.04006, "I": 4.59105, "S": 0.12132, "T": 7.0471}, "epoch": 9, "iter": 1776, "lr": 0.001, "elapsed": 3.8106534481048584}, "time": 1650729383.8721988}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.77308, "M": 1.13091, "C": 1.65011, "I": 2.18628, "S": 0.11494, "T": 5.85531}, "epoch": 9, "iter": 1777, "lr": 0.001, "elapsed": 3.866854190826416}, "time": 1650729387.7390776}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.96133, "M": 1.41661, "C": 1.20116, "I": 4.42049, "S": 0.08424, "T": 8.08384}, "epoch": 9, "iter": 1778, "lr": 0.001, "elapsed": 3.843855619430542}, "time": 1650729391.5829546}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.46494, "M": 0.69324, "C": 1.1121, "I": 3.92098, "S": 0.13192, "T": 6.32318}, "epoch": 9, "iter": 1779, "lr": 0.001, "elapsed": 3.8269383907318115}, "time": 1650729395.409849}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62569, "M": 0.96491, "C": 1.60919, "I": 4.78226, "S": 0.41952, "T": 8.40158}, "epoch": 9, "iter": 1780, "lr": 0.001, "elapsed": 3.8432869911193848}, "time": 1650729399.2532814}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.63021, "M": 0.57984, "C": 1.56817, "I": 5.27708, "S": 0.30799, "T": 8.36328}, "epoch": 9, "iter": 1781, "lr": 0.001, "elapsed": 3.821760654449463}, "time": 1650729403.0749125}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.64306, "M": 0.97407, "C": 1.78755, "I": 1.14845, "S": 0.16958, "T": 4.72271}, "epoch": 9, "iter": 1782, "lr": 0.001, "elapsed": 3.8167247772216797}, "time": 1650729406.8916447}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.5637, "M": 1.00013, "C": 1.29529, "I": 0.04871, "S": 0.16124, "T": 3.06908}, "epoch": 9, "iter": 1783, "lr": 0.001, "elapsed": 3.8150534629821777}, "time": 1650729410.7066734}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58117, "M": 1.19165, "C": 1.32667, "I": 3.64741, "S": 0.14756, "T": 6.89446}, "epoch": 9, "iter": 1784, "lr": 0.001, "elapsed": 3.8516907691955566}, "time": 1650729414.5583656}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.48301, "M": 0.89061, "C": 1.04177, "I": 6.60163, "S": 0.11852, "T": 9.13554}, "epoch": 9, "iter": 1785, "lr": 0.001, "elapsed": 3.8322880268096924}, "time": 1650729418.39066}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.82829, "M": 1.31351, "C": 1.89156, "I": 4.16526, "S": 0.17477, "T": 8.37339}, "epoch": 9, "iter": 1786, "lr": 0.001, "elapsed": 3.812626600265503}, "time": 1650729422.203286}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.56154, "M": 0.97734, "C": 1.49788, "I": 0.02724, "S": 0.15916, "T": 3.22316}, "epoch": 9, "iter": 1787, "lr": 0.001, "elapsed": 3.7675540447235107}, "time": 1650729425.9708362}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.44172, "M": 1.25263, "C": 1.4284, "I": 2.33371, "S": 0.24134, "T": 5.69781}, "epoch": 9, "iter": 1788, "lr": 0.001, "elapsed": 3.82745361328125}, "time": 1650729429.7982843}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.92131, "M": 1.25421, "C": 1.35206, "I": 5.19254, "S": 0.33207, "T": 9.0522}, "epoch": 9, "iter": 1789, "lr": 0.001, "elapsed": 3.84836483001709}, "time": 1650729433.6466496}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.90993, "M": 1.26061, "C": 1.74657, "I": 4.03029, "S": 0.13258, "T": 8.07997}, "epoch": 9, "iter": 1790, "lr": 0.001, "elapsed": 3.8270843029022217}, "time": 1650729437.4739227}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.91869, "M": 0.94268, "C": 1.81922, "I": 6.47137, "S": 0.44372, "T": 10.59568}, "epoch": 9, "iter": 1791, "lr": 0.001, "elapsed": 3.808987855911255}, "time": 1650729441.2827313}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.66582, "M": 0.95131, "C": 1.38758, "I": 6.04374, "S": 0.10402, "T": 9.15248}, "epoch": 9, "iter": 1792, "lr": 0.001, "elapsed": 3.869637966156006}, "time": 1650729445.1523993}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.57974, "M": 1.1002, "C": 1.31011, "I": 4.097, "S": 0.32374, "T": 7.41079}, "epoch": 9, "iter": 1793, "lr": 0.001, "elapsed": 3.831490993499756}, "time": 1650729448.983854}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.66344, "M": 0.8944, "C": 1.16049, "I": 4.23298, "S": 0.30302, "T": 7.25433}, "epoch": 9, "iter": 1794, "lr": 0.001, "elapsed": 3.8479678630828857}, "time": 1650729452.8318257}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.01135, "M": 1.21226, "C": 1.70034, "I": 0.05856, "S": 0.14994, "T": 4.13244}, "epoch": 9, "iter": 1795, "lr": 0.001, "elapsed": 3.8044955730438232}, "time": 1650729456.6363378}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.84112, "M": 0.85708, "C": 1.93472, "I": 1.78634, "S": 0.41029, "T": 5.82955}, "epoch": 9, "iter": 1796, "lr": 0.001, "elapsed": 3.817247152328491}, "time": 1650729460.4535725}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.13115, "M": 1.33742, "C": 1.77124, "I": 3.56907, "S": 0.21228, "T": 8.02116}, "epoch": 9, "iter": 1797, "lr": 0.001, "elapsed": 3.8181512355804443}, "time": 1650729464.27172}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.50236, "M": 1.15858, "C": 1.18324, "I": 2.78262, "S": 0.08932, "T": 5.71612}, "epoch": 9, "iter": 1798, "lr": 0.001, "elapsed": 3.7804245948791504}, "time": 1650729468.0521657}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.89133, "M": 1.18537, "C": 1.37781, "I": 4.59196, "S": 0.09998, "T": 8.14645}, "epoch": 9, "iter": 1799, "lr": 0.001, "elapsed": 3.8635342121124268}, "time": 1650729471.9156754}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.637, "M": 1.13588, "C": 1.30149, "I": 4.39077, "S": 0.18121, "T": 7.64634}, "epoch": 9, "iter": 1800, "lr": 0.001, "elapsed": 3.807481050491333}, "time": 1650729475.723317}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62282, "M": 0.88718, "C": 1.21533, "I": 4.98207, "S": 0.07556, "T": 7.78296}, "epoch": 9, "iter": 1801, "lr": 0.001, "elapsed": 3.808138608932495}, "time": 1650729479.531299}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.75359, "M": 1.38697, "C": 1.2613, "I": 2.1467, "S": 0.12221, "T": 5.67077}, "epoch": 9, "iter": 1802, "lr": 0.001, "elapsed": 3.8155741691589355}, "time": 1650729483.3468897}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.8331, "M": 1.10684, "C": 1.43997, "I": 3.70343, "S": 0.21971, "T": 7.30305}, "epoch": 9, "iter": 1803, "lr": 0.001, "elapsed": 3.816356897354126}, "time": 1650729487.1632235}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.63946, "M": 0.86713, "C": 1.01041, "I": 7.17296, "S": 0.1426, "T": 9.83256}, "epoch": 9, "iter": 1804, "lr": 0.001, "elapsed": 3.8435041904449463}, "time": 1650729491.0067272}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60089, "M": 1.74432, "C": 1.55476, "I": 5.66409, "S": 0.32081, "T": 9.88487}, "epoch": 9, "iter": 1805, "lr": 0.001, "elapsed": 3.827378273010254}, "time": 1650729494.8341494}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.51619, "M": 0.64463, "C": 1.30678, "I": 4.13709, "S": 0.31194, "T": 6.91663}, "epoch": 9, "iter": 1806, "lr": 0.001, "elapsed": 3.8385677337646484}, "time": 1650729498.6726768}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.35704, "M": 0.85341, "C": 0.85358, "I": 4.19671, "S": 0.117, "T": 6.37775}, "epoch": 9, "iter": 1807, "lr": 0.001, "elapsed": 3.8167436122894287}, "time": 1650729502.489447}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60519, "M": 0.72229, "C": 1.34666, "I": 4.89808, "S": 0.18746, "T": 7.75968}, "epoch": 9, "iter": 1808, "lr": 0.001, "elapsed": 3.814218044281006}, "time": 1650729506.3036397}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.08935, "M": 1.61263, "C": 1.9416, "I": 0.89317, "S": 0.16467, "T": 5.70142}, "epoch": 9, "iter": 1809, "lr": 0.001, "elapsed": 3.8182532787323}, "time": 1650729510.1218944}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62566, "M": 1.07397, "C": 1.38947, "I": 2.69554, "S": 0.17532, "T": 5.95995}, "epoch": 10, "iter": 1810, "lr": 0.001, "elapsed": 5.7572407722473145}, "time": 1650729515.8793623}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.81374, "M": 1.56398, "C": 2.02353, "I": 5.82546, "S": 0.24283, "T": 10.46955}, "epoch": 10, "iter": 1811, "lr": 0.001, "elapsed": 3.8647336959838867}, "time": 1650729519.7438805}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.65779, "M": 0.83682, "C": 1.57976, "I": 7.31781, "S": 0.28897, "T": 10.68114}, "epoch": 10, "iter": 1812, "lr": 0.001, "elapsed": 3.8478500843048096}, "time": 1650729523.591717}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.1788, "M": 1.44599, "C": 1.59568, "I": 4.04022, "S": 0.0977, "T": 8.35839}, "epoch": 10, "iter": 1813, "lr": 0.001, "elapsed": 3.828941583633423}, "time": 1650729527.4206572}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.8329, "M": 1.39104, "C": 1.69178, "I": 0.12005, "S": 0.24708, "T": 4.28285}, "epoch": 10, "iter": 1814, "lr": 0.001, "elapsed": 3.8196096420288086}, "time": 1650729531.2403035}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.51459, "M": 1.14945, "C": 1.47065, "I": 3.01277, "S": 0.16843, "T": 6.31588}, "epoch": 10, "iter": 1815, "lr": 0.001, "elapsed": 3.857210874557495}, "time": 1650729535.0975034}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.93195, "M": 1.31163, "C": 1.99987, "I": 5.03496, "S": 0.30988, "T": 9.58828}, "epoch": 10, "iter": 1816, "lr": 0.001, "elapsed": 3.88070011138916}, "time": 1650729538.9781957}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.68194, "M": 1.29874, "C": 1.34785, "I": 5.68641, "S": 0.27289, "T": 9.28783}, "epoch": 10, "iter": 1817, "lr": 0.001, "elapsed": 3.8267054557800293}, "time": 1650729542.8048825}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.47241, "M": 1.38719, "C": 1.66902, "I": 0.05129, "S": 0.46071, "T": 4.04062}, "epoch": 10, "iter": 1818, "lr": 0.001, "elapsed": 3.7939698696136475}, "time": 1650729546.5988605}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.3026, "M": 2.17639, "C": 2.32023, "I": 2.2098, "S": 0.18078, "T": 8.1898}, "epoch": 10, "iter": 1819, "lr": 0.001, "elapsed": 3.8422904014587402}, "time": 1650729550.4412796}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.94978, "M": 1.11057, "C": 1.90816, "I": 3.70468, "S": 0.22475, "T": 7.89793}, "epoch": 10, "iter": 1820, "lr": 0.001, "elapsed": 3.827760934829712}, "time": 1650729554.269088}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.68398, "M": 1.06349, "C": 1.11065, "I": 4.86988, "S": 0.10643, "T": 7.83442}, "epoch": 10, "iter": 1821, "lr": 0.001, "elapsed": 3.870938777923584}, "time": 1650729558.139884}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60251, "M": 1.02077, "C": 1.47096, "I": 2.41499, "S": 0.08562, "T": 5.59485}, "epoch": 10, "iter": 1822, "lr": 0.001, "elapsed": 3.8341360092163086}, "time": 1650729561.9740875}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.48272, "M": 0.5596, "C": 1.01994, "I": 6.76993, "S": 0.1084, "T": 8.94059}, "epoch": 10, "iter": 1823, "lr": 0.001, "elapsed": 3.8405280113220215}, "time": 1650729565.81451}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67891, "M": 0.88445, "C": 1.37012, "I": 3.65381, "S": 0.23192, "T": 6.8192}, "epoch": 10, "iter": 1824, "lr": 0.001, "elapsed": 3.8907816410064697}, "time": 1650729569.7053225}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.51242, "M": 0.7504, "C": 1.2163, "I": 6.31945, "S": 0.15826, "T": 8.95683}, "epoch": 10, "iter": 1825, "lr": 0.001, "elapsed": 3.850640296936035}, "time": 1650729573.5559716}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58575, "M": 1.01065, "C": 1.41624, "I": 2.89277, "S": 0.21619, "T": 6.12159}, "epoch": 10, "iter": 1826, "lr": 0.001, "elapsed": 3.8381831645965576}, "time": 1650729577.394137}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.63315, "M": 0.83955, "C": 1.5085, "I": 3.94496, "S": 0.20952, "T": 7.13569}, "epoch": 10, "iter": 1827, "lr": 0.001, "elapsed": 3.820425271987915}, "time": 1650729581.2145376}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.6014, "M": 1.13494, "C": 1.89488, "I": 1.07744, "S": 0.18958, "T": 4.89824}, "epoch": 10, "iter": 1828, "lr": 0.001, "elapsed": 3.8130950927734375}, "time": 1650729585.0276372}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.74896, "M": 0.88489, "C": 1.31002, "I": 4.62203, "S": 0.11559, "T": 7.6815}, "epoch": 10, "iter": 1829, "lr": 0.001, "elapsed": 3.820699453353882}, "time": 1650729588.8483484}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.70203, "M": 1.23307, "C": 1.60873, "I": 1.68118, "S": 0.24416, "T": 5.46916}, "epoch": 10, "iter": 1830, "lr": 0.001, "elapsed": 3.7990176677703857}, "time": 1650729592.6475508}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.4915, "M": 0.84309, "C": 1.38249, "I": 8.69039, "S": 0.1833, "T": 11.59077}, "epoch": 10, "iter": 1831, "lr": 0.001, "elapsed": 3.8416895866394043}, "time": 1650729596.4890862}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67784, "M": 0.7189, "C": 1.25853, "I": 5.01951, "S": 0.24429, "T": 7.91906}, "epoch": 10, "iter": 1832, "lr": 0.001, "elapsed": 3.845254898071289}, "time": 1650729600.3343055}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.51364, "M": 0.93919, "C": 1.32176, "I": 0.02382, "S": 0.43162, "T": 3.23004}, "epoch": 10, "iter": 1833, "lr": 0.001, "elapsed": 3.814995050430298}, "time": 1650729604.1493046}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67488, "M": 1.26493, "C": 1.65797, "I": 3.04581, "S": 0.43081, "T": 7.07441}, "epoch": 10, "iter": 1834, "lr": 0.001, "elapsed": 3.8571629524230957}, "time": 1650729608.0064654}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.72072, "M": 0.93951, "C": 1.63846, "I": 0.91253, "S": 0.17885, "T": 4.39007}, "epoch": 10, "iter": 1835, "lr": 0.001, "elapsed": 3.813347339630127}, "time": 1650729611.8198054}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.67182, "M": 1.00163, "C": 1.68621, "I": 3.14246, "S": 0.2175, "T": 6.71962}, "epoch": 10, "iter": 1836, "lr": 0.001, "elapsed": 3.8432836532592773}, "time": 1650729615.6631098}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.5159, "M": 1.09183, "C": 1.0649, "I": 4.44093, "S": 0.1442, "T": 7.25775}, "epoch": 10, "iter": 1837, "lr": 0.001, "elapsed": 3.8326916694641113}, "time": 1650729619.495789}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.74739, "M": 0.96292, "C": 1.07816, "I": 6.1487, "S": 0.21894, "T": 9.15612}, "epoch": 10, "iter": 1838, "lr": 0.001, "elapsed": 3.825035572052002}, "time": 1650729623.3208172}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.16815, "M": 1.33918, "C": 2.22969, "I": 2.99263, "S": 0.37945, "T": 8.10911}, "epoch": 10, "iter": 1839, "lr": 0.001, "elapsed": 3.839273452758789}, "time": 1650729627.1601067}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.73379, "M": 0.98328, "C": 1.21213, "I": 5.14076, "S": 0.21373, "T": 8.28369}, "epoch": 10, "iter": 1840, "lr": 0.001, "elapsed": 3.78863263130188}, "time": 1650729630.9488783}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.6483, "M": 0.85197, "C": 1.39682, "I": 5.92396, "S": 0.14109, "T": 8.96214}, "epoch": 10, "iter": 1841, "lr": 0.001, "elapsed": 3.843243360519409}, "time": 1650729634.7919943}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.9253, "M": 1.10373, "C": 1.59117, "I": 1.93738, "S": 0.11004, "T": 5.66762}, "epoch": 10, "iter": 1842, "lr": 0.001, "elapsed": 3.8168997764587402}, "time": 1650729638.6088767}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.68118, "M": 0.98584, "C": 1.9106, "I": 4.01733, "S": 0.2741, "T": 7.86905}, "epoch": 10, "iter": 1843, "lr": 0.001, "elapsed": 3.808258533477783}, "time": 1650729642.4171407}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.81724, "M": 1.14994, "C": 1.49267, "I": 3.8853, "S": 0.2823, "T": 7.62745}, "epoch": 10, "iter": 1844, "lr": 0.001, "elapsed": 3.840123414993286}, "time": 1650729646.2572756}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.71627, "M": 0.93384, "C": 1.99509, "I": 4.03848, "S": 0.23602, "T": 7.91969}, "epoch": 10, "iter": 1845, "lr": 0.001, "elapsed": 3.819828748703003}, "time": 1650729650.077091}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.40989, "M": 1.04042, "C": 0.98111, "I": 0.08809, "S": 0.1255, "T": 2.64501}, "epoch": 10, "iter": 1846, "lr": 0.001, "elapsed": 3.7972769737243652}, "time": 1650729653.8743591}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.47276, "M": 0.93248, "C": 1.05452, "I": 3.92972, "S": 0.16588, "T": 6.55536}, "epoch": 10, "iter": 1847, "lr": 0.001, "elapsed": 3.8146164417266846}, "time": 1650729657.688991}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.61899, "M": 1.30033, "C": 1.69253, "I": 0.05203, "S": 0.09345, "T": 3.75733}, "epoch": 10, "iter": 1848, "lr": 0.001, "elapsed": 3.849835157394409}, "time": 1650729661.5388403}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.87277, "M": 1.66529, "C": 1.34042, "I": 2.5825, "S": 0.13317, "T": 6.59416}, "epoch": 10, "iter": 1849, "lr": 0.001, "elapsed": 3.8482251167297363}, "time": 1650729665.3870547}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.06598, "M": 1.67667, "C": 1.97944, "I": 3.52649, "S": 0.21438, "T": 8.46295}, "epoch": 10, "iter": 1850, "lr": 0.001, "elapsed": 3.871687173843384}, "time": 1650729669.2588475}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.3461, "M": 0.58252, "C": 1.00501, "I": 6.96488, "S": 0.14291, "T": 9.04141}, "epoch": 10, "iter": 1851, "lr": 0.001, "elapsed": 3.85396409034729}, "time": 1650729673.1126702}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.32722, "M": 0.61774, "C": 0.85053, "I": 7.39365, "S": 0.15595, "T": 9.3451}, "epoch": 10, "iter": 1852, "lr": 0.001, "elapsed": 3.8173367977142334}, "time": 1650729676.9300416}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.65293, "M": 1.13009, "C": 1.21796, "I": 6.15601, "S": 0.14291, "T": 9.29991}, "epoch": 10, "iter": 1853, "lr": 0.001, "elapsed": 3.8111917972564697}, "time": 1650729680.741205}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.59141, "M": 0.77749, "C": 1.00627, "I": 4.25535, "S": 0.15828, "T": 6.7888}, "epoch": 10, "iter": 1854, "lr": 0.001, "elapsed": 3.862837314605713}, "time": 1650729684.6040452}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.90389, "M": 1.27353, "C": 1.68515, "I": 0.05903, "S": 0.29651, "T": 4.2181}, "epoch": 10, "iter": 1855, "lr": 0.001, "elapsed": 3.7817068099975586}, "time": 1650729688.3857465}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.62474, "M": 1.02702, "C": 1.30003, "I": 5.1198, "S": 0.0888, "T": 8.16038}, "epoch": 10, "iter": 1856, "lr": 0.001, "elapsed": 3.850680112838745}, "time": 1650729692.2364514}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.73412, "M": 0.92465, "C": 1.44238, "I": 5.85216, "S": 0.16996, "T": 9.12327}, "epoch": 10, "iter": 1857, "lr": 0.001, "elapsed": 3.875887393951416}, "time": 1650729696.1123524}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60563, "M": 1.42224, "C": 1.67039, "I": 4.25885, "S": 0.13364, "T": 8.09075}, "epoch": 10, "iter": 1858, "lr": 0.001, "elapsed": 3.8503475189208984}, "time": 1650729699.9626548}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.75081, "M": 1.1804, "C": 1.42035, "I": 5.64913, "S": 0.27014, "T": 9.27081}, "epoch": 10, "iter": 1859, "lr": 0.001, "elapsed": 3.851077079772949}, "time": 1650729703.813743}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.45252, "M": 0.80266, "C": 1.07788, "I": 5.02507, "S": 0.11413, "T": 7.47226}, "epoch": 10, "iter": 1860, "lr": 0.001, "elapsed": 3.8449418544769287}, "time": 1650729707.6588578}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.59476, "M": 1.06709, "C": 1.4692, "I": 3.60658, "S": 0.13475, "T": 6.87237}, "epoch": 10, "iter": 1861, "lr": 0.001, "elapsed": 3.8507816791534424}, "time": 1650729711.5094802}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.76329, "M": 1.5848, "C": 1.57347, "I": 1.183, "S": 0.14373, "T": 5.24829}, "epoch": 10, "iter": 1862, "lr": 0.001, "elapsed": 3.7911040782928467}, "time": 1650729715.3005788}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.55903, "M": 1.05108, "C": 1.55556, "I": 1.91734, "S": 0.30443, "T": 5.38744}, "epoch": 10, "iter": 1863, "lr": 0.001, "elapsed": 3.8202528953552246}, "time": 1650729719.1208184}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.36423, "M": 1.0565, "C": 0.65273, "I": 5.52972, "S": 0.10483, "T": 7.70801}, "epoch": 10, "iter": 1864, "lr": 0.001, "elapsed": 3.8078596591949463}, "time": 1650729722.9286745}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.33646, "M": 1.07184, "C": 1.19351, "I": 2.83955, "S": 0.18398, "T": 5.62534}, "epoch": 10, "iter": 1865, "lr": 0.001, "elapsed": 3.8112220764160156}, "time": 1650729726.7399197}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.31052, "M": 0.99973, "C": 0.74076, "I": 0.03283, "S": 0.14279, "T": 2.22663}, "epoch": 10, "iter": 1866, "lr": 0.001, "elapsed": 3.779029607772827}, "time": 1650729730.5189552}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.68993, "M": 1.18852, "C": 1.65328, "I": 4.14552, "S": 0.18371, "T": 7.86097}, "epoch": 10, "iter": 1867, "lr": 0.001, "elapsed": 3.818950653076172}, "time": 1650729734.337894}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58134, "M": 0.80627, "C": 1.03071, "I": 5.51401, "S": 0.09416, "T": 8.02649}, "epoch": 10, "iter": 1868, "lr": 0.001, "elapsed": 3.82532000541687}, "time": 1650729738.1632228}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.79571, "M": 1.70098, "C": 1.90666, "I": 0.12369, "S": 0.22351, "T": 4.75055}, "epoch": 10, "iter": 1869, "lr": 0.001, "elapsed": 3.857858657836914}, "time": 1650729742.0210876}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.58516, "M": 0.83169, "C": 1.73438, "I": 4.73553, "S": 0.19326, "T": 8.08002}, "epoch": 10, "iter": 1870, "lr": 0.001, "elapsed": 3.813204526901245}, "time": 1650729745.8345323}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.9447, "M": 1.33998, "C": 1.5549, "I": 2.12769, "S": 0.1408, "T": 6.10807}, "epoch": 10, "iter": 1871, "lr": 0.001, "elapsed": 3.8588740825653076}, "time": 1650729749.6931527}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.86708, "M": 1.44199, "C": 1.52478, "I": 3.69627, "S": 0.0859, "T": 7.61602}, "epoch": 10, "iter": 1872, "lr": 0.001, "elapsed": 3.813281536102295}, "time": 1650729753.5064237}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.41013, "M": 0.69957, "C": 0.73282, "I": 7.79846, "S": 0.24042, "T": 9.8814}, "epoch": 10, "iter": 1873, "lr": 0.001, "elapsed": 3.860827922821045}, "time": 1650729757.367278}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.38265, "M": 0.8436, "C": 1.34417, "I": 3.53871, "S": 0.16823, "T": 6.27736}, "epoch": 10, "iter": 1874, "lr": 0.001, "elapsed": 3.8166630268096924}, "time": 1650729761.1839576}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.63845, "M": 1.12277, "C": 1.17817, "I": 6.76987, "S": 0.11525, "T": 9.82452}, "epoch": 10, "iter": 1875, "lr": 0.001, "elapsed": 3.8683202266693115}, "time": 1650729765.0522408}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.85365, "M": 1.73243, "C": 1.64845, "I": 1.58944, "S": 0.43796, "T": 6.26194}, "epoch": 10, "iter": 1876, "lr": 0.001, "elapsed": 3.879040002822876}, "time": 1650729768.9312754}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.75018, "M": 1.33026, "C": 1.66527, "I": 3.86149, "S": 0.20753, "T": 7.81472}, "epoch": 10, "iter": 1877, "lr": 0.001, "elapsed": 3.8040530681610107}, "time": 1650729772.7353249}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.66068, "M": 1.06641, "C": 1.76044, "I": 4.06861, "S": 0.15629, "T": 7.71243}, "epoch": 10, "iter": 1878, "lr": 0.001, "elapsed": 3.8251349925994873}, "time": 1650729776.5604708}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.40098, "M": 0.61809, "C": 0.72942, "I": 2.92876, "S": 0.12951, "T": 4.80677}, "epoch": 10, "iter": 1879, "lr": 0.001, "elapsed": 3.827773094177246}, "time": 1650729780.3882945}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.95824, "M": 1.61706, "C": 1.96716, "I": 2.99946, "S": 0.18669, "T": 7.72861}, "epoch": 10, "iter": 1880, "lr": 0.001, "elapsed": 3.9020700454711914}, "time": 1650729784.2904525}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.46741, "M": 0.85958, "C": 0.98508, "I": 1.03008, "S": 0.12856, "T": 3.47072}, "epoch": 10, "iter": 1881, "lr": 0.001, "elapsed": 3.9311938285827637}, "time": 1650729788.221581}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.70081, "M": 1.06178, "C": 1.5363, "I": 1.96003, "S": 0.29758, "T": 5.55649}, "epoch": 10, "iter": 1882, "lr": 0.001, "elapsed": 3.8419694900512695}, "time": 1650729792.0634654}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.66261, "M": 0.86328, "C": 1.31159, "I": 3.35925, "S": 0.09988, "T": 6.29661}, "epoch": 10, "iter": 1883, "lr": 0.001, "elapsed": 3.8686928749084473}, "time": 1650729795.932186}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.70033, "M": 1.49576, "C": 1.78946, "I": 0.06639, "S": 0.28346, "T": 4.33541}, "epoch": 10, "iter": 1884, "lr": 0.001, "elapsed": 3.8047542572021484}, "time": 1650729799.7369335}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.77786, "M": 0.97805, "C": 1.2659, "I": 2.48863, "S": 0.09369, "T": 5.60413}, "epoch": 10, "iter": 1885, "lr": 0.001, "elapsed": 3.886988878250122}, "time": 1650729803.6238995}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.72948, "M": 0.85854, "C": 1.25339, "I": 3.7681, "S": 0.20868, "T": 6.81819}, "epoch": 10, "iter": 1886, "lr": 0.001, "elapsed": 3.8467438220977783}, "time": 1650729807.470647}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.89151, "M": 1.37033, "C": 1.76937, "I": 4.76381, "S": 0.10647, "T": 8.90149}, "epoch": 10, "iter": 1887, "lr": 0.001, "elapsed": 3.8629279136657715}, "time": 1650729811.3335726}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.59473, "M": 1.06336, "C": 1.18495, "I": 8.64217, "S": 0.14354, "T": 11.62876}, "epoch": 10, "iter": 1888, "lr": 0.001, "elapsed": 3.8330917358398438}, "time": 1650729815.1666899}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.01879, "M": 0.96881, "C": 1.75129, "I": 3.8389, "S": 0.14268, "T": 7.72046}, "epoch": 10, "iter": 1889, "lr": 0.001, "elapsed": 3.8320937156677246}, "time": 1650729818.9987736}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.60994, "M": 1.07778, "C": 1.48507, "I": 3.20593, "S": 0.16333, "T": 6.54206}, "epoch": 10, "iter": 1890, "lr": 0.001, "elapsed": 3.808856248855591}, "time": 1650729822.807757}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.46806, "M": 0.75487, "C": 1.16543, "I": 3.88952, "S": 0.21608, "T": 6.49396}, "epoch": 10, "iter": 1891, "lr": 0.001, "elapsed": 3.8313217163085938}, "time": 1650729826.6389692}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.50732, "M": 0.7633, "C": 1.03709, "I": 2.92602, "S": 0.34002, "T": 5.57375}, "epoch": 10, "iter": 1892, "lr": 0.001, "elapsed": 3.8010947704315186}, "time": 1650729830.440223}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.63407, "M": 0.98104, "C": 1.42799, "I": 3.0265, "S": 0.16426, "T": 6.23387}, "epoch": 10, "iter": 1893, "lr": 0.001, "elapsed": 3.8366096019744873}, "time": 1650729834.2766457}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.50339, "M": 1.06013, "C": 0.97325, "I": 0.02787, "S": 0.26973, "T": 2.83436}, "epoch": 10, "iter": 1894, "lr": 0.001, "elapsed": 3.824617862701416}, "time": 1650729838.1012857}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.81524, "M": 1.03446, "C": 1.4172, "I": 3.58234, "S": 0.20023, "T": 7.04946}, "epoch": 10, "iter": 1895, "lr": 0.001, "elapsed": 3.8138458728790283}, "time": 1650729841.9151244}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.34301, "M": 0.92156, "C": 1.12591, "I": 1.81516, "S": 0.18831, "T": 4.39395}, "epoch": 10, "iter": 1896, "lr": 0.001, "elapsed": 3.8565587997436523}, "time": 1650729845.7717798}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.88838, "M": 2.65725, "C": 1.89578, "I": 0.51117, "S": 0.35421, "T": 6.30679}, "epoch": 10, "iter": 1897, "lr": 0.001, "elapsed": 3.8055787086486816}, "time": 1650729849.577257}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.84146, "M": 1.16936, "C": 1.31669, "I": 0.90744, "S": 0.1221, "T": 4.35706}, "epoch": 10, "iter": 1898, "lr": 0.001, "elapsed": 3.932249069213867}, "time": 1650729853.5097015}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.55688, "M": 1.03839, "C": 1.42552, "I": 4.59398, "S": 0.10813, "T": 7.7229}, "epoch": 10, "iter": 1899, "lr": 0.001, "elapsed": 3.885376453399658}, "time": 1650729857.394871}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.88386, "M": 1.31265, "C": 2.42216, "I": 1.02083, "S": 0.23865, "T": 5.87814}, "epoch": 10, "iter": 1900, "lr": 0.001, "elapsed": 3.8035902976989746}, "time": 1650729861.1985912}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.79131, "M": 1.20679, "C": 1.38549, "I": 2.70997, "S": 0.11133, "T": 6.2049}, "epoch": 10, "iter": 1901, "lr": 0.001, "elapsed": 3.815838575363159}, "time": 1650729865.0143855}
{"type": "train", "session": 1, "data": {"loss": {"B": 1.1183, "M": 1.55084, "C": 2.20209, "I": 3.16289, "S": 0.24053, "T": 8.27464}, "epoch": 10, "iter": 1902, "lr": 0.001, "elapsed": 3.805905342102051}, "time": 1650729868.820204}
{"type": "train", "session": 1, "data": {"loss": {"B": 0.77493, "M": 0.84478, "C": 1.75305, "I": 6.2173, "S": 0.24779, "T": 9.83785}, "epoch": 10, "iter": 1903, "lr": 0.001, "elapsed": 3.851733684539795}, "time": 1650729872.6719754}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.44111, "M": 0.74121, "C": 0.98125, "I": 7.42698, "S": 0.10707, "T": 9.69762}, "epoch": 10, "iter": 1904, "lr": 0.001, "elapsed": 3.8504722118377686}, "time": 1650729876.5225174}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.81978, "M": 1.27316, "C": 1.52855, "I": 2.47994, "S": 0.27265, "T": 6.37409}, "epoch": 10, "iter": 1905, "lr": 0.001, "elapsed": 3.821892738342285}, "time": 1650729880.3443532}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.33907, "M": 0.96278, "C": 1.36081, "I": 0.1122, "S": 0.13148, "T": 2.90634}, "epoch": 10, "iter": 1906, "lr": 0.001, "elapsed": 3.8002123832702637}, "time": 1650729884.144528}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.29788, "M": 0.75287, "C": 1.35694, "I": 3.88699, "S": 0.16331, "T": 6.45799}, "epoch": 10, "iter": 1907, "lr": 0.001, "elapsed": 3.855613946914673}, "time": 1650729888.0002365}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.72775, "M": 1.15007, "C": 1.47736, "I": 4.36287, "S": 0.15957, "T": 7.87763}, "epoch": 10, "iter": 1908, "lr": 0.001, "elapsed": 3.971891164779663}, "time": 1650729891.9720738}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.58312, "M": 0.93745, "C": 1.18262, "I": 7.52222, "S": 0.2476, "T": 10.473}, "epoch": 10, "iter": 1909, "lr": 0.001, "elapsed": 3.9005579948425293}, "time": 1650729895.872578}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.54791, "M": 0.89767, "C": 1.38845, "I": 3.07918, "S": 0.2232, "T": 6.13641}, "epoch": 10, "iter": 1910, "lr": 0.001, "elapsed": 3.8742802143096924}, "time": 1650729899.7470334}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.13767, "M": 1.68178, "C": 1.90187, "I": 3.46178, "S": 0.06817, "T": 8.25128}, "epoch": 10, "iter": 1911, "lr": 0.001, "elapsed": 3.8315720558166504}, "time": 1650729903.578456}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.37208, "M": 0.81115, "C": 1.09846, "I": 3.31617, "S": 0.13464, "T": 5.7325}, "epoch": 10, "iter": 1912, "lr": 0.001, "elapsed": 3.8270201683044434}, "time": 1650729907.4055495}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.98628, "M": 1.39369, "C": 1.47094, "I": 2.96911, "S": 0.39129, "T": 7.21131}, "epoch": 10, "iter": 1913, "lr": 0.001, "elapsed": 3.8558719158172607}, "time": 1650729911.2613182}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.47149, "M": 1.38757, "C": 1.13835, "I": 3.02625, "S": 0.27415, "T": 6.29781}, "epoch": 10, "iter": 1914, "lr": 0.001, "elapsed": 3.845529794692993}, "time": 1650729915.1068583}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.74906, "M": 1.01556, "C": 1.81128, "I": 4.61264, "S": 0.25712, "T": 8.44565}, "epoch": 10, "iter": 1915, "lr": 0.001, "elapsed": 3.8384289741516113}, "time": 1650729918.9452906}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.70232, "M": 1.11259, "C": 1.58081, "I": 2.69064, "S": 0.11942, "T": 6.20578}, "epoch": 10, "iter": 1916, "lr": 0.001, "elapsed": 3.873417854309082}, "time": 1650729922.8187819}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.3781, "M": 0.79943, "C": 1.16968, "I": 1.73276, "S": 0.0876, "T": 4.16757}, "epoch": 10, "iter": 1917, "lr": 0.001, "elapsed": 3.8480710983276367}, "time": 1650729926.6668782}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.54012, "M": 1.23114, "C": 1.53718, "I": 1.12536, "S": 0.14544, "T": 4.57925}, "epoch": 10, "iter": 1918, "lr": 0.001, "elapsed": 3.8058078289031982}, "time": 1650729930.4726546}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.4773, "M": 1.15456, "C": 1.01211, "I": 2.45693, "S": 0.19197, "T": 5.29288}, "epoch": 10, "iter": 1919, "lr": 0.001, "elapsed": 3.8439340591430664}, "time": 1650729934.316526}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.45097, "M": 0.91827, "C": 0.9358, "I": 6.12242, "S": 0.17752, "T": 8.60498}, "epoch": 10, "iter": 1920, "lr": 0.001, "elapsed": 3.8955202102661133}, "time": 1650729938.2122211}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.24569, "M": 1.81458, "C": 2.37814, "I": 4.00413, "S": 0.3248, "T": 9.76734}, "epoch": 10, "iter": 1921, "lr": 0.001, "elapsed": 3.8670804500579834}, "time": 1650729942.0791252}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.4432, "M": 0.95911, "C": 1.35937, "I": 1.07371, "S": 0.22782, "T": 4.06321}, "epoch": 10, "iter": 1922, "lr": 0.001, "elapsed": 3.8160622119903564}, "time": 1650729945.8952086}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.28711, "M": 0.59183, "C": 0.86402, "I": 1.61314, "S": 0.305, "T": 3.6611}, "epoch": 10, "iter": 1923, "lr": 0.001, "elapsed": 3.840116500854492}, "time": 1650729949.735311}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.50495, "M": 0.54962, "C": 1.07803, "I": 7.5712, "S": 0.14068, "T": 9.84449}, "epoch": 10, "iter": 1924, "lr": 0.001, "elapsed": 3.9100449085235596}, "time": 1650729953.6453903}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.45009, "M": 0.66183, "C": 0.76942, "I": 7.87988, "S": 0.16692, "T": 9.92815}, "epoch": 10, "iter": 1925, "lr": 0.001, "elapsed": 3.855868339538574}, "time": 1650729957.5012105}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.81167, "M": 0.83852, "C": 1.78533, "I": 3.99792, "S": 0.18999, "T": 7.62343}, "epoch": 10, "iter": 1926, "lr": 0.001, "elapsed": 3.8359947204589844}, "time": 1650729961.3372085}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.36505, "M": 0.7622, "C": 0.9977, "I": 1.40243, "S": 0.12759, "T": 3.65497}, "epoch": 10, "iter": 1927, "lr": 0.001, "elapsed": 3.978092670440674}, "time": 1650729965.3152957}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.47774, "M": 0.78128, "C": 1.51448, "I": 7.06814, "S": 0.20291, "T": 10.04454}, "epoch": 10, "iter": 1928, "lr": 0.001, "elapsed": 3.883877754211426}, "time": 1650729969.1991725}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.3183, "M": 0.71704, "C": 0.44326, "I": 3.17909, "S": 0.24298, "T": 4.90067}, "epoch": 10, "iter": 1929, "lr": 0.001, "elapsed": 3.8226146697998047}, "time": 1650729973.0218112}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.6159, "M": 0.87459, "C": 1.24559, "I": 6.93959, "S": 0.09523, "T": 9.77089}, "epoch": 10, "iter": 1930, "lr": 0.001, "elapsed": 3.8528292179107666}, "time": 1650729976.8747597}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.08076, "M": 1.29794, "C": 1.39775, "I": 4.35465, "S": 0.10506, "T": 8.23615}, "epoch": 10, "iter": 1931, "lr": 0.001, "elapsed": 3.811210870742798}, "time": 1650729980.6858282}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.48557, "M": 0.44062, "C": 0.93989, "I": 6.35793, "S": 0.09163, "T": 8.31563}, "epoch": 10, "iter": 1932, "lr": 0.001, "elapsed": 3.810939073562622}, "time": 1650729984.496756}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.74961, "M": 1.00604, "C": 1.75637, "I": 5.93739, "S": 0.26794, "T": 9.71734}, "epoch": 10, "iter": 1933, "lr": 0.001, "elapsed": 3.8364782333374023}, "time": 1650729988.3332698}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.47399, "M": 0.60628, "C": 1.35135, "I": 3.54178, "S": 0.19054, "T": 6.16393}, "epoch": 10, "iter": 1934, "lr": 0.001, "elapsed": 3.849839687347412}, "time": 1650729992.1831207}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.67311, "M": 0.80529, "C": 1.14373, "I": 5.17668, "S": 0.11411, "T": 7.91293}, "epoch": 10, "iter": 1935, "lr": 0.001, "elapsed": 3.813504695892334}, "time": 1650729995.996587}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.39317, "M": 0.78979, "C": 1.34276, "I": 0.60737, "S": 0.20807, "T": 3.34116}, "epoch": 10, "iter": 1936, "lr": 0.001, "elapsed": 3.8620026111602783}, "time": 1650729999.858613}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.39925, "M": 0.6814, "C": 1.04103, "I": 6.14292, "S": 0.12337, "T": 8.38797}, "epoch": 10, "iter": 1937, "lr": 0.001, "elapsed": 3.8341362476348877}, "time": 1650730003.692732}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.01119, "M": 1.31402, "C": 1.53551, "I": 2.42099, "S": 0.14872, "T": 6.43043}, "epoch": 10, "iter": 1938, "lr": 0.001, "elapsed": 3.8291561603546143}, "time": 1650730007.5219035}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.80392, "M": 0.78275, "C": 1.17211, "I": 3.33536, "S": 0.16359, "T": 6.25772}, "epoch": 10, "iter": 1939, "lr": 0.001, "elapsed": 3.820443630218506}, "time": 1650730011.3423295}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.6329, "M": 0.85954, "C": 1.42159, "I": 6.80332, "S": 0.10639, "T": 9.82374}, "epoch": 10, "iter": 1940, "lr": 0.001, "elapsed": 3.832979679107666}, "time": 1650730015.1756065}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.34539, "M": 1.09954, "C": 1.3881, "I": 3.59342, "S": 0.32466, "T": 6.75111}, "epoch": 10, "iter": 1941, "lr": 0.001, "elapsed": 3.7900984287261963}, "time": 1650730018.9654183}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.97467, "M": 1.17683, "C": 1.32651, "I": 3.27986, "S": 0.24129, "T": 6.99916}, "epoch": 10, "iter": 1942, "lr": 0.001, "elapsed": 3.8041977882385254}, "time": 1650730022.7696035}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.8817, "M": 1.3531, "C": 1.76697, "I": 2.71502, "S": 0.26462, "T": 6.98141}, "epoch": 10, "iter": 1943, "lr": 0.001, "elapsed": 3.8415112495422363}, "time": 1650730026.6111488}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.97645, "M": 1.15843, "C": 1.46702, "I": 3.92541, "S": 0.13194, "T": 7.65925}, "epoch": 10, "iter": 1944, "lr": 0.001, "elapsed": 3.777069568634033}, "time": 1650730030.3881896}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.64842, "M": 1.19413, "C": 1.37881, "I": 6.23818, "S": 0.1037, "T": 9.56325}, "epoch": 10, "iter": 1945, "lr": 0.001, "elapsed": 3.803806781768799}, "time": 1650730034.192052}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.88791, "M": 1.13738, "C": 1.90963, "I": 2.71825, "S": 0.09, "T": 6.74317}, "epoch": 10, "iter": 1946, "lr": 0.001, "elapsed": 3.818202257156372}, "time": 1650730038.010202}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.46639, "M": 1.20814, "C": 0.99453, "I": 1.39208, "S": 0.19494, "T": 4.25609}, "epoch": 10, "iter": 1947, "lr": 0.001, "elapsed": 3.8497538566589355}, "time": 1650730041.8601222}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.62607, "M": 1.01109, "C": 1.4126, "I": 1.9651, "S": 0.20822, "T": 5.22307}, "epoch": 10, "iter": 1948, "lr": 0.001, "elapsed": 3.8676297664642334}, "time": 1650730045.7275712}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.86805, "M": 1.2327, "C": 2.3484, "I": 0.05574, "S": 0.23279, "T": 4.73769}, "epoch": 10, "iter": 1949, "lr": 0.001, "elapsed": 3.837017774581909}, "time": 1650730049.564689}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.539, "M": 0.5025, "C": 1.18684, "I": 1.28628, "S": 0.12227, "T": 3.63689}, "epoch": 10, "iter": 1950, "lr": 0.001, "elapsed": 3.8216025829315186}, "time": 1650730053.386325}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.84166, "M": 1.10994, "C": 1.43373, "I": 6.45415, "S": 0.08491, "T": 9.9244}, "epoch": 10, "iter": 1951, "lr": 0.001, "elapsed": 3.9244139194488525}, "time": 1650730057.3106742}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.7176, "M": 1.77397, "C": 1.96107, "I": 3.65245, "S": 0.29829, "T": 8.40338}, "epoch": 10, "iter": 1952, "lr": 0.001, "elapsed": 3.849863290786743}, "time": 1650730061.1604981}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.8279, "M": 1.0944, "C": 1.71762, "I": 6.357, "S": 0.24327, "T": 10.24019}, "epoch": 10, "iter": 1953, "lr": 0.001, "elapsed": 3.8394503593444824}, "time": 1650730064.9999576}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.87994, "M": 0.86508, "C": 1.63615, "I": 7.67882, "S": 0.1462, "T": 11.20619}, "epoch": 10, "iter": 1954, "lr": 0.001, "elapsed": 3.8460636138916016}, "time": 1650730068.8459842}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.77034, "M": 1.10096, "C": 2.12883, "I": 1.02875, "S": 0.14494, "T": 5.17382}, "epoch": 10, "iter": 1955, "lr": 0.001, "elapsed": 3.796088218688965}, "time": 1650730072.642077}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.7571, "M": 1.09103, "C": 1.54232, "I": 3.95378, "S": 0.10699, "T": 7.45122}, "epoch": 10, "iter": 1956, "lr": 0.001, "elapsed": 3.8323380947113037}, "time": 1650730076.4744225}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.55873, "M": 0.72397, "C": 1.04337, "I": 6.02166, "S": 0.14426, "T": 8.49199}, "epoch": 10, "iter": 1957, "lr": 0.001, "elapsed": 3.8471269607543945}, "time": 1650730080.3215446}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.55702, "M": 0.81055, "C": 1.20171, "I": 3.76449, "S": 0.13073, "T": 6.4645}, "epoch": 10, "iter": 1958, "lr": 0.001, "elapsed": 3.8231217861175537}, "time": 1650730084.1446662}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.3905, "M": 0.74168, "C": 1.03651, "I": 4.4689, "S": 0.20546, "T": 6.84304}, "epoch": 10, "iter": 1959, "lr": 0.001, "elapsed": 3.7980287075042725}, "time": 1650730087.942703}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.46911, "M": 1.02412, "C": 1.33853, "I": 0.47508, "S": 0.2186, "T": 3.52544}, "epoch": 10, "iter": 1960, "lr": 0.001, "elapsed": 3.7918167114257812}, "time": 1650730091.7346668}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.62275, "M": 1.48957, "C": 1.61158, "I": 3.57533, "S": 0.13301, "T": 7.43224}, "epoch": 10, "iter": 1961, "lr": 0.001, "elapsed": 3.875628709793091}, "time": 1650730095.610153}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.84758, "M": 1.68607, "C": 2.09294, "I": 1.91311, "S": 0.10731, "T": 6.64701}, "epoch": 10, "iter": 1962, "lr": 0.001, "elapsed": 3.833130359649658}, "time": 1650730099.4432878}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.47752, "M": 0.86613, "C": 1.32631, "I": 6.03728, "S": 0.21254, "T": 8.91978}, "epoch": 10, "iter": 1963, "lr": 0.001, "elapsed": 3.8488693237304688}, "time": 1650730103.2921853}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.93125, "M": 1.53182, "C": 1.78231, "I": 0.16416, "S": 0.14144, "T": 4.55099}, "epoch": 10, "iter": 1964, "lr": 0.001, "elapsed": 3.8124241828918457}, "time": 1650730107.1045554}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.19971, "M": 2.19909, "C": 1.40786, "I": 3.58877, "S": 0.07254, "T": 8.46797}, "epoch": 10, "iter": 1965, "lr": 0.001, "elapsed": 3.8328092098236084}, "time": 1650730110.9373863}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.30012, "M": 0.38246, "C": 0.83125, "I": 5.68191, "S": 0.08659, "T": 7.28233}, "epoch": 10, "iter": 1966, "lr": 0.001, "elapsed": 3.7858927249908447}, "time": 1650730114.72326}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.83235, "M": 1.21186, "C": 1.05801, "I": 4.75114, "S": 0.10004, "T": 7.95339}, "epoch": 10, "iter": 1967, "lr": 0.001, "elapsed": 3.81656813621521}, "time": 1650730118.5398307}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.63043, "M": 1.44164, "C": 1.0285, "I": 0.06514, "S": 0.12906, "T": 3.29476}, "epoch": 10, "iter": 1968, "lr": 0.001, "elapsed": 3.797635793685913}, "time": 1650730122.3374796}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.87202, "M": 1.11155, "C": 1.0965, "I": 4.48378, "S": 0.23215, "T": 7.79599}, "epoch": 10, "iter": 1969, "lr": 0.001, "elapsed": 3.8552937507629395}, "time": 1650730126.1927562}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.93009, "M": 1.69945, "C": 1.39153, "I": 7.43153, "S": 0.17103, "T": 11.62363}, "epoch": 10, "iter": 1970, "lr": 0.001, "elapsed": 3.8416240215301514}, "time": 1650730130.0345688}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.94724, "M": 1.33704, "C": 1.59844, "I": 3.56848, "S": 0.21802, "T": 7.66922}, "epoch": 10, "iter": 1971, "lr": 0.001, "elapsed": 3.849661111831665}, "time": 1650730133.8840744}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.68116, "M": 1.2157, "C": 2.03051, "I": 1.05378, "S": 0.13228, "T": 5.11343}, "epoch": 10, "iter": 1972, "lr": 0.001, "elapsed": 3.794945240020752}, "time": 1650730137.679045}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.7165, "M": 1.08808, "C": 1.55052, "I": 8.51616, "S": 0.13168, "T": 12.00293}, "epoch": 10, "iter": 1973, "lr": 0.001, "elapsed": 3.8766326904296875}, "time": 1650730141.5556264}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.92325, "M": 1.27113, "C": 1.90702, "I": 4.13966, "S": 0.24677, "T": 8.48784}, "epoch": 10, "iter": 1974, "lr": 0.001, "elapsed": 3.8969671726226807}, "time": 1650730145.4526036}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.5567, "M": 0.9466, "C": 1.24067, "I": 2.37649, "S": 0.22153, "T": 5.34199}, "epoch": 10, "iter": 1975, "lr": 0.001, "elapsed": 3.8316643238067627}, "time": 1650730149.2842543}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.64926, "M": 0.77121, "C": 0.81444, "I": 1.18847, "S": 0.07124, "T": 3.49463}, "epoch": 10, "iter": 1976, "lr": 0.001, "elapsed": 3.784609794616699}, "time": 1650730153.0688758}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.0229, "M": 1.78083, "C": 1.90513, "I": 2.60034, "S": 0.10452, "T": 7.41372}, "epoch": 10, "iter": 1977, "lr": 0.001, "elapsed": 3.839595079421997}, "time": 1650730156.908484}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.50581, "M": 0.77236, "C": 1.04528, "I": 3.15759, "S": 0.16286, "T": 5.64391}, "epoch": 10, "iter": 1978, "lr": 0.001, "elapsed": 3.8639559745788574}, "time": 1650730160.772426}

{"type": "train", "session": 1, "data": {"loss": {"B": 1.08527, "M": 1.04653, "C": 1.81589, "I": 4.04147, "S": 0.3562, "T": 8.34537}, "epoch": 10, "iter": 1979, "lr": 0.001, "elapsed": 3.856473922729492}, "time": 1650730164.628905}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.76814, "M": 1.14679, "C": 1.44595, "I": 0.05148, "S": 0.12769, "T": 3.54005}, "epoch": 10, "iter": 1980, "lr": 0.001, "elapsed": 3.8353524208068848}, "time": 1650730168.4644072}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.62412, "M": 1.83107, "C": 0.92592, "I": 2.84922, "S": 0.51099, "T": 6.74132}, "epoch": 10, "iter": 1981, "lr": 0.001, "elapsed": 3.8100321292877197}, "time": 1650730172.274278}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.46424, "M": 0.66138, "C": 1.14247, "I": 8.38299, "S": 0.32719, "T": 10.97827}, "epoch": 10, "iter": 1982, "lr": 0.001, "elapsed": 3.817039966583252}, "time": 1650730176.091326}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.54668, "M": 0.82137, "C": 0.73881, "I": 5.4061, "S": 0.10431, "T": 7.61727}, "epoch": 10, "iter": 1983, "lr": 0.001, "elapsed": 3.8158059120178223}, "time": 1650730179.9071493}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.90506, "M": 0.95619, "C": 1.53251, "I": 3.60091, "S": 0.14246, "T": 7.13713}, "epoch": 10, "iter": 1984, "lr": 0.001, "elapsed": 3.843662738800049}, "time": 1650730183.75079}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.49755, "M": 0.84271, "C": 1.41073, "I": 5.29389, "S": 0.16302, "T": 8.20789}, "epoch": 10, "iter": 1985, "lr": 0.001, "elapsed": 3.841791868209839}, "time": 1650730187.5925698}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.72298, "M": 1.29605, "C": 1.35961, "I": 3.42443, "S": 0.17607, "T": 6.97914}, "epoch": 10, "iter": 1986, "lr": 0.001, "elapsed": 3.874052047729492}, "time": 1650730191.4666233}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.63103, "M": 1.09715, "C": 1.05147, "I": 4.68426, "S": 0.15581, "T": 7.61972}, "epoch": 10, "iter": 1987, "lr": 0.001, "elapsed": 3.7969765663146973}, "time": 1650730195.2636175}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.67501, "M": 1.33004, "C": 1.23517, "I": 0.04345, "S": 0.136, "T": 3.41967}, "epoch": 10, "iter": 1988, "lr": 0.001, "elapsed": 3.8099310398101807}, "time": 1650730199.0735488}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.58587, "M": 0.82934, "C": 0.77783, "I": 4.38192, "S": 0.11873, "T": 6.69369}, "epoch": 10, "iter": 1989, "lr": 0.001, "elapsed": 3.808518648147583}, "time": 1650730202.8821034}

{"type": "train", "session": 1, "data": {"loss": {"B": 0.71834, "M": 1.05781, "C": 1.151, "I": 1.59151, "S": 0.10568, "T": 4.62434}, "epoch": 10, "iter": 1990, "lr": 0.001, "elapsed": 3.795703887939453}, "time": 1650730206.677923}

{"type": "val", "session": 1, "data": {"elapsed": 67.51123070716858, "epoch": 10, "iter": 1991, "box": {"all": 55.14, "50": 79.7, "55": 77.73, "60": 76.17, "65": 74.57, "70": 69.75, "75": 64.68, "80": 58.86, "85": 34.84, "90": 14.14, "95": 0.97}, "mask": {"all": 50.89, "50": 69.03, "55": 66.8, "60": 65.44, "65": 63.22, "70": 61.83, "75": 58.46, "80": 52.99, "85": 43.88, "90": 20.84, "95": 6.4}}, "time": 1650730274.2673907}
