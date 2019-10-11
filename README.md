# bazel-ij-info-with-resolve
Repo to repro Bazel IntelliJ issue when IJ libraries point to bazel execroot symlinks which go missing

1. Make sure you have `jar-cache` setting turned off before importing this repo.
2. Import this repo with the default .bazelproject file
3. After sync see all files are resolved.
4. Partially sync B.java
5. Use IntelliJ synchronize to make sure IJ notices the library went missing (this is just to remove the voodoo effect of varying time). To do this you can use shift-shift shortcut and choose the non Bazel Synchronize.
6. Open A.java and see java-format library usage and import are unresolved.
7. In libraries view of project settings you should probably also see java-format highlighted as broken.
8. Run sync for all and after IJ synchrnoize all should be resolved. 
