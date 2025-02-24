# bitsandbytes-windows-webui
Windows compile of bitsandbytes for use in text-generation-webui.  
Compiled for CUDA 11.1-11.8.  
0.38.1+ additionally includes support for 12.0 and 12.1.

***0.39.0 does not support cards with compute less than 7.0.***

Can be installed with the following command:

0.37.2:
```
python -m pip install https://github.com/jllllll/bitsandbytes-windows-webui/raw/main/bitsandbytes-0.37.2-py3-none-any.whl --force-reinstall
```
0.38.1:
```
python -m pip install https://github.com/jllllll/bitsandbytes-windows-webui/raw/main/bitsandbytes-0.38.1-py3-none-any.whl --force-reinstall
```
0.39.0:
```
python -m pip install https://github.com/jllllll/bitsandbytes-windows-webui/raw/main/bitsandbytes-0.39.0-py3-none-any.whl
```

Credit to [Adrian Popescu](https://github.com/acpopescu) at: https://github.com/acpopescu/bitsandbytes/tree/cmake_windows

0.37.2 was compiled from here: https://github.com/jllllll/bitsandbytes/tree/cmake_windows_0.37.2

0.38.1 was compiled from here: https://github.com/jllllll/bitsandbytes/tree/cmake_windows_0.38.1

0.39.0 was compiled from here: https://github.com/jllllll/bitsandbytes/tree/cmake_windows

#### All wheels are compiled using GitHub Actions.
