# insomwrt-package

```bash
sed -i 's/option check_signature/# option check_signature/g' /etc/opkg.conf
echo "src/gz insomwrt_packages https://raw.githubusercontent.com/bobbyunknown/insomwrt-package/package/aarch64_generic" >> /etc/opkg/customfeeds.conf
```
> opkg update
