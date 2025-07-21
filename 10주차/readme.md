### 📘 Pandas 기능 정리표 (3개 그룹)

#### 🟦 Pandas 1: 데이터 구조 및 기초 이해
| 주제 | 기능 설명 |
|------|-----------|
| **Pandas 이해하기** | - `pd.DataFrame`, `pd.Series` 생성<br>- 다양한 데이터 구조를 지원 (CSV, Excel, SQL 등)<br>- `pd.read_csv()`, `pd.read_excel()` 등으로 데이터 불러오기 |
| **Pandas 기초 이해하기** | - `.head()`, `.tail()`, `.info()`, `.describe()`로 데이터 구조 파악<br>- `df['col']`, `df[['col1', 'col2']]`로 열 선택<br>- `df.loc[]`, `df.iloc[]`으로 행 선택 및 필터링<br>- `.isnull()`, `.dropna()`, `.fillna()`로 결측치 처리 |

#### 🟩 Pandas 2: 시각화 및 통계 처리
| 주제 | 기능 설명 |
|------|-----------|
| **Pandas 시각화 활용하기** | - `df.plot()`, `df.plot(kind='bar')`, `df.plot.hist()` 등<br>- `matplotlib` 연동: `plt.title()`, `plt.xlabel()` 등<br>- `seaborn`과의 연계 가능 |
| **새로운 열 생성 및 요약 통계** | - `df['new_col'] = df['a'] + df['b']` 형태로 열 생성<br>- `df.assign()`으로 파생변수 추가<br>- `df.mean()`, `df.median()`, `df.std()` 등 요약통계<br>- `df.groupby('col').sum()` 그룹 집계 |

#### 🟨 Pandas 3: 구조 변환, 결합 및 시계열 처리
| 주제 | 기능 설명 |
|------|-----------|
| **테이블 구조 변환 및 결합** | - `.pivot()`, `.pivot_table()` 피벗 변환<br>- `.melt()`로 wide to long 변환<br>- `.merge()`, `.join()`, `pd.concat()`으로 테이블 결합<br>- `on`, `how` 인자를 통한 다양한 조인 수행 |
| **시계열 데이터 및 텍스트 데이터 처리** | - `pd.to_datetime()`, `.resample()`, `.dt` 접근자 활용<br>- `.str` 접근자로 텍스트 전처리 (`.str.lower()`, `.str.extract()` 등)<br>- `.replace()`, `.apply()` 등을 이용한 텍스트 정제 |
