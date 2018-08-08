
# `dummy_pipeline`
<!--
NOTE: replace all the **TODO** marks with your own content.
-->

**TODO**: insert high-level description of the pipeline. It consists of the following stages:

* [`setup`](./setup.sh). **TODO**. Add high-level description of stage `setup`.

* [`run`](./run.sh). **TODO**. Add high-level description of stage `run`.

* [`post-run`](./post-run.sh). **TODO**. Add high-level description of stage `post-run`.

* [`validate`](./validate.sh). **TODO**. Add high-level description of stage `validate`.

* [`teardown`](./teardown.sh). **TODO**. Add high-level description of stage `teardown`.


# Obtaining the pipeline

To add this pipeline to  the [`popper` CLI tool](https://github.com/systemslab/popper):

```bash
cd your-repo
popper add org/MockPipeline/dummy_pipeline
```

**TODO**: replace `org` appropriately.

# Running the pipeline

To run the pipeline using the [`popper` CLI tool](https://github.com/systemslab/popper):

```bash
cd MockPipeline
popper run dummy_pipeline
```

The pipeline can be executed on the following environment(s):

* `host`.

---
The pipeline expects the following environment variables:

* `<ENV_VAR1>`. Description of environment variable.
* `<ENV_VAR2>`. Description of environment variable.

For example, the following is an execution with all expected
variables:

```bash
export <ENV_VAR1>=value-for-<ENV_VAR_1>
export <ENV_VAR2>=value-for-<ENV_VAR_2>

popper run dummy_pipeline
```


# Dependencies

**TODO**: add list of dependencies, for example:

  * Python.
  * C++ compiler.
  * [Docker](https://docker.com) (for generating plots).
  * etc.
