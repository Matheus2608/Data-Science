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

-------------------------------------------------

loading annotations into memory...
Done (t=0.05s)
creating index...
index created!
loading annotations into memory...
Done (t=0.01s)
creating index...
index created!
Resuming training, loading weights/yolact_plus_base_9_1632_interrupt.pth...
Begin training!

[  9]    1640 || B: 0.655 | C: 1.292 | M: 1.053 | S: 0.205 | I: 4.121 | T: 7.326 || ETA: 12 days, 13:58:09 || timer: 1.375
[  9]    1650 || B: 0.641 | C: 1.383 | M: 1.029 | S: 0.237 | I: 4.522 | T: 7.812 || ETA: 12 days, 14:40:20 || timer: 1.370
[  9]    1660 || B: 0.653 | C: 1.474 | M: 1.048 | S: 0.211 | I: 3.886 | T: 7.272 || ETA: 12 days, 16:04:52 || timer: 1.423
[  9]    1670 || B: 0.646 | C: 1.475 | M: 1.059 | S: 0.211 | I: 3.919 | T: 7.309 || ETA: 12 days, 17:42:42 || timer: 1.411
[  9]    1680 || B: 0.676 | C: 1.508 | M: 1.096 | S: 0.214 | I: 4.065 | T: 7.560 || ETA: 12 days, 18:46:37 || timer: 1.391
[  9]    1690 || B: 0.679 | C: 1.491 | M: 1.133 | S: 0.207 | I: 3.960 | T: 7.470 || ETA: 12 days, 19:58:11 || timer: 1.418
[  9]    1700 || B: 0.680 | C: 1.492 | M: 1.143 | S: 0.204 | I: 4.110 | T: 7.628 || ETA: 12 days, 21:24:30 || timer: 1.439
[  9]    1710 || B: 0.694 | C: 1.504 | M: 1.147 | S: 0.204 | I: 3.933 | T: 7.482 || ETA: 12 days, 22:18:33 || timer: 1.425
[  9]    1720 || B: 0.694 | C: 1.494 | M: 1.155 | S: 0.204 | I: 3.958 | T: 7.505 || ETA: 12 days, 23:25:07 || timer: 1.433
[  9]    1730 || B: 0.698 | C: 1.504 | M: 1.155 | S: 0.204 | I: 4.033 | T: 7.594 || ETA: 13 days, 0:36:26 || timer: 1.458
[  9]    1740 || B: 0.708 | C: 1.516 | M: 1.158 | S: 0.200 | I: 4.019 | T: 7.601 || ETA: 13 days, 1:43:00 || timer: 1.452
[  9]    1750 || B: 0.715 | C: 1.523 | M: 1.183 | S: 0.191 | I: 3.878 | T: 7.491 || ETA: 13 days, 2:27:18 || timer: 1.457
[  9]    1760 || B: 0.715 | C: 1.505 | M: 1.181 | S: 0.199 | I: 3.968 | T: 7.568 || ETA: 13 days, 3:10:33 || timer: 1.455
[  9]    1770 || B: 0.726 | C: 1.519 | M: 1.182 | S: 0.202 | I: 3.806 | T: 7.434 || ETA: 13 days, 3:53:14 || timer: 1.460
[  9]    1780 || B: 0.722 | C: 1.505 | M: 1.177 | S: 0.201 | I: 3.702 | T: 7.307 || ETA: 13 days, 4:22:31 || timer: 1.446
[  9]    1790 || B: 0.718 | C: 1.520 | M: 1.164 | S: 0.203 | I: 3.680 | T: 7.286 || ETA: 13 days, 4:49:07 || timer: 1.431
[  9]    1800 || B: 0.715 | C: 1.516 | M: 1.153 | S: 0.207 | I: 3.540 | T: 7.131 || ETA: 13 days, 5:17:28 || timer: 1.463


