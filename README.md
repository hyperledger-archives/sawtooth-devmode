![Hyperledger Sawtooth](https://raw.githubusercontent.com/hyperledger/sawtooth-core/master/images/sawtooth_logo_light_blue-small.png)

Sawtooth Devmode
-------------

Sawtooth dev mode is a consensus engine for Hyperledger Sawtooth that offers a
simplified random-leader algorithm. This method is intended for testing
applications built on top of the Hyperledger Sawtooth platform. It is useful
when developing transaction processors, smart contracts, or other components
because of its high commit rate. Dev mode commits batches as fast as possible,
in order to provide quick feedback to the developer.

Dev mode also demonstrates how to use the Sawtooth consensus engine API for a
lottery-style consensus implementation. Developers interested in implementing
a consensus engine can use the dev mode source code as an example.

Although the dev mode consensus engine can be used in a Sawtooth network, it
has a very inefficient fork-resolution algorithm and makes no guarantees about
crash fault tolerance. It should not be used in a production environment.

Documentation
-------------

Documentation for how to run and extend Sawtooth is available here:
https://sawtooth.hyperledger.org/docs/


Project Status
-----------------

This project is an _active_ Hyperledger project. It was proposed to the
community and documented [here](https://docs.google.com/document/d/1j7YcGLJH6LkzvWdOYFIt2kpkVlLEmILErXL6t-Ky2zU/edit).
Information on what _Active_ entails can be found in the
[Hyperledger Project Lifecycle document](https://wiki.hyperledger.org/community/project-lifecycle).

License
-------

Hyperledger Sawtooth software is licensed under the [Apache License Version 2.0](LICENSE) software license.
