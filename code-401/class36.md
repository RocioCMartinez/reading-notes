# Amplify & Cognito

## [Amplify and Cognito](https://docs.amplify.aws/lib/auth/getting-started/q/platform/android/)

Where in your application should you check the current auth session?

You can run a code segment from MainActivity onCreate method.

Imports:

> `import android.util.Log;` <br>
> `import com.amplifyframework.core.Amplify;`

Session status log:

> `Amplify.Auth.fetchAuthSession(
    result -> Log.i("AmplifyQuickstart", result.toString()),
    error -> Log.e("AmplifyQuickstart", error.toString())
);`

What is the command that is used to push your changes to the cloud?

To push changes to the cloud you would run: `amplify push` from the terminal.

What does Amplify Auth do for your application?

It helps set up the interface for authenticating users. Tracks user information and session status.
