# READ GOOD GO CODE
1) мови Go: https://go.googlesource.com/
2) Chezmoi https://github.com/twpayne/chezmoi : автор слідкує за тематичними блогами та регулярно вносить якісь фішки в проект
3) https://github.com/golangci/golangci-lint: тут дуже хороші описи пул реквестів від ldez
4) Goreleaser https://github.com/goreleaser/goreleaser: тести хороші
5) Delve https://github.com/go-delve/delve: тут низькорівневий код
6) Perkeep https://github.com/perkeep/perkeep: хоч вже майже не підтримується, але подобається організація коду. Автор раніше працював над http в Go.
7) https://github.com/trending/go 


# YOUTUBE
## O.Redko recommends , 
1) https://www.youtube.com/@JustForFunc (contains idiomatic constructions)
2) Код рев'ю, огляди книг та лайфхаки https://www.youtube.com/@boldlygo
3) Сучасні фреймворки та підходи https://www.youtube.com/@packagemain.
4) 

# ARTICLES
## PROD CODE
1) хороший цикл статей по розробці продакшен сервісів на Go, який показує плюси-мінуси того чи іншого рішення: https://threedots.tech/series/modern-business-software-in-go/ (оказує плюси-мінуси того чи іншого рішення)

## DESIGN PATTERNS
1) https://refactoring.guru/design-patterns/go
2) https://github.com/tmrts/go-patterns
3) https://dave.cheney.net/2014/10/17/functional-options-for-friendly-apis
4) Adapter: https://bitfieldconsulting.com/posts/adapter
5) Китайською  https://github.com/senghoo/golang-design-pattern
6) Backends for Frontends Pattern - Azure Arch. Centre https://learn.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends

## DEPLOYMENT strategies
1) AWS https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-strategies.html#placement-groups-spread

## POSTGRS
1) https://openai.com/index/scaling-postgresql/

## TESTS
- https://threedots.tech/post/microservices-test-architecture/
- https://threedots.tech/post/database-integration-testing/
- https://fossa.com/blog/golang-best-practices-testing-go/
- https://abseil.io/resources/swe-book/html/ch11.html Testing overview
- https://abseil.io/resources/swe-book/html/ch12.html Unit tests
- https://abseil.io/resources/swe-book/html/ch13.html Test Doubles
- https://abseil.io/resources/swe-book/html/ch14.html Larger Testing
- https://oblique.security/blog/go-synctest/
- https://medium.com/@guleym/fuzz-testing-and-property-based-testing-in-go-3ad0b9ae71c5 Fuzz testing 45m read

## CONTEXT
1) https://medium.com/@syntaxSavage/why-your-go-context-cancel-works-in-postman-but-fails-behind-nginx-and-how-to-fix-it-2c915799a55d

## VPN 
https://onlinelibrary.wiley.com/doi/full/10.1002/spe.3329

## pgx
https://www.youtube.com/watch?v=sXMSWhcHCf8
+ приклади коду https://github.com/jackc/pgx-top-to-bottom

## ONBOARDING Go example
1) https://stream-wiki.notion.site/Stream-Go-10-Week-Backend-Eng-Onboarding-625363c8c3684753b7f2b7d829bcd67a
2) Який проект на Go зробити, щоб свічнутись на Golang: https://dou.ua/forums/topic/50512/

## DDD, CQRS
1) https://threedots.tech/post/basic-cqrs-in-go/
2) https://threedots.tech/post/list-of-recommended-libraries/#ddd--clean-architecture
 
## OBSERVABILITY
https://www.crowdstrike.com/en-us/cybersecurity-101/observability/three-pillars-of-observability/

## PLAYWRIGHT
https://wisdomgoody.medium.com/master-api-testing-with-playwright-javascript-27337dd44c4d
HINT ("клауде кодом плейврайт за 5 мін розгортаю, без реєстрації і смс")

## CLAUDE
1) https://anthropic.skilljar.com/claude-code-in-action 
2) https://x.com/bcherny/status/2007179832300581177

## STRUCTURE LARGE apps
1) https://medium.com/@gane18/structuring-large-go-codebases-package-organization-and-dependency-management-05a95c727c27
2) https://monorepo.tools/

## CHANNELS
1) https://dave.cheney.net/2013/04/30/curious-channels
2) https://go101.org/article/channel-closing.html 


