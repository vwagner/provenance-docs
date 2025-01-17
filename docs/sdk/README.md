---
sidebar_position: 0
---

# List of Modules

Modules are the code components of the Provenance Blockchain that execute the majority of the business logic for applications. The [Cosmos SDK](https://docs.cosmos.network/v0.47) enables developers to build modules that utilize the core structure of the SDK to allow the modules to function together. To read more about creating modules, refer to the [Cosmos documentation on modules](https://docs.cosmos.network/v0.47/building-modules/intro).

Provenance Blockchain leverages inherited modules from Cosmos SDK, and has purpose-built custom modules unique to Provenance Blockchain.

* [Inherited Cosmos modules](https://docs.cosmos.network/v0.47/build/modules)
* [Attribute](./attribute/README.md) - Functions as a blockchain registry for storing \<Name, Value\> pairs.
* [Exchange](./exchange/README.md) - Facilitates the trading of on-chain assets.
* [Hold](./hold/README.md) - Keeps track of funds in an account that have a hold placed on them.
* [Ibc Hooks](./ibchooks/README.md) - Forked from https://github.com/osmosis-labs/osmosis/tree/main/x/ibchooks
* [Ibc Rate Limit](./ibcratelimit/README.md) - Forked from https://github.com/osmosis-labs/osmosis/tree/main/x/ibc-rate-limit
* [Marker](./marker/README.md) - Allows for the creation of fungible tokens.
* [Metadata](./metadata/README.md) - Provides a system for referencing off-chain information.
* [Msg Fees](./msgfees/README.md) - Manages additional fees that can be applied to tx msgs.
* [Name](./name/README.md) - Provides a system for providing human-readable names as aliases for addresses.
* [Oracle](./oracle/README.md) - Provides the capability to dynamically expose query endpoints.
* [Quarantine](./quarantine/README.md) - Prevents accounts from receiving unwanted funds.
* [Sanction](./sanction/README.md) - Provides a mechanism for freezing accounts.
* [Trigger](./trigger/README.md) - Provides a system for triggering transactions based on predeterminded events.
