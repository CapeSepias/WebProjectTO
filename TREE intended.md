# Tree

The tree reflects the intend to keep all backend stuff in the backend folder, frontend code in the frontend folder and shared JS/JVM code in the shared folder.

Additionally the project should be able to start with a CLI: mill run. This to make things the least complicated for people that want to run the project but are not so into the splits available for compile and run.

├── README.md
├── backend
│   └── src
│       └── webapp
│           └── WebApp.scala├── resourcesp
│       └── index.css├── build.mill
├── frontend
│   └── src
│       └── FrontendApp.scala
├── mill

├── shared
│   └── src
│       └── Shared.scala
├── src
│   └── RootApp.scala
└── test
    └── src
        └── WebAppTests.scala
