This is a example for how to use AOT compilation on TensorFlow XLA. The code are extracted form the TensorFlow github repo.

Usage:

	1. Clone Tensorflow github repo. Configure the repo with XLA enabled. Create a folder named plugins.

	2. Download all code here and put them in tensoflow/plugins folder.

	3. build --config=opt //plugins:my\_binary

	4. execute bazel-bin/plugins/my\_binary and it should return "Success".
