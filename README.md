# Japan Stock Master (CSV)

20260127時点データ

## Files
- `data/master.csv`

## CSV Format
- Encoding: UTF-8（推奨: UTF-8 with BOM でも可。どちらかに統一）
- Header: `code,name,sector`
- `code`: 4桁の数字（例: `7203`）
- `name`: 銘柄名（例: `トヨタ自動車`）
- `sector`: セクター（任意 / 空欄可）

Example:
```csv
code,name,sector
7203,トヨタ自動車,輸送用機器
6758,ソニーグループ,電気機器
