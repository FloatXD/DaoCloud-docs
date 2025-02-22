# Global management

On this page, you can download the offline installation packages of various versions of the global management module.

## Download

| Version | Architecture | File Size | Pack | MD5 file | Date |
| --------------------------- | ----- |-------- | -------------------------------------- | ---------- | ---------- |
| [v0.15.0](../../ghippo/intro/release-notes.md) | AMD 64 | 426.40MB | [:arrow_down: ghippo_v0.15.0_amd64.tar](https://qiniu-download- public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.15.0_amd64.tar) | [:arrow_down: ghippo_v0.15.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.15.0_amd64_checksum.sha5 ) | 2023-03-29 |
| [v0.14.0](../../ghippo/intro/release-notes.md) | AMD 64 | 10.00KB | [:arrow_down: ghippo_v0.14.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.14.0_amd64.tar) | [:arrow_down: ghippo_v0.14.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.14.0_amd64_checksum.sha5 ) | 2023-02-27 |
| [v0.13.2](../../ghippo/intro/release-notes.md) | AMD64 | 439.90MB | [:arrow_down: ghippo_v0.13.2_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.13.2_amd64.tar) | [:arrow_down: ghippo_v0.13.2_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.13.2_amd64_checksum.sha512) | 2022-12-29 |
| [v0.13.0](../../ghippo/intro/release-notes.md) | AMD64 | 439.89MB | [:arrow_down: ghippo_v0.13.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.13.0_amd64.tar) | [:arrow_down: ghippo_v0.13.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.13.0_amd64_checksum.sha512) | 2022-12-29 |
| [v0.12.1](../../ghippo/intro/release-notes.md) | AMD64 | 442 MB | [:arrow_down: ghippo-0.12.1-amd64.bundle.tar](https://proxy-qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo-0.12.1-amd64.bundle.tar) | [:arrow_down: ghippo_v0.12.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/ghippo_v0.12.1_amd64_checksum.sha512sum) | 2022-11-29 |

## Validation

In the directory where the offline installation package and verification file are downloaded, execute the following command to verify the integrity:

```sh
echo "$(cat ghippo_v0.13.2_amd64_checksum.sha512sum)" | sha512sum -c
```

After the verification is successful, the printed result is similar to:

```none
ghippo_v0.13.2_amd64.tar: ok
```

## Install

Refer to [Global Management](../../ghippo/install/offline-install.md) installation process for installation.

If you are installing for the first time, please [apply for a free trial](../../dce/license0.md) or contact us for authorization: email info@daocloud.io or call 400 002 6898.
If you have any license key related questions, please contact DaoCloud delivery team.
