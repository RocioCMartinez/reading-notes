# Amazon S3

## [Introduction to Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/dev/Introduction.html)

What is Amazon S3?

It is a data storage service. Can be used in various cases like websites, mobile apps, archives, and backup/restoration.

List at least 3 features that it offers to its users.

- Storage logging and monitoring

- Access management and security

- Storage management

What is an object key?

Also known as *key name*, is the unique identifier for an object inside a bucket. It is how you locate/verify an object inside a bucket among other objects (each one has its own key).

## [S3 with Amplify](https://docs.amplify.aws/lib/storage/getting-started/q/platform/android/)

Which dependencies are needed to install Amplify AWS S3 to your Android application?

In dependencies block:

`implementation 'com.amplifyframework:aws-storage-s3:2.12.0'`

What is needed in order to upload data to your bucket?

You need to specify the key and data object to be uploaded. This is a large chunk of code would recommend going to the **S3 with Amplify** doc resource for code example.

What method(s) initialize(s) the Amplify Auth and Storage categories?

`Amplify.addPlugin()`

`Amplify.configure()`
