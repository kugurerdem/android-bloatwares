This is a personal repository where I keep track of package codes for the
applications that I consider bloatware and unnecessary for my phone.

If you have `adb` and `xargs` installed, you can easily remove these packages
from your phone by executing the following command:

```
cat bloatwares.txt | xargs adb shell pm uninstall -k --user 0
```

If you are interested, you can also check [my
essay](https://rugu.dev/en/blog/debloat-with-adb) on using `adb` for debloating
your phone.
