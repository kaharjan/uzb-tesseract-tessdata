# uzb-tesseract-tessdata
Tesseract trained data for Uzbek

Моделларни яратишда [мана бу машқ маълумотларидан] (https://github.com/bmansurov/uzb-tesseract-langdata) фойдаланилди.

* `uzb_cyrl_no_latin` is an `uzb_cyrl` model from the [tesseract langdata repository](https://github.com/tesseract-ocr/langdata)
without support for latin characters. This model is especially useful for
books that don't contain latin characters whatsoever.

* `uzb_the_base.traineddata` З.М. Маъруфов таҳрири остида 1981 йилда чоп
этилган «Ўзбек тилининг изоҳли луғати»ни таҳлилига мўлжалланган. Ушбу китобдан
матнлар файлга териб чиқилиб автоматик равишда ушбу модел яратилган.

* `uzb_the.traineddata` эса юқоридаги китобни яхшироқ таҳлилига мўлжалланган.
Унда китобдаги бетларнинг фотонусхалари дастаки таҳлил қилиб яратилган.

Ушбу моделлар Apache License v2.0 билан лицензияланган.