# BOOKS
## SYSTEM DESIGN
1) Clean Code; A Handbook of Agile Software Craftsmanship, 2nd Edition
2) A Philosophy of Software Design
3) Righting Software by Juvai Lowy (нішове, на думку Андрія Хом'яка)
## DISTRIBUTED SYSTEMS
1) https://blog.devgenius.io/saga-pattern-in-go-building-resilient-distributed-transactions-with-orchestration-19d9746d8b85
## FINANCE
1) Designing Financial Data Architectures (Tamer Khraisha)
2) Financial Data Engineering (Tamer Khraisha)

## DDD
Vernon https://www.dddcommunity.org/library/vernon_2011/ в

## PROGRAMMING
1) Клін код підсумок 
1. Називайте речі своїми іменами
2. Розділяйте роботу з інфраструктурою від бізнес логіки
3. Пишіть тести
4. Організовуйте код відносно функціоналу, а не технічного призначення
2) Керніган і Роб Пайк «Практика програмування». В рази конденсованіша. Артем З. вважає.
3) Микита М. вважає, Алан Голуб книга, ще Керніган і Річі про C.
4) Computer Systems: A Programmer's Perspective Global Edition. David O'Hallaron (відгук-2/3 прочитав - прикольна. Чуть важко читається, але хороша)
5) Кабанчик Designing Data Intensive Applications
6) The Pragmatic Programmer — Hunt, Thomas https://www.goodreads.com/book/show/4099.The_Pragmatic_Programmer інженерний майндсет
7) Design Patterns (GoF) https://www.goodreads.com/book/show/85009.Design_Patterns словник архітектурних рішень
8) Refactoring — Martin Fowler https://martinfowler.com/books/refactoring.html як покращувати код без поломок
9) Domain-Driven Design — Eric Evans https://www.goodreads.com/book/show/179133.Domain_Driven_Design як не плутати бізнес і технічку
10) Building Microservices — Sam Newman https://www.goodreads.com/book/show/23692271-building-microservices коли сервісів стає забагато
11) Release It! — Michael T. Nygard https://www.goodreads.com/book/show/1069827.Release_It_ чому все падає в проді
12) A philosophy of software design by Osterhout (APOSD скорочено), воно менш догматичне, вважає А.Хом'як.


# COURSES
1) **Kubernetes**. https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/?couponCode=ST16MT28125BROW .
Btw, Robusta - Kubernetes Observability and AUtomation
2) **System Design** https://www.educative.io/courses/system-design-deep-dive-real-world-distributed-systems. І **обовязково вайтпейпери популярних систем почитати.**

 
# BLOG
1) SLACK https://slack.engineering/
2) Netflix Tech Blog
3) Uber Engineering
4) Cloud flare blog


# GO
1) Recipies https://github.com/nikolaydubina/go-recipes
2) Roadmap https://roadmap.sh/golang
3) Ivan K. recommended https://github.com/enocom/gopher-reading-list (перелік оновлюється, структурован по рівням і темам, обирайте те що цікавить і занурюйтесь.)
4) StyleGuide https://google.github.io/styleguide/go/decisions#repetition
5) https://go.dev/blog/allocation-optimizations
6) https://go-perf.dev/
## COMPILER
1) https://internals-for-interns.com/posts/the-go-lexer/
2) https://go.dev/blog/type-construction-and-cycle-detection (О.Р.; "Стаття більш теоретична, ніж практична. Якщо не сильно цікаві нутрощі компілятора, можна не читати".)


# DOCUMENTATION
1) go-redis клієнту https://redis.uptrace.dev/guide/ з купою прикладів, гайдів.


# CODING
https://codingchallenges.fyi/challenges/intro/ 


# USE NOTEBOOKLM to check what's here
1) AI, щр буде з твоєю командою, твоєю роллю https://youtu.be/xNg1uVc3NKU?si=7EXx-FBhTeVVV_kj


# Quotes
Oleksii виділяє основні етапи розвитку розробника 
+ спочатку він молиться на патерни і клін код 
+ потім повне розчарування у клін коді і обʼєкт надрочування зміщюється на перформанс 
+ потім повне розчарування у перших двох і просто починається гріндінг CS fundamentals без привʼязки до мови

Artem Yadelskyi вважає, що в Go патерни це if + interface. Не тре наслідування, абстрактні класи.

Ilia D.: Головне не сприймай все написане як 100% правильні/потрібні рішення. Завжди має бути своя голова на плечах. Особливо в книжках як-от clean architecture



