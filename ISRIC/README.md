
# ISRIC data from SoilGrids.org

```bash
wget --recursive \
     --mirror \
     --no-parent \
     --no-host-directories \
     --cut-dirs=2 \
     --directory-prefix <DEST_DIR> \
     ftp://ftp.soilgrids.org/data/recent/
```
## Notes

**URL** ftp://ftp.soilgrids.org/data/recent/ was provided by Lele via https://github.com/mintproject/MINT-tasks/issues/3

**Possible Alternate URL** https://files.isric.org/soilgrids/data/recent/