[ 10]    1810 || B: 0.706 | C: 1.487 | M: 1.141 | S: 0.214 | I: 3.725 | T: 7.274 || ETA: 13 days, 7:32:50 || timer: 2.890
[ 10]    1820 || B: 0.700 | C: 1.479 | M: 1.133 | S: 0.214 | I: 3.650 | T: 7.177 || ETA: 13 days, 7:48:19 || timer: 1.466
[ 10]    1830 || B: 0.697 | C: 1.457 | M: 1.125 | S: 0.212 | I: 3.644 | T: 7.136 || ETA: 13 days, 8:07:10 || timer: 1.472
[ 10]    1840 || B: 0.701 | C: 1.487 | M: 1.138 | S: 0.219 | I: 3.638 | T: 7.183 || ETA: 13 days, 8:17:37 || timer: 1.462
[ 10]    1850 || B: 0.712 | C: 1.491 | M: 1.138 | S: 0.230 | I: 3.653 | T: 7.225 || ETA: 13 days, 8:29:39 || timer: 1.448
[ 10]    1860 || B: 0.717 | C: 1.475 | M: 1.140 | S: 0.220 | I: 3.751 | T: 7.303 || ETA: 13 days, 8:40:53 || timer: 1.460
[ 10]    1870 || B: 0.718 | C: 1.450 | M: 1.142 | S: 0.215 | I: 3.858 | T: 7.384 || ETA: 13 days, 8:54:14 || timer: 1.477
[ 10]    1880 || B: 0.718 | C: 1.470 | M: 1.142 | S: 0.211 | I: 3.780 | T: 7.320 || ETA: 13 days, 9:08:34 || timer: 1.474
[ 10]    1890 || B: 0.724 | C: 1.447 | M: 1.137 | S: 0.213 | I: 3.799 | T: 7.320 || ETA: 13 days, 9:19:00 || timer: 1.474
[ 10]    1900 || B: 0.730 | C: 1.449 | M: 1.139 | S: 0.215 | I: 3.858 | T: 7.391 || ETA: 13 days, 9:30:19 || timer: 1.473
[ 10]    1910 || B: 0.730 | C: 1.463 | M: 1.145 | S: 0.204 | I: 3.687 | T: 7.229 || ETA: 13 days, 9:40:43 || timer: 1.484
[ 10]    1920 || B: 0.740 | C: 1.480 | M: 1.146 | S: 0.204 | I: 3.749 | T: 7.319 || ETA: 13 days, 9:50:30 || timer: 1.474
[ 10]    1930 || B: 0.754 | C: 1.504 | M: 1.152 | S: 0.209 | I: 3.675 | T: 7.294 || ETA: 13 days, 9:55:59 || timer: 1.449
[ 10]    1940 || B: 0.742 | C: 1.467 | M: 1.142 | S: 0.207 | I: 3.710 | T: 7.269 || ETA: 13 days, 10:00:04 || timer: 1.439
[ 10]    1950 || B: 0.719 | C: 1.440 | M: 1.119 | S: 0.201 | I: 3.669 | T: 7.147 || ETA: 13 days, 10:03:23 || timer: 1.495
[ 10]    1960 || B: 0.716 | C: 1.459 | M: 1.118 | S: 0.208 | I: 3.578 | T: 7.079 || ETA: 13 days, 10:10:04 || timer: 1.480
[ 10]    1970 || B: 0.732 | C: 1.485 | M: 1.137 | S: 0.205 | I: 3.567 | T: 7.126 || ETA: 13 days, 10:14:50 || timer: 1.463
[ 10]    1980 || B: 0.720 | C: 1.458 | M: 1.111 | S: 0.211 | I: 3.663 | T: 7.163 || ETA: 13 days, 10:18:52 || timer: 1.459
[ 10]    1990 || B: 0.711 | C: 1.465 | M: 1.104 | S: 0.212 | I: 3.613 | T: 7.105 || ETA: 13 days, 10:18:52 || timer: 1.458

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+
   box | 55.55 | 81.40 | 80.42 | 79.46 | 74.85 | 69.86 | 63.21 | 53.80 | 37.04 | 13.03 |  2.44 |
  mask | 51.57 | 69.33 | 68.03 | 67.24 | 66.40 | 63.71 | 59.09 | 53.00 | 43.81 | 20.13 |  4.99 |

