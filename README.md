# DCGAN
---
## 运行环境
python 3.7 64bit

tensorflow 1.15.2

scipy 1.4.1

scikit-image 0.16.2

---
## 文件结构

---
## 启动参数

--epoch "Epoch to train [25]"

--learning_rate "Learning rate of for adam [0.0002]"

--beta1 "Momentum term of adam [0.5]"

--train_size "The size of train images [np.inf]"

--batch_size "The size of batch images [64]"

--input_height "The size of image to use (will be center cropped). [108]"

--input_width "The size of image to use (will be center cropped). If None, same value as input_height [None]"

--output_height "The size of the output images to produce [64]"

--output_width "The size of the output images to produce. If None, same value as output_height [None]"

--dataset "The name of dataset [celebA, mnist, lsun]"

--input_fname_pattern "Glob pattern of filename of input images [*]"

--data_dir "path to datasets [e.g. $HOME/data]"

--out_dir "Root directory for outputs [e.g. $HOME/out]"

--out_name "Folder (under out_root_dir) for all outputs. Generated automatically if left blank []"

--checkpoint_dir "Folder (under out_root_dir/out_name) to save checkpoints [checkpoint]"

--sample_dir "Folder (under out_root_dir/out_name) to save samples [samples]"

--train "True for training, False for testing [False]"

--crop" "True for training, False for testing [False]"

--visualize "True for visualizing, False for nothing [False]"

--export "True for exporting with new batch size"

--freeze "True for exporting with new batch size"

--max_to_keep "maximum number of checkpoints to keep"

--sample_freq "sample every this many iterations"

--ckpt_freq "save checkpoint every this many iterations"

--z_dim "dimensions of z"

--z_dist" "'normal01' or 'uniform_unsigned' or uniform_signed"

--G_img_sum "Save generator image summaries in log"
