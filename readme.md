
### requirement
```
pip install zmq
```


### Installation
* Put android_robosuite folder next to scripts folder.


### usage in collect_demo 
```
import sys
sys.path.append("../")

from android_robosuite.android_spinner import Android
 
device=Android(serverIP="10.0.0.12")
```

