# openWorkBenchesService-code

The planned organization onboarding, configuration distribution, workstation pairing, and approval service.

This repository is an initial project scaffold. Application functionality will be implemented in the code leg.

The **code leg** of the `openworkbenchesservice` project: the implementation and its
tests. The requirements it implements live in
[`opensoft/openWorkBenchesService-spec`](https://github.com/opensoft/openWorkBenchesService-spec).

**Clone the assembly root, not this repository.** This leg is mounted as a
submodule at `code/` inside
[`opensoft/openWorkBenchesService`](https://github.com/opensoft/openWorkBenchesService), which
is what pins the commit of this repository that the project currently is:

```sh
git clone --recurse-submodules https://github.com/opensoft/openWorkBenchesService.git
cd openWorkBenchesService
make bootstrap
```

Working here directly is fine — it is an ordinary repository with an ordinary
branch. What advancing this leg does NOT do is advance the project: that is a
commit in the assembly root moving the gitlink, `contracts/code-pin.yaml` and
any workflow `@<sha>` reference together.

Being the code leg confers no authority over the implementation. The split is
navigation; authority travels in grants, and a project that keeps spec and
code in one repository is reviewed identically.

Topic: `xf-project-openworkbenchesservice`.


## License

Apache-2.0. Copyright 2026 OpenSoft. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
