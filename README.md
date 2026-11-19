# house-rules · the station

*English first, Russian below · сначала по-английски, ниже по-русски*

---

## One locomotive, many cars

We are a small circle of people who build products with AI sessions writing the code.

Everyone who works this way hits the same walls: a session forgets why a decision was made, a check
that "passed" never actually checked anything, a deploy goes out on a Friday night with nobody
watching, a secret slips into a commit. Each of us could discover these walls alone, one bruise at
a time. We would rather discover them once.

So there is a locomotive. It is one working installation — real products, real production, real
money — that runs ahead and lays the track: a set of working rules for repositories where AI
sessions write code, each rule backed by a check that can actually fail. Behind it travel the cars:
other projects that take the same rules, release by release, and keep their own cargo, their own
destination and their own driver.

The track is laid in both directions.

* **Down the line** come releases. Every change is numbered, explained, and marked either *core*
  (a handful of rules nobody skips) or *try-on* (everything else).
* **Up the line** comes the truth about how the rules behave in the wild: a rule that turned out
  wrong, a guard that missed, a tool that broke, a rule you tried and declined, a practice of your
  own that the standard lacks. Your session files these by itself, the moment it trips.

A car does not obey blindly. By default it simply takes the rules — most of them just fit. Where
one does not, the car says so, with a reason, and that reason travels back to the locomotive and
makes the track better for everyone behind.

## What you get

* **Rules sized to your risk.** Five stages, chosen from facts: a trial folder needs nothing; a
  product with customers and money needs proof. Nobody is asked to carry machinery they don't need.
* **Checks that can fail.** A rule without a check is advice. Each requirement comes with a way to
  prove it — and a way to prove the proof is not decorative.
* **A plugin that does the routine.** Your session joins, takes releases, reports problems and
  keeps a heartbeat on its own. You are asked only when a real decision is yours.
* **Other people's bruises.** Every finding from every car is visible to all cars, with names and
  business details removed. You learn from failures you did not have to live through.

## What we ask

* Let your session report what it trips over — automatically, without polishing.
* Keep the channel guard on. A silent car is a car nobody can help.
* Keep your business out of the reports: the rule and the fact, never clients, names or keys.

## How to apply

The rules repository itself is private: only connected projects can read it.

Open an issue in **this** repository titled `join: <any neutral word for your project>` and tell
us, in a few lines:

1. the GitHub account that should receive the invitation;
2. what kind of thing you are building, in general words — no company or client names;
3. where it stands: an experiment, a repository with ongoing work, or something already serving
   real users or money;
4. which AI coding tools your sessions use.

You will get an invitation and an alias — the neutral name your project carries
in the channel. From there your session reads one file and connects itself.

There is no fee and no contract. There is one expectation: the track is laid both ways.

---

## Один тепловоз, много вагонов

Мы — небольшой круг людей, которые делают продукты, а код в них пишут AI-сессии.

Все, кто так работает, упираются в одни и те же стены: сессия забыла, почему было принято решение;
проверка «прошла», хотя ничего не проверяла; выкатка ушла в пятницу вечером, и за ней никто не
смотрел; ключ попал в коммит. Каждую из этих стен можно найти самому — по одному синяку за раз.
Мы предпочитаем находить их один раз на всех.

Поэтому есть тепловоз. Это одна рабочая установка — настоящие продукты, настоящий бой, настоящие
деньги, — которая идёт впереди и кладёт рельсы: набор правил работы для репозиториев, где код пишут
AI-сессии, и у каждого правила есть проверка, способная покраснеть. За тепловозом идут вагоны:
другие проекты, которые берут те же правила выпуск за выпуском — и везут свой груз, в свою сторону,
со своим машинистом.

Рельсы проложены в обе стороны.

* **Вниз по линии** идут выпуски. Каждое изменение пронумеровано, объяснено и помечено: *ядро*
  (горстка правил, которые не пропускает никто) или *примеряемое* (всё остальное).
* **Вверх по линии** идёт правда о том, как правила ведут себя в жизни: правило оказалось неверным,
  сторож пропустил, инструмент сломался, правило примерили и отказались, у вас есть своя практика,
  которой в стандарте нет. Ваша сессия сообщает об этом сама — в тот момент, когда споткнулась.

Вагон не подчиняется вслепую. По умолчанию он просто принимает правила — большинство подходит как
есть. Где не подходит, вагон говорит об этом и называет причину; причина уходит к тепловозу и делает
путь лучше для всех, кто едет следом.

## Что вы получаете

* **Правила по размеру риска.** Пять стадий, которые выбираются по фактам: пробной папке не нужно
  ничего; продукту с клиентами и деньгами нужны доказательства. Никого не заставляют тащить
  механизмы, которые ему не нужны.
* **Проверки, которые умеют краснеть.** Правило без проверки — это совет. К каждому требованию
  приложен способ его доказать — и способ доказать, что само доказательство не декорация.
* **Плагин, который делает рутину сам.** Ваша сессия подключается, принимает выпуски, сообщает о
  проблемах и отмечается «жив» без вашего участия. Вас спрашивают, только когда решение
  действительно ваше.
* **Чужие синяки.** Каждую находку каждого вагона видят все вагоны — без названий и деталей
  бизнеса. Вы учитесь на сбоях, которые вам не пришлось пережить.

## О чём мы просим

* Дайте вашей сессии сообщать обо всём, обо что она спотыкается, — автоматически, без причёсывания.
* Не выключайте сторож канала. Молчащему вагону никто не может помочь.
* Оставляйте свой бизнес за пределами сообщений: правило и факт — и никогда клиенты, имена, ключи.

## Как подать заявку

Сам репозиторий с правилами закрыт: читать его могут только подключённые проекты.

Откройте обращение (issue) в **этом** репозитории с заголовком `join: <любое нейтральное слово для
вашего проекта>` и напишите в нескольких строках:

1. учётную запись GitHub, на которую прислать приглашение;
2. что вы делаете — общими словами, без названий компаний и клиентов;
3. на каком вы этапе: эксперимент, репозиторий с постоянной работой или уже продукт с живыми
   пользователями либо деньгами;
4. какими AI-инструментами для кода пользуются ваши сессии.

Вы получите приглашение и псевдоним — нейтральное имя, под которым ваш проект живёт
в канале. Дальше ваша сессия читает один файл и подключается сама.

Платы нет, договора нет. Есть одно ожидание: рельсы проложены в обе стороны.
