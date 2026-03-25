# medical-interop-gateway
病院内外を繋ぎ、医療データの相互運用性を実現する連携基盤。

## 🌐 システムの役割
- **標準規格変換:** 日本国内規格（SS-MIX2）や独自形式から国際標準 **HL7 FHIR** への変換。
- **API連携基盤:** 電子カルテ、地域医療連携ネットワーク、PHRアプリとの安全なデータ交換。
- **標準コードマッピング:** 施設内コードと厚労省策定の標準マスター（HOTコード等）の統合。

## 🛠 使用フレームワーク・技術
- **Language:** Go または Python (FastAPI) (軽量・高速なAPI処理)
- **Standard:** HL7 FHIR R4/R5 (JSON形式)
- **Protocol:** REST API / OAuth2 / OpenID Connect
