---
Keywords: injection, 危険
Copyright: (C) 2017 Ryuichi Ueda
---

# 邪文字列

sed '/<a class="nav-link"/s;href="<a href="\(.*\)" class="uri">.*</a>";href="\1";'

<a class="nav-link"   href="<a href="

