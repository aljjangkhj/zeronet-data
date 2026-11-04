# zeronet-data

ZERO-NET 앱이 내려받는 **오프라인 데이터 팩** 저장소예요. 앱 코드는 여기 없어요.

- `index.json`: 팩 목록. 앱은 `https://raw.githubusercontent.com/aljjangkhj/zeronet-data/main/index.json`을 읽어요.
- `packs/*.json`: 팩 파일(서명된 봉투). 앱은 ZERO-NET 서명 키로 서명된 팩만 설치해요.

- `sources/`: 원본 데이터와 변환된 본문(**서명 전**, 앱이 읽지 않음).
  - `sources/kr/mois_civil_defense_shelters.csv`: 행정안전부 민방위대피시설 원본(공공데이터포털)
  - `sources/kr/kr-body.json`: 변환 결과(운영 중 17,214곳). 서명하면 `packs/kr-civil-defense.json`이 돼요.
  - `sources/osm/osm-XX-body.json`: OpenStreetMap 병원·식수대·비상 집결지(나라별). 2026-11-04 기준
    DE 16,184 · JP 20,415 · CH 15,666 · AT 8,864 · KR 6,979 · UA 6,012 · MX 4,318곳

## 팩 올리는 방법 (소유자 PC, 비밀키 필요)
앱 저장소(`zeronet`) 폴더에서:
```
$env:ZERONET_PACK_KEY = "$env:USERPROFILE\zeronet_pack_key.pem"
py tools/datapack.py publish ..\zeronet-data\sources\kr\kr-body.json ..\zeronet-data
```
여러 개를 한 번에(이미 같은 버전이 올라간 팩은 건너뛰어요):
```
py tools/datapack.py publish (Get-ChildItem ..\zeronet-data\sources\osm\*.json).FullName ..\zeronet-data
```
→ `packs/kr-civil-defense.json`(서명된 팩)과 `index.json`(UTF-8)이 만들어져요. 그다음 이 저장소에서 커밋·푸시하면 바로 배포돼요.
자세한 절차는 앱 저장소의 `docs/data_packs.md`.

## 데이터 출처·라이선스
| 팩 | 출처 | 라이선스 |
| --- | --- | --- |
| `kr-civil-defense` | 행정안전부 민방위대피시설 (공공데이터포털) | 이용허락범위 제한 없음 |
| `jp-NN` | 国土地理院 指定緊急避難場所データ | 国土地理院コンテンツ利用規約 |
| `osm-XX` | OpenStreetMap contributors | **ODbL 1.0** — 이 저장소의 `osm-*` 팩은 ODbL로 공개돼요 |

각 팩 파일 안에도 출처·라이선스·주의 문구가 들어 있고, 앱 화면에 표시돼요.

---

Offline data packs for the ZERO-NET app. OpenStreetMap-derived packs (`osm-*`) are © OpenStreetMap contributors and available under the Open Database License (ODbL 1.0).
