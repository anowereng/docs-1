# Technical documentation

[Knowledge map (SVG)](https://raw.githubusercontent.com/mialkin/documentation/master/knowledge%20map.svg)

## .NET

- C#
  - Boxing and unboxing
  - [Access modifiers](dotnet/csharp/access%20modifiers.md)
  - [Constructor execution order](dotnet/csharp/constructor%20execution%20order.md)
  - [Covariance and contravariance](dotnet/csharp/covariance%20and%20contravariance.md)
  - [Lambda expression](dotnet/csharp/lambda%20expression.md)
  - [Nullable reference types](dotnet/csharp/nullable%20reference%20types.md)
  - [↑ Asynchronous programming patterns](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/)
  - Operators and expressions
    - [Equality operator](dotnet/csharp/equality%20operator.md)
- .NET API
  - System
    - Classes
      - Array
      - [Delegate](dotnet/api/system/delegate/delegate.md)
        - Action\<T>
        - Func\<TResult>
        - [Event](dotnet/api/system/delegate/event.md)
      - Exception
      - GC
        - Properties
          - MaxGeneration
        - Methods
          - Collect(Int32)
          - CollectionCount(Int32)
          - GetGeneration(Object)
          - GetTotalMemeory(Boolean)
          - SuppressFinalize(Object)
          - WaitForPendingFinalizers()
      - Lazy\<T>
      - MarshalByRefObject
      - Object
        - Methods
          - [Equals](dotnet/api/system/object/equals.md)
          - [GetType](dotnet/api/system//object/getType.md)
          - [ToString](dotnet/api/system/object/toString.md)
          - [Finalize](dotnet/api/system/object/finalize.md)
          - [MemberwiseClone](dotnet/api/system/object/memberwiseClone.md)
          - [ReferenceEquals](dotnet/api/system/object/referenceEquals.md)
      - String
      - Tuple\<T1>
      - ValueType
        - Enum
        - Guid
        - Nullable\<T>
    - Enums
    - Interfaces
      - IComparable\<T>
      - ICloneable
      - IDisposable
    - Structs
  - System.Collections.Concurrent
    - ConcurrentDictionary\<T>
    - ConcurrentQueue\<T>
    - ConcurrentStack\<T>
  - System.IO
    - FileStream
    - MemoryStream
  - System.Linq
    - [Expression tree](dotnet/api/system/linq/expression%20tree.md)
    - Interfaces
      - [IQueryable\<T>](dotnet/api/system/linq/iqueryable.md)
  - System.Threading
    - [Task Parallel Library (TPL)](dotnet/api/system/threading/tpl.md)
    - Classes
      - Interlocked
      - Monitor
      - Mutex
      - ReaderWriterLock
      - ReaderWriterSlimLock
      - Semaphore
      - SynchronizationContext
      - [Thread](dotnet/api/system/threading/thread.md)
      - [ThreadPool](dotnet/api/system/threading/threadpool.md)
    - Structs
      - CancellationToken
      - SpinLock
      - SpinWait
  - System.Threading.Tasks
    - Classes
      - Parallel
      - [Task & Task\<T>](dotnet/api/system/threading/tasks/task.md)
      - TaskFactory
- .NET Core
  - CoreCLR
    - Memory managment
      - Garbage collector (GC)
      - Managed heap
        - Small object heap (SOH)
    - Just-in-time (JIT) compilation
  - CoreFx
    - [ASP.NET Core](dotnet/asp.net/asp.net%20core.md)
      - Dependency injection
      - Middleware
      - Host
      - Configuration
      - Options
      - Environments
      - [Logging](dotnet/asp.net/logging.md)
      - Routing
      - Security
        - Authentication
        - Authorization
      - [↑ SignalR](https://dotnet.microsoft.com/apps/aspnet/signalr)

## Computer science

- Data structures
  - Hash-based structures
    - Hash table
    - Hash tree
- Algorithms
  - Sorting algorithms
    - Insertion sort
    - Selection sort
    - Merge sort
    - Quick sort
    - Bubble sort
  - Analysis of algorithm
    - Time complexity
    - Space complexity
    - Big O notation
- Object-oriented programming (OOP)
  - Abstraction
  - Incapsulation
  - Inheritance
  - Polymorphism
- Cryptography
  - Symmetric cryptography
  - [Asymmetric cryptography](computer%20science/asymmetric%20cryptography.md)

## Databases

- ACID
  - Atomicity
  - Consistency
  - Isolation
  - Durability
- Cursor
- Database normalization
- Document databases
  - CouchDB
  - Elasticsearch
  - MongoDB
- Execution plan
- Function
- In-memory databases
  - Memcached
  - Redis
- Relational databases
  - Microsoft SQL Server
  - Oracle Database
  - SQLite
  - PostgreSQL
- Stored procedure
- SQL
  - T-SQL
  - [PL/SQL](db/oracle/plsql.md)
- [Terminology](db/terminology.md)
- Transaction
  - Isolation levels
    - Read uncommitted
    - Read commmitted
    - Repeatable read
    - Serializable
- Trigger
- Window function

## Designing

- Design principles
  - SOLID
    - Single responsibility principle
    - Open-closed principle
    - Liskov substitution principle
    - Interface segregation principle
    - [Dependency Inversion Principle](software%20design/dependency%20inversion/dependency%20inversion.md)
  - DRY
  - KISS
  - YAGNI
  - [Composition over inheritance](software%20design/composition%20over%20inheritance.md)
  - Idempotence
- Unified Modeling Language (UML)
  - Diagrams
    - Class diagram
    - Sequence diagram
- [Design patterns](software%20design/design%20patterns/design%20patterns.md)

## Miscellaneous

- [Reading list](reading%20list.md)
- [Study list](study%20list.md)
- [Перевод технических терминов](translation.md)

## Networking

- HTTP
  - HTTP/2
    - [gRPC](network/grpc.md)
- WebSocket

## Programming

- Git
  - Git flows
    - [Ветки](programming/git/branches.md)
      - [Релиз](programming/git/release.md)
      - [Именование релизных веток](programming/git/branch%20names.md)
- [Regular expressions](programming/regular%20expressions/regular%20expressions.md)
- Testing
  - Unit testing
    - Unit testing libraries
      - NUnit
    - Mock objects
  - Integration testing
  - Load testing
  - Stress testing
- Tools
  - [Docker](programming/docker/docker.md)
    - [Docker Compose](programming/docker/compose.md)
  - [Kubernetes](programming/kubernetes/kubernetes.md)
    - [kubectl](programming/kubernetes/kubectl.md)
  - GitLab
  - Apache Kafka

## Unix

- [Environment variables](unix/environment%20variables.md)
- [macOS](unix/macos/macos.md)
  - [Finder](unix/macos/finder.md)
  - [Jekyll](unix/macos/jekyll.md)
  - [Terminal](unix/macos/terminal.md)
- Linux
  - CentOS
    - [YUM](unix/yum.md)
  - [Ubuntu](unix/ubuntu.md)
    - [APT](unix/apt.md)
- [shell](unix/shell.md)
  - [Bourne again shell (bash)](unix/bash.md)
  - Commands
    - System
      - [crontab](unix/crontab.md)
      - [df](unix/df.md)
      - [du](unix/du.md)
      - [htop](unix/htop.md)
      - [systemctl](unix/systemctl.md)
      - [tmux](unix/tmux.md)
    - Files
      - [chmod](unix/chmod.md)
      - [less](unix/less.md)
      - [rg](unix/rg.md)
      - [tail](unix/tail.md)
      - [tar](unix/tar.md)
      - [vim](unix/vim.md)
    - Network
      - [rsync](unix/rsync.md)
      - [scp](unix/scp.md)
      - [ssh](unix/ssh.md)
- [Nginx](unix/nginx.md)

## Web

- HTML
  - [Viewport](web/html/viewport.md)
- [CSS](web/css/css.md)
  - [Grid](web/css/grid.md)
  - [Media queries](web/css/media%20queries.md)
  - [Selectors](web/css/selectors.md)
  - [Units](web/css/units.md)
- JavaScript
- Web services
  - Representational State Transfer (REST)
    - JSON Web Token (JWT)
    - OpenAPI 3.0
    - [OAuth 2.0](web/oauth.md)
- HTTP cookies
  - Secure
  - HttpOnly
