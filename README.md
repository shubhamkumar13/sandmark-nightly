**sandmark-nightly is been added to ocaml-bench and future developments would continue [here](https://github.com/ocaml-bench/sandmark-nightly)**

# sandmark-nightly
Stores nightly runs of sandmark

# How to setup on an AWS machine

1. Use the AWS setup tutorial mentioned in the [TLJH documentation](https://tljh.jupyter.org/en/latest/install/amazon.html).
2. Check the `SKEL` variable in `/etc/default/useradd` to be uncommented and it should be assigned to `/etc/skel` and it should end up looking like `SKEL=/etc/skel`.
3. Start the JupyterHub server on the aws machine which is currently empty.
4. Then open the terminal and download the setup script using `wget https://raw.githubusercontent.com/shubhamkumar13/sandmark-nightly/main/scripts/setup_aws.sh`.
5. Run the script from the terminal with `bash setup_aws.sh`.
