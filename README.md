# List-KR
[Adguard][]를 위한 한국어 웹 사이트 필터 리스트입니다.

필터링하는 대상은 광고 뿐만 아니라 알려진 트래커, 모바일 앱의 광고, 그 외 사용자 경험에 지장을 초래하는 스크립트(안티 애드블록, 자동 스크롤, 우클릭 방지 등)을 포함합니다.



이 필터는 Adguard Windows, Mac, Android 버전에 최적화되어 있습니다. 대다수의 룰은 [Adblock Plus][]의 문법을 따르고 있으나, 몇몇 까다로운 필터링을 위한 규칙은 Adguard에서 제공하는 확장된 기능을 이용하고 있으며 다른 툴로는 활성화되지 않습니다. Adblock plus는 현재 지원하지 않으며, [ublock origin][]은 비록 Adguard의 모든 기능을 지원하진 않지만 일부 규칙과 호환되어 이 필터를 사용할 수 있습니다.

이 필터에서는 한국어 웹 사이트에만 집중하기 때문에, EasyList등 영어권 필터와 같이 사용하는 것을 권장합니다.

Adguard에 대한 정보는 [이곳][]에서 찾으실 수 있습니다.

## 사용하는 법

사용하고자 하는 프로그램에서 다음 URL을 사용하여 필터를 구독 또는 Import 하십시오:
```
https://github.com/SlowMemory/List-KR/raw/master/filter.txt
```
Adguard 윈도우, 맥, 확장 프로그램(2.3.9버전 이상), 안드로이드 버전(2.8버전 이상)의 경우, 사용 가능한 필터 목록에 List-KR이 포함되어, 이를 찾아서 활성화하면 됩니다.

ublock (origin)의 경우, 위 기본 필터와 함께 다음 보충 필터도 구독하십시오. 이는 ublock origin에서 지원하지 않는 규칙으로 인해 발생하는 호환성 문제를 보정하기 위해 필요합니다.
```
https://github.com/SlowMemory/List-KR/raw/master/unbreak.txt
```

#### 목록 향상에 기여하는 법

환영합니다! 차단되지 않은 광고나, 차단 후 남은 빈 공간 혹은 그 외에 이 필터에서 차단하는 대상을 발견하셨다면 [Issues][] 항목에 글을 남겨 주십시오. 글을 남기실 시, 사용하시는 브라우저, 차단되지 않은 광고가 있는 정확한 주소와 차단되지 않은 광고의 위치를 묘사해주시면 도움이 됩니다. 대상을 차단할 수 있는 규칙까지 제안해 주시면 더욱 좋습니다.

#### 인터넷 익스플로러에 대해서

인터넷 익스플로러는 크롬, 파이어폭스 등과 렌더링 방식에 차이가 있어, 기존 확장 프로그램에서 사용하도록 제작된 필터를 IE에 적용할 경우 차단 결과가 다를 수 있습니다 (이것이 Adguard를 위한 필터가 필요한 한 이유입니다). 이 필터 또한 기존에 존재하던 필터를 기반으로 작성되었기 때문에, IE에서만 광고가 차단되지 않는 경우가 있으며, 이는 지속적으로 개선 중입니다.

#List-KR (English)
This is a web filter for websites in Korean language, to be used with [Adguard][] ad blocker.

This filter aims to filter not only ads, but also known trackers and other scripts which negatively affects user experience(including anti-adblock, automatic scrolling, and disabling context menu).

This filter is optimized for Adguard Windows, Mac, and Android versions. Yet most of rules are following the grammer of [Adblock Plus][], some rules for more difficult filtering utilizes Adguard's advanced filtering methods, and will not be activated in other filtering tools. This filter does not currently support ABP. [ublock origin] is known to be compatible with part of the Adguard's syntax, and can be used with this filter.

This filter is focused on Korean websites, and it is recommended to use this filter together with English filter.

You can find an informal introduction to Adguard [here][].

##How to use
In the program you would like to use, use the following url to subscribe to or import List-KR.
```
https://github.com/SlowMemory/List-KR/raw/master/filter.txt
```
In Adguard Windows, Mac, browser extension (above v2.3.9), Android(above v2.8), List-KR is included in a list of available filters, so you can activate it without manually adding url above.

To use with ublock (origin), add a following url as well. It is needed to fix filtration errors caused by incompatibility of ublock (origin) with Adguard's syntax.
```
https://github.com/SlowMemory/List-KR/raw/master/unbreak.txt
```


#### How to contribute
Welcome! If you found unblocked ads, ads leftovers or any other objects that are blocked in this filter, please report it in [Issues][]. When reporting issues, it would be helpful to include the exact url where ads can be found and the description of its location. To suggest a rule to block the object is even better.

#### For IE
There is a slight difference in rendering methods between IE and Chrome, Firefox, so applying filters developed to be used for extensions which are present in Chrome and Firefox to IE would rarely allow some ads to be displayed. (This is why we need a filter for Adguard). This filter is based on several existing filters as well, so you may see some ads particular to IE, which I will keep fixing.

[Adguard]: http://adguard.com/
[Adblock Plus]: https://adblockplus.org/
[ublock origin]: https://github.com/gorhill/uBlock
[이곳]: https://namu.wiki/w/Adguard
[here]: https://namu.wiki/w/Adguard
[Issues]: https://github.com/SlowMemory/List-KR/issues
## License
This filter is licensed under [Creative Commons Attribution-ShareAlike 4.0][] license.
[Creative Commons Attribution-ShareAlike 4.0]: https://creativecommons.org/licenses/by-sa/4.0/deed.hi

