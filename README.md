#������ "Kittygram"

![build passing](https://img.shields.io/badge/build-passing-brightgreen)

������ Kittygram ������������ ����� ���-���������� ��� ������ ������������ �������.

## ��������� �������

### ����������

- Python 3.8 ��� ����
- Docker � Docker Compose

### ��������� ������������

```bash
pip install -r backend/requirements.txt

### ���������� ���������

```bash
�������� ���� .env � ����� ������� � ������� � ��� ����������� ���������� ���������, ����� ��� SECRET_KEY, DATABASE_URL � ������.

### ������ ������� � �����������

```bash
docker-compose up
```
����� ���������� ���� �����, ������ Kittygram ����� �������� �� ������ http://localhost:8000/.

### ������������
```bash
pip install -r requirements.txt
pytest
```
### GitHub Actions

GitHub Actions ��������� ��� ��������������� ������������ � ������ ������� Kittygram ����� ������� push � ����� main.
