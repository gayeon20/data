---
title: "[Python] 개발 (Development)"
excerpt: 
categories:
  - Python
tags:
  - Python-Library
last_modified_at: 2024-04-11T15:10:56+09:00
link: 
상위 항목: "[[python_library|파이썬 라이브러리 (Python Library)]]"
---
**최초 작성일**: `:::this.file.cday`
**최종 수정일**: `:::this.file.mtime`

**하위 항목**
- [[python_test|파이썬 테스트 (Python Test)]]

---

[`pydoc`](https://docs.python.org/ko/3/library/pydoc.html#module-pydoc "pydoc: Documentation generator and online help system.") 모듈은 모듈을 가져와서 모듈의 내용을 기반으로 설명서를 만듭니다. [`doctest`](https://docs.python.org/ko/3/library/doctest.html#module-doctest "doctest: Test pieces of code within docstrings.") 와 [`unittest`](https://docs.python.org/ko/3/library/unittest.html#module-unittest "unittest: Unit testing framework for Python.") 모듈에는 예상 출력이 만들어지는지 코드를 자동으로 실행하고 확인하는 단위 테스트를 작성하기 위한 프레임워크가 포함되어 있습니다. **2to3**는 파이썬 2.x 소스 코드를 유효한 파이썬 3.x 코드로 변환할 수 있습니다.

이 장에서 설명하는 모듈 목록은 다음과 같습니다:

- [`typing` — 형 힌트 지원](https://docs.python.org/ko/3/library/typing.html)
    - [Specification for the Python Type System](https://docs.python.org/ko/3/library/typing.html#specification-for-the-python-type-system)
    - [형 에일리어스](https://docs.python.org/ko/3/library/typing.html#type-aliases)
    - [NewType](https://docs.python.org/ko/3/library/typing.html#newtype)
    - [Annotating callable objects](https://docs.python.org/ko/3/library/typing.html#annotating-callable-objects)
    - [제네릭](https://docs.python.org/ko/3/library/typing.html#generics)
    - [Annotating tuples](https://docs.python.org/ko/3/library/typing.html#annotating-tuples)
    - [The type of class objects](https://docs.python.org/ko/3/library/typing.html#the-type-of-class-objects)
    - [사용자 정의 제네릭 형](https://docs.python.org/ko/3/library/typing.html#user-defined-generic-types)
    - [`Any` 형](https://docs.python.org/ko/3/library/typing.html#the-any-type)
    - [명목적 대 구조적 서브 타이핑](https://docs.python.org/ko/3/library/typing.html#nominal-vs-structural-subtyping)
    - [모듈 내용](https://docs.python.org/ko/3/library/typing.html#module-contents)
        - [특수 타이핑 프리미티브](https://docs.python.org/ko/3/library/typing.html#special-typing-primitives)
            - [특수형](https://docs.python.org/ko/3/library/typing.html#special-types)
            - [특수 형태](https://docs.python.org/ko/3/library/typing.html#special-forms)
            - [Building generic types and type aliases](https://docs.python.org/ko/3/library/typing.html#building-generic-types-and-type-aliases)
            - [기타 특수 지시자](https://docs.python.org/ko/3/library/typing.html#other-special-directives)
        - [프로토콜](https://docs.python.org/ko/3/library/typing.html#protocols)
        - [ABCs for working with IO](https://docs.python.org/ko/3/library/typing.html#abcs-for-working-with-io)
        - [함수와 데코레이터](https://docs.python.org/ko/3/library/typing.html#functions-and-decorators)
        - [인트로스펙션 도우미](https://docs.python.org/ko/3/library/typing.html#introspection-helpers)
        - [상수](https://docs.python.org/ko/3/library/typing.html#constant)
        - [Deprecated aliases](https://docs.python.org/ko/3/library/typing.html#deprecated-aliases)
            - [Aliases to built-in types](https://docs.python.org/ko/3/library/typing.html#aliases-to-built-in-types)
            - [Aliases to types in `collections`](https://docs.python.org/ko/3/library/typing.html#aliases-to-types-in-collections)
            - [Aliases to other concrete types](https://docs.python.org/ko/3/library/typing.html#aliases-to-other-concrete-types)
            - [Aliases to container ABCs in `collections.abc`](https://docs.python.org/ko/3/library/typing.html#aliases-to-container-abcs-in-collections-abc)
            - [Aliases to asynchronous ABCs in `collections.abc`](https://docs.python.org/ko/3/library/typing.html#aliases-to-asynchronous-abcs-in-collections-abc)
            - [Aliases to other ABCs in `collections.abc`](https://docs.python.org/ko/3/library/typing.html#aliases-to-other-abcs-in-collections-abc)
            - [Aliases to `contextlib` ABCs](https://docs.python.org/ko/3/library/typing.html#aliases-to-contextlib-abcs)
    - [Deprecation Timeline of Major Features](https://docs.python.org/ko/3/library/typing.html#deprecation-timeline-of-major-features)
- [`pydoc` — Documentation generator and online help system](https://docs.python.org/ko/3/library/pydoc.html)
- [파이썬 개발 모드](https://docs.python.org/ko/3/library/devmode.html)
    - [파이썬 개발 모드의 효과](https://docs.python.org/ko/3/library/devmode.html#effects-of-the-python-development-mode)
    - [ResourceWarning 예](https://docs.python.org/ko/3/library/devmode.html#resourcewarning-example)
    - [잘못된 파일 기술자 에러 예](https://docs.python.org/ko/3/library/devmode.html#bad-file-descriptor-error-example)
- [`doctest` — Test interactive Python examples](https://docs.python.org/ko/3/library/doctest.html)
    - [간단한 사용법: 독스트링에 있는 예제 확인하기](https://docs.python.org/ko/3/library/doctest.html#simple-usage-checking-examples-in-docstrings)
    - [간단한 사용법: 텍스트 파일에 있는 예제 확인하기](https://docs.python.org/ko/3/library/doctest.html#simple-usage-checking-examples-in-a-text-file)
    - [작동 방법](https://docs.python.org/ko/3/library/doctest.html#how-it-works)
        - [어떤 독스트링을 검사합니까?](https://docs.python.org/ko/3/library/doctest.html#which-docstrings-are-examined)
        - [독스트링 예제는 어떻게 인식됩니까?](https://docs.python.org/ko/3/library/doctest.html#how-are-docstring-examples-recognized)
        - [실행 컨텍스트란 무엇입니까?](https://docs.python.org/ko/3/library/doctest.html#what-s-the-execution-context)
        - [예외는 어떻게 됩니까?](https://docs.python.org/ko/3/library/doctest.html#what-about-exceptions)
        - [옵션 플래그](https://docs.python.org/ko/3/library/doctest.html#option-flags)
        - [지시자](https://docs.python.org/ko/3/library/doctest.html#directives)
        - [경고](https://docs.python.org/ko/3/library/doctest.html#warnings)
    - [기본 API](https://docs.python.org/ko/3/library/doctest.html#basic-api)
    - [Unittest API](https://docs.python.org/ko/3/library/doctest.html#unittest-api)
    - [고급 API](https://docs.python.org/ko/3/library/doctest.html#advanced-api)
        - [DocTest 객체](https://docs.python.org/ko/3/library/doctest.html#doctest-objects)
        - [Example 객체](https://docs.python.org/ko/3/library/doctest.html#example-objects)
        - [DocTestFinder 객체](https://docs.python.org/ko/3/library/doctest.html#doctestfinder-objects)
        - [DocTestParser 객체](https://docs.python.org/ko/3/library/doctest.html#doctestparser-objects)
        - [DocTestRunner 객체](https://docs.python.org/ko/3/library/doctest.html#doctestrunner-objects)
        - [OutputChecker 객체](https://docs.python.org/ko/3/library/doctest.html#outputchecker-objects)
    - [디버깅](https://docs.python.org/ko/3/library/doctest.html#debugging)
    - [맺음말](https://docs.python.org/ko/3/library/doctest.html#soapbox)
- [`unittest` — Unit testing framework](https://docs.python.org/ko/3/library/unittest.html)
    - [기본 예시](https://docs.python.org/ko/3/library/unittest.html#basic-example)
    - [명령행 인터페이스](https://docs.python.org/ko/3/library/unittest.html#command-line-interface)
        - [명령행 옵션](https://docs.python.org/ko/3/library/unittest.html#command-line-options)
    - [테스트 탐색(Discovery)](https://docs.python.org/ko/3/library/unittest.html#test-discovery)
    - [테스트 코드 구조 잡기](https://docs.python.org/ko/3/library/unittest.html#organizing-test-code)
    - [이전의 테스트 코드를 다시 사용하기](https://docs.python.org/ko/3/library/unittest.html#re-using-old-test-code)
    - [테스트 건너뛰기와 예상된 실패](https://docs.python.org/ko/3/library/unittest.html#skipping-tests-and-expected-failures)
    - [부분 테스트(subtest)를 사용하여 테스트 반복 구별 짓기](https://docs.python.org/ko/3/library/unittest.html#distinguishing-test-iterations-using-subtests)
    - [클래스와 함수](https://docs.python.org/ko/3/library/unittest.html#classes-and-functions)
        - [테스트 케이스](https://docs.python.org/ko/3/library/unittest.html#test-cases)
        - [테스트 분류](https://docs.python.org/ko/3/library/unittest.html#grouping-tests)
        - [테스트를 로드하고 실행하기](https://docs.python.org/ko/3/library/unittest.html#loading-and-running-tests)
            - [load_tests 프로토콜](https://docs.python.org/ko/3/library/unittest.html#load-tests-protocol)
    - [클래스와 모듈 픽스쳐](https://docs.python.org/ko/3/library/unittest.html#class-and-module-fixtures)
        - [setUpClass 와 tearDownClass](https://docs.python.org/ko/3/library/unittest.html#setupclass-and-teardownclass)
        - [setUpModule 과 tearDownModule](https://docs.python.org/ko/3/library/unittest.html#setupmodule-and-teardownmodule)
    - [시그널 처리하기](https://docs.python.org/ko/3/library/unittest.html#signal-handling)
- [`unittest.mock` — mock object library](https://docs.python.org/ko/3/library/unittest.mock.html)
    - [간략 지침](https://docs.python.org/ko/3/library/unittest.mock.html#quick-guide)
    - [Mock 클래스](https://docs.python.org/ko/3/library/unittest.mock.html#the-mock-class)
        - [호출](https://docs.python.org/ko/3/library/unittest.mock.html#calling)
        - [어트리뷰트 삭제](https://docs.python.org/ko/3/library/unittest.mock.html#deleting-attributes)
        - [모의 객체 이름과 이름 어트리뷰트](https://docs.python.org/ko/3/library/unittest.mock.html#mock-names-and-the-name-attribute)
        - [모의 객체를 어트리뷰트로 연결하기](https://docs.python.org/ko/3/library/unittest.mock.html#attaching-mocks-as-attributes)
    - [패처](https://docs.python.org/ko/3/library/unittest.mock.html#the-patchers)
        - [patch](https://docs.python.org/ko/3/library/unittest.mock.html#patch)
        - [patch.object](https://docs.python.org/ko/3/library/unittest.mock.html#patch-object)
        - [patch.dict](https://docs.python.org/ko/3/library/unittest.mock.html#patch-dict)
        - [patch.multiple](https://docs.python.org/ko/3/library/unittest.mock.html#patch-multiple)
        - [패처 메서드: start와 stop](https://docs.python.org/ko/3/library/unittest.mock.html#patch-methods-start-and-stop)
        - [내장 패치](https://docs.python.org/ko/3/library/unittest.mock.html#patch-builtins)
        - [TEST_PREFIX](https://docs.python.org/ko/3/library/unittest.mock.html#test-prefix)
        - [패치 데코레이터 중첩하기](https://docs.python.org/ko/3/library/unittest.mock.html#nesting-patch-decorators)
        - [패치할 곳](https://docs.python.org/ko/3/library/unittest.mock.html#where-to-patch)
        - [디스크립터와 프락시 객체 패치하기](https://docs.python.org/ko/3/library/unittest.mock.html#patching-descriptors-and-proxy-objects)
    - [MagicMock과 매직 메서드 지원](https://docs.python.org/ko/3/library/unittest.mock.html#magicmock-and-magic-method-support)
        - [매직 메서드 모킹하기](https://docs.python.org/ko/3/library/unittest.mock.html#mocking-magic-methods)
        - [매직 모의 객체](https://docs.python.org/ko/3/library/unittest.mock.html#magic-mock)
    - [도우미](https://docs.python.org/ko/3/library/unittest.mock.html#helpers)
        - [sentinel](https://docs.python.org/ko/3/library/unittest.mock.html#sentinel)
        - [DEFAULT](https://docs.python.org/ko/3/library/unittest.mock.html#default)
        - [call](https://docs.python.org/ko/3/library/unittest.mock.html#call)
        - [create_autospec](https://docs.python.org/ko/3/library/unittest.mock.html#create-autospec)
        - [ANY](https://docs.python.org/ko/3/library/unittest.mock.html#any)
        - [FILTER_DIR](https://docs.python.org/ko/3/library/unittest.mock.html#filter-dir)
        - [mock_open](https://docs.python.org/ko/3/library/unittest.mock.html#mock-open)
        - [자동 사양](https://docs.python.org/ko/3/library/unittest.mock.html#autospeccing)
        - [실링 모의 객체 봉인하기](https://docs.python.org/ko/3/library/unittest.mock.html#sealing-mocks)
    - [Order of precedence of `side_effect`, `return_value` and _wraps_](https://docs.python.org/ko/3/library/unittest.mock.html#order-of-precedence-of-side-effect-return-value-and-wraps)
- [`unittest.mock` — getting started](https://docs.python.org/ko/3/library/unittest.mock-examples.html)
    - [모의 객체 사용하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#using-mock)
        - [메서드를 패치하는 모의 객체](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mock-patching-methods)
        - [객체의 메서드 호출을 위한 모의 객체](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mock-for-method-calls-on-an-object)
        - [클래스 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-classes)
        - [모의 객체 이름 붙이기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#naming-your-mocks)
        - [모든 호출 추적하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#tracking-all-calls)
        - [반환 값과 어트리뷰트 설정하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#setting-return-values-and-attributes)
        - [모의 객체로 예외 발생시키기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#raising-exceptions-with-mocks)
        - [부작용 함수와 이터러블](https://docs.python.org/ko/3/library/unittest.mock-examples.html#side-effect-functions-and-iterables)
        - [비동기 이터레이터 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-asynchronous-iterators)
        - [비동기 컨텍스트 관리자 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-asynchronous-context-manager)
        - [기존 객체에서 모의 객체 만들기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#creating-a-mock-from-an-existing-object)
        - [Using side_effect to return per file content](https://docs.python.org/ko/3/library/unittest.mock-examples.html#using-side-effect-to-return-per-file-content)
    - [패치 데코레이터](https://docs.python.org/ko/3/library/unittest.mock-examples.html#patch-decorators)
    - [추가 예](https://docs.python.org/ko/3/library/unittest.mock-examples.html#further-examples)
        - [연쇄 호출 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-chained-calls)
        - [부분 모킹](https://docs.python.org/ko/3/library/unittest.mock-examples.html#partial-mocking)
        - [제너레이터 메서드 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-a-generator-method)
        - [모든 테스트 메서드에 같은 패치 적용하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#applying-the-same-patch-to-every-test-method)
        - [연결되지 않은 메서드 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-unbound-methods)
        - [모의 객체로 여러 호출 확인하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#checking-multiple-calls-with-mock)
        - [가변 인자에 대처하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#coping-with-mutable-arguments)
        - [중첩 패치](https://docs.python.org/ko/3/library/unittest.mock-examples.html#nesting-patches)
        - [MagicMock으로 딕셔너리 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-a-dictionary-with-magicmock)
        - [Mock 서브 클래스와 그 어트리뷰트](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mock-subclasses-and-their-attributes)
        - [patch.dict로 임포트를 모킹하기](https://docs.python.org/ko/3/library/unittest.mock-examples.html#mocking-imports-with-patch-dict)
        - [호출 순서 추적과 덜 상세한 호출 어서션](https://docs.python.org/ko/3/library/unittest.mock-examples.html#tracking-order-of-calls-and-less-verbose-call-assertions)
        - [더 복잡한 인자 일치](https://docs.python.org/ko/3/library/unittest.mock-examples.html#more-complex-argument-matching)
- [2to3 — Automated Python 2 to 3 code translation](https://docs.python.org/ko/3/library/2to3.html)
    - [2to3 사용법](https://docs.python.org/ko/3/library/2to3.html#using-2to3)
    - [변환자 목록](https://docs.python.org/ko/3/library/2to3.html#fixers)
    - [`lib2to3` — 2to3’s library](https://docs.python.org/ko/3/library/2to3.html#module-lib2to3)
- [`test` — Regression tests package for Python](https://docs.python.org/ko/3/library/test.html)
    - [`test` 패키지를 위한 단위 테스트 작성하기](https://docs.python.org/ko/3/library/test.html#writing-unit-tests-for-the-test-package)
    - [명령 줄 인터페이스를 사용하여 테스트 실행하기](https://docs.python.org/ko/3/library/test.html#module-test.regrtest)
- [`test.support` — 파이썬 테스트 스위트용 유틸리티](https://docs.python.org/ko/3/library/test.html#module-test.support)
- [`test.support.socket_helper` — 소켓 테스트용 유틸리티](https://docs.python.org/ko/3/library/test.html#module-test.support.socket_helper)
- [`test.support.script_helper` — 파이썬 실행 테스트용 유틸리티](https://docs.python.org/ko/3/library/test.html#module-test.support.script_helper)
- [`test.support.bytecode_helper` — 올바른 바이트 코드 생성 테스트를 위한 지원 도구](https://docs.python.org/ko/3/library/test.html#module-test.support.bytecode_helper)
- [`test.support.threading_helper` — Utilities for threading tests](https://docs.python.org/ko/3/library/test.html#module-test.support.threading_helper)
- [`test.support.os_helper` — Utilities for os tests](https://docs.python.org/ko/3/library/test.html#module-test.support.os_helper)
- [`test.support.import_helper` — Utilities for import tests](https://docs.python.org/ko/3/library/test.html#module-test.support.import_helper)
- [`test.support.warnings_helper` — Utilities for warnings tests](https://docs.python.org/ko/3/library/test.html#module-test.support.warnings_helper)

## 디버깅과 프로파일링
디버거를 사용하면 코드를 단계별로 실행하고, 스택 프레임을 분석하고, 중단 점을 설정할 수 있으며, 프로파일러는 코드를 실행하고, 프로그램의 병목 지점을 식별할 수 있도록 실행 시간을 자세하게 분석합니다. 감사 이벤트는 이것이 없다면 침입적인 디버깅이나 패치가 필요한 실행 시간 동작에 대한 가시성을 제공합니다.

- [감사 이벤트 표](https://docs.python.org/ko/3/library/audit_events.html)
- [`bdb` — Debugger framework](https://docs.python.org/ko/3/library/bdb.html)
- [`faulthandler` — Dump the Python traceback](https://docs.python.org/ko/3/library/faulthandler.html)
    - [트레이스백 덤프하기](https://docs.python.org/ko/3/library/faulthandler.html#dumping-the-traceback)
    - [결함 처리기 상태](https://docs.python.org/ko/3/library/faulthandler.html#fault-handler-state)
    - [시간 초과 후에 트레이스백 덤프하기](https://docs.python.org/ko/3/library/faulthandler.html#dumping-the-tracebacks-after-a-timeout)
    - [사용자 시그널에 트레이스백 덤프하기](https://docs.python.org/ko/3/library/faulthandler.html#dumping-the-traceback-on-a-user-signal)
    - [파일 기술자 관련 문제](https://docs.python.org/ko/3/library/faulthandler.html#issue-with-file-descriptors)
    - [예제](https://docs.python.org/ko/3/library/faulthandler.html#example)
- [`pdb` — 파이썬 디버거](https://docs.python.org/ko/3/library/pdb.html)
    - [디버거 명령들](https://docs.python.org/ko/3/library/pdb.html#debugger-commands)
- [파이썬 프로파일러](https://docs.python.org/ko/3/library/profile.html)
    - [프로파일러 소개](https://docs.python.org/ko/3/library/profile.html#introduction-to-the-profilers)
    - [즉석 사용자 설명서](https://docs.python.org/ko/3/library/profile.html#instant-user-s-manual)
    - [`profile`과 `cProfile` 모듈 레퍼런스](https://docs.python.org/ko/3/library/profile.html#module-cProfile)
    - [`Stats` 클래스](https://docs.python.org/ko/3/library/profile.html#the-stats-class)
    - [결정론적 프로파일링이란 무엇입니까?](https://docs.python.org/ko/3/library/profile.html#what-is-deterministic-profiling)
    - [한계](https://docs.python.org/ko/3/library/profile.html#limitations)
    - [보정](https://docs.python.org/ko/3/library/profile.html#calibration)
    - [사용자 정의 타이머 사용하기](https://docs.python.org/ko/3/library/profile.html#using-a-custom-timer)
- [`timeit` — Measure execution time of small code snippets](https://docs.python.org/ko/3/library/timeit.html)
    - [기본 예제](https://docs.python.org/ko/3/library/timeit.html#basic-examples)
    - [파이썬 인터페이스](https://docs.python.org/ko/3/library/timeit.html#python-interface)
    - [명령 줄 인터페이스](https://docs.python.org/ko/3/library/timeit.html#command-line-interface)
    - [예제](https://docs.python.org/ko/3/library/timeit.html#examples)
- [`trace` — Trace or track Python statement execution](https://docs.python.org/ko/3/library/trace.html)
    - [명령 줄 사용법](https://docs.python.org/ko/3/library/trace.html#command-line-usage)
        - [주요 옵션](https://docs.python.org/ko/3/library/trace.html#main-options)
        - [수정자](https://docs.python.org/ko/3/library/trace.html#modifiers)
        - [필터](https://docs.python.org/ko/3/library/trace.html#filters)
    - [프로그래밍 인터페이스](https://docs.python.org/ko/3/library/trace.html#programmatic-interface)
- [`tracemalloc` — Trace memory allocations](https://docs.python.org/ko/3/library/tracemalloc.html)
    - [예](https://docs.python.org/ko/3/library/tracemalloc.html#examples)
        - [상위 10개 표시](https://docs.python.org/ko/3/library/tracemalloc.html#display-the-top-10)
        - [차이 계산](https://docs.python.org/ko/3/library/tracemalloc.html#compute-differences)
        - [메모리 블록의 트레이스백 얻기](https://docs.python.org/ko/3/library/tracemalloc.html#get-the-traceback-of-a-memory-block)
        - [예쁜 탑(top)](https://docs.python.org/ko/3/library/tracemalloc.html#pretty-top)
            - [모든 추적한 메모리 블록의 현재 및 최대 크기를 기록](https://docs.python.org/ko/3/library/tracemalloc.html#record-the-current-and-peak-size-of-all-traced-memory-blocks)
    - [API](https://docs.python.org/ko/3/library/tracemalloc.html#api)
        - [함수](https://docs.python.org/ko/3/library/tracemalloc.html#functions)
        - [DomainFilter](https://docs.python.org/ko/3/library/tracemalloc.html#domainfilter)
        - [Filter](https://docs.python.org/ko/3/library/tracemalloc.html#filter)
        - [Frame](https://docs.python.org/ko/3/library/tracemalloc.html#frame)
        - [Snapshot](https://docs.python.org/ko/3/library/tracemalloc.html#snapshot)
        - [Statistic](https://docs.python.org/ko/3/library/tracemalloc.html#statistic)
        - [StatisticDiff](https://docs.python.org/ko/3/library/tracemalloc.html#statisticdiff)
        - [Trace](https://docs.python.org/ko/3/library/tracemalloc.html#trace)
        - [Traceback](https://docs.python.org/ko/3/library/tracemalloc.html#traceback)

## 소프트웨어 패키징 및 배포
파이썬 소프트웨어를 게시하고 설치하는 데 도움을 줍니다. 이 모듈은 [파이썬 패키지 색인](https://pypi.org/)과 함께 작동하도록 설계되었지만, 로컬 색인 서버와 함께 사용할 수도, 색인 서버 없이 사용할 수도 있습니다.

- [`ensurepip` — Bootstrapping the `pip` installer](https://docs.python.org/ko/3/library/ensurepip.html)
    - [명령 줄 인터페이스](https://docs.python.org/ko/3/library/ensurepip.html#command-line-interface)
    - [모듈 API](https://docs.python.org/ko/3/library/ensurepip.html#module-api)
- [`venv` — Creation of virtual environments](https://docs.python.org/ko/3/library/venv.html)
    - [가상 환경 만들기](https://docs.python.org/ko/3/library/venv.html#creating-virtual-environments)
    - [How venvs work](https://docs.python.org/ko/3/library/venv.html#how-venvs-work)
    - [API](https://docs.python.org/ko/3/library/venv.html#api)
    - [`EnvBuilder` 확장 예제](https://docs.python.org/ko/3/library/venv.html#an-example-of-extending-envbuilder)
- [`zipapp` — Manage executable Python zip archives](https://docs.python.org/ko/3/library/zipapp.html)
    - [기본 예](https://docs.python.org/ko/3/library/zipapp.html#basic-example)
    - [명령 줄 인터페이스](https://docs.python.org/ko/3/library/zipapp.html#command-line-interface)
    - [파이썬 API](https://docs.python.org/ko/3/library/zipapp.html#python-api)
    - [예](https://docs.python.org/ko/3/library/zipapp.html#examples)
    - [인터프리터 지정하기](https://docs.python.org/ko/3/library/zipapp.html#specifying-the-interpreter)
    - [zipapp으로 독립형 응용 프로그램 만들기](https://docs.python.org/ko/3/library/zipapp.html#creating-standalone-applications-with-zipapp)
        - [경고](https://docs.python.org/ko/3/library/zipapp.html#caveats)
    - [파이썬 Zip 응용 프로그램 아카이브 형식](https://docs.python.org/ko/3/library/zipapp.html#the-python-zip-application-archive-format)

## 언어
이 모듈들은 토큰화, 구문 분석, 문법 분석, 바이트 코드 역 어셈블리 및 기타 다양한 기능을 지원합니다.

이 모듈들은 다음과 같습니다:

- [`ast` — Abstract Syntax Trees](https://docs.python.org/ko/3/library/ast.html)
    - [추상 문법](https://docs.python.org/ko/3/library/ast.html#abstract-grammar)
    - [노드 클래스](https://docs.python.org/ko/3/library/ast.html#node-classes)
        - [Root nodes](https://docs.python.org/ko/3/library/ast.html#root-nodes)
        - [리터럴](https://docs.python.org/ko/3/library/ast.html#literals)
        - [변수](https://docs.python.org/ko/3/library/ast.html#variables)
        - [표현식](https://docs.python.org/ko/3/library/ast.html#expressions)
            - [서브스크립팅](https://docs.python.org/ko/3/library/ast.html#subscripting)
            - [컴프리헨션](https://docs.python.org/ko/3/library/ast.html#comprehensions)
        - [문장](https://docs.python.org/ko/3/library/ast.html#statements)
            - [임포트](https://docs.python.org/ko/3/library/ast.html#imports)
        - [제어 흐름](https://docs.python.org/ko/3/library/ast.html#control-flow)
        - [Pattern matching](https://docs.python.org/ko/3/library/ast.html#pattern-matching)
        - [Type parameters](https://docs.python.org/ko/3/library/ast.html#type-parameters)
        - [함수와 클래스 정의](https://docs.python.org/ko/3/library/ast.html#function-and-class-definitions)
        - [Async와 await](https://docs.python.org/ko/3/library/ast.html#async-and-await)
    - [`ast` 도우미](https://docs.python.org/ko/3/library/ast.html#ast-helpers)
    - [컴파일러 플래그](https://docs.python.org/ko/3/library/ast.html#compiler-flags)
    - [명령 줄 사용법](https://docs.python.org/ko/3/library/ast.html#command-line-usage)
- [`symtable` — Access to the compiler’s symbol tables](https://docs.python.org/ko/3/library/symtable.html)
    - [심볼 테이블 생성하기](https://docs.python.org/ko/3/library/symtable.html#generating-symbol-tables)
    - [심볼 테이블 검사하기](https://docs.python.org/ko/3/library/symtable.html#examining-symbol-tables)
- [`token` — Constants used with Python parse trees](https://docs.python.org/ko/3/library/token.html)
- [`keyword` — Testing for Python keywords](https://docs.python.org/ko/3/library/keyword.html)
- [`tokenize` — Tokenizer for Python source](https://docs.python.org/ko/3/library/tokenize.html)
    - [입력 토큰화하기](https://docs.python.org/ko/3/library/tokenize.html#tokenizing-input)
    - [명령 줄 사용법](https://docs.python.org/ko/3/library/tokenize.html#command-line-usage)
    - [예제](https://docs.python.org/ko/3/library/tokenize.html#examples)
- [`tabnanny` — Detection of ambiguous indentation](https://docs.python.org/ko/3/library/tabnanny.html)
- [`pyclbr` — Python module browser support](https://docs.python.org/ko/3/library/pyclbr.html)
    - [Function 객체](https://docs.python.org/ko/3/library/pyclbr.html#function-objects)
    - [Class 객체](https://docs.python.org/ko/3/library/pyclbr.html#class-objects)
- [`py_compile` — Compile Python source files](https://docs.python.org/ko/3/library/py_compile.html)
    - [Command-Line Interface](https://docs.python.org/ko/3/library/py_compile.html#command-line-interface)
- [`compileall` — Byte-compile Python libraries](https://docs.python.org/ko/3/library/compileall.html)
    - [명령 줄 사용](https://docs.python.org/ko/3/library/compileall.html#command-line-use)
    - [공용 함수](https://docs.python.org/ko/3/library/compileall.html#public-functions)
- [`dis` — Disassembler for Python bytecode](https://docs.python.org/ko/3/library/dis.html)
    - [Command-line interface](https://docs.python.org/ko/3/library/dis.html#command-line-interface)
    - [바이트 코드 분석](https://docs.python.org/ko/3/library/dis.html#bytecode-analysis)
    - [분석 함수](https://docs.python.org/ko/3/library/dis.html#analysis-functions)
    - [파이썬 바이트 코드 명령어](https://docs.python.org/ko/3/library/dis.html#python-bytecode-instructions)
    - [옵코드 모음](https://docs.python.org/ko/3/library/dis.html#opcode-collections)
- [`pickletools` — Tools for pickle developers](https://docs.python.org/ko/3/library/pickletools.html)
    - [명령 줄 사용법](https://docs.python.org/ko/3/library/pickletools.html#command-line-usage)
        - [명령 줄 옵션](https://docs.python.org/ko/3/library/pickletools.html#command-line-options)
    - [프로그래밍 인터페이스](https://docs.python.org/ko/3/library/pickletools.html#programmatic-interface)

---
## 참조
