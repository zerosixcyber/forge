# Forge - Architecture Decisions

- Distro Name: Forge
- Approach: LFS	(Linux From Scratch)
- libc:	glibc
- Init System: runit
- Architectures: x86_64	(Phase 1-2), ARM64 (Phase 3+)
- Primary Build Host: VirtualBox VM on Windows PC, Fedora guest, i5-9600KF, 12G>
- Secondary Edit Host: ThinkPad	with Fedora, i5-8365U, 32GB RAM
- ARM Build Host: MacBook Air M2 with Asahi Linux, 8GB RAM
- Compile Defaults: make -j8 on	ThinkPad / make	-j4 on VM, ccache enabled



