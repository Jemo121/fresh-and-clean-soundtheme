## 📦 Packaging

**Distro:** <!-- Debian/Ubuntu · Fedora/RHEL · Arch · openSUSE/SLE -->  
**Type:** <!-- deb · rpm · PKGBUILD · OBS -->  
**Tag:** <!-- vMAJOR.MINOR.PATCH stable tag this targets -->

## Build output

```
# paste lintian / rpmlint / namcap output here
```

## Checklist

- [ ] Builds without errors
- [ ] Linter clean
- [ ] `paplay` cue after install — works
- [ ] Version in spec matches the semver tag
- [ ] Files land in `/usr/share/sounds/Fresh_and_Clean/`
- [ ] CI `package-test` green
- [ ] LXD multitest green for this distro (if applicable)

Closes #
