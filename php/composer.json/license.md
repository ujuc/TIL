# license

* 패키지에 대한 라이선스를 작성한다.
* 문자열로 보여주거나, 배열로된 문자열들로 나타낸다.
* Closed-source 소프트웨어의 경우, `proprietary` 로 나타낸다.

* 하나일때

```json
{
    "license": "MIT"
}
```

* 두개 이상일때

```json
{
    "license": [
        "LGPL-2.1-only",
        "GPL-3.0-or-later"
    ]
}
```

* `or` 이나 `and` 를 사용할 경우

```json
{
    "license": "(LGPL-2.1-only or GPL-3.0-or-later)"
}
```

