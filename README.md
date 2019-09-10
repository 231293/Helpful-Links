- Regular expression
    - https://regexr.com/
- Docker
    - https://itnext.io/dockerizing-net-core-app-a-case-study-on-the-allready-app-4d4a3b01a12a
    - https://github.com/HTBox/allReady
- Angular
    - http://slides.com/abhikmitra/teams-react#/29
- NService Bus/ RabbitMQ
    - https://docs.particular.net/nservicebus/sagas/
- Dot Net
    - The actor model in computer science is a mathematical model of concurrent computation that treats "actors" as the universal primitives of concurrent computation. If your use case is to build highly concurrent, distributed, and fault tolerant event-driven applications, then you need Actor Model.

    - Please see https://www.brianstorti.com/the-actor-model/ & https://doc.akka.io/docs/akka/2.5.3/scala/guide/actors-intro.html for more details

    - I am sure you must be wondering how to do it in Dotnet. Well, the most popular choice of all times has been Akka.Net (https://getakka.net/). This project was originally written for Java (https://akka.io/). However, it has also been ported to Dotnet, it is very popular and is actively being maintained.

    - You will be intrigued to know that TPL (Task Parallel Library) also has this Actor based programming model / feature baked in called as Dataflows (https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/dataflow-task-parallel-library), which we are seldom using. So, plan your designs accordingly and if it fits the use case, then don't hesitate to use this primitive Dotnet construct.
