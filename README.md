## ERC-6900 Subscription Plugin

This is a basic example of an ERC-6900 compatible subscription plugin called **SubscriptionPlugin**, built in Foundry. Similar to services like Netflix, this plugin allows users to manage monthly subscriptions. It has one primary function that can be called through a user operation, called `subscribe`, which processes a user's subscription payment.

In the `/src` directory, you will find this plugin documented in detail to help you understand its functionality.

In the `/test` directory, there is a basic test demonstrating how the subscription plugin works. This will show you how to set up the modular account, install the plugins, and send a user operation that specifies the intent to subscribe or manage subscriptions. Use `forge test` to run these tests.

Also included is a helper contract for tests called `AccountTestBase`, which simplifies the process of setting up the EntryPoint and a testing account. If you're writing your own tests for a custom subscription plugin, you can use this test base to streamline your setup.

Feel free to modify the plugin and tests to deepen your understanding of ERC-6900 plugins, or use this as a starting point to create your own subscription plugin! Click "Use this template" above to create your own plugin.

## Foundry Documentation

[Foundry Documentation](https://book.getfoundry.sh/)
