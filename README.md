# pwa-codelab

- [만들면서 이해하는 PWA 코드랩](https://festa.io/events/287)
- [PWA 코드랩 가이드라인](https://medium.com/@euncho/pwa-%EC%BD%94%EB%93%9C%EB%9E%A9-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8-597049b2df40)
- [PWA 관련 코드랩](https://codelabs.developers.google.com)
- [더 나은 웹 앱을 만들 수 있는 가이드](https://web.dev/)

## PWA란?

- PWA는 Progreeive Web Apps 의 약자로 어플리케이션의 경험을 웹 기술을 이용해 구현하는 것이다.
- 자주 사용하는 앱을 웹을 통해서 들어가게 되면 반복적으로 해야 하는 불필요한 작업이 생긴다. (도메인 입력 등)

- 플레이스토어에 등록이 가능하다.
- 오프라인에서도 사용할 수 있다. 웹은 접속할 때마다 HTTP 리퀘스트를 날리고 리소스를 다운받아야 하기 때문에 오프라인 모드 지원이 어렵다.

- 그 어떤 기술도 PWA를 위해 **반드시** 사용할 필요는 없다.

### Progressive Enhancement

- HTML은 어떤 환경에서든 접근 가능하도록 하되 CSS나 JS는 지원범위에 따라서 더 나은 UI를 제공하자는 전략.
- 모두가 콘텐츠를 이용할 수 있어야 한다.
- 지원 범위에 따라서 더 나은 사용성을 제공해준다.

- `picture` element

## FIRE

PWA의 핵심 점략을 담고 있는 키워드들의 집합.

- Fast - 빠른
- Intergrated - 앱처럼 보이는
- Reliable - 안정적인
- Engaging - 유저가 참여할 수 있는

어떤 기술을 사용한다고 PWA가 되는 것이 아니라 웹 앱을 만드는 접근방식에 따라서 PWA다 아니다를 가늠할 수 있다.\
PWA에서 중요한 기술은 아래 두가지가 있다.

- Web App Manifast
- Service Worker

# Your First Progressive Web App Codelab

These are the resource files needed for the
[Your First Progressive Web App][codelab] codelab.

In this codelab, you'll build a weather web app using Progressive Web App
techniques. Your app will:

- Use responsive design, so it works on desktop or mobile.
- Be fast & reliable, using a service worker to precache the app resources
  (HTML, CSS, JavaScript, images) needed to run, and cache the weather data
  at runtime to improve performance.
- Be installable, using a web app manifest and the `beforeinstallprompt` event
  to notify the user it's installable.

## What you'll learn

- How to create and add a web app manifest
- How to provide a simple offline experience
- How to provide a full offline experience
- How to make your app installable

## Getting started

To get started, check out the [codelab instruction][codelab]

## Feedback

This is a work in progress, if you find a mistake, please [file an issue][git-issue].

## License

Copyright 2019 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements. See the NOTICE file distributed with this work for
additional information regarding copyright ownership. The ASF licenses this
file to you under the Apache License, Version 2.0 (the “License”); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an “AS IS” BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.

[codelab]: https://codelabs.developers.google.com/codelabs/your-first-pwapp/
[git-issue]: https://github.com/googlecodelabs/your-first-pwapp/issues
