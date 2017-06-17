Binaries for AUR package [chromium-vaapi-bin][1].

-------------------------------------------------

**Build** on any Linux host with Docker:

```
$ docker pull maximbaz/arch-build-aur
$ docker run --rm -v $(pwd):/pkg maximbaz/arch-build-aur /bin/bash -c '/build.sh chromium-vaapi'
```


[1]: https://aur.archlinux.org/packages/chromium-vaapi-bin/
