# Unibench

This is a small universal benchmark repository for VelCom.

It tries to treat its task repo (the repo it is supposed to be benchmarking) as
a bench repo and apply it to itself. To do that, it tries to find a bench script
in the task repo and call execv on it with the correct path as argument. Take
care not to use this repo as benchmark *and* test repo at the same time!

This repo is useful for debugging or when you want to benchmark a variety of
different repos on a single VelCom instance.