[ 11]    2000 || B: 0.716 | C: 1.461 | M: 1.103 | S: 0.205 | I: 3.628 | T: 7.114 || ETA: 14 days, 1:30:11 || timer: 1.454
[ 11]    2010 || B: 0.709 | C: 1.438 | M: 1.100 | S: 0.204 | I: 3.779 | T: 7.231 || ETA: 14 days, 1:08:51 || timer: 1.466
[ 11]    2020 || B: 0.697 | C: 1.422 | M: 1.101 | S: 0.200 | I: 3.643 | T: 7.063 || ETA: 14 days, 0:47:37 || timer: 1.457
[ 11]    2030 || B: 0.674 | C: 1.401 | M: 1.084 | S: 0.200 | I: 3.661 | T: 7.020 || ETA: 14 days, 0:27:13 || timer: 1.467
[ 11]    2040 || B: 0.688 | C: 1.405 | M: 1.100 | S: 0.198 | I: 3.535 | T: 6.925 || ETA: 14 days, 0:10:01 || timer: 1.481
[ 11]    2050 || B: 0.698 | C: 1.406 | M: 1.100 | S: 0.191 | I: 3.636 | T: 7.031 || ETA: 13 days, 23:53:12 || timer: 1.461
[ 11]    2060 || B: 0.704 | C: 1.415 | M: 1.118 | S: 0.194 | I: 3.528 | T: 6.959 || ETA: 13 days, 23:34:10 || timer: 1.447
[ 11]    2070 || B: 0.683 | C: 1.398 | M: 1.080 | S: 0.194 | I: 3.641 | T: 6.996 || ETA: 13 days, 23:18:14 || timer: 1.456
[ 11]    2080 || B: 0.693 | C: 1.380 | M: 1.085 | S: 0.184 | I: 3.750 | T: 7.091 || ETA: 13 days, 23:02:38 || timer: 1.466
[ 11]    2090 || B: 0.714 | C: 1.381 | M: 1.103 | S: 0.178 | I: 3.738 | T: 7.115 || ETA: 13 days, 22:47:47 || timer: 1.452
[ 11]    2100 || B: 0.707 | C: 1.368 | M: 1.091 | S: 0.180 | I: 3.741 | T: 7.087 || ETA: 13 days, 22:35:27 || timer: 1.481
[ 11]    2110 || B: 0.702 | C: 1.374 | M: 1.081 | S: 0.182 | I: 3.662 | T: 7.001 || ETA: 13 days, 22:24:34 || timer: 1.487
[ 11]    2120 || B: 0.703 | C: 1.367 | M: 1.056 | S: 0.181 | I: 3.792 | T: 7.100 || ETA: 13 days, 22:11:18 || timer: 1.459
[ 11]    2130 || B: 0.724 | C: 1.374 | M: 1.076 | S: 0.181 | I: 3.786 | T: 7.140 || ETA: 13 days, 21:58:24 || timer: 1.479
[ 11]    2140 || B: 0.715 | C: 1.392 | M: 1.061 | S: 0.181 | I: 3.811 | T: 7.160 || ETA: 13 days, 21:46:35 || timer: 1.457
[ 11]    2150 || B: 0.709 | C: 1.406 | M: 1.060 | S: 0.181 | I: 3.762 | T: 7.117 || ETA: 13 days, 21:35:24 || timer: 1.479
[ 11]    2160 || B: 0.701 | C: 1.389 | M: 1.053 | S: 0.175 | I: 4.017 | T: 7.335 || ETA: 13 days, 21:24:27 || timer: 1.443
[ 11]    2170 || B: 0.699 | C: 1.357 | M: 1.054 | S: 0.181 | I: 3.932 | T: 7.223 || ETA: 13 days, 21:10:45 || timer: 1.451

