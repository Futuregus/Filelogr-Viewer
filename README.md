# Filelogr Viewer
  ![license](https://img.shields.io/badge/license-MIT-green?style=flat) ![Static Badge](https://img.shields.io/badge/Python-4179a8?style=flat&label=Language&color=%234179a8&link=https%3A%2F%2Fwww.python.org%2F)


**Viewing logs should be easy**

---
Filelogr-Viewer is a simple log viewer for your Filelogr logs, built with CustomTkinter.
---
## ![Installation](https://raw.githubusercontent.com/Futuregus/filelogr/main/filelogr%20assets/cmdlogo.png) Installation 

```bash

pip  install  filelogr-viewer

```

---
## 🔨Usage:

All it takes is a couple lines of code and Filelogr-Viewer is ready

```python
from  filelogr_viewer  import  LogViewer

LogViewer.configure(

tags_colors={
"INFO": "#00ff00",
"WARNING": "#ffff00",
"ERROR": "#ff0000"},
title="My Log Viewer",
width=1000,
height=250
)

LogViewer.open()

```


##  💬 Questions or ideas?
(Dont forget to check the docs first found here: (N/A)

 **Open an issue or suggest a feature here:** 
 https://github.com/Futuregus/Filelogr-Viewer/issues
 
**Email at**:
 futuregus11@gmail.com
