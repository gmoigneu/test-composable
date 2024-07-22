```
upsun push
Selected project: Test PDO (ivm43wde7ztac)

Enter the target branch name (default: composable):

Create composable as an active environment? [Y/n]

Pushing HEAD to the branch composable of project Test PDO (ivm43wde7ztac)
It will be created as an active environment.

Are you sure you want to continue? [Y/n]

  Enumerating objects: 7, done.
  Counting objects: 100% (7/7), done.
  Delta compression using up to 10 threads
  Compressing objects: 100% (3/3), done.
  Writing objects: 100% (4/4), 496 bytes | 496.00 KiB/s, done.
  Total 4 (delta 1), reused 0 (delta 0), pack-reused 0

  Validating submodules

  Validating configuration files

  E: Error parsing configuration files:
      - applications.config.yaml:test-project.stack: Mapping should only have one top level key
  To git.ca-1.platform.sh:ivm43wde7ztac.git
   ! [remote rejected] HEAD -> composable (invalid configuration files)
  error: failed to push some refs to 'git.ca-1.platform.sh:ivm43wde7ztac.git'
```
