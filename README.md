```sh
bazel run //:xcodeproj --//:word=1  # prints hello
bazel run //:xcodeproj --//:word=2  # prints world

bazel run //:xcodeproj --//:word=2
# will print hello and includes word1.cc instead of word2.cc
xed ExampleProj.xcodeproj
```