# RxSwift <img src = "https://github.com/ReactiveX/RxSwift/raw/master/assets/Rx_Logo_M.png" width = 60  align = right> 

>드디어 얘기만 듣던 `RxSwift` 스터디를 시작합니다.

## Contents
* [Tools](https://github.com/fimuxd/RxSwift#tools)
* [Curriculum](https://github.com/fimuxd/RxSwift#curriculum)
* [Contributors](https://github.com/fimuxd/RxSwift#Contributors)
* [ContactMe](https://github.com/fimuxd/RxSwift#ContactMe)

## Tools
* 📕 RxSwift - Reactive Programming with Swift by Martin Todorov ([구매하기](https://store.raywenderlich.com/products/rxswift?_ga=2.88706715.1421367013.1516248812-515082446.1516248812))
* 🔨 Xcode 9 or Later

## Curriculum

* 총 5개의 Section과 24개의 Chapter로 구성되어 있습니다.
* 일단 한 Chapter 씩 차근차근히 읽어나갈 계획입니다. (goals: min 1 chapter/day)
* 각 Chapter 별로 Summary한 내용들을 기록할 계획입니다.
* 개인적인 스터디 + 추후 틈틈히 챙겨볼 handbook 목적입니다.

* **Section I: Getting Started with RxSwift**
	> | Ch# | Chapter Subject | Question | Note | 
	> |:---:| :--- | :--- | :--- |
	> |1|[Hello RxSwift!](https://github.com/fimuxd/RxSwift/blob/master/01_HelloRxSwift/Ch.1%20Hello%20RxSwift.md) | - | RxSwift 개요|
	> |2|[Observables](https://github.com/fimuxd/RxSwift/blob/master/02_Observables/Ch2.%20Observables.md) | - | **관찰가능한. RxSwift의 심장**<p>just<p>of<p>from<p>subscribe.empty<p>never<p>range<p>dispose<p>create<p>deferred<p>single<p>completable<p>maybe<p>do<p>debug |
	> |3|[Subjects](https://github.com/fimuxd/RxSwift/blob/master/03_Subjects/Ch3.%20Subjects.md) | [Relays & Variables](https://github.com/fimuxd/RxSwift/blob/master/03_Subjects/Ch3.%20Homework.md) | **Observable이자 Observer 인 녀석**<p>PublishSubject<p>BehaviorSubject<p>RelaySubject<p>Variable|
	> |4|[Observables and Subjects in Practice](https://github.com/fimuxd/RxSwift/blob/master/04_ObservablesAndSubjectsInPractice/Ch4.ObservablesAndSubjectsInPractice.md)|| 실전 연습 |

* **Section II: Operators and Best Practices**
	> | Ch# | Chapter Subject | Practice | Note |
	> |:---:| :--- | :---: | :--- |
	> |5|[Filtering Operators](https://github.com/fimuxd/RxSwift/blob/master/05_Filtering%20Operators/Ch5.%20FilteringOperators.md)||**필터링 연산자**<p>ignoreElements<p>elementAt<p>filter<p>skip<p>skipWhile<p>skipUntil<p>take<p>takeWhile<p>enumerated<p>takeUntil<p>distinctUntilChanged|
	> |6|Filtering Operators in Practice|||
	> |7|[Transforming Operators](https://github.com/fimuxd/RxSwift/blob/master/07_Transforming%20Operators/CH7_TransformingOperators.md)||**변환 연산자**<p>toArray<p>map<p>enumerated<p>flatMap<p>flapMapLatest<p>materialize<p>dematerialize<p>unwrap|
	> |8|Transforming Operators in Practice|||
	> |9|[Combining Operators](https://github.com/fimuxd/RxSwift/blob/master/09_Combining%20Operators/Ch9.CombiningOperators.md)||**결합 연산자**<p>startWith<p>concat<p>concatMap<p>merge<p>merge(maxConcurrent)<p>combineLatest<p>zip<p>withLatestFrom<p>sample<p>amb<p>switchLatest<p>reduce<p>scan<p>|
	> |10|Combining Operators in Practice|||
	> |11|[Time Based Operators](https://github.com/fimuxd/RxSwift/blob/master/11_Time%20Based%20Operators/Time%20Based%20Operators.md)||**시간 기반 연산자**<p>replay<p>replayAll<p>buffer<p>window<p>delaySubscription<p>interval<p>timer<p>timeout|

* **Section III: iOS Apps with RxCocoa**
	> | Ch# | Chapter Subject | Practice | Note |
	> |:---:| :--- | :---: | :--- |
	> |12|[Beginning RxCocoa](https://github.com/fimuxd/RxSwift/blob/master/12.%20Beginning%20RxCocoa/Ch12.%20Beginning%20RxCocoa.md)||**초급 RxCocoa**<p>rx<p>bindTo<p>ControlProperty<p>Driver<p>share|
	> |13|[Intermediate RxCocoa](https://github.com/fimuxd/RxSwift/blob/master/13.%20Intermediate%20RxCocoa/Ch13.Intermediate%20RxCocoa.md)||**고급 RxCocoa**<p>Signal|

* **Section IV: Intermediaate RxSwift/RxCocoa**
	> | Ch# | Chapter Subject | Practice | Note |
	> |:---:| :--- | :---: | :--- |
	> |14|[Error Handling in Practice](https://github.com/fimuxd/RxSwift/blob/master/14.%20Error%20Handling%20in%20Practice/Ch.14%20Error%20Handling%20in%20Practice.md)||**에러처리**<p>catch<p>retry|
	> |15|Intro To Schedulers|||
	> |16|Testing with RxTest|||
	> |17|Creating Custom Reactive Extensions|||

* **Section V: RxSwift Community Cookbook**
	> | Ch# | Chapter Subject | Practice | Note |
	> |:---:| :--- | :---: | :--- |
	> |18|Table and collection views|||
	> |19|Action|||
	> |20|RxGesture|||
	> |21|RxRealm|||
	> |22|RxAlamofire|||

* **Section VI: Putting it All Together**
	> | Ch# | Chapter Subject | Practice | Note |
	> |:---:| :--- | :---: | :--- |
	> |23|MVVM with RxSwift|||
	> |24|Building a Complete RxSwfit App|||

## Contributors

> Rx 무식자인 저의 눈높이에 맞춰 가르쳐주시는 멘토분들입니다. 고맙습니다. 

* [studiogaram](https://github.com/studiogaram)
* [dooho1016](https://github.com/dooho1016)

## ContactMe
* 📱 +82 10.3316.1609
* 📧 iosdeveloperkr@gmail.com

***
***Life is a game. Play it :)***