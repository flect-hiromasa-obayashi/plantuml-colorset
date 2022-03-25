# plantuml-colorset
1. PlantUML用のカラーセット
1. 参考にさせていただいたリポジトリ
    1. GitHub: Kazuhito00/[PlantUML-ColorSet-Example](https://github.com/Kazuhito00/PlantUML-ColorSet-Example)

## Requirement
1. 以下のバージョンで確認
    1. Version 1.2022.2
    1. 確認先: PlantUML.[ダウンロード](https://plantuml.com/ja/download)

## Usage
1. 使用したいカラーセットを`!include`で取り込む

```
@startuml
!define colorset https://raw.githubusercontent.com/flect-hiromasa-obayashi/plantuml-colorset/main/colorset
!include colorset/ocean-blue.puml

@enduml
```

## Reference
1. [plantuml/plantuml](https://github.com/plantuml/plantuml)
1. [PlantUML公式](https://plantuml.com/ja/)

## Author
大林 弘昌

## License
plantuml-colorset is under [MIT License](LICENSE).
