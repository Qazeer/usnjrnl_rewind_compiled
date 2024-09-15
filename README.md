# usnjrnl_rewind compiled

PyInstaller compiled version of the `Usnjrnl Rewind` Python script from
[CyberCX-DFIR's `usnjrnl_rewind` project](https://github.com/CyberCX-DFIR/usnjrnl_rewind).

The provided binary has been built using:

```bash
# Tested on Windows, for Python 3.12.2 and PyInstaller 6.10.0.

git clone https://github.com/CyberCX-DFIR/usnjrnl_rewind.git

python.exe -m pip install pyinstaller

python.exe -m PyInstaller --clean -n usnjrnl_rewind -F usnjrnl_rewind/usnjrnl_rewind.py
```