[ 12]    2180 || B: 0.697 | C: 1.383 | M: 1.066 | S: 0.194 | I: 3.785 | T: 7.125 || ETA: 13 days, 21:40:03 || timer: 1.465
[ 12]    2190 || B: 0.683 | C: 1.389 | M: 1.045 | S: 0.200 | I: 3.825 | T: 7.143 || ETA: 13 days, 21:29:25 || timer: 1.466
[ 12]    2200 || B: 0.683 | C: 1.401 | M: 1.063 | S: 0.203 | I: 3.712 | T: 7.062 || ETA: 13 days, 21:18:55 || timer: 1.463
[ 12]    2210 || B: 0.680 | C: 1.400 | M: 1.059 | S: 0.203 | I: 3.764 | T: 7.107 || ETA: 13 days, 21:09:17 || timer: 1.480
[ 12]    2220 || B: 0.692 | C: 1.413 | M: 1.082 | S: 0.202 | I: 3.652 | T: 7.041 || ETA: 13 days, 20:59:24 || timer: 1.463
[ 12]    2230 || B: 0.673 | C: 1.391 | M: 1.076 | S: 0.195 | I: 3.621 | T: 6.955 || ETA: 13 days, 20:51:25 || timer: 1.481
[ 12]    2240 || B: 0.659 | C: 1.362 | M: 1.077 | S: 0.192 | I: 3.647 | T: 6.936 || ETA: 13 days, 20:42:25 || timer: 1.485
[ 12]    2250 || B: 0.660 | C: 1.351 | M: 1.077 | S: 0.194 | I: 3.532 | T: 6.814 || ETA: 13 days, 20:34:54 || timer: 1.454
[ 12]    2260 || B: 0.661 | C: 1.354 | M: 1.072 | S: 0.193 | I: 3.427 | T: 6.706 || ETA: 13 days, 20:27:19 || timer: 1.432
[ 12]    2270 || B: 0.653 | C: 1.363 | M: 1.076 | S: 0.185 | I: 3.480 | T: 6.757 || ETA: 13 days, 20:22:18 || timer: 1.468
[ 12]    2280 || B: 0.663 | C: 1.374 | M: 1.076 | S: 0.180 | I: 3.569 | T: 6.863 || ETA: 13 days, 20:13:35 || timer: 1.458
[ 12]    2290 || B: 0.655 | C: 1.337 | M: 1.070 | S: 0.173 | I: 3.708 | T: 6.942 || ETA: 13 days, 20:05:50 || timer: 1.471
[ 12]    2300 || B: 0.647 | C: 1.316 | M: 1.051 | S: 0.168 | I: 3.744 | T: 6.926 || ETA: 13 days, 19:58:47 || timer: 1.453
[ 12]    2310 || B: 0.669 | C: 1.339 | M: 1.066 | S: 0.172 | I: 3.675 | T: 6.922 || ETA: 13 days, 19:50:27 || timer: 1.455
[ 12]    2320 || B: 0.657 | C: 1.328 | M: 1.057 | S: 0.176 | I: 3.730 | T: 6.948 || ETA: 13 days, 19:44:04 || timer: 1.469
[ 12]    2330 || B: 0.667 | C: 1.339 | M: 1.054 | S: 0.175 | I: 3.716 | T: 6.950 || ETA: 13 days, 19:36:09 || timer: 1.458
[ 12]    2340 || B: 0.676 | C: 1.326 | M: 1.031 | S: 0.173 | I: 3.767 | T: 6.973 || ETA: 13 days, 19:29:45 || timer: 1.460
[ 12]    2350 || B: 0.663 | C: 1.308 | M: 1.010 | S: 0.173 | I: 4.031 | T: 7.185 || ETA: 13 days, 19:21:38 || timer: 1.447

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+
   box | 58.15 | 82.95 | 81.15 | 80.38 | 77.62 | 74.63 | 68.27 | 56.98 | 38.18 | 17.33 |  4.01 |
  mask | 53.37 | 71.67 | 69.88 | 68.65 | 67.35 | 64.77 | 61.18 | 54.19 | 44.41 | 24.23 |  7.39 |
-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+

