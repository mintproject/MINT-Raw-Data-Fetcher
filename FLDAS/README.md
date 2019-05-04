## Setup
```bash
echo "machine urs.earthdata.nasa.gov login <username> password <password>" >> ~/.netrc
```

## Setup
```bash
touch ~/.urs_cookies

wget --recursive \
     --no-clobber \
     --no-parent \
     --no-host-directories \
     --cut-dirs=2 \
     --directory-prefix <DEST_DIR> \
     --load-cookies ~/.urs_cookies \
     --save-cookies ~/.urs_cookies \
     --auth-no-challenge=on \
     --keep-session-cookies \
     https://hydro1.gesdisc.eosdis.nasa.gov/data/FLDAS/
```

## Notes

**URL** https://hydro1.gesdisc.eosdis.nasa.gov/data/FLDAS/ was provided by Lele via https://app.box.com/file/299353144863

**Download Instructions** https://disc.gsfc.nasa.gov/data-access#mac_linux_wget
