# Belt: Intelligent Multimodal Companion Robot for Dementia Care

Group 23 data science project (IIT / Robert Gordon University).

## Components
| Folder | Component | Owner (branch) |
|---|---|---|
| `component1_emotion/` | C1: Live emotion detecting, responding and caregiver notification | Nisila |
| `component2_memory/` | C2: Memory assistance and cognitive stimulation | Savithu |
| `component3_rewind/` | C3: Memory rewinding (long-term and short-term) | Pamula |
| `component4_reminders/` | C4: Medication and daily routine reminding | Sithula |

## Setup
```
pip install -r requirements.txt
```

## Dataset (not stored in git)
1. Download FER-2013 from https://www.kaggle.com/datasets/msambare/fer2013
2. Unzip it into a `dataset/` folder at the repo root, so you have `dataset/train/<emotion>/` and `dataset/test/<emotion>/`.

## Team rules
- One person owns each component folder and works on their own branch.
- Clear notebook outputs before every commit.
- Merge `main` into your branch before opening a pull request.