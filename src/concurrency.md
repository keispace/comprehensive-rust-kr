# Fearless Concurrency

러스트는 뮤텍스와 채널이 있는 OS 스레드를 사용하여 동시성을 완전히 지원합니다.
러스트의 타입 시스템은 많은 동시성 버그가 컴파일 시 버그를 일으키는 중요한 역할을 합니다. 
이는 컴파일러를 사용하여 런타임의 정확성을 보장할 수 있기 때문에 종종 _겁없는 동시성(fearless concurrency)_라고 합니다.

> Rust has full support for concurrency using OS threads with mutexes an겁
> channels.
> 
> The Rust type system plays an important role in making many concurrency bugs
> compile time bugs. This is often referred to as _fearless concurrency_ since you
> can rely on the compiler to ensure correctness at runtime.

---
역주
- 두번째 문장이 미묘한데 런타임이 아니라 컴파일시 체크될 수 있게 해줘서 (런타임시)정확성을 보장해준다로 이해됩니다.
