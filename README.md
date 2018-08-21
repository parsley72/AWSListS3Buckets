# AWSListS3Buckets

Demo of Nuget using AWS presented at Auckland C++ Meetup on 21st August 2018.

Original code taken from https://github.com/awsdocs/aws-doc-sdk-examples/blob/master/cpp/example_code/s3/list_buckets.cpp

Credentials can be set as explained here https://docs.aws.amazon.com/sdk-for-cpp/v1/developer-guide/credentials.html

Don't try using PackageReference, it's not supported in C++ yet (there's a note under Limitations)
https://blog.nuget.org/20180409/migrate-packages-config-to-package-reference.html

The post-build option problem I mentioned is raised here
https://developercommunity.visualstudio.com/content/problem/245884/nuget-doesnt-handle-dependencies-for-debugging.html
