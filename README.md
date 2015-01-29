# Device Tree of the BBB

Install/Update the device tree compiler
```bash
./dtc.sh
```

```bash
#Compile the dt
dtc -O dtb -o am335x-boneblack.dtb -b 0 /root/am335x-boneblack.dts
```
