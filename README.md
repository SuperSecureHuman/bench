# Benchmark! Heavy ones

Compiling a set of diverse workloads to test a high performance DL setup.

The benchmark should test the following

GPU bound task (processing high res images directly, processing large models)
CPU bound task (put on the fly preprocessing)
IO Bound tasks (rapidly access disk)
Network bound tasks (Try uploading checkpoints during training to see if there is any network bottleneck)


Once I start getting results, I will be making a new file for it, and try to maintain a wandb dashboard for it too.
