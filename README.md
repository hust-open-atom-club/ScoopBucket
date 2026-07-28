# Scoop Bucket for HUST OpenAtom Club [![Tests](https://github.com/hust-open-atom-club/ScoopBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/hust-open-atom-club/ScoopBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/hust-open-atom-club/ScoopBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/hust-open-atom-club/ScoopBucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh/) bucket containing software released by [HUST OpenAtom Club](https://github.com/hust-open-atom-club).

## Usage

To add this bucket to Scoop, run:

```console
scoop bucket add hust-open-atom-club https://github.com/hust-open-atom-club/ScoopBucket.git
```

Then install apps from this bucket, for example:

```console
scoop install atomgit-cli
```

Alternatively, install apps without adding the bucket:

```console
scoop install https://raw.githubusercontent.com/hust-open-atom-club/ScoopBucket/main/bucket/atomgit-cli.json
```

## Apps

| Name                                                               | Version | Description                                                               | License                                                |
| ------------------------------------------------------------------ | ------- | ------------------------------------------------------------------------- | ------------------------------------------------------ |
| [atomgit-cli](https://atomgit.com/hust-open-atom-club/atomgit-cli) | 0.7.0   | A command-line interface for managing AtomGit repositories and workflows. | [Mulan PSL v2](https://license.coscl.org.cn/MulanPSL2) |
