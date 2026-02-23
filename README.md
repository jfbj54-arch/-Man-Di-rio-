# -Man-Di-rio-
APLICATIVO BIBLICO
name: mana_diario
description: Aplicativo bíblico com devocionais diários.
publish_to: "none"

environment:
  sdk: ">=3.0.0 <4.0.0"

dependencies:
  flutter:
    sdk: flutter

flutter:
  uses-material-design: true

  assets:
    - lib/data/devocionais.json
