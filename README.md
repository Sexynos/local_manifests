# Local Manifests for Galaxy S9 / S9+ / Note9

These trees have **forced encryption** for non-encrypted trees use the twelve-noencrypt branch

## Encrypted
```git clone https://github.com/Sexynos/local_manifests -b twelve .repo/local_manifests```

## Non-Encrypted
```git clone https://github.com/Sexynos/local_manifests -b twelve-noencrypt .repo/local_manifests```

## Dolby Atmos
To enable SamsungDAP and Dolby Atmos effect add the following flag into aosp_starlte.mk / aosp_star2lte.mk / aosp_crownlte.mk

```TARGET_HAVE_SAMSUNG_DAP := true```