[ 13]    2360 || B: 0.653 | C: 1.295 | M: 1.001 | S: 0.175 | I: 3.985 | T: 7.109 || ETA: 14 days, 2:36:26 || timer: 1.464
[ 13]    2370 || B: 0.662 | C: 1.304 | M: 1.004 | S: 0.176 | I: 3.919 | T: 7.065 || ETA: 14 days, 2:21:30 || timer: 1.457
[ 13]    2380 || B: 0.642 | C: 1.264 | M: 0.987 | S: 0.172 | I: 3.998 | T: 7.064 || ETA: 14 days, 2:09:18 || timer: 1.437
[ 13]    2390 || B: 0.636 | C: 1.270 | M: 0.995 | S: 0.169 | I: 3.831 | T: 6.901 || ETA: 14 days, 1:57:08 || timer: 1.444
[ 13]    2400 || B: 0.644 | C: 1.281 | M: 1.004 | S: 0.171 | I: 4.019 | T: 7.119 || ETA: 14 days, 1:44:12 || timer: 1.447
[ 13]    2410 || B: 0.629 | C: 1.268 | M: 1.002 | S: 0.174 | I: 3.948 | T: 7.021 || ETA: 14 days, 1:33:15 || timer: 1.478
[ 13]    2420 || B: 0.634 | C: 1.274 | M: 1.014 | S: 0.170 | I: 4.093 | T: 7.185 || ETA: 14 days, 1:23:04 || timer: 1.479
[ 13]    2430 || B: 0.641 | C: 1.292 | M: 1.028 | S: 0.173 | I: 4.000 | T: 7.135 || ETA: 14 days, 1:11:15 || timer: 1.460
[ 13]    2440 || B: 0.640 | C: 1.307 | M: 1.038 | S: 0.175 | I: 3.954 | T: 7.114 || ETA: 14 days, 1:00:41 || timer: 1.478
[ 13]    2450 || B: 0.665 | C: 1.344 | M: 1.082 | S: 0.183 | I: 3.686 | T: 6.961 || ETA: 14 days, 0:50:36 || timer: 1.448
[ 13]    2460 || B: 0.677 | C: 1.343 | M: 1.076 | S: 0.184 | I: 3.769 | T: 7.050 || ETA: 14 days, 0:41:31 || timer: 1.497
[ 13]    2470 || B: 0.669 | C: 1.321 | M: 1.068 | S: 0.182 | I: 3.721 | T: 6.963 || ETA: 14 days, 0:30:57 || timer: 1.448
[ 13]    2480 || B: 0.669 | C: 1.343 | M: 1.071 | S: 0.185 | I: 3.572 | T: 6.840 || ETA: 14 days, 0:22:23 || timer: 1.486
[ 13]    2490 || B: 0.685 | C: 1.351 | M: 1.091 | S: 0.192 | I: 3.826 | T: 7.145 || ETA: 14 days, 0:13:51 || timer: 1.466
[ 13]    2500 || B: 0.688 | C: 1.357 | M: 1.103 | S: 0.195 | I: 3.589 | T: 6.932 || ETA: 14 days, 0:06:01 || timer: 1.474
[ 13]    2510 || B: 0.713 | C: 1.375 | M: 1.126 | S: 0.190 | I: 3.673 | T: 7.077 || ETA: 13 days, 23:58:19 || timer: 1.503
[ 13]    2520 || B: 0.715 | C: 1.385 | M: 1.114 | S: 0.195 | I: 3.568 | T: 6.977 || ETA: 13 days, 23:49:08 || timer: 1.461
[ 13]    2530 || B: 0.708 | C: 1.383 | M: 1.103 | S: 0.196 | I: 3.586 | T: 6.977 || ETA: 13 days, 23:40:23 || timer: 1.441

[ 14]    2540 || B: 0.703 | C: 1.373 | M: 1.104 | S: 0.195 | I: 3.628 | T: 7.003 || ETA: 13 days, 23:53:26 || timer: 1.440
[ 14]    2550 || B: 0.698 | C: 1.355 | M: 1.087 | S: 0.185 | I: 3.743 | T: 7.068 || ETA: 13 days, 23:45:11 || timer: 1.462
[ 14]    2560 || B: 0.695 | C: 1.348 | M: 1.094 | S: 0.179 | I: 3.732 | T: 7.048 || ETA: 13 days, 23:36:00 || timer: 1.438
[ 14]    2570 || B: 0.700 | C: 1.373 | M: 1.103 | S: 0.181 | I: 3.719 | T: 7.075 || ETA: 13 days, 23:28:28 || timer: 1.501
[ 14]    2580 || B: 0.713 | C: 1.361 | M: 1.108 | S: 0.175 | I: 3.868 | T: 7.226 || ETA: 13 days, 23:20:50 || timer: 1.456
[ 14]    2590 || B: 0.703 | C: 1.363 | M: 1.072 | S: 0.169 | I: 3.728 | T: 7.036 || ETA: 13 days, 23:13:49 || timer: 1.500
[ 14]    2600 || B: 0.691 | C: 1.359 | M: 1.060 | S: 0.163 | I: 3.798 | T: 7.070 || ETA: 13 days, 23:06:26 || timer: 1.459
[ 14]    2610 || B: 0.666 | C: 1.335 | M: 1.029 | S: 0.160 | I: 3.785 | T: 6.975 || ETA: 13 days, 22:57:56 || timer: 1.456
[ 14]    2620 || B: 0.667 | C: 1.330 | M: 1.033 | S: 0.156 | I: 3.674 | T: 6.861 || ETA: 13 days, 22:52:10 || timer: 1.480
[ 14]    2630 || B: 0.651 | C: 1.307 | M: 1.017 | S: 0.155 | I: 3.812 | T: 6.942 || ETA: 13 days, 22:45:46 || timer: 1.457
[ 14]    2640 || B: 0.666 | C: 1.336 | M: 1.022 | S: 0.158 | I: 3.738 | T: 6.921 || ETA: 13 days, 22:54:41 || timer: 1.461
[ 14]    2650 || B: 0.658 | C: 1.341 | M: 1.009 | S: 0.155 | I: 3.798 | T: 6.962 || ETA: 13 days, 23:06:18 || timer: 1.452
[ 14]    2660 || B: 0.647 | C: 1.330 | M: 1.006 | S: 0.159 | I: 3.694 | T: 6.835 || ETA: 13 days, 23:16:04 || timer: 1.457
[ 14]    2670 || B: 0.646 | C: 1.319 | M: 1.005 | S: 0.165 | I: 3.861 | T: 6.997 || ETA: 13 days, 23:23:13 || timer: 1.439
[ 14]    2680 || B: 0.631 | C: 1.302 | M: 0.988 | S: 0.165 | I: 3.802 | T: 6.889 || ETA: 13 days, 23:30:17 || timer: 1.480
[ 14]    2690 || B: 0.633 | C: 1.304 | M: 0.994 | S: 0.178 | I: 3.818 | T: 6.927 || ETA: 13 days, 23:36:04 || timer: 1.435
[ 14]    2700 || B: 0.636 | C: 1.293 | M: 0.990 | S: 0.176 | I: 3.775 | T: 6.870 || ETA: 13 days, 23:39:01 || timer: 1.463
[ 14]    2710 || B: 0.642 | C: 1.305 | M: 1.001 | S: 0.186 | I: 3.771 | T: 6.906 || ETA: 13 days, 23:42:43 || timer: 1.440

