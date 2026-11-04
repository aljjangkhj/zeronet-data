# zeronet-data

ZERO-NET 앱이 내려받는 **오프라인 데이터 팩** 저장소예요. 앱 코드는 여기 없어요.

- `index.json`: 팩 목록. 앱은 `https://raw.githubusercontent.com/aljjangkhj/zeronet-data/main/index.json`을 읽어요.
- `packs/*.json`: 팩 파일(서명된 봉투). 앱은 ZERO-NET 서명 키로 서명된 팩만 설치해요.

## 팩 올리는 방법
팩은 앱 저장소(`zeronet`)의 도구로 만들고 소유자 PC에서 서명해요. 자세한 절차는 앱 저장소의 `docs/data_packs.md`.

```
py tools/datapack.py build <본문.json> ..\zeronet-data\packs\<팩id>.json
py tools/datapack.py index packs ..\zeronet-data\packs\*.json > ..\zeronet-data\index.json
```
그다음 이 저장소에서 커밋·푸시하면 바로 배포돼요.

## 데이터 출처·라이선스
| 팩 | 출처 | 라이선스 |
| --- | --- | --- |
| `kr-civil-defense` | 행정안전부 민방위대피시설 (공공데이터포털) | 이용허락범위 제한 없음 |
| `jp-NN` | 国土地理院 指定緊急避難場所データ | 国土地理院コンテンツ利用規約 |
| `osm-XX` | OpenStreetMap contributors | **ODbL 1.0** — 이 저장소의 `osm-*` 팩은 ODbL로 공개돼요 |

각 팩 파일 안에도 출처·라이선스·주의 문구가 들어 있고, 앱 화면에 표시돼요.

---

Offline data packs for the ZERO-NET app. OpenStreetMap-derived packs (`osm-*`) are © OpenStreetMap contributors and available under the Open Database License (ODbL 1.0).
