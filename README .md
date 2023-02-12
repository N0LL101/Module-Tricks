
## Works in Linux only 

- **fcntl**:
This module provides access to the fcntl function, which can be used to set flags on file descriptors. This module is only supported on Linux.

An alternative on Windows is the ****ctypes**** library:

which provides a way to call C functions from Python. You can find the ctypes library in the standard library of Python; no separate repository is needed.

- **grp**

This module provides access to the Unix group database and is only supported on Linux.

 An alternative for Windows is the ****win32net****
 
  module, which provides access to various network-related functions on Windows.


- **pwd**

This module provides access to the Unix password database and is only supported on Linux.

 An alternative for Windows is the ****win32security****
 
 module, which provides access to Windows security API functions.

 ## Works on Windows only

- **winreg**

This module provides access to the Windows registry. This module is only supported on Windows.

 An alternative for Linux is the ****configparser****
 
  module, which provides a way to read and write configuration files.

 - **win32event**
  This module provides access to the Windows event mechanism. This module is only supported on Windows

. An alternative for Linux is the ****threading****

module, which provides a way to work with threads and synchronize access to shared resources.

- **win32process**
This module provides access to the Windows process and thread functions in the Windows API. This module is only supported on Windows.

 An alternative for Linux is the ****subprocess****

This module
which provides a way to start new processes and interact with their input/output/error streams.