Doesn't succeed yet

```
INFO: Analysed target //app:app (45 packages loaded).
INFO: Found 1 target...
ERROR: missing input file '@androidsdk//:build-tools/26.0.1/zipalign'
ERROR: /Users/kazuaki/GitHub/bazel-example/app/BUILD:28:1: //app:app: missing input file '@androidsdk//:build-tools/26.0.1/zipalign'
Target //app:app failed to build
Use --verbose_failures to see the command lines of failed build steps.
ERROR: /Users/kazuaki/GitHub/bazel-example/app/BUILD:28:1 1 input file(s) do not exist
INFO: Elapsed time: 51.649s, Critical Path: 5.61s
FAILED: Build did NOT complete successfully
```


- https://docs.bazel.build/versions/master/be/android.html
- https://github.com/bazelbuild/examples/tree/master/tutorial

```
# Get available paclages
$ bazel query @androidsdk//...
```


```
$ bazel build //app:app
```