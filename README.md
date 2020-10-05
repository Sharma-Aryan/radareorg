#clock
import time
while True:
    from datetime import datetime
    now = datetime.now()
    print ("%s/%s/%s %s:%s:%s" % (now.month,now.day,now.year,now.hour,now.minute,now.second))
    time.sleep(1)
We have a [new website](radare.org/)!
If you want to contribute, have a look at the [repository](https://github.com/radareorg/radare.org)!

[~old website link~](http://radare2s-website.readthedocs.io)

# How to build documentation html pages

## 1. Install sphinx

```bash
sudo pip install sphinx
```

## 2. Build documentation

```
cd radareorg
sphinx-build source build
```

Open `index.html` located in `build` directory to start reading the documentation.