Computing validation mAP (this may take a while)...


Calculating mAP...

       |  all  |  .50  |  .55  |  .60  |  .65  |  .70  |  .75  |  .80  |  .85  |  .90  |  .95  |
-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+
   box | 56.27 | 82.25 | 80.25 | 78.66 | 77.71 | 72.12 | 66.86 | 55.62 | 36.26 | 11.23 |  1.71 |
  mask | 52.57 | 71.05 | 69.56 | 68.54 | 66.29 | 63.33 | 58.32 | 52.62 | 41.59 | 24.86 |  9.56 |
-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+-------+

[ 15]    2720 || B: 0.642 | C: 1.299 | M: 1.000 | S: 0.189 | I: 3.792 | T: 6.922 || ETA: 14 days, 5:11:36 || timer: 1.462
[ 15]    2730 || B: 0.657 | C: 1.305 | M: 1.003 | S: 0.185 | I: 3.865 | T: 7.014 || ETA: 14 days, 5:12:40 || timer: 1.471
[ 15]    2740 || B: 0.642 | C: 1.276 | M: 0.984 | S: 0.181 | I: 4.040 | T: 7.124 || ETA: 14 days, 5:12:30 || timer: 1.452
[ 15]    2750 || B: 0.654 | C: 1.279 | M: 1.004 | S: 0.188 | I: 3.920 | T: 7.045 || ETA: 14 days, 5:13:10 || timer: 1.457
[ 15]    2760 || B: 0.666 | C: 1.313 | M: 1.006 | S: 0.187 | I: 3.943 | T: 7.115 || ETA: 14 days, 5:13:47 || timer: 1.459
[ 15]    2770 || B: 0.662 | C: 1.328 | M: 1.011 | S: 0.178 | I: 3.773 | T: 6.951 || ETA: 14 days, 5:11:54 || timer: 1.482
[ 15]    2780 || B: 0.665 | C: 1.338 | M: 1.023 | S: 0.179 | I: 3.723 | T: 6.928 || ETA: 14 days, 5:11:13 || timer: 1.442
[ 15]    2790 || B: 0.649 | C: 1.333 | M: 1.024 | S: 0.172 | I: 3.634 | T: 6.812 || ETA: 14 days, 5:09:32 || timer: 1.472
[ 15]    2800 || B: 0.644 | C: 1.320 | M: 1.011 | S: 0.174 | I: 3.749 | T: 6.898 || ETA: 14 days, 5:09:01 || timer: 1.480
[ 15]    2810 || B: 0.634 | C: 1.302 | M: 1.010 | S: 0.167 | I: 3.759 | T: 6.872 || ETA: 14 days, 4:49:02 || timer: 1.449
[ 15]    2820 || B: 0.637 | C: 1.312 | M: 1.008 | S: 0.166 | I: 3.789 | T: 6.912 || ETA: 14 days, 4:47:43 || timer: 1.452
[ 15]    2830 || B: 0.630 | C: 1.310 | M: 1.005 | S: 0.172 | I: 3.696 | T: 6.813 || ETA: 14 days, 4:46:43 || timer: 1.451
[ 15]    2840 || B: 0.632 | C: 1.301 | M: 1.014 | S: 0.171 | I: 3.672 | T: 6.791 || ETA: 14 days, 4:46:22 || timer: 1.446
[ 15]    2850 || B: 0.613 | C: 1.286 | M: 0.994 | S: 0.170 | I: 3.733 | T: 6.797 || ETA: 14 days, 4:44:35 || timer: 1.479
[ 15]    2860 || B: 0.601 | C: 1.253 | M: 0.985 | S: 0.172 | I: 3.650 | T: 6.662 || ETA: 14 days, 4:43:37 || timer: 1.477
[ 15]    2870 || B: 0.602 | C: 1.244 | M: 0.984 | S: 0.169 | I: 3.710 | T: 6.709 || ETA: 14 days, 4:42:09 || timer: 1.453
[ 15]    2880 || B: 0.605 | C: 1.249 | M: 0.994 | S: 0.175 | I: 3.679 | T: 6.702 || ETA: 14 days, 4:40:10 || timer: 1.479
[ 15]    2890 || B: 0.610 | C: 1.245 | M: 0.978 | S: 0.173 | I: 3.748 | T: 6.755 || ETA: 14 days, 4:38:39 || timer: 1.449

