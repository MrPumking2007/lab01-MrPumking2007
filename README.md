# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

git clone git@github.com:MrPumking2007/lab01-MrPumking2007.git
cd lab01-MrPumking2007
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
pip install -e .

## Run

python -m assistant "where is the library?"

## Test

pytest -q

## Project structure

- `src/`: Mã nguồn ứng dụng (backend).
- `tests/`: Chứa các bài kiểm thử tự động.
- `docs/`: Tài liệu, bản thiết kế dự án và báo cáo.
- `data/`: Dữ liệu mẫu (chỉ chứa các file nhỏ).
- `scripts/`: Chứa các đoạn script hỗ trợ chạy dự án.
