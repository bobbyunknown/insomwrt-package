# insomwrt-package

```bash
sed -i 's/option check_signature/# option check_signature/g' /etc/opkg.conf
echo "src-git insomwrt https://github.com/bobbyunknown/insomwrt-package.git;package" >> feeds.conf
```
> opkg update
