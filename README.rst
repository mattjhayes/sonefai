SONEFAI
=======

(Scalable Open Network Environment for Artificial Intelligence)

The goal of the SONEFAI project is to deliver a distributed
network environment that enables new research in the field of
Artificial Intelligence (AI).
 
This project is just starting, check back later or get in touch
to find out more.

System Design Principles
------------------------

* Parallel Execution. The human brain is massively parallel, so why shouldn't this
  system be the same?
* Decentralised. A large system should be self-organising without need 
  for a centralised control system. There should of course be some supervisory
  control, but this should be kept to a minimum.
* The Network is the Computer*. Use software-defined networking (SDN) to 
  create an overlay network that is more than just transport - it defines the
  dynamic wiring of the system.
* Not opinionated. The system shouldn't be opinionated about the type of
  workload it supports. Supports wide and mixed range of AI models.
* Open. The code will be licensed as "Free and Open Source Software" (FOSS)
* Distributed. Can run on a large number of heterogeneous compute nodes distributed
  across any kind of network
* Instrumented. It should be possible to ascertain how the system is, and has been running,
  down to a fine-grained level of detail, through instrumentation built into the system
* Dynamic configuration. Configuration can be self-updated or externally updated during runtime
* Self adjusting. Can dynamically adjust to changes in infrastructure (example:
  network latency) and workload
* Don’t reinvent the wheel. Build on existing platforms where possible
* Don’t be afraid to forego determinism in favour of statistical probability
* Use systems thinking
* Asynchronous. May need dwell functions in neurons to cater for lack of explicit timing
* Secure
* Scalable
* Extensible

``*`` Quote attributed to John Gage