[ 16]    2900 || B: 0.625 | C: 1.287 | M: 1.006 | S: 0.174 | I: 3.656 | T: 6.748 || ETA: 14 days, 5:00:08 || timer: 1.445
[ 16]    2910 || B: 0.624 | C: 1.284 | M: 0.997 | S: 0.172 | I: 3.603 | T: 6.680 || ETA: 14 days, 4:57:11 || timer: 1.460
[ 16]    2920 || B: 0.628 | C: 1.274 | M: 0.998 | S: 0.176 | I: 3.781 | T: 6.858 || ETA: 14 days, 4:54:53 || timer: 1.483
[ 16]    2930 || B: 0.623 | C: 1.253 | M: 1.006 | S: 0.175 | I: 3.770 | T: 6.828 || ETA: 14 days, 4:54:22 || timer: 1.479
[ 16]    2940 || B: 0.615 | C: 1.249 | M: 1.001 | S: 0.173 | I: 3.702 | T: 6.739 || ETA: 14 days, 4:54:00 || timer: 1.458
[ 16]    2950 || B: 0.625 | C: 1.252 | M: 1.010 | S: 0.168 | I: 3.648 | T: 6.703 || ETA: 14 days, 4:53:02 || timer: 1.443
[ 16]    2960 || B: 0.636 | C: 1.257 | M: 1.013 | S: 0.165 | I: 3.786 | T: 6.857 || ETA: 14 days, 4:52:30 || timer: 1.453
[ 16]    2970 || B: 0.643 | C: 1.252 | M: 1.020 | S: 0.172 | I: 3.791 | T: 6.878 || ETA: 14 days, 4:51:11 || timer: 1.451
[ 16]    2980 || B: 0.649 | C: 1.243 | M: 1.027 | S: 0.165 | I: 3.817 | T: 6.902 || ETA: 14 days, 4:51:11 || timer: 1.459
[ 16]    2990 || B: 0.651 | C: 1.234 | M: 1.039 | S: 0.163 | I: 3.740 | T: 6.826 || ETA: 14 days, 4:51:33 || timer: 1.446
[ 16]    3000 || B: 0.643 | C: 1.215 | M: 1.037 | S: 0.161 | I: 3.683 | T: 6.739 || ETA: 13 days, 23:15:51 || timer: 1.461
[ 16]    3010 || B: 0.638 | C: 1.189 | M: 1.030 | S: 0.155 | I: 3.743 | T: 6.755 || ETA: 13 days, 23:14:56 || timer: 1.476
[ 16]    3020 || B: 0.623 | C: 1.168 | M: 1.027 | S: 0.150 | I: 3.524 | T: 6.492 || ETA: 13 days, 23:14:53 || timer: 1.461
Stopping early. Saving network...
