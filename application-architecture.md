## Application architecture

The idea is to have the entire project divided into numerous, easy to develop components so that one part of the infrastructure does not block the other, and it becomes easy to maintain in the long run. As of now, it is decided to write a majority of the technology needed in javascript, and minor components in languages that are most suitable for them. Parts requiring high performance might be rewritten as and when needed, but that is mostly a distant milestone.

It would not be wrong to say that we are using a hybrid architecture, and not specifically a monolithic or micro-service one. The main reason is the need to avoid the redundancy in the system. Therefore as and when needed, few components run as a micro-service, and few run bundled together.

The development of the project is being developed following the Agile method of development, and the primary goal is to get a working prototype into usage as soon as possible. Many of the points mentioned about the architecture may (and would surely) come into existence only after we pass the initial prototype milestone.

The entire application stack is being developed over github, and types of new contributions are welcomed. Developers, Designers, Content Writers, Testers and even users, we are open to the entire community for all sorts of contributions.

## Desktop Application

- Technologies : Electron, TypeScript
- MileStones:
  - all tests and preparatory material to be accessible offline, to ensure connectivity is never a barrier.
  - application to be easily upgradeable, so that users don't have to worry which version they are running.

## Mobile Application

- Technology: React Native, React, TypeScript
- MileStones:
  - allow accessing all features provided by server.
  - allow giving tests offline, reasons already stated above.
  - allow sharing downloaded data to other devices to make application usable in limited connectivity.
