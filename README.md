## TDDIV Dataset

### Overview

TDDIV is a large-scale benchmark designed for tiny drone detection in diverse and highly cluttered outdoor infrared scenes. The raw data were captured with a mid-wave infrared (MWIR) camera across woodlands, complex urban structures, and mountainous terrains.

| Property | Value |
|----------|-------|
| Sequences | 121  |
| Annotated frames | ~139,000 |
| Bounding boxes | ~136,000 |
| Frame rate | 25 FPS |

### Download
- [TDDIV dataset (full)](URL) — images, labels

### Data Structure

```
TDDIV/
├── images/
│   ├── seq_001/
│   │   ├── 000001.jpg
│   │   ├── 000002.jpg
│   │   └── ...
│   └── ...
├── labels/
│   ├── seq_001
│   │   ├── 000001.txt
│   │   ├── 000002.txt
│   │   └── ...
│   └── ...

```

## AMSTMD

AMSTMD is a training-free bio-inspired motion detector that can be used independently:

```python
from amstmd import AMSTMD

detector = AMSTMD()

```

| Device | Input | Speed |
|--------|-------|-------|
| CPU | 640×512 | 33.0 ms |
| GPU | 640×512 | 1.6 ms |


