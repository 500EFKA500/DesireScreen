# DesireScreen: сторонние компоненты перевода

Дополнение поставляется отдельно от базового приложения. Его компоненты имеют собственные лицензии; лицензия DesireScreen их не ограничивает.

- Python 3.12.10: PSF, лицензия сохранена в python/LICENSE.txt.
- CTranslate2 4.6.0: MIT; лицензия и уведомления в python/Lib/site-packages/ctranslate2-4.6.0.dist-info.
- SentencePiece 0.2.1: Apache-2.0; лицензия в соответствующем dist-info.
- NumPy 2.2.6: BSD и лицензии включённых библиотек; см. numpy-2.2.6.dist-info и numpy.libs.
- setuptools, PyYAML и прочие комплектные зависимости: лицензии сохранены в их dist-info.
- Модели Argos translate-en_ru-1_9 и translate-ru_en-1_9: автор Aleksey Kutashov, Argos Open Technologies. Исходные README и metadata.json сохранены в models/.

Разработчик Argos подтвердил распространение бинарных .argosmodel под MIT/CC0:
https://github.com/argosopentech/argos-translate/issues/533
Обсуждение: https://github.com/argosopentech/argos-translate/issues/533
Лицензия Argos: https://github.com/argosopentech/argos-translate/blob/master/LICENSE

MIT License
Copyright (c) 2020 Argos Open Technologies, LLC
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Благодарности данным: OPUS (https://opus.nlpl.eu/), WikiMatrix/CCMatrix, Global Voices, MultiUN, News Commentary, OpenSubtitles (https://www.opensubtitles.org/), ParaCrawl, QED, Tatoeba, TED. Подробные сведения и требуемые ссылки сохранены в README моделей. Наборы обучающих данных отдельно не распространяются. Неиспользуемые модели Stanza в пакет не входят.
Базовый DesireScreen включает .NET / WPF и Windows SDK .NET projections Microsoft. Оригинальные уведомления .NET включены в licenses/ готовой сборки. Исходники .NET: https://github.com/dotnet/runtime и https://github.com/dotnet/wpf (MIT). Windows OCR — системный компонент Windows, отдельно приложением не распространяется.
