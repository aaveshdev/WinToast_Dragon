# WinToast 
WinToast is a Windows Toast notification library for Dragon.

```dragon
include "WinToast.dgn"

toast = new WinToast()
toast.isCompatible()
toast.setAppName("Dragon")
toast.Initialize()
toast.setData("","Hello from Dragon!","Notification test")
toast.showToast()

```
