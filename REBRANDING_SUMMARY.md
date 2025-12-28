# LocalSylvania Rebranding Summary

## Changes Made

### Integration Name
- **Old Name**: LocalTuya
- **New Name**: LocalSylvania
- **Domain**: `localtuya` (unchanged to maintain compatibility)

### Author/Owner
- **Old Owner**: @rospogrigio
- **New Owner**: @clutchthrower

## Files Updated

### Configuration Files
✅ **manifest.json**
   - Changed name to "LocalSylvania"
   - Updated codeowners to ["@clutchthrower"]
   - Updated documentation URL to github.com/clutchthrower/localtuya
   - Updated issue tracker URL

✅ **strings.json**
   - Changed title to "LocalSylvania"
   - Changed configuration title to "LocalSylvania Configuration"

### Translation Files
✅ **translations/en.json** - Updated all references
✅ **translations/it.json** - Updated all references
✅ **translations/pt-BR.json** - Updated all references

### Documentation Files
✅ **README.md** - Updated all references to LocalSylvania and @clutchthrower
✅ **info.md** - Updated all references
✅ **SYLVANIA_INTEGRATION_SUMMARY.md** - Updated references
✅ **VERIFICATION_REPORT.md** - Updated references

### Source Code Files
✅ **__init__.py** - Updated docstrings
✅ **config_flow.py** - Updated docstrings
✅ **diagnostics.py** - Updated docstrings
✅ **cloud_api.py** - Updated docstrings
✅ **pytuya/__init__.py** - Updated author and maintainer info

## What Was NOT Changed

### Internal Class Names (Preserved for Compatibility)
The following class names were intentionally kept as-is to maintain code compatibility:
- `LocalTuyaEntity`
- `LocaltuyaLight`
- `LocaltuyaClimate`
- `LocaltuyaVacuum`
- `LocaltuyaSelect`
- `LocaltuyaCover`
- `LocalTuyaOptionsFlowHandler`

These are internal implementation details and don't affect the user-facing integration name.

### Domain Name
The domain `localtuya` was kept unchanged to maintain compatibility with existing installations and configurations.

## User-Facing Changes

Users will now see:
- ✅ Integration name: **"LocalSylvania"** (in Home Assistant UI)
- ✅ Configuration title: **"LocalSylvania Configuration"**
- ✅ GitHub repository: **github.com/clutchthrower/localtuya**
- ✅ Issue tracker: **github.com/clutchthrower/localtuya/issues**
- ✅ Codeowner: **@clutchthrower**

## Credits

Original LocalTuya integration by: @rospogrigio, @postlund  
OEM API support by: @avataar  
Sylvania integration maintained by: @clutchthrower

---
Updated: 2025-12-27
Version: 5.2.3
