
### requirement
```
pip install zmq
```


### Installation
* Put device_android folder next to scripts folder.


### usage in collect_demo 
```
import sys
sys.path.append("../")

from device_android.android_spinner import Android
 
device=Android(serverIP="10.0.0.12")
```

