
# GloDroid

---

Glodroid is a project that adapts Android Open-Source Project
to support Orange Pi platform in a way that is:

- Open and free as much as it's possible;
- Up-to-date version of Android;
- Close to mainline Android as much as it's possible;
- Provided with necessary libraries and software so user/customer
  could have up and running latest Android OS with no efforts;

---

<iframe
	name="GloDroid presentation"
	src="https://docs.google.com/presentation/d/e/2PACX-1vQud4_nsH-UFpPsVYR7IPTBDYwzyqr-JgiRL452GcZIvm_PXkGaeBMiccsOgaId9aT-dpoPXe4cR_-z/embed?start=true&loop=true&delayms=3000"
	frameborder="0"
	width="620"
	height="367"
	allowfullscreen="true"
	mozallowfullscreen="true"
	webkitallowfullscreen="true"
></iframe>

---

## Fetch and Build

```shell
mkdir -p GloDroid
cd GloDroid
repo init -u https://github.com/glodroid/glodroid_manifest
repo sync -cq
source ./build/envsetup.sh
lunch plus2e-userdebug
make sdcard
```

### [Releases](https://github.com/GloDroid/glodroid_manifest/releases)

---

Visit the [wiki](https://github.com/GloDroid/glodroid_manifest/wiki)
for details.
