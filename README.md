# BadgeUtils

Badge utilities for Roblox, packaged for pesde.

## Install

```bash
pesde add gh#idkaboutbytes/badgeutils#v2.0.0
pesde install
```

This package pulls:

- `idkaboutbytes/loader` at `v1.1.0` as `Loader`
- `idkaboutbytes/promise` at `v2.0.0` as `Promise`

## Require

```lua
local ReplicatedStorage = game:GetService('ReplicatedStorage')
local require = require(ReplicatedStorage.Packages.Loader).load()

local BadgeUtils = require('BadgeUtils')
```

## Publish

```bash
pnpm run packages:release -- badgeutils
pnpm run packages:publish -- badgeutils --yes
```
