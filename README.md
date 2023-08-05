# pointops for windows

Original code repo [point-transformer](https://github.com/POSTECH-CVLab/point-transformer).

I build this repo for directly installing pointops with 

```bash
pip install "git+https://github.com/QJSQJS/pointops_cuda_windows"
```

or

```bash
cd point_cuda_windows
pip install -e.
```

Modification:
1. Adapt the code to the Windows system.
2. Comment `#include <THC/THC.h>` for using `pytorch` with latest pytorch version.(from--https://github.com/Silverster98/pointops)
