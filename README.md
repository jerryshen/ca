Setup Development Environment: Web/README.md


# Git Branches Rules

### Run git hook install script

```
cd .git_hooks/
./install.sh
```

### Branches

your git branches structure should be like the following one:

```
master
production
x_releases
  yyyymmdd
y_hotfix
  yyyymm_underscore_hotfix_name
z_features
  yyyymm_underscore_feature_name
```

For example:

```
master
production
x_releases
  20210419
y_hotfix
  202103_dynamic_offers_service_hotfix
z_features
  202103_ap_placement
```

### Open New Pull Request

Everyone should compare your own branch against base branch, the base branch should not be `master`, it should be `x_releases/yyyymmdd`
