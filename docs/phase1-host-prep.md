# Phase 1 - Host Preparation Log

## Step 3: LFS user and build environment

- Created lfs user/group on Fedora host
- /mnt/lfs/sources (sticky+world-writeable) and /mnt/lfs/tools created
- /tools symlinked to /mnt/lfs/tools (avoid path divergence)
- lfs user uses exec env -i in ~/.bash_profile for sterile shell
- ~/.bashrc sets LFS, LFS_TGT, PATH, LC_ALL, CONFIG_SITE per LFS book Ch. 4
- Build rule: always work as lfs user, never as the regular host user
