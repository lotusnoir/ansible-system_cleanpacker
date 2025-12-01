# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.1](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/2.2.0...2.2.1) - 2025-11-29

### Commits

- add no changes on run flag to keep idempotence [`e106c0d`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/e106c0d7163a1b4d0ff7f636b6b273e305d0eb31)

## [2.2.0](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/2.1.0...2.2.0) - 2025-11-26

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`79248f3`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/79248f35c5d4f30aced95574a211c25051f04ddf)

## [2.1.0](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/2.0.0...2.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`da9b89f`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/da9b89fa91abf31682fe8e0ef7985bab323e281b)
- update core and molecule [`f302fb3`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/f302fb30ab66d36948d660d72396cd615a1482f4)
- add oraclelinux10 support + lint and core fixes [`ac23ae1`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/ac23ae1ff7a81e472df84304c8c6c7fa31efbc3b)

## [2.0.0](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/1.1.0...2.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`988a2c3`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/988a2c3bfbe258699c95d3deaf9ddd54a1c9c3c8)
- update core, molecule + gitlab-ci [`f31c759`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/f31c759c7788f0c61dc2d904ba9427785297f1ef)
- changes on molecule [`3ff959f`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/3ff959fce2b7476981504805545628ba1eabe97c)
- changes on molecule + fix remove locales [`7693387`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/769338763e5abcb54b3c76bea3a8ce47bc3289cc)
- add molecule need [`d455024`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/d4550243822bcbe7cd3173471c58fec4eda33bd4)
- fix truncate_logs [`af939ca`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/af939cae1c9d64505cc4b58ce69a85f2737c664a)
- fix lint [`bd26468`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/bd264686d7de3d36596949a33161f928f7cb1341)
- fix molecule paralelism and little updates [`30bf7b3`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/30bf7b31190ad61c5e58773812eca84ec3a7e287)

## [1.1.0](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/1.0.0...1.1.0) - 2025-01-22

### Commits

- update ubuntu24 [`5b65385`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/5b653853528d50e5013762cea03e7c3fdf100310)
- add support for ubuntu24 [`27322c3`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/27322c36c0645588f859cc4aab7692a551071cb8)
- add version on molecule play image to maintain support on old release [`1f43053`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/1f43053b77e515038465575d8da7b14efe0ceabe)
- update molecule [`e59d565`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/e59d5652878d5911f064b3cd59671f9ae372ce5c)
- add consul node-id delete [`973dc16`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/973dc1675cc0e8fe8476323b21562f477b29cd84)
- remobe NetworkManager template config [`7f3cb91`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/7f3cb91d84d68eb5012a7c7a2490ee768839c3ca)
- remove dns management by network manger if installed [`32ee9eb`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/32ee9eb76b1ee9d334dbdda9d0f366e0cec73df0)
- add redhat 9 to default supported distrib [`c2e1918`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/c2e1918a086d0c091afab2e80450f998041b8127)
- add redhat 8 to default supported distrib [`cbaca80`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/cbaca8062a3f3410e8751c6befb9bd25e2c7a122)
- sort testing distrib to avoid random changes [`f8a8399`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/f8a83998df67188e0292d628ccc59b10951c51b7)

## [1.0.0](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`ae1d0aa`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/ae1d0aa622cde7da399b8f27f6e9b2f3f9eb79d1)
- update readme + precommit + include vars [`b6eeb60`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/b6eeb605b3edba1c4b11558decd64e2adfad7941)
- change import tasks to include in order to support facts on name [`a9d83f7`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/a9d83f72276491d20486d413fd4a4c320e0afc10)
- add extra tasks for ubuntu20 to clean cloudinit [`749e3f6`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/749e3f6ffeb7bd019e97e5b570292c7bb91c77c7)

## [0.2.0](https://github.com/lotusnoir/ansible-system_cleanpacker/compare/0.1.0...0.2.0) - 2023-06-14

### Commits

- add debian12 support [`3b3f9a4`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/3b3f9a49760e2e4026166cc2e49867db351139c6)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`1f4d1bb`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/1f4d1bb8470a9b334d35843899a0d83f51530eb8)
- add precommit for lint [`d2f3173`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/d2f3173d64099f97d4eb175e3125b314ddf5a2f6)
- remove grub cause managed by dedicated role and add services to disable for ubuntu [`af1906b`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/af1906b4c22a3b4933daa70871bfaeeb2e9299c6)
- fix checks [`f645826`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/f645826d8ea6c7ce18490d0b39e35a84bed21b6e)
- update molecule playbook [`cf75769`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/cf757691149fdaad00522d9703eaad80c2b3eabc)
- fix idempotence [`75d4f9f`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/75d4f9f52b4cdfffeca2020bad35b9cb9bb1235b)
- add new molecule all scenario [`1322967`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/13229670666ebd429078226060c6f96dbd82f2ab)
- split distro for molecule tests on ci [`a6a677a`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/a6a677a602bde51f88175f22ed5ae2a696a4796f)
- update checks and Readme [`9c70924`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/9c709248dece95051f019ce52b684b9b2ff5ffeb)
- update vars [`3318fef`](https://github.com/lotusnoir/ansible-system_cleanpacker/commit/3318fef1e637c952ebecfa3e70a7c2c2cf9ba6c1)
