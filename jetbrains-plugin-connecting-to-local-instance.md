Q: How can I start up a local instance of the JetBrains plugin that points to a locally-running search backend instance?

A: 
- Run the custom version of the plugin via `runIde`, as described in the [README](https://github.com/sourcegraph/sourcegraph/blob/main/client/jetbrains/README.md#development).
- Go to your running local instance (https://sourcegraph.test:3443), log in as admin, go to Admin → Access tokens, generate an access token
- Go to Preferences (⌘S) | Tools | Sourcegraph, and set the Sourcegraph URL to https://sourcegraph.test:3443, and the access token.
You should be good to go!
